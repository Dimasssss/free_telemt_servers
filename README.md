# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-12 21:39:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 50791.4 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239164
telemt_connections_bad_total 2676
telemt_handshake_timeouts_total 5180
telemt_upstream_connect_attempt_total 12756
telemt_upstream_connect_success_total 12698
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 12756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7033
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1461
telemt_me_reconnect_attempts_total 13572
telemt_me_reconnect_success_total 10105
telemt_me_reader_eof_total 10749
telemt_me_idle_close_by_peer_total 10748
telemt_me_route_drop_no_conn_total 73562
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197335
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 671
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 423
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 296
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 10329
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 10089
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 197102
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 3707685056 (3.45 GB)
telemt_user_octets_to_client{user="hello"} 96249595172 (89.64 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 50684.5 (14h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106846
telemt_connections_bad_total 549
telemt_handshake_timeouts_total 806
telemt_upstream_connect_attempt_total 30616
telemt_upstream_connect_success_total 30279
telemt_upstream_connect_fail_total 337
telemt_upstream_connect_attempts_per_request{bucket="1"} 30616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9391
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 497
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 337
telemt_me_keepalive_timeout_total 376
telemt_me_reconnect_attempts_total 51852
telemt_me_reconnect_success_total 11203
telemt_me_reader_eof_total 12713
telemt_me_idle_close_by_peer_total 12713
telemt_me_route_drop_no_conn_total 38793
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85106
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 12557
telemt_me_refill_failed_total 1269
telemt_me_writer_restored_same_endpoint_total 11188
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1354
telemt_user_connections_total{user="hello"} 101609
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 1116290904 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 31248236451 (29.10 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 50647.9 (14h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132911
telemt_connections_bad_total 1554
telemt_handshake_timeouts_total 2212
telemt_upstream_connect_attempt_total 13991
telemt_upstream_connect_success_total 13990
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 13991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7348
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 308
telemt_me_reconnect_attempts_total 12516
telemt_me_reconnect_success_total 11376
telemt_me_reader_eof_total 12119
telemt_me_idle_close_by_peer_total 12119
telemt_me_route_drop_no_conn_total 50169
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124066
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 47
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 11520
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 11356
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 124032
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 2552471880 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 59743160368 (55.64 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 50623.6 (14h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193648
telemt_connections_bad_total 13178
telemt_handshake_timeouts_total 1363
telemt_upstream_connect_attempt_total 25099
telemt_upstream_connect_success_total 15423
telemt_upstream_connect_fail_total 9676
telemt_upstream_connect_attempts_per_request{bucket="1"} 25099
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6935
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9676
telemt_me_keepalive_timeout_total 2460
telemt_me_reconnect_attempts_total 42224
telemt_me_reconnect_success_total 9981
telemt_me_reader_eof_total 11332
telemt_me_idle_close_by_peer_total 11325
telemt_me_route_drop_no_conn_total 67668
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 157912
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 491
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 349
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 182
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 11150
telemt_me_refill_failed_total 1004
telemt_me_writer_restored_same_endpoint_total 9971
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1169
telemt_user_connections_total{user="hello"} 160667
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 2939447334 (2.74 GB)
telemt_user_octets_to_client{user="hello"} 65512471781 (61.01 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 795.2 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 842
telemt_connections_bad_total 138
telemt_upstream_connect_attempt_total 148
telemt_upstream_connect_success_total 146
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 78
telemt_me_reconnect_success_total 78
telemt_me_reader_eof_total 57
telemt_me_idle_close_by_peer_total 57
telemt_me_route_drop_no_conn_total 112
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 689
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 75
telemt_me_writer_restored_same_endpoint_total 62
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_user_connections_total{user="hello"} 689
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 3725100 (3.55 MB)
telemt_user_octets_to_client{user="hello"} 578715068 (551.91 MB)
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 50580.1 (14h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312241
telemt_connections_bad_total 4089
telemt_handshake_timeouts_total 2463
telemt_upstream_connect_attempt_total 10587
telemt_upstream_connect_success_total 10530
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 10587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 497
telemt_me_reconnect_attempts_total 11578
telemt_me_reconnect_success_total 7970
telemt_me_reader_eof_total 8515
telemt_me_idle_close_by_peer_total 8514
telemt_me_route_drop_no_conn_total 142279
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308031
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 285
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 177
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8181
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 7963
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 296333
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 5291446904 (4.93 GB)
telemt_user_octets_to_client{user="hello"} 147348232176 (137.23 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 24
```
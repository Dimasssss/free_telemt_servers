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

# Server Metrics 2026-03-12 23:37:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 57849.2 (16h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251600
telemt_connections_bad_total 2729
telemt_handshake_timeouts_total 5260
telemt_upstream_connect_attempt_total 14575
telemt_upstream_connect_success_total 14512
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 14575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8052
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1483
telemt_me_reconnect_attempts_total 15041
telemt_me_reconnect_success_total 11570
telemt_me_reader_eof_total 12335
telemt_me_idle_close_by_peer_total 12334
telemt_me_route_drop_no_conn_total 78090
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 207873
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 696
telemt_desync_full_logged_total 257
telemt_desync_suppressed_total 439
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 258
telemt_desync_frames_bucket_total{bucket="gt_10"} 314
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11809
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 11554
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 207639
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 3841746876 (3.58 GB)
telemt_user_octets_to_client{user="hello"} 106342596096 (99.04 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 57742.3 (16h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114855
telemt_connections_bad_total 635
telemt_handshake_timeouts_total 904
telemt_upstream_connect_attempt_total 33377
telemt_upstream_connect_success_total 32995
telemt_upstream_connect_fail_total 381
telemt_upstream_connect_attempts_per_request{bucket="1"} 33376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11078
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 500
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 381
telemt_me_keepalive_timeout_total 411
telemt_me_reconnect_attempts_total 55441
telemt_me_reconnect_success_total 13569
telemt_me_reader_eof_total 15217
telemt_me_idle_close_by_peer_total 15217
telemt_me_route_drop_no_conn_total 41653
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92561
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 14
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
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 14975
telemt_me_refill_failed_total 1307
telemt_me_writer_restored_same_endpoint_total 13554
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1406
telemt_user_connections_total{user="hello"} 109063
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 1206538272 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 34036915319 (31.70 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 57705.9 (16h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140300
telemt_connections_bad_total 1661
telemt_handshake_timeouts_total 2239
telemt_upstream_connect_attempt_total 15861
telemt_upstream_connect_success_total 15860
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8392
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 339
telemt_me_reconnect_attempts_total 14041
telemt_me_reconnect_success_total 12892
telemt_me_reader_eof_total 13762
telemt_me_idle_close_by_peer_total 13762
telemt_me_route_drop_no_conn_total 52903
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131123
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 13054
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 12872
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 131089
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 2599115872 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 60642405024 (56.48 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 57681.6 (16h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203752
telemt_connections_bad_total 13276
telemt_handshake_timeouts_total 1381
telemt_upstream_connect_attempt_total 27303
telemt_upstream_connect_success_total 17592
telemt_upstream_connect_fail_total 9711
telemt_upstream_connect_attempts_per_request{bucket="1"} 27303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8166
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9711
telemt_me_keepalive_timeout_total 2500
telemt_me_reconnect_attempts_total 44073
telemt_me_reconnect_success_total 11826
telemt_me_reader_eof_total 13278
telemt_me_idle_close_by_peer_total 13271
telemt_me_route_drop_no_conn_total 72131
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167739
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13011
telemt_me_refill_failed_total 1004
telemt_me_writer_restored_same_endpoint_total 11816
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1185
telemt_user_connections_total{user="hello"} 170493
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 2987054006 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 69584544565 (64.81 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 7853.1 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7045
telemt_connections_bad_total 1443
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 2451
telemt_upstream_connect_success_total 2424
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 2451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 2012
telemt_me_reconnect_success_total 2009
telemt_me_reader_eof_total 2111
telemt_me_idle_close_by_peer_total 2111
telemt_me_route_drop_no_conn_total 2044
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5351
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2021
telemt_me_writer_restored_same_endpoint_total 1993
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 5351
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 15704580 (14.98 MB)
telemt_user_octets_to_client{user="hello"} 1588027968 (1.48 GB)
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 57637.9 (16h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 335423
telemt_connections_bad_total 5148
telemt_handshake_timeouts_total 2533
telemt_upstream_connect_attempt_total 12066
telemt_upstream_connect_success_total 11999
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 12066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 513
telemt_me_reconnect_attempts_total 12734
telemt_me_reconnect_success_total 9120
telemt_me_reader_eof_total 9753
telemt_me_idle_close_by_peer_total 9752
telemt_me_route_drop_no_conn_total 150413
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 329693
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9344
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 9113
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 317996
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 5517393088 (5.14 GB)
telemt_user_octets_to_client{user="hello"} 171446589640 (159.67 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 26
```
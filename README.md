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

# Server Metrics 2026-03-13 00:54:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 62454.0 (17h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259983
telemt_connections_bad_total 2764
telemt_handshake_timeouts_total 5577
telemt_upstream_connect_attempt_total 15762
telemt_upstream_connect_success_total 15694
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 15762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1501
telemt_me_reconnect_attempts_total 16007
telemt_me_reconnect_success_total 12533
telemt_me_reader_eof_total 13371
telemt_me_idle_close_by_peer_total 13370
telemt_me_route_drop_no_conn_total 80789
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 215122
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 726
telemt_desync_full_logged_total 272
telemt_desync_suppressed_total 454
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 270
telemt_desync_frames_bucket_total{bucket="gt_10"} 328
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12780
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 12517
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 214890
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 3913929316 (3.65 GB)
telemt_user_octets_to_client{user="hello"} 108938799840 (101.46 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 62347.0 (17h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120343
telemt_connections_bad_total 728
telemt_handshake_timeouts_total 969
telemt_upstream_connect_attempt_total 35345
telemt_upstream_connect_success_total 34918
telemt_upstream_connect_fail_total 427
telemt_upstream_connect_attempts_per_request{bucket="1"} 35345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12324
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 501
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 427
telemt_me_keepalive_timeout_total 445
telemt_me_reconnect_attempts_total 59482
telemt_me_reconnect_success_total 15273
telemt_me_reader_eof_total 17042
telemt_me_idle_close_by_peer_total 17042
telemt_me_route_drop_no_conn_total 43021
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97715
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 15
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
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 16767
telemt_me_refill_failed_total 1380
telemt_me_writer_restored_same_endpoint_total 15258
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1494
telemt_user_connections_total{user="hello"} 114215
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 1235345744 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 34702004559 (32.32 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 62310.7 (17h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145619
telemt_connections_bad_total 1681
telemt_handshake_timeouts_total 2332
telemt_upstream_connect_attempt_total 17157
telemt_upstream_connect_success_total 17155
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 17157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9136
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 362
telemt_me_reconnect_attempts_total 15122
telemt_me_reconnect_success_total 13968
telemt_me_reader_eof_total 14943
telemt_me_idle_close_by_peer_total 14943
telemt_me_route_drop_no_conn_total 55381
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136157
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
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 14144
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 13948
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 136121
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 2627552764 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 62253892224 (57.98 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 62286.3 (17h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208967
telemt_connections_bad_total 13296
telemt_handshake_timeouts_total 1426
telemt_upstream_connect_attempt_total 29234
telemt_upstream_connect_success_total 19473
telemt_upstream_connect_fail_total 9761
telemt_upstream_connect_attempts_per_request{bucket="1"} 29234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9290
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9761
telemt_me_keepalive_timeout_total 3203
telemt_me_reconnect_attempts_total 49782
telemt_me_reconnect_success_total 13462
telemt_me_reader_eof_total 15058
telemt_me_idle_close_by_peer_total 15051
telemt_me_route_drop_no_conn_total 74967
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172763
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 12
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
telemt_me_writer_removed_unexpected_total 14797
telemt_me_refill_failed_total 1131
telemt_me_writer_restored_same_endpoint_total 13452
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1335
telemt_user_connections_total{user="hello"} 175516
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 3016277202 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 72361931617 (67.39 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 12458.0 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11400
telemt_connections_bad_total 2374
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 3873
telemt_upstream_connect_success_total 3837
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 3873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 3210
telemt_me_reconnect_success_total 3203
telemt_me_reader_eof_total 3410
telemt_me_idle_close_by_peer_total 3410
telemt_me_route_drop_no_conn_total 3399
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8634
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3220
telemt_me_writer_restored_same_endpoint_total 3187
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 8634
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 34585848 (32.98 MB)
telemt_user_octets_to_client{user="hello"} 2772881136 (2.58 GB)
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 62242.9 (17h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 349447
telemt_connections_bad_total 6541
telemt_handshake_timeouts_total 2596
telemt_upstream_connect_attempt_total 13161
telemt_upstream_connect_success_total 13090
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 13161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6928
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 1331
telemt_me_reconnect_attempts_total 13579
telemt_me_reconnect_success_total 9962
telemt_me_reader_eof_total 10688
telemt_me_idle_close_by_peer_total 10686
telemt_me_route_drop_no_conn_total 156152
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341950
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10196
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 9955
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 330251
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 5611020560 (5.23 GB)
telemt_user_octets_to_client{user="hello"} 178815483256 (166.53 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 34
```
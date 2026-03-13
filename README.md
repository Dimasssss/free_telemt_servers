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

# Server Metrics 2026-03-13 04:34:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 75654.1 (21h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289128
telemt_connections_bad_total 3031
telemt_handshake_timeouts_total 5770
telemt_upstream_connect_attempt_total 19109
telemt_upstream_connect_success_total 19021
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 19109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1540
telemt_me_reconnect_attempts_total 18711
telemt_me_reconnect_success_total 15221
telemt_me_reader_eof_total 16265
telemt_me_idle_close_by_peer_total 16264
telemt_me_route_drop_no_conn_total 90160
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242504
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 811
telemt_desync_full_logged_total 302
telemt_desync_suppressed_total 509
telemt_desync_frames_bucket_total{bucket="1_2"} 155
telemt_desync_frames_bucket_total{bucket="3_10"} 295
telemt_desync_frames_bucket_total{bucket="gt_10"} 361
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 15493
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 15205
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 242442
telemt_user_connections_current{user="hello"} 281
telemt_user_octets_from_client{user="hello"} 4217315424 (3.93 GB)
telemt_user_octets_to_client{user="hello"} 119702464556 (111.48 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 75546.6 (20h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132901
telemt_connections_bad_total 751
telemt_handshake_timeouts_total 1001
telemt_upstream_connect_attempt_total 40586
telemt_upstream_connect_success_total 40085
telemt_upstream_connect_fail_total 501
telemt_upstream_connect_attempts_per_request{bucket="1"} 40586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15467
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 504
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 501
telemt_me_keepalive_timeout_total 544
telemt_me_reconnect_attempts_total 66381
telemt_me_reconnect_success_total 19819
telemt_me_reader_eof_total 21879
telemt_me_idle_close_by_peer_total 21879
telemt_me_route_drop_no_conn_total 48775
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109764
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
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
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 21425
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 19804
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1606
telemt_user_connections_total{user="hello"} 126264
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 1306447204 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 37967650119 (35.36 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 75510.3 (20h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160286
telemt_connections_bad_total 1845
telemt_handshake_timeouts_total 2598
telemt_upstream_connect_attempt_total 20859
telemt_upstream_connect_success_total 20857
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 20859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11222
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 428
telemt_me_reconnect_attempts_total 18215
telemt_me_reconnect_success_total 17051
telemt_me_reader_eof_total 18253
telemt_me_idle_close_by_peer_total 18253
telemt_me_route_drop_no_conn_total 61993
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149903
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 17239
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 17031
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 149830
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 2827144572 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 69768927972 (64.98 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 75485.9 (20h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230823
telemt_connections_bad_total 13506
telemt_handshake_timeouts_total 1461
telemt_upstream_connect_attempt_total 33325
telemt_upstream_connect_success_total 23461
telemt_upstream_connect_fail_total 9864
telemt_upstream_connect_attempts_per_request{bucket="1"} 33325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11473
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9864
telemt_me_keepalive_timeout_total 3310
telemt_me_reconnect_attempts_total 62861
telemt_me_reconnect_success_total 16835
telemt_me_reader_eof_total 18796
telemt_me_idle_close_by_peer_total 18789
telemt_me_route_drop_no_conn_total 84336
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193023
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 505
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 18497
telemt_me_refill_failed_total 1434
telemt_me_writer_restored_same_endpoint_total 16825
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1662
telemt_user_connections_total{user="hello"} 195771
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 3220317134 (3.00 GB)
telemt_user_octets_to_client{user="hello"} 79088246617 (73.66 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 25657.5 (7h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25955
telemt_connections_bad_total 4799
telemt_handshake_timeouts_total 100
telemt_upstream_connect_attempt_total 8071
telemt_upstream_connect_success_total 7994
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 8070
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4459
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 184
telemt_me_reconnect_attempts_total 6723
telemt_me_reconnect_success_total 6697
telemt_me_reader_eof_total 7177
telemt_me_idle_close_by_peer_total 7177
telemt_me_route_drop_no_conn_total 7169
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20316
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6758
telemt_me_writer_restored_same_endpoint_total 6679
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 20316
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 147466336 (140.63 MB)
telemt_user_octets_to_client{user="hello"} 9069951692 (8.45 GB)
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 75442.3 (20h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 388884
telemt_connections_bad_total 7703
telemt_handshake_timeouts_total 2935
telemt_upstream_connect_attempt_total 16044
telemt_upstream_connect_success_total 15955
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 16044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 1432
telemt_me_reconnect_attempts_total 15839
telemt_me_reconnect_success_total 12211
telemt_me_reader_eof_total 13112
telemt_me_idle_close_by_peer_total 13109
telemt_me_route_drop_no_conn_total 173697
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 379143
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 12481
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 12204
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 367387
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 6116744540 (5.70 GB)
telemt_user_octets_to_client{user="hello"} 218554885540 (203.55 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 42
```
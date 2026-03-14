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

# Server Metrics 2026-03-14 15:31:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 8138.6 (2h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46586
telemt_connections_bad_total 8088
telemt_handshake_timeouts_total 234
telemt_upstream_connect_attempt_total 2106
telemt_upstream_connect_success_total 2104
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1027
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 66
telemt_me_reconnect_attempts_total 1676
telemt_me_reconnect_success_total 1653
telemt_me_reader_eof_total 1716
telemt_me_idle_close_by_peer_total 1716
telemt_me_route_drop_no_conn_total 18039
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37134
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 70
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 29
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1688
telemt_me_writer_restored_same_endpoint_total 1635
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 37070
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 662659484 (631.96 MB)
telemt_user_octets_to_client{user="hello"} 13428452008 (12.51 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 8137.0 (2h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18726
telemt_connections_bad_total 40
telemt_handshake_timeouts_total 500
telemt_upstream_connect_attempt_total 2277
telemt_upstream_connect_success_total 2250
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 2277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 4365
telemt_me_reconnect_success_total 1809
telemt_me_reader_eof_total 1931
telemt_me_idle_close_by_peer_total 1931
telemt_me_route_drop_no_conn_total 9872
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17572
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1915
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1804
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 17555
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 237498004 (226.50 MB)
telemt_user_octets_to_client{user="hello"} 6111984104 (5.69 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 8141.3 (2h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18189
telemt_connections_bad_total 133
telemt_handshake_timeouts_total 529
telemt_upstream_connect_attempt_total 3558
telemt_upstream_connect_success_total 3530
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 3558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1774
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 96650
telemt_me_reconnect_success_total 2771
telemt_me_reader_eof_total 2907
telemt_me_idle_close_by_peer_total 2907
telemt_me_route_drop_no_conn_total 7336
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16224
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2893
telemt_me_refill_failed_total 3045
telemt_me_writer_restored_same_endpoint_total 2733
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 16517
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 517877249 (493.89 MB)
telemt_user_octets_to_client{user="hello"} 7730102318 (7.20 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 8146.1 (2h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25998
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 181
telemt_upstream_connect_attempt_total 2265
telemt_upstream_connect_success_total 2253
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 1819
telemt_me_reconnect_success_total 1806
telemt_me_reader_eof_total 1841
telemt_me_idle_close_by_peer_total 1841
telemt_me_route_drop_no_conn_total 12436
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24697
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 294
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 212
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1817
telemt_me_writer_restored_same_endpoint_total 1804
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 24579
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 290202428 (276.76 MB)
telemt_user_octets_to_client{user="hello"} 9763932916 (9.09 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 8139.3 (2h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17766
telemt_connections_bad_total 1652
telemt_handshake_timeouts_total 231
telemt_upstream_connect_attempt_total 1776
telemt_upstream_connect_success_total 1749
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 1776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 7811
telemt_me_reconnect_success_total 1304
telemt_me_reader_eof_total 1490
telemt_me_idle_close_by_peer_total 1490
telemt_me_route_drop_no_conn_total 6443
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14996
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 65
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1506
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 1300
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 14992
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 121446560 (115.82 MB)
telemt_user_octets_to_client{user="hello"} 3773756792 (3.51 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 8139.1 (2h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64124
telemt_connections_bad_total 199
telemt_handshake_timeouts_total 448
telemt_upstream_connect_attempt_total 1826
telemt_upstream_connect_success_total 1786
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 1825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 890
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 1371
telemt_me_reconnect_success_total 1340
telemt_me_reader_eof_total 1361
telemt_me_idle_close_by_peer_total 1361
telemt_me_route_drop_no_conn_total 32267
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59449
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1352
telemt_me_writer_restored_same_endpoint_total 1336
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 59354
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 1018080564 (970.92 MB)
telemt_user_octets_to_client{user="hello"} 22904426772 (21.33 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 88
```
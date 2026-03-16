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

# Server Metrics 2026-03-16 09:10:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 125783.2 (34h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 599046
telemt_connections_bad_total 9295
telemt_handshake_timeouts_total 20847
telemt_upstream_connect_attempt_total 29459
telemt_upstream_connect_success_total 29318
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 29459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16214
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 26538
telemt_me_reconnect_success_total 23098
telemt_me_reader_eof_total 24678
telemt_me_idle_close_by_peer_total 24678
telemt_me_route_drop_no_conn_total 534660
telemt_me_route_drop_channel_closed_total 85
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 589522
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2772
telemt_desync_full_logged_total 1086
telemt_desync_suppressed_total 1686
telemt_desync_frames_bucket_total{bucket="1_2"} 613
telemt_desync_frames_bucket_total{bucket="3_10"} 1062
telemt_desync_frames_bucket_total{bucket="gt_10"} 1097
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23458
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 23064
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 360
telemt_user_connections_total{user="hello"} 528327
telemt_user_connections_current{user="hello"} 506
telemt_user_octets_from_client{user="hello"} 10209952836 (9.51 GB)
telemt_user_octets_to_client{user="hello"} 332492730828 (309.66 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 125790.9 (34h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244941
telemt_connections_bad_total 3290
telemt_handshake_timeouts_total 15271
telemt_upstream_connect_attempt_total 33682
telemt_upstream_connect_success_total 33607
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 33682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18457
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 670
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 36257
telemt_me_reconnect_success_total 26967
telemt_me_reader_eof_total 28922
telemt_me_idle_close_by_peer_total 28921
telemt_me_route_drop_no_conn_total 117829
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217909
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 183
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 126
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 27633
telemt_me_refill_failed_total 282
telemt_me_writer_restored_same_endpoint_total 26951
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 666
telemt_user_connections_total{user="hello"} 217446
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 4859747957 (4.53 GB)
telemt_user_octets_to_client{user="hello"} 120148283268 (111.90 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 125783.3 (34h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256152
telemt_connections_bad_total 5754
telemt_handshake_timeouts_total 5287
telemt_upstream_connect_attempt_total 35003
telemt_upstream_connect_success_total 34995
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 35003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 36115
telemt_me_reconnect_success_total 28701
telemt_me_reader_eof_total 30869
telemt_me_idle_close_by_peer_total 30868
telemt_me_route_drop_no_conn_total 88971
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206847
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 100
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 29218
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 28693
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 206548
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 17638400845 (16.43 GB)
telemt_user_octets_to_client{user="hello"} 116239148628 (108.26 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 125782.7 (34h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363450
telemt_connections_bad_total 1378
telemt_handshake_timeouts_total 3142
telemt_upstream_connect_attempt_total 29042
telemt_upstream_connect_success_total 29006
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 29042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14935
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 22913
telemt_me_reconnect_success_total 22764
telemt_me_reader_eof_total 24303
telemt_me_idle_close_by_peer_total 24302
telemt_me_route_drop_no_conn_total 126689
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 335836
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1241
telemt_desync_full_logged_total 426
telemt_desync_suppressed_total 815
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 533
telemt_desync_frames_bucket_total{bucket="gt_10"} 455
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 23068
telemt_me_writer_restored_same_endpoint_total 22753
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 335713
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 5790032634 (5.39 GB)
telemt_user_octets_to_client{user="hello"} 139055785340 (129.51 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 100854.1 (28h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232180
telemt_connections_bad_total 36956
telemt_handshake_timeouts_total 4223
telemt_upstream_connect_attempt_total 28732
telemt_upstream_connect_success_total 28575
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 28732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15784
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 117900
telemt_me_reconnect_success_total 23401
telemt_me_reader_eof_total 24855
telemt_me_idle_close_by_peer_total 24855
telemt_me_route_drop_no_conn_total 72540
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184365
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 597
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 459
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 265
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 23600
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 23297
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 183983
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 2437904245 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 78021521227 (72.66 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 125782.0 (34h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 845711
telemt_connections_bad_total 72545
telemt_handshake_timeouts_total 9853
telemt_upstream_connect_attempt_total 26310
telemt_upstream_connect_success_total 26172
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 26310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13649
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 21275
telemt_me_reconnect_success_total 19923
telemt_me_reader_eof_total 21271
telemt_me_idle_close_by_peer_total 21271
telemt_me_route_drop_no_conn_total 658263
telemt_me_route_drop_channel_closed_total 115
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 837274
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 20204
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 19896
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 695897
telemt_user_connections_current{user="hello"} 600
telemt_user_octets_from_client{user="hello"} 14963590820 (13.94 GB)
telemt_user_octets_to_client{user="hello"} 420850555304 (391.95 GB)
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 107
```
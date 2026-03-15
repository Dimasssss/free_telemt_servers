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

# Server Metrics 2026-03-15 05:27:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 25987.5 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64925
telemt_connections_bad_total 400
telemt_handshake_timeouts_total 1333
telemt_upstream_connect_attempt_total 6448
telemt_upstream_connect_success_total 6410
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 6448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3490
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5136
telemt_me_reconnect_success_total 5117
telemt_me_reader_eof_total 5474
telemt_me_idle_close_by_peer_total 5474
telemt_me_route_drop_no_conn_total 19809
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60894
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 478
telemt_desync_full_logged_total 216
telemt_desync_suppressed_total 262
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 5154
telemt_me_writer_restored_same_endpoint_total 5086
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 60890
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 749283160 (714.57 MB)
telemt_user_octets_to_client{user="hello"} 20137832900 (18.75 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 25994.1 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23143
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 76
telemt_upstream_connect_attempt_total 7101
telemt_upstream_connect_success_total 7101
telemt_upstream_connect_attempts_per_request{bucket="1"} 7101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5822
telemt_me_reconnect_success_total 5796
telemt_me_reader_eof_total 6226
telemt_me_idle_close_by_peer_total 6226
telemt_me_route_drop_no_conn_total 11406
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21982
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 5850
telemt_me_writer_restored_same_endpoint_total 5780
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 21985
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 684003864 (652.32 MB)
telemt_user_octets_to_client{user="hello"} 7783116144 (7.25 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 25986.7 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29749
telemt_connections_bad_total 430
telemt_handshake_timeouts_total 1717
telemt_upstream_connect_attempt_total 6942
telemt_upstream_connect_success_total 6941
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3892
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 5668
telemt_me_reconnect_success_total 5641
telemt_me_reader_eof_total 6092
telemt_me_idle_close_by_peer_total 6092
telemt_me_route_drop_no_conn_total 9980
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26638
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 5693
telemt_me_writer_restored_same_endpoint_total 5637
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 26589
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 8731200344 (8.13 GB)
telemt_user_octets_to_client{user="hello"} 16545777984 (15.41 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 25986.3 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30211
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 177
telemt_upstream_connect_attempt_total 6122
telemt_upstream_connect_success_total 6121
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3256
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 4852
telemt_me_reconnect_success_total 4835
telemt_me_reader_eof_total 5173
telemt_me_idle_close_by_peer_total 5173
telemt_me_route_drop_no_conn_total 14038
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28197
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4887
telemt_me_writer_restored_same_endpoint_total 4824
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 28117
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 552575016 (526.98 MB)
telemt_user_octets_to_client{user="hello"} 18047272684 (16.81 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 1057.9 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1515
telemt_connections_bad_total 187
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 890
telemt_upstream_connect_success_total 867
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 486
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 94999
telemt_me_reconnect_success_total 613
telemt_me_reader_eof_total 540
telemt_me_idle_close_by_peer_total 540
telemt_me_route_drop_no_conn_total 365
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1139
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 528
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 509
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 1284
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 8564065 (8.17 MB)
telemt_user_octets_to_client{user="hello"} 694764607 (662.58 MB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 25985.7 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80657
telemt_connections_bad_total 1651
telemt_handshake_timeouts_total 351
telemt_upstream_connect_attempt_total 5760
telemt_upstream_connect_success_total 5729
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 5760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2869
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_reconnect_attempts_total 4453
telemt_me_reconnect_success_total 4433
telemt_me_reader_eof_total 4711
telemt_me_idle_close_by_peer_total 4711
telemt_me_route_drop_no_conn_total 44168
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77883
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4451
telemt_me_writer_restored_same_endpoint_total 4406
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 76445
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 2026291832 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 45698013856 (42.56 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 38
```
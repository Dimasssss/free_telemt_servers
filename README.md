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

# Server Metrics 2026-03-15 06:53:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 31169.1 (8h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91519
telemt_connections_bad_total 485
telemt_handshake_timeouts_total 1949
telemt_upstream_connect_attempt_total 7577
telemt_upstream_connect_success_total 7532
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 7577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6000
telemt_me_reconnect_success_total 5980
telemt_me_reader_eof_total 6405
telemt_me_idle_close_by_peer_total 6405
telemt_me_route_drop_no_conn_total 105257
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98346
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 753
telemt_desync_full_logged_total 329
telemt_desync_suppressed_total 424
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 316
telemt_desync_frames_bucket_total{bucket="gt_10"} 304
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 6028
telemt_me_writer_restored_same_endpoint_total 5949
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 85437
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 1101805572 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 55959816740 (52.12 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 31176.4 (8h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30300
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 122
telemt_upstream_connect_attempt_total 8367
telemt_upstream_connect_success_total 8367
telemt_upstream_connect_attempts_per_request{bucket="1"} 8367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4682
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6830
telemt_me_reconnect_success_total 6803
telemt_me_reader_eof_total 7314
telemt_me_idle_close_by_peer_total 7314
telemt_me_route_drop_no_conn_total 15540
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28837
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 6868
telemt_me_writer_restored_same_endpoint_total 6787
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 28840
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 758483088 (723.35 MB)
telemt_user_octets_to_client{user="hello"} 10880789448 (10.13 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 31168.9 (8h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38232
telemt_connections_bad_total 457
telemt_handshake_timeouts_total 1798
telemt_upstream_connect_attempt_total 8287
telemt_upstream_connect_success_total 8286
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4631
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6753
telemt_me_reconnect_success_total 6723
telemt_me_reader_eof_total 7270
telemt_me_idle_close_by_peer_total 7270
telemt_me_route_drop_no_conn_total 13222
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34678
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 6781
telemt_me_writer_restored_same_endpoint_total 6719
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 34616
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 8805707896 (8.20 GB)
telemt_user_octets_to_client{user="hello"} 18721289220 (17.44 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 31168.8 (8h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43463
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 276
telemt_upstream_connect_attempt_total 7302
telemt_upstream_connect_success_total 7301
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 5774
telemt_me_reconnect_success_total 5752
telemt_me_reader_eof_total 6165
telemt_me_idle_close_by_peer_total 6165
telemt_me_route_drop_no_conn_total 18848
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39134
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 81
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 59
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5812
telemt_me_writer_restored_same_endpoint_total 5741
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 39053
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 729422176 (695.63 MB)
telemt_user_octets_to_client{user="hello"} 24885993916 (23.18 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 6240.3 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8860
telemt_connections_bad_total 1182
telemt_handshake_timeouts_total 155
telemt_upstream_connect_attempt_total 2476
telemt_upstream_connect_success_total 2445
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 2476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_reconnect_attempts_total 96359
telemt_me_reconnect_success_total 1966
telemt_me_reader_eof_total 1969
telemt_me_idle_close_by_peer_total 1969
telemt_me_route_drop_no_conn_total 2405
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7204
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1896
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 1862
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 7349
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 42466957 (40.50 MB)
telemt_user_octets_to_client{user="hello"} 2503615035 (2.33 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 31168.0 (8h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110937
telemt_connections_bad_total 4304
telemt_handshake_timeouts_total 503
telemt_upstream_connect_attempt_total 6806
telemt_upstream_connect_success_total 6767
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 6806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3365
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 5231
telemt_me_reconnect_success_total 5208
telemt_me_reader_eof_total 5547
telemt_me_idle_close_by_peer_total 5547
telemt_me_route_drop_no_conn_total 58439
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102981
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5232
telemt_me_writer_restored_same_endpoint_total 5181
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 101539
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 2568150684 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 51723733960 (48.17 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 55
```
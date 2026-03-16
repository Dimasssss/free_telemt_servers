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

# Server Metrics 2026-03-16 14:17:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 2379.1 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30683
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 832
telemt_upstream_connect_attempt_total 437
telemt_upstream_connect_success_total 435
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 201
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 279
telemt_me_reconnect_success_total 275
telemt_me_reader_eof_total 243
telemt_me_idle_close_by_peer_total 243
telemt_me_route_drop_no_conn_total 8832
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28431
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 265
telemt_me_writer_restored_same_endpoint_total 273
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 28377
telemt_user_connections_current{user="hello"} 778
telemt_user_octets_from_client{user="hello"} 639216368 (609.60 MB)
telemt_user_octets_to_client{user="hello"} 18016807668 (16.78 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 1882.7 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20641
telemt_connections_bad_total 889
telemt_handshake_timeouts_total 86
telemt_upstream_connect_attempt_total 18898
telemt_upstream_connect_success_total 18872
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 18897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1141
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2265
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18870
telemt_user_connections_current{user="hello"} 693
telemt_user_octets_from_client{user="hello"} 148147056 (141.28 MB)
telemt_user_octets_to_client{user="hello"} 2450727723 (2.28 GB)
telemt_user_msgs_from_client{user="hello"} 217616
telemt_user_msgs_to_client{user="hello"} 821674
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 2491.9 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12677
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 87
telemt_upstream_connect_attempt_total 2094
telemt_upstream_connect_success_total 2064
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 2094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 29280
telemt_me_reconnect_success_total 939
telemt_me_reader_eof_total 904
telemt_me_idle_close_by_peer_total 904
telemt_me_route_drop_no_conn_total 2869
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10880
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 925
telemt_me_refill_failed_total 885
telemt_me_writer_restored_same_endpoint_total 895
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_user_connections_total{user="hello"} 11837
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 139587150 (133.12 MB)
telemt_user_octets_to_client{user="hello"} 2007405146 (1.87 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 2628.1 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22011
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 216
telemt_upstream_connect_attempt_total 615
telemt_upstream_connect_success_total 613
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 256
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 448
telemt_me_reconnect_success_total 436
telemt_me_reader_eof_total 415
telemt_me_idle_close_by_peer_total 415
telemt_me_route_drop_no_conn_total 6505
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20865
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 165
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 71
telemt_me_writer_removed_unexpected_total 432
telemt_me_writer_restored_same_endpoint_total 432
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_user_connections_total{user="hello"} 20848
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 530221144 (505.66 MB)
telemt_user_octets_to_client{user="hello"} 4428878004 (4.12 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 88.7 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 626
telemt_connections_bad_total 42
telemt_upstream_connect_attempt_total 98
telemt_upstream_connect_success_total 96
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 98
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 31
telemt_me_reconnect_success_total 30
telemt_me_route_drop_no_conn_total 67
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 566
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 16
telemt_me_writer_restored_same_endpoint_total 30
telemt_me_async_recovery_trigger_total 22
telemt_user_connections_total{user="hello"} 552
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 88225108 (84.14 MB)
telemt_user_octets_to_client{user="hello"} 16555688 (15.79 MB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 2196.0 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27605
telemt_connections_bad_total 584
telemt_handshake_timeouts_total 178
telemt_upstream_connect_attempt_total 465
telemt_upstream_connect_success_total 465
telemt_upstream_connect_attempts_per_request{bucket="1"} 465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 192
telemt_me_reconnect_attempts_total 305
telemt_me_reconnect_success_total 303
telemt_me_reader_eof_total 273
telemt_me_idle_close_by_peer_total 273
telemt_me_route_drop_no_conn_total 11777
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26134
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_me_writer_removed_unexpected_total 295
telemt_me_writer_restored_same_endpoint_total 299
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_user_connections_total{user="hello"} 26007
telemt_user_connections_current{user="hello"} 778
telemt_user_octets_from_client{user="hello"} 537829776 (512.91 MB)
telemt_user_octets_to_client{user="hello"} 6451200956 (6.01 GB)
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 109
```
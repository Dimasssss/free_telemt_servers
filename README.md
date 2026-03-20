# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

**Принимаю донаты криптой для добавления и продления серверов:**  
- TON: UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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
Этот сервер пользуется большим спросом. Я арендовал еще один такой же, чтобы распределить нагрузку.

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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-20 10:21:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.27

telemt_uptime_seconds 242.1 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48375
telemt_connections_bad_total 627
telemt_connections_current 2148
telemt_connections_me_current 2148
telemt_handshake_timeouts_total 185
telemt_upstream_connect_attempt_total 140
telemt_upstream_connect_success_total 134
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 92362
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43618
telemt_me_endpoint_quarantine_total 6
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_close_signal_drop_total 3
telemt_me_draining_writers_reap_progress_total 53
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53
telemt_me_writer_teardown_success_total{mode="normal"} 50
telemt_me_writer_teardown_noop_total 53
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.798250
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 3
telemt_user_connections_total{user="hello"} 43517
telemt_user_connections_current{user="hello"} 2148
telemt_user_octets_from_client{user="hello"} 198706368 (189.50 MB)
telemt_user_octets_to_client{user="hello"} 685487280 (653.73 MB)
telemt_user_unique_ips_current{user="hello"} 586
telemt_user_unique_ips_recent_window{user="hello"} 441
```

## psb.hosting №1

```
telemt 3.3.27

telemt_uptime_seconds 224.1 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32153
telemt_connections_bad_total 1880
telemt_connections_current 4920
telemt_connections_me_current 4920
telemt_handshake_timeouts_total 833
telemt_upstream_connect_attempt_total 133
telemt_upstream_connect_success_total 132
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_route_drop_no_conn_total 10696
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25440
telemt_me_endpoint_quarantine_total 5
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 68
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_me_draining_writers_reap_progress_total 49
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49
telemt_me_writer_teardown_success_total{mode="normal"} 49
telemt_me_writer_teardown_noop_total 49
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.002582
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98
telemt_user_connections_total{user="hello"} 25449
telemt_user_connections_current{user="hello"} 4920
telemt_user_octets_from_client{user="hello"} 178864484 (170.58 MB)
telemt_user_octets_to_client{user="hello"} 4966601600 (4.63 GB)
telemt_user_unique_ips_current{user="hello"} 1630
telemt_user_unique_ips_recent_window{user="hello"} 530
```

## psb.hosting №2

```
telemt 3.3.27

telemt_uptime_seconds 212.7 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17980
telemt_connections_bad_total 1580
telemt_connections_current 2596
telemt_connections_me_current 2596
telemt_handshake_timeouts_total 296
telemt_upstream_connect_attempt_total 133
telemt_upstream_connect_success_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 56
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 5697
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15084
telemt_me_single_endpoint_shadow_rotate_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 15
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_draining_writers_reap_progress_total 49
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49
telemt_me_writer_teardown_success_total{mode="normal"} 49
telemt_me_writer_teardown_noop_total 49
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.003817
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98
telemt_user_connections_total{user="hello"} 15086
telemt_user_connections_current{user="hello"} 2596
telemt_user_octets_from_client{user="hello"} 123562220 (117.84 MB)
telemt_user_octets_to_client{user="hello"} 5318403776 (4.95 GB)
telemt_user_unique_ips_current{user="hello"} 946
telemt_user_unique_ips_recent_window{user="hello"} 444
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

Не удалось получить метрики для этого сервера.

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 15430.9 (4h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3664518
telemt_connections_bad_total 260063
telemt_connections_current 6562
telemt_connections_me_current 6562
telemt_handshake_timeouts_total 40417
telemt_upstream_connect_attempt_total 2571
telemt_upstream_connect_success_total 2556
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 2571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1234
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 256
telemt_me_reconnect_attempts_total 1735
telemt_me_reconnect_success_total 1725
telemt_me_reader_eof_total 1785
telemt_me_idle_close_by_peer_total 1783
telemt_me_route_drop_no_conn_total 6042174
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3134274
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6668
telemt_desync_full_logged_total 1890
telemt_desync_suppressed_total 4778
telemt_desync_frames_bucket_total{bucket="1_2"} 1261
telemt_desync_frames_bucket_total{bucket="3_10"} 2784
telemt_desync_frames_bucket_total{bucket="gt_10"} 2623
telemt_pool_swap_total 10
telemt_me_writer_close_signal_drop_total 49
telemt_me_writer_removed_unexpected_total 1744
telemt_me_writer_restored_same_endpoint_total 1695
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 3128884
telemt_user_connections_current{user="hello"} 6562
telemt_user_octets_from_client{user="hello"} 26579346120 (24.75 GB)
telemt_user_octets_to_client{user="hello"} 360991858148 (336.20 GB)
telemt_user_unique_ips_current{user="hello"} 2057
telemt_user_unique_ips_recent_window{user="hello"} 1016
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 5009.6 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116640
telemt_connections_bad_total 25739
telemt_connections_current 831
telemt_connections_me_current 831
telemt_relay_adaptive_promotions_total 2
telemt_relay_adaptive_hard_promotions_total 2
telemt_handshake_timeouts_total 1701
telemt_upstream_connect_attempt_total 2420
telemt_upstream_connect_success_total 2397
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 2420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 534
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 744
telemt_me_reconnect_success_total 739
telemt_me_reader_eof_total 720
telemt_me_idle_close_by_peer_total 720
telemt_me_route_drop_no_conn_total 42564
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83129
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 8
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 180
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 711
telemt_me_writer_restored_same_endpoint_total 737
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 168
telemt_me_async_recovery_trigger_total 1532
telemt_user_connections_total{user="hello"} 84649
telemt_user_connections_current{user="hello"} 831
telemt_user_octets_from_client{user="hello"} 1304730895 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 15430780084 (14.37 GB)
telemt_user_msgs_from_client{user="hello"} 4554
telemt_user_msgs_to_client{user="hello"} 7676
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 77813.6 (21h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4315533
telemt_connections_bad_total 291789
telemt_connections_current 6906
telemt_connections_me_current 6906
telemt_handshake_timeouts_total 100540
telemt_upstream_connect_attempt_total 13590
telemt_upstream_connect_success_total 13505
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 13590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 9698
telemt_me_reconnect_success_total 9629
telemt_me_reader_eof_total 10190
telemt_me_idle_close_by_peer_total 10189
telemt_me_route_drop_no_conn_total 1569593
telemt_me_route_drop_channel_closed_total 42
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3626346
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17275
telemt_desync_full_logged_total 5702
telemt_desync_suppressed_total 11573
telemt_desync_frames_bucket_total{bucket="1_2"} 3635
telemt_desync_frames_bucket_total{bucket="3_10"} 6265
telemt_desync_frames_bucket_total{bucket="gt_10"} 7375
telemt_pool_swap_total 77
telemt_me_writer_close_signal_drop_total 61
telemt_me_writer_removed_unexpected_total 9776
telemt_me_writer_restored_same_endpoint_total 9612
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 3624204
telemt_user_connections_current{user="hello"} 6906
telemt_user_octets_from_client{user="hello"} 81378741884 (75.79 GB)
telemt_user_octets_to_client{user="hello"} 1813154911892 (1.65 TB)
telemt_user_unique_ips_current{user="hello"} 2115
telemt_user_unique_ips_recent_window{user="hello"} 798
```
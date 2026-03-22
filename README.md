# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-22 14:52:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 63980.5 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2154212
telemt_connections_bad_total 105206
telemt_connections_current 2297
telemt_connections_me_current 2297
telemt_handshake_timeouts_total 84071
telemt_upstream_connect_attempt_total 23805
telemt_upstream_connect_success_total 23804
telemt_upstream_connect_attempts_per_request{bucket="1"} 23804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15468
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 977
telemt_me_reconnect_success_total 401
telemt_me_reader_eof_total 403
telemt_me_idle_close_by_peer_total 403
telemt_me_route_drop_no_conn_total 1628609
telemt_me_route_drop_channel_closed_total 686
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1831959
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 437
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 501
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_me_writers_warm_current 37
telemt_desync_total 9351
telemt_desync_full_logged_total 2891
telemt_desync_suppressed_total 6460
telemt_desync_frames_bucket_total{bucket="1_2"} 2576
telemt_desync_frames_bucket_total{bucket="3_10"} 3502
telemt_desync_frames_bucket_total{bucket="gt_10"} 3273
telemt_pool_swap_total 70
telemt_pool_force_close_total 2139
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 368
telemt_me_draining_writers_reap_progress_total 21691
telemt_me_writer_removed_unexpected_total 390
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1561
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20341
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2095
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 44
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19552
telemt_me_writer_teardown_success_total{mode="normal"} 21902
telemt_me_writer_teardown_noop_total 21695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43597
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 179.419619
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43597
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 368
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 352
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 1828931
telemt_user_connections_current{user="hello"} 2297
telemt_user_octets_from_client{user="hello"} 28167242956 (26.23 GB)
telemt_user_octets_to_client{user="hello"} 506715593956 (471.92 GB)
telemt_user_unique_ips_current{user="hello"} 743
telemt_user_unique_ips_recent_window{user="hello"} 608
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 77346.4 (21h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3416939
telemt_connections_bad_total 307982
telemt_connections_current 1826
telemt_connections_me_current 1826
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 80328
telemt_upstream_connect_attempt_total 49151
telemt_upstream_connect_success_total 48558
telemt_upstream_connect_fail_total 524
telemt_upstream_connect_attempts_per_request{bucket="1"} 49082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19651
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 524
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 5591
telemt_me_reconnect_success_total 1899
telemt_me_reader_eof_total 1822
telemt_me_idle_close_by_peer_total 1822
telemt_me_route_drop_no_conn_total 3377047
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2708871
telemt_me_endpoint_quarantine_total 630
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 600
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 10426
telemt_desync_full_logged_total 5793
telemt_desync_suppressed_total 4633
telemt_desync_frames_bucket_total{bucket="1_2"} 2459
telemt_desync_frames_bucket_total{bucket="3_10"} 4117
telemt_desync_frames_bucket_total{bucket="gt_10"} 3850
telemt_pool_swap_total 74
telemt_pool_force_close_total 2174
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 185
telemt_me_draining_writers_reap_progress_total 30587
telemt_me_writer_removed_unexpected_total 1780
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3536
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28832
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 292
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28413
telemt_me_writer_teardown_success_total{mode="normal"} 32368
telemt_me_writer_teardown_noop_total 30587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62955
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.344968
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62955
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 185
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1610
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 2720280
telemt_user_connections_current{user="hello"} 1826
telemt_user_octets_from_client{user="hello"} 32565012231 (30.33 GB)
telemt_user_octets_to_client{user="hello"} 594290197634 (553.48 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1267
telemt_user_unique_ips_recent_window{user="hello"} 697
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 152207.3 (42h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14825465
telemt_connections_bad_total 1329472
telemt_connections_current 4716
telemt_connections_me_current 4716
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 363126
telemt_upstream_connect_attempt_total 69320
telemt_upstream_connect_success_total 69226
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 69243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32545
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1656
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2535
telemt_me_reconnect_success_total 1319
telemt_me_reader_eof_total 1257
telemt_me_idle_close_by_peer_total 1256
telemt_me_route_drop_no_conn_total 13363764
telemt_me_route_drop_channel_closed_total 132
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11882948
telemt_me_endpoint_quarantine_total 966
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1130
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_me_writers_active_current 45
telemt_desync_total 47934
telemt_desync_full_logged_total 15100
telemt_desync_suppressed_total 32834
telemt_desync_frames_bucket_total{bucket="1_2"} 10835
telemt_desync_frames_bucket_total{bucket="3_10"} 18771
telemt_desync_frames_bucket_total{bucket="gt_10"} 18328
telemt_pool_swap_total 164
telemt_pool_force_close_total 5550
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 906
telemt_me_draining_writers_reap_progress_total 50077
telemt_me_writer_removed_unexpected_total 1212
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4360
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46249
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5099
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 451
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44527
telemt_me_writer_teardown_success_total{mode="normal"} 50609
telemt_me_writer_teardown_noop_total 50126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100735
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 286.762523
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100735
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 906
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 1132
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 11884608
telemt_user_connections_current{user="hello"} 4716
telemt_user_octets_from_client{user="hello"} 166641396609 (155.20 GB)
telemt_user_octets_to_client{user="hello"} 3070222691175 (2.79 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 1914
telemt_user_unique_ips_recent_window{user="hello"} 850
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 152207.6 (42h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10766102
telemt_connections_bad_total 1038490
telemt_connections_current 4667
telemt_connections_me_current 4667
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 318577
telemt_upstream_connect_attempt_total 81340
telemt_upstream_connect_success_total 80191
telemt_upstream_connect_fail_total 826
telemt_upstream_connect_attempts_per_request{bucket="1"} 81017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32348
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3683
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 826
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3782
telemt_me_reconnect_success_total 1494
telemt_me_reader_eof_total 1367
telemt_me_idle_close_by_peer_total 1367
telemt_me_route_drop_no_conn_total 4264717
telemt_me_route_drop_channel_closed_total 467
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8035744
telemt_me_endpoint_quarantine_total 954
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1152
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 32
telemt_desync_total 35814
telemt_desync_full_logged_total 12029
telemt_desync_suppressed_total 23785
telemt_desync_frames_bucket_total{bucket="1_2"} 8810
telemt_desync_frames_bucket_total{bucket="3_10"} 13788
telemt_desync_frames_bucket_total{bucket="gt_10"} 13216
telemt_pool_swap_total 162
telemt_pool_force_close_total 5012
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 633
telemt_me_draining_writers_reap_progress_total 48281
telemt_me_writer_removed_unexpected_total 1399
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4401
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45136
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4575
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 437
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43269
telemt_me_writer_teardown_success_total{mode="normal"} 49537
telemt_me_writer_teardown_noop_total 48296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97833
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 96.581175
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97833
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 633
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 1265
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 7974782
telemt_user_connections_current{user="hello"} 4667
telemt_user_octets_from_client{user="hello"} 201137940653 (187.32 GB)
telemt_user_octets_to_client{user="hello"} 3592681026486 (3.27 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1968
telemt_user_unique_ips_recent_window{user="hello"} 711
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 152172.5 (42h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10214785
telemt_connections_bad_total 871063
telemt_connections_current 4206
telemt_connections_me_current 4206
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 327183
telemt_upstream_connect_attempt_total 66779
telemt_upstream_connect_success_total 65856
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 66038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31028
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2038
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4541
telemt_me_reconnect_success_total 1847
telemt_me_reader_eof_total 1600
telemt_me_idle_close_by_peer_total 1599
telemt_me_route_drop_no_conn_total 5052167
telemt_me_route_drop_channel_closed_total 346
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7713277
telemt_me_endpoint_quarantine_total 1047
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1113
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_me_writers_warm_current 18
telemt_desync_total 35459
telemt_desync_full_logged_total 11741
telemt_desync_suppressed_total 23718
telemt_desync_frames_bucket_total{bucket="1_2"} 8971
telemt_desync_frames_bucket_total{bucket="3_10"} 13577
telemt_desync_frames_bucket_total{bucket="gt_10"} 12911
telemt_pool_swap_total 158
telemt_pool_force_close_total 4960
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 669
telemt_me_draining_writers_reap_progress_total 48898
telemt_me_writer_removed_unexpected_total 1744
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4891
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45659
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4428
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 532
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43938
telemt_me_writer_teardown_success_total{mode="normal"} 50550
telemt_me_writer_teardown_noop_total 48968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99518
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3167.395382
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99518
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 669
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 1604
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 7706649
telemt_user_connections_current{user="hello"} 4206
telemt_user_octets_from_client{user="hello"} 178895338225 (166.61 GB)
telemt_user_octets_to_client{user="hello"} 3198189514081 (2.91 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1760
telemt_user_unique_ips_recent_window{user="hello"} 743
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 22451.4 (6h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9502079
telemt_connections_bad_total 592784
telemt_connections_current 6709
telemt_connections_me_current 6709
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 152518
telemt_upstream_connect_attempt_total 29483
telemt_upstream_connect_success_total 28019
telemt_upstream_connect_fail_total 1034
telemt_upstream_connect_attempts_per_request{bucket="1"} 29053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7172
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4761
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1034
telemt_me_keepalive_timeout_total 887
telemt_me_reconnect_attempts_total 5526
telemt_me_reconnect_success_total 604
telemt_me_reader_eof_total 397
telemt_me_idle_close_by_peer_total 397
telemt_me_route_drop_no_conn_total 23511466
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7914606
telemt_me_endpoint_quarantine_total 137
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 63
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 63
telemt_me_single_endpoint_shadow_rotate_total 169
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 11880
telemt_desync_full_logged_total 3048
telemt_desync_suppressed_total 8832
telemt_desync_frames_bucket_total{bucket="1_2"} 2095
telemt_desync_frames_bucket_total{bucket="3_10"} 4829
telemt_desync_frames_bucket_total{bucket="gt_10"} 4956
telemt_pool_swap_total 20
telemt_pool_force_close_total 855
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 307
telemt_me_draining_writers_reap_progress_total 5923
telemt_me_writer_removed_unexpected_total 516
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1013
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5389
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 590
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 265
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5068
telemt_me_writer_teardown_success_total{mode="normal"} 6402
telemt_me_writer_teardown_noop_total 5927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12329
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 28.522178
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12329
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 307
telemt_me_refill_failed_total 284
telemt_me_writer_restored_same_endpoint_total 432
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 7929239
telemt_user_connections_current{user="hello"} 6709
telemt_user_octets_from_client{user="hello"} 45132701491 (42.03 GB)
telemt_user_octets_to_client{user="hello"} 231837849008 (215.92 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2502
telemt_user_unique_ips_recent_window{user="hello"} 1333
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 152178.1 (42h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9933574
telemt_connections_bad_total 823867
telemt_connections_current 4934
telemt_connections_me_current 4934
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 217333
telemt_upstream_connect_attempt_total 91240
telemt_upstream_connect_success_total 90319
telemt_upstream_connect_fail_total 797
telemt_upstream_connect_attempts_per_request{bucket="1"} 91116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33090
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1259
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 797
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71500
telemt_me_reconnect_success_total 2481
telemt_me_reader_eof_total 2213
telemt_me_idle_close_by_peer_total 2212
telemt_me_route_drop_no_conn_total 4919115
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7844570
telemt_me_endpoint_quarantine_total 1017
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1130
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_me_writers_warm_current 22
telemt_desync_total 40368
telemt_desync_full_logged_total 13824
telemt_desync_suppressed_total 26544
telemt_desync_frames_bucket_total{bucket="1_2"} 8210
telemt_desync_frames_bucket_total{bucket="3_10"} 15650
telemt_desync_frames_bucket_total{bucket="gt_10"} 16508
telemt_pool_swap_total 155
telemt_pool_force_close_total 4625
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 565
telemt_me_draining_writers_reap_progress_total 51674
telemt_me_writer_removed_unexpected_total 2239
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5465
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48466
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3973
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 652
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47049
telemt_me_writer_teardown_success_total{mode="normal"} 53931
telemt_me_writer_teardown_noop_total 51675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105606
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.048757
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105606
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 565
telemt_me_refill_failed_total 4258
telemt_me_writer_restored_same_endpoint_total 2084
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 7845162
telemt_user_connections_current{user="hello"} 4934
telemt_user_octets_from_client{user="hello"} 179071871859 (166.77 GB)
telemt_user_octets_to_client{user="hello"} 2955535965801 (2.69 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2035
telemt_user_unique_ips_recent_window{user="hello"} 682
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 89014.2 (24h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10203453
telemt_connections_bad_total 372601
telemt_connections_current 4750
telemt_connections_me_current 4750
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4297152
telemt_upstream_connect_attempt_total 43316
telemt_upstream_connect_success_total 43002
telemt_upstream_connect_fail_total 305
telemt_upstream_connect_attempts_per_request{bucket="1"} 43307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18422
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 305
telemt_me_reconnect_attempts_total 47952
telemt_me_reconnect_success_total 1466
telemt_me_reader_eof_total 1132
telemt_me_idle_close_by_peer_total 1132
telemt_me_route_drop_no_conn_total 3801455
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4909165
telemt_me_endpoint_quarantine_total 581
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 667
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 26835
telemt_desync_full_logged_total 9052
telemt_desync_suppressed_total 17783
telemt_desync_frames_bucket_total{bucket="1_2"} 5426
telemt_desync_frames_bucket_total{bucket="3_10"} 10602
telemt_desync_frames_bucket_total{bucket="gt_10"} 10807
telemt_pool_swap_total 93
telemt_pool_force_close_total 2889
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 298
telemt_me_draining_writers_reap_progress_total 30573
telemt_me_writer_removed_unexpected_total 1197
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2762
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29036
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2476
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 413
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27684
telemt_me_writer_teardown_success_total{mode="normal"} 31798
telemt_me_writer_teardown_noop_total 30580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62378
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.297265
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62378
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 298
telemt_me_refill_failed_total 2702
telemt_me_writer_restored_same_endpoint_total 1308
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4903195
telemt_user_connections_current{user="hello"} 4750
telemt_user_octets_from_client{user="hello"} 105986869952 (98.71 GB)
telemt_user_octets_to_client{user="hello"} 1845949326550 (1.68 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1898
telemt_user_unique_ips_recent_window{user="hello"} 672
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 69985.1 (19h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 873503
telemt_connections_bad_total 11167
telemt_connections_current 1106
telemt_connections_me_current 1106
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 17125
telemt_upstream_connect_attempt_total 34981
telemt_upstream_connect_success_total 34895
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 34965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 468
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_reconnect_attempts_total 1584
telemt_me_reconnect_success_total 669
telemt_me_reader_eof_total 644
telemt_me_idle_close_by_peer_total 644
telemt_me_route_drop_no_conn_total 299591
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 776964
telemt_me_endpoint_quarantine_total 619
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 582
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 4299
telemt_desync_full_logged_total 1305
telemt_desync_suppressed_total 2994
telemt_desync_frames_bucket_total{bucket="1_2"} 1021
telemt_desync_frames_bucket_total{bucket="3_10"} 1707
telemt_desync_frames_bucket_total{bucket="gt_10"} 1571
telemt_pool_swap_total 74
telemt_pool_force_close_total 1853
telemt_me_writer_close_signal_drop_total 107
telemt_me_draining_writers_reap_progress_total 28831
telemt_me_writer_removed_unexpected_total 623
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2212
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27265
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1775
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26978
telemt_me_writer_teardown_success_total{mode="normal"} 29477
telemt_me_writer_teardown_noop_total 28833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58310
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.319745
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58310
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 107
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 571
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 778120
telemt_user_connections_current{user="hello"} 1106
telemt_user_octets_from_client{user="hello"} 14549944585 (13.55 GB)
telemt_user_octets_to_client{user="hello"} 360755341383 (335.98 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 392
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 152182.7 (42h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12158911
telemt_connections_bad_total 1417710
telemt_connections_current 6575
telemt_connections_me_current 6575
telemt_handshake_timeouts_total 333658
telemt_upstream_connect_attempt_total 57030
telemt_upstream_connect_success_total 56807
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 56980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28752
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_reconnect_attempts_total 2213
telemt_me_reconnect_success_total 1189
telemt_me_reader_eof_total 1151
telemt_me_idle_close_by_peer_total 1151
telemt_me_route_drop_no_conn_total 3966340
telemt_me_route_drop_channel_closed_total 118
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9168389
telemt_me_endpoint_quarantine_total 1029
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1135
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_me_writers_warm_current 34
telemt_desync_total 37655
telemt_desync_full_logged_total 12319
telemt_desync_suppressed_total 25336
telemt_desync_frames_bucket_total{bucket="1_2"} 8980
telemt_desync_frames_bucket_total{bucket="3_10"} 13953
telemt_desync_frames_bucket_total{bucket="gt_10"} 14722
telemt_pool_swap_total 168
telemt_pool_force_close_total 4647
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 596
telemt_me_draining_writers_reap_progress_total 51332
telemt_me_writer_removed_unexpected_total 1107
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4217
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48252
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4476
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 171
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46685
telemt_me_writer_teardown_success_total{mode="normal"} 52469
telemt_me_writer_teardown_noop_total 51334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103803
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.535953
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103803
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 596
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1043
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 9138091
telemt_user_connections_current{user="hello"} 6575
telemt_user_octets_from_client{user="hello"} 176077672024 (163.99 GB)
telemt_user_octets_to_client{user="hello"} 4065612864856 (3.70 TB)
telemt_user_unique_ips_current{user="hello"} 2423
telemt_user_unique_ips_recent_window{user="hello"} 777
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 152179.0 (42h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10524449
telemt_connections_bad_total 1174951
telemt_connections_current 4898
telemt_connections_me_current 4898
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 272220
telemt_upstream_connect_attempt_total 82573
telemt_upstream_connect_success_total 81959
telemt_upstream_connect_fail_total 532
telemt_upstream_connect_attempts_per_request{bucket="1"} 82491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33787
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2013
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 532
telemt_me_reconnect_attempts_total 8756
telemt_me_reconnect_success_total 1975
telemt_me_reader_eof_total 1840
telemt_me_idle_close_by_peer_total 1840
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 5078150
telemt_me_route_drop_channel_closed_total 335
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8125012
telemt_me_endpoint_quarantine_total 1155
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1140
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 16
telemt_desync_total 37334
telemt_desync_full_logged_total 12064
telemt_desync_suppressed_total 25270
telemt_desync_frames_bucket_total{bucket="1_2"} 9302
telemt_desync_frames_bucket_total{bucket="3_10"} 13914
telemt_desync_frames_bucket_total{bucket="gt_10"} 14118
telemt_pool_swap_total 161
telemt_pool_force_close_total 4504
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 585
telemt_me_draining_writers_reap_progress_total 50625
telemt_me_writer_removed_unexpected_total 1865
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5252
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47305
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4092
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 412
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46121
telemt_me_writer_teardown_success_total{mode="normal"} 52557
telemt_me_writer_teardown_noop_total 50630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103187
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.805474
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103187
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 585
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 1598
telemt_me_writer_restored_fallback_total 98
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8131268
telemt_user_connections_current{user="hello"} 4898
telemt_user_octets_from_client{user="hello"} 143466367165 (133.61 GB)
telemt_user_octets_to_client{user="hello"} 3127410058483 (2.84 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1984
telemt_user_unique_ips_recent_window{user="hello"} 752
```
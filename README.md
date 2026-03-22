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

# Server Metrics 2026-03-22 10:15:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 47345.7 (13h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1244343
telemt_connections_bad_total 65567
telemt_connections_current 1831
telemt_connections_me_current 1831
telemt_handshake_timeouts_total 57261
telemt_upstream_connect_attempt_total 18371
telemt_upstream_connect_success_total 18369
telemt_upstream_connect_attempts_per_request{bucket="1"} 18369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11939
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 553
telemt_me_reconnect_success_total 284
telemt_me_reader_eof_total 283
telemt_me_idle_close_by_peer_total 283
telemt_me_route_drop_no_conn_total 688069
telemt_me_route_drop_channel_closed_total 299
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1038243
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 330
telemt_me_single_endpoint_shadow_rotate_total 380
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_desync_total 7026
telemt_desync_full_logged_total 2051
telemt_desync_suppressed_total 4975
telemt_desync_frames_bucket_total{bucket="1_2"} 2050
telemt_desync_frames_bucket_total{bucket="3_10"} 2658
telemt_desync_frames_bucket_total{bucket="gt_10"} 2318
telemt_pool_swap_total 52
telemt_pool_force_close_total 1516
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 193
telemt_me_draining_writers_reap_progress_total 16728
telemt_me_writer_removed_unexpected_total 280
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1153
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15773
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1484
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15212
telemt_me_writer_teardown_success_total{mode="normal"} 16926
telemt_me_writer_teardown_noop_total 16730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33656
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 82.619004
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33656
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 193
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 260
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1036397
telemt_user_connections_current{user="hello"} 1831
telemt_user_octets_from_client{user="hello"} 16335634140 (15.21 GB)
telemt_user_octets_to_client{user="hello"} 328652082480 (306.08 GB)
telemt_user_unique_ips_current{user="hello"} 671
telemt_user_unique_ips_recent_window{user="hello"} 277
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 60712.1 (16h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1950947
telemt_connections_bad_total 168526
telemt_connections_current 1627
telemt_connections_me_current 1627
telemt_handshake_timeouts_total 48469
telemt_upstream_connect_attempt_total 36019
telemt_upstream_connect_success_total 35539
telemt_upstream_connect_fail_total 421
telemt_upstream_connect_attempts_per_request{bucket="1"} 35960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 421
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3143
telemt_me_reconnect_success_total 1393
telemt_me_reader_eof_total 1286
telemt_me_idle_close_by_peer_total 1286
telemt_me_route_drop_no_conn_total 1291448
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1516296
telemt_me_endpoint_quarantine_total 520
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 481
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 6457
telemt_desync_full_logged_total 3672
telemt_desync_suppressed_total 2785
telemt_desync_frames_bucket_total{bucket="1_2"} 1449
telemt_desync_frames_bucket_total{bucket="3_10"} 2522
telemt_desync_frames_bucket_total{bucket="gt_10"} 2486
telemt_pool_swap_total 61
telemt_pool_force_close_total 1725
telemt_me_writer_close_signal_drop_total 142
telemt_me_draining_writers_reap_progress_total 24599
telemt_me_writer_removed_unexpected_total 1252
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2683
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23162
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1542
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 183
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22874
telemt_me_writer_teardown_success_total{mode="normal"} 25845
telemt_me_writer_teardown_noop_total 24599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50444
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.383576
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50444
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 142
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1162
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1522342
telemt_user_connections_current{user="hello"} 1627
telemt_user_octets_from_client{user="hello"} 21482652402 (20.01 GB)
telemt_user_octets_to_client{user="hello"} 446884892260 (416.19 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 1007
telemt_user_unique_ips_recent_window{user="hello"} 911
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 135571.9 (37h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11000883
telemt_connections_bad_total 958193
telemt_connections_current 5393
telemt_connections_me_current 5393
telemt_handshake_timeouts_total 307886
telemt_upstream_connect_attempt_total 49631
telemt_upstream_connect_success_total 49551
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 49559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26931
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 201
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2128
telemt_me_reconnect_success_total 1091
telemt_me_reader_eof_total 1074
telemt_me_idle_close_by_peer_total 1073
telemt_me_route_drop_no_conn_total 7450642
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8711881
telemt_me_endpoint_quarantine_total 869
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1011
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_me_writers_active_current 42
telemt_desync_total 36892
telemt_desync_full_logged_total 11990
telemt_desync_suppressed_total 24902
telemt_desync_frames_bucket_total{bucket="1_2"} 8290
telemt_desync_frames_bucket_total{bucket="3_10"} 14307
telemt_desync_frames_bucket_total{bucket="gt_10"} 14295
telemt_pool_swap_total 146
telemt_pool_force_close_total 4885
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 762
telemt_me_draining_writers_reap_progress_total 45260
telemt_me_writer_removed_unexpected_total 1032
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3865
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41877
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4553
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 332
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40375
telemt_me_writer_teardown_success_total{mode="normal"} 45742
telemt_me_writer_teardown_noop_total 45304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91046
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 205.574605
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91046
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 762
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 948
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 8701290
telemt_user_connections_current{user="hello"} 5393
telemt_user_octets_from_client{user="hello"} 135915911776 (126.58 GB)
telemt_user_octets_to_client{user="hello"} 2683501465960 (2.44 TB)
telemt_user_unique_ips_current{user="hello"} 2049
telemt_user_unique_ips_recent_window{user="hello"} 1145
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 135573.6 (37h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8724166
telemt_connections_bad_total 782944
telemt_connections_current 4695
telemt_connections_me_current 4695
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 269516
telemt_upstream_connect_attempt_total 55816
telemt_upstream_connect_success_total 55295
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 55548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27093
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 118
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 3026
telemt_me_reconnect_success_total 1185
telemt_me_reader_eof_total 1089
telemt_me_idle_close_by_peer_total 1089
telemt_me_route_drop_no_conn_total 3415495
telemt_me_route_drop_channel_closed_total 356
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6480341
telemt_me_endpoint_quarantine_total 860
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 1043
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 29294
telemt_desync_full_logged_total 9920
telemt_desync_suppressed_total 19374
telemt_desync_frames_bucket_total{bucket="1_2"} 7083
telemt_desync_frames_bucket_total{bucket="3_10"} 11329
telemt_desync_frames_bucket_total{bucket="gt_10"} 10882
telemt_pool_swap_total 147
telemt_pool_force_close_total 4461
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 492
telemt_me_draining_writers_reap_progress_total 43607
telemt_me_writer_removed_unexpected_total 1105
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3766
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40841
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4156
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 305
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39146
telemt_me_writer_teardown_success_total{mode="normal"} 44607
telemt_me_writer_teardown_noop_total 43613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88220
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 64.287093
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88220
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 492
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 1004
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 6402275
telemt_user_connections_current{user="hello"} 4695
telemt_user_octets_from_client{user="hello"} 169568024199 (157.92 GB)
telemt_user_octets_to_client{user="hello"} 2979412478874 (2.71 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1803
telemt_user_unique_ips_recent_window{user="hello"} 640
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 135552.7 (37h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8297509
telemt_connections_bad_total 695920
telemt_connections_current 4151
telemt_connections_me_current 4151
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 268774
telemt_upstream_connect_attempt_total 60392
telemt_upstream_connect_success_total 59693
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 59840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28145
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1372
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3525
telemt_me_reconnect_success_total 1477
telemt_me_reader_eof_total 1359
telemt_me_idle_close_by_peer_total 1359
telemt_me_route_drop_no_conn_total 3488325
telemt_me_route_drop_channel_closed_total 229
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6209225
telemt_me_endpoint_quarantine_total 934
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 993
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 50
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
telemt_me_writers_active_current 48
telemt_desync_total 28774
telemt_desync_full_logged_total 9786
telemt_desync_suppressed_total 18988
telemt_desync_frames_bucket_total{bucket="1_2"} 6949
telemt_desync_frames_bucket_total{bucket="3_10"} 11065
telemt_desync_frames_bucket_total{bucket="gt_10"} 10760
telemt_pool_swap_total 143
telemt_pool_force_close_total 4358
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 515
telemt_me_draining_writers_reap_progress_total 44550
telemt_me_writer_removed_unexpected_total 1386
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4179
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41703
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3969
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40192
telemt_me_writer_teardown_success_total{mode="normal"} 45882
telemt_me_writer_teardown_noop_total 44567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90449
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.367139
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90449
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 515
telemt_me_refill_failed_total 105
telemt_me_writer_restored_same_endpoint_total 1298
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 6201175
telemt_user_connections_current{user="hello"} 4151
telemt_user_octets_from_client{user="hello"} 155162070595 (144.51 GB)
telemt_user_octets_to_client{user="hello"} 2705166613007 (2.46 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1677
telemt_user_unique_ips_recent_window{user="hello"} 613
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 5832.4 (1h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2484635
telemt_connections_bad_total 182273
telemt_connections_current 6699
telemt_connections_me_current 6699
telemt_handshake_timeouts_total 33449
telemt_upstream_connect_attempt_total 8719
telemt_upstream_connect_success_total 8260
telemt_upstream_connect_fail_total 342
telemt_upstream_connect_attempts_per_request{bucket="1"} 8602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1643
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2693
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 342
telemt_me_keepalive_timeout_total 278
telemt_me_reconnect_attempts_total 453
telemt_me_reconnect_success_total 169
telemt_me_reader_eof_total 121
telemt_me_idle_close_by_peer_total 121
telemt_me_route_drop_no_conn_total 5621719
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2065718
telemt_me_endpoint_quarantine_total 28
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 48
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_writers_active_current 86
telemt_desync_total 3183
telemt_desync_full_logged_total 810
telemt_desync_suppressed_total 2373
telemt_desync_frames_bucket_total{bucket="1_2"} 564
telemt_desync_frames_bucket_total{bucket="3_10"} 1244
telemt_desync_frames_bucket_total{bucket="gt_10"} 1375
telemt_pool_swap_total 4
telemt_pool_force_close_total 156
telemt_me_writer_close_signal_drop_total 68
telemt_me_draining_writers_reap_progress_total 1464
telemt_me_writer_removed_unexpected_total 164
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 270
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1359
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 48
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1308
telemt_me_writer_teardown_success_total{mode="normal"} 1629
telemt_me_writer_teardown_noop_total 1464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3093
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.455129
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3093
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 68
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 121
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 2071234
telemt_user_connections_current{user="hello"} 6699
telemt_user_octets_from_client{user="hello"} 11028935058 (10.27 GB)
telemt_user_octets_to_client{user="hello"} 60447968959 (56.30 GB)
telemt_user_msgs_from_client{user="hello"} 6014
telemt_user_msgs_to_client{user="hello"} 4995
telemt_user_unique_ips_current{user="hello"} 2369
telemt_user_unique_ips_recent_window{user="hello"} 1376
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 135544.1 (37h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7922128
telemt_connections_bad_total 695548
telemt_connections_current 4275
telemt_connections_me_current 4275
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 162191
telemt_upstream_connect_attempt_total 76721
telemt_upstream_connect_success_total 75888
telemt_upstream_connect_fail_total 713
telemt_upstream_connect_attempts_per_request{bucket="1"} 76601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29350
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 445
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 713
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70595
telemt_me_reconnect_success_total 2152
telemt_me_reader_eof_total 1893
telemt_me_idle_close_by_peer_total 1892
telemt_me_route_drop_no_conn_total 3357109
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6254430
telemt_me_endpoint_quarantine_total 910
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 1020
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 31622
telemt_desync_full_logged_total 10923
telemt_desync_suppressed_total 20699
telemt_desync_frames_bucket_total{bucket="1_2"} 6397
telemt_desync_frames_bucket_total{bucket="3_10"} 12138
telemt_desync_frames_bucket_total{bucket="gt_10"} 13087
telemt_pool_swap_total 140
telemt_pool_force_close_total 4087
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 491
telemt_me_draining_writers_reap_progress_total 46921
telemt_me_writer_removed_unexpected_total 1922
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4817
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44053
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3568
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 519
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42834
telemt_me_writer_teardown_success_total{mode="normal"} 48870
telemt_me_writer_teardown_noop_total 46922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95792
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.855321
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95792
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 491
telemt_me_refill_failed_total 4233
telemt_me_writer_restored_same_endpoint_total 1791
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 6249513
telemt_user_connections_current{user="hello"} 4275
telemt_user_octets_from_client{user="hello"} 153503064267 (142.96 GB)
telemt_user_octets_to_client{user="hello"} 2517545162211 (2.29 TB)
telemt_user_msgs_from_client{user="hello"} 115484
telemt_user_msgs_to_client{user="hello"} 517108
telemt_user_unique_ips_current{user="hello"} 1660
telemt_user_unique_ips_recent_window{user="hello"} 780
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 72380.2 (20h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6844617
telemt_connections_bad_total 256546
telemt_connections_current 5077
telemt_connections_me_current 5077
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2776785
telemt_upstream_connect_attempt_total 38000
telemt_upstream_connect_success_total 37725
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 37993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_reconnect_attempts_total 47616
telemt_me_reconnect_success_total 1312
telemt_me_reader_eof_total 976
telemt_me_idle_close_by_peer_total 976
telemt_me_route_drop_no_conn_total 2041617
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3408646
telemt_me_endpoint_quarantine_total 493
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 553
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_me_writers_active_current 88
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 18221
telemt_desync_full_logged_total 6122
telemt_desync_suppressed_total 12099
telemt_desync_frames_bucket_total{bucket="1_2"} 3688
telemt_desync_frames_bucket_total{bucket="3_10"} 6985
telemt_desync_frames_bucket_total{bucket="gt_10"} 7548
telemt_pool_swap_total 76
telemt_pool_force_close_total 2310
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 222
telemt_me_draining_writers_reap_progress_total 25804
telemt_me_writer_removed_unexpected_total 1046
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2294
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24579
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1988
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23494
telemt_me_writer_teardown_success_total{mode="normal"} 26873
telemt_me_writer_teardown_noop_total 25810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52683
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.909716
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52683
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 222
telemt_me_refill_failed_total 2692
telemt_me_writer_restored_same_endpoint_total 1172
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3408453
telemt_user_connections_current{user="hello"} 5077
telemt_user_octets_from_client{user="hello"} 82212416040 (76.57 GB)
telemt_user_octets_to_client{user="hello"} 1407150936566 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 2010
telemt_user_unique_ips_recent_window{user="hello"} 737
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 53351.0 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 531074
telemt_connections_bad_total 3792
telemt_connections_current 1068
telemt_connections_me_current 1068
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 9843
telemt_upstream_connect_attempt_total 28010
telemt_upstream_connect_success_total 27945
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 28003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14625
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 289
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1155
telemt_me_reconnect_success_total 462
telemt_me_reader_eof_total 460
telemt_me_idle_close_by_peer_total 460
telemt_me_route_drop_no_conn_total 173576
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 480432
telemt_me_endpoint_quarantine_total 489
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 455
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 2372
telemt_desync_full_logged_total 677
telemt_desync_suppressed_total 1695
telemt_desync_frames_bucket_total{bucket="1_2"} 719
telemt_desync_frames_bucket_total{bucket="3_10"} 914
telemt_desync_frames_bucket_total{bucket="gt_10"} 739
telemt_pool_swap_total 57
telemt_pool_force_close_total 1354
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 22691
telemt_me_writer_removed_unexpected_total 443
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1664
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21487
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1303
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21337
telemt_me_writer_teardown_success_total{mode="normal"} 23151
telemt_me_writer_teardown_noop_total 22691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45842
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.429918
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45842
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 408
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 482388
telemt_user_connections_current{user="hello"} 1068
telemt_user_octets_from_client{user="hello"} 9607239293 (8.95 GB)
telemt_user_octets_to_client{user="hello"} 233491824375 (217.46 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 135548.4 (37h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9697393
telemt_connections_bad_total 1129440
telemt_connections_current 6081
telemt_connections_me_current 6081
telemt_handshake_timeouts_total 261953
telemt_upstream_connect_attempt_total 52164
telemt_upstream_connect_success_total 51966
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 52118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26239
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 1983
telemt_me_reconnect_success_total 1073
telemt_me_reader_eof_total 1040
telemt_me_idle_close_by_peer_total 1040
telemt_me_route_drop_no_conn_total 2769298
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 28
telemt_me_route_drop_queue_full_profile_total{profile="high"} 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7215412
telemt_me_endpoint_quarantine_total 954
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1026
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 29299
telemt_desync_full_logged_total 9604
telemt_desync_suppressed_total 19695
telemt_desync_frames_bucket_total{bucket="1_2"} 7233
telemt_desync_frames_bucket_total{bucket="3_10"} 10706
telemt_desync_frames_bucket_total{bucket="gt_10"} 11360
telemt_pool_swap_total 150
telemt_pool_force_close_total 4056
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 490
telemt_me_draining_writers_reap_progress_total 47055
telemt_me_writer_removed_unexpected_total 999
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3787
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44299
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3942
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 114
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42999
telemt_me_writer_teardown_success_total{mode="normal"} 48086
telemt_me_writer_teardown_noop_total 47057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95143
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.031618
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95143
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 490
telemt_me_refill_failed_total 47
telemt_me_writer_restored_same_endpoint_total 940
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 7187707
telemt_user_connections_current{user="hello"} 6081
telemt_user_octets_from_client{user="hello"} 138940701492 (129.40 GB)
telemt_user_octets_to_client{user="hello"} 3352617724596 (3.05 TB)
telemt_user_unique_ips_current{user="hello"} 2129
telemt_user_unique_ips_recent_window{user="hello"} 788
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 135545.2 (37h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8419864
telemt_connections_bad_total 935287
telemt_connections_current 4751
telemt_connections_me_current 4751
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 218728
telemt_upstream_connect_attempt_total 76663
telemt_upstream_connect_success_total 76120
telemt_upstream_connect_fail_total 474
telemt_upstream_connect_attempts_per_request{bucket="1"} 76594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30725
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1967
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 474
telemt_me_reconnect_attempts_total 6569
telemt_me_reconnect_success_total 1533
telemt_me_reader_eof_total 1361
telemt_me_idle_close_by_peer_total 1361
telemt_me_seq_mismatch_total 65
telemt_me_route_drop_no_conn_total 2997759
telemt_me_route_drop_channel_closed_total 263
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6437056
telemt_me_endpoint_quarantine_total 1054
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1026
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 28421
telemt_desync_full_logged_total 9377
telemt_desync_suppressed_total 19044
telemt_desync_frames_bucket_total{bucket="1_2"} 7000
telemt_desync_frames_bucket_total{bucket="3_10"} 10476
telemt_desync_frames_bucket_total{bucket="gt_10"} 10945
telemt_pool_swap_total 147
telemt_pool_force_close_total 3985
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 490
telemt_me_draining_writers_reap_progress_total 45734
telemt_me_writer_removed_unexpected_total 1380
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4439
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42737
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3690
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 295
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41749
telemt_me_writer_teardown_success_total{mode="normal"} 47176
telemt_me_writer_teardown_noop_total 45738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92914
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.548408
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92914
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 490
telemt_me_refill_failed_total 290
telemt_me_writer_restored_same_endpoint_total 1194
telemt_me_writer_restored_fallback_total 89
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 6445234
telemt_user_connections_current{user="hello"} 4751
telemt_user_octets_from_client{user="hello"} 117146746505 (109.10 GB)
telemt_user_octets_to_client{user="hello"} 2726449096195 (2.48 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1831
telemt_user_unique_ips_recent_window{user="hello"} 721
```
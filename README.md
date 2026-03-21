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

# Server Metrics 2026-03-21 23:32:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 8769.2 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142091
telemt_connections_bad_total 11135
telemt_connections_current 678
telemt_connections_me_current 678
telemt_handshake_timeouts_total 7043
telemt_upstream_connect_attempt_total 3510
telemt_upstream_connect_success_total 3509
telemt_upstream_connect_attempts_per_request{bucket="1"} 3509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2201
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 86
telemt_me_reconnect_success_total 52
telemt_me_reader_eof_total 52
telemt_me_idle_close_by_peer_total 52
telemt_me_route_drop_no_conn_total 29652
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115380
telemt_me_endpoint_quarantine_total 57
telemt_me_single_endpoint_shadow_rotate_total 76
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
telemt_me_writers_active_current 46
telemt_desync_total 670
telemt_desync_full_logged_total 212
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 210
telemt_desync_frames_bucket_total{bucket="gt_10"} 326
telemt_pool_swap_total 9
telemt_pool_force_close_total 251
telemt_me_writer_close_signal_drop_total 18
telemt_me_draining_writers_reap_progress_total 3125
telemt_me_writer_removed_unexpected_total 49
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2938
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 247
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2874
telemt_me_writer_teardown_success_total{mode="normal"} 3161
telemt_me_writer_teardown_noop_total 3125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6286
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.701021
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6286
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 18
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 115257
telemt_user_connections_current{user="hello"} 678
telemt_user_octets_from_client{user="hello"} 1371269468 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 43564237736 (40.57 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 22135.5 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 653237
telemt_connections_bad_total 31926
telemt_connections_current 445
telemt_connections_me_current 445
telemt_handshake_timeouts_total 25029
telemt_upstream_connect_attempt_total 9294
telemt_upstream_connect_success_total 9132
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 9277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4990
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_reconnect_attempts_total 820
telemt_me_reconnect_success_total 279
telemt_me_reader_eof_total 241
telemt_me_idle_close_by_peer_total 241
telemt_me_route_drop_no_conn_total 322990
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 531990
telemt_me_endpoint_quarantine_total 192
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 179
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_me_writers_active_current 47
telemt_desync_total 2358
telemt_desync_full_logged_total 1347
telemt_desync_suppressed_total 1011
telemt_desync_frames_bucket_total{bucket="1_2"} 497
telemt_desync_frames_bucket_total{bucket="3_10"} 889
telemt_desync_frames_bucket_total{bucket="gt_10"} 972
telemt_pool_swap_total 24
telemt_pool_force_close_total 680
telemt_me_writer_close_signal_drop_total 54
telemt_me_draining_writers_reap_progress_total 8180
telemt_me_writer_removed_unexpected_total 225
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 714
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7694
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 673
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7500
telemt_me_writer_teardown_success_total{mode="normal"} 8408
telemt_me_writer_teardown_noop_total 8180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16588
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.362140
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16588
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 54
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 193
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 531252
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 8951121576 (8.34 GB)
telemt_user_octets_to_client{user="hello"} 183912069836 (171.28 GB)
telemt_user_unique_ips_current{user="hello"} 331
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 96995.3 (26h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7394192
telemt_connections_bad_total 580090
telemt_connections_current 1686
telemt_connections_me_current 1686
telemt_handshake_timeouts_total 239012
telemt_upstream_connect_attempt_total 35086
telemt_upstream_connect_success_total 35017
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 35024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19027
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1477
telemt_me_reconnect_success_total 731
telemt_me_reader_eof_total 739
telemt_me_idle_close_by_peer_total 739
telemt_me_route_drop_no_conn_total 4490894
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6037364
telemt_me_endpoint_quarantine_total 611
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 721
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 25575
telemt_desync_full_logged_total 8447
telemt_desync_suppressed_total 17128
telemt_desync_frames_bucket_total{bucket="1_2"} 5482
telemt_desync_frames_bucket_total{bucket="3_10"} 9985
telemt_desync_frames_bucket_total{bucket="gt_10"} 10108
telemt_pool_swap_total 104
telemt_pool_force_close_total 3504
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 566
telemt_me_draining_writers_reap_progress_total 31989
telemt_me_writer_removed_unexpected_total 711
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2709
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29568
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3265
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28485
telemt_me_writer_teardown_success_total{mode="normal"} 32277
telemt_me_writer_teardown_noop_total 32033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64310
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 152.401950
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64310
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 566
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 651
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 6029849
telemt_user_connections_current{user="hello"} 1686
telemt_user_octets_from_client{user="hello"} 103527272332 (96.42 GB)
telemt_user_octets_to_client{user="hello"} 1973458445348 (1.79 TB)
telemt_user_unique_ips_current{user="hello"} 814
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 96996.6 (26h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6077671
telemt_connections_bad_total 577051
telemt_connections_current 1567
telemt_connections_me_current 1567
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 200742
telemt_upstream_connect_attempt_total 39004
telemt_upstream_connect_success_total 38666
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 38844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18702
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1797
telemt_me_reconnect_success_total 761
telemt_me_reader_eof_total 738
telemt_me_idle_close_by_peer_total 738
telemt_me_route_drop_no_conn_total 2158241
telemt_me_route_drop_channel_closed_total 250
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4554384
telemt_me_endpoint_quarantine_total 593
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 740
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 21938
telemt_desync_full_logged_total 7400
telemt_desync_suppressed_total 14538
telemt_desync_frames_bucket_total{bucket="1_2"} 5286
telemt_desync_frames_bucket_total{bucket="3_10"} 8518
telemt_desync_frames_bucket_total{bucket="gt_10"} 8134
telemt_pool_swap_total 106
telemt_pool_force_close_total 3195
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 30522
telemt_me_writer_removed_unexpected_total 713
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2602
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28567
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2996
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27327
telemt_me_writer_teardown_success_total{mode="normal"} 31169
telemt_me_writer_teardown_noop_total 30528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61697
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.841560
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61697
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 657
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 4498399
telemt_user_connections_current{user="hello"} 1567
telemt_user_octets_from_client{user="hello"} 137600917985 (128.15 GB)
telemt_user_octets_to_client{user="hello"} 2102323640539 (1.91 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 772
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 96960.8 (26h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5995991
telemt_connections_bad_total 538895
telemt_connections_current 1612
telemt_connections_me_current 1612
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 191131
telemt_upstream_connect_attempt_total 45459
telemt_upstream_connect_success_total 45152
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 45287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20133
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1801
telemt_me_reconnect_success_total 814
telemt_me_reader_eof_total 763
telemt_me_idle_close_by_peer_total 763
telemt_me_route_drop_no_conn_total 2094987
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4479635
telemt_me_endpoint_quarantine_total 654
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 724
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_me_writers_active_current 43
telemt_desync_total 21782
telemt_desync_full_logged_total 7245
telemt_desync_suppressed_total 14537
telemt_desync_frames_bucket_total{bucket="1_2"} 5339
telemt_desync_frames_bucket_total{bucket="3_10"} 8330
telemt_desync_frames_bucket_total{bucket="gt_10"} 8113
telemt_pool_swap_total 104
telemt_pool_force_close_total 3069
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 366
telemt_me_draining_writers_reap_progress_total 31979
telemt_me_writer_removed_unexpected_total 730
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2686
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30030
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2854
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28910
telemt_me_writer_teardown_success_total{mode="normal"} 32716
telemt_me_writer_teardown_noop_total 31990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64706
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.309564
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64706
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 366
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 705
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 4481081
telemt_user_connections_current{user="hello"} 1612
telemt_user_octets_from_client{user="hello"} 131194856315 (122.18 GB)
telemt_user_octets_to_client{user="hello"} 2052492994395 (1.87 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 741
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 97000.1 (26h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19894509
telemt_connections_bad_total 1448456
telemt_connections_current 2137
telemt_connections_me_current 2137
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 573159
telemt_upstream_connect_attempt_total 188612
telemt_upstream_connect_success_total 171020
telemt_upstream_connect_fail_total 16025
telemt_upstream_connect_attempts_per_request{bucket="1"} 187045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39718
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8880
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16025
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64278
telemt_me_reconnect_success_total 2136
telemt_me_reader_eof_total 1332
telemt_me_idle_close_by_peer_total 1331
telemt_me_route_drop_no_conn_total 39437875
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16216726
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 743
telemt_me_single_endpoint_outage_enter_total 122
telemt_me_single_endpoint_outage_exit_total 122
telemt_me_single_endpoint_outage_reconnect_attempt_total 258
telemt_me_single_endpoint_outage_reconnect_success_total 61
telemt_me_single_endpoint_quarantine_bypass_total 258
telemt_me_single_endpoint_shadow_rotate_total 755
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 31190
telemt_desync_full_logged_total 9264
telemt_desync_suppressed_total 21926
telemt_desync_frames_bucket_total{bucket="1_2"} 6810
telemt_desync_frames_bucket_total{bucket="3_10"} 13810
telemt_desync_frames_bucket_total{bucket="gt_10"} 10570
telemt_pool_swap_total 99
telemt_pool_force_close_total 3287
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 749
telemt_me_draining_writers_reap_progress_total 30064
telemt_me_writer_removed_unexpected_total 1993
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4155
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27636
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2771
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 516
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26777
telemt_me_writer_teardown_success_total{mode="normal"} 31791
telemt_me_writer_teardown_noop_total 30090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61881
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 210.123971
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61881
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 749
telemt_me_refill_failed_total 3787
telemt_me_writer_restored_same_endpoint_total 1478
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14672
telemt_me_writer_removed_unexpected_minus_restored_total 494
telemt_user_connections_total{user="hello"} 16344709
telemt_user_connections_current{user="hello"} 2137
telemt_user_octets_from_client{user="hello"} 181902760808 (169.41 GB)
telemt_user_octets_to_client{user="hello"} 1099011542198 (1023.53 GB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 1004
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 96967.5 (26h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5791047
telemt_connections_bad_total 537941
telemt_connections_current 1719
telemt_connections_me_current 1719
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 119404
telemt_upstream_connect_attempt_total 53519
telemt_upstream_connect_success_total 52906
telemt_upstream_connect_fail_total 523
telemt_upstream_connect_attempts_per_request{bucket="1"} 53429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21008
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 338
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 523
telemt_me_reconnect_attempts_total 68084
telemt_me_reconnect_success_total 1678
telemt_me_reader_eof_total 1457
telemt_me_idle_close_by_peer_total 1456
telemt_me_route_drop_no_conn_total 2350581
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4519636
telemt_me_endpoint_quarantine_total 637
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 726
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 22852
telemt_desync_full_logged_total 7983
telemt_desync_suppressed_total 14869
telemt_desync_frames_bucket_total{bucket="1_2"} 4335
telemt_desync_frames_bucket_total{bucket="3_10"} 8844
telemt_desync_frames_bucket_total{bucket="gt_10"} 9673
telemt_pool_swap_total 99
telemt_pool_force_close_total 2921
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 372
telemt_me_draining_writers_reap_progress_total 33270
telemt_me_writer_removed_unexpected_total 1503
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3566
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31230
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2520
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30349
telemt_me_writer_teardown_success_total{mode="normal"} 34796
telemt_me_writer_teardown_noop_total 33271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68067
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.873283
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68067
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 372
telemt_me_refill_failed_total 4118
telemt_me_writer_restored_same_endpoint_total 1422
telemt_me_writer_restored_fallback_total 26
telemt_me_no_writer_failfast_total 223
telemt_me_async_recovery_trigger_total 7257
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 4512760
telemt_user_connections_current{user="hello"} 1719
telemt_user_octets_from_client{user="hello"} 121390480836 (113.05 GB)
telemt_user_octets_to_client{user="hello"} 1841555126982 (1.67 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 785
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 33803.4 (9h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3665875
telemt_connections_bad_total 129737
telemt_connections_current 1272
telemt_connections_me_current 1272
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1532432
telemt_upstream_connect_attempt_total 21706
telemt_upstream_connect_success_total 21570
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 21699
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_reconnect_attempts_total 45578
telemt_me_reconnect_success_total 878
telemt_me_reader_eof_total 549
telemt_me_idle_close_by_peer_total 549
telemt_me_route_drop_no_conn_total 989546
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1766421
telemt_me_endpoint_quarantine_total 233
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 254
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 9824
telemt_desync_full_logged_total 3354
telemt_desync_suppressed_total 6470
telemt_desync_frames_bucket_total{bucket="1_2"} 1732
telemt_desync_frames_bucket_total{bucket="3_10"} 3757
telemt_desync_frames_bucket_total{bucket="gt_10"} 4335
telemt_pool_swap_total 36
telemt_pool_force_close_total 1202
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 117
telemt_me_draining_writers_reap_progress_total 11265
telemt_me_writer_removed_unexpected_total 631
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1264
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10650
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 996
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10063
telemt_me_writer_teardown_success_total{mode="normal"} 11914
telemt_me_writer_teardown_noop_total 11267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 23075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 23181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 23181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 23181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 23181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 23181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 23181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 23181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 23181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 23181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 23181
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.997149
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 23181
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 117
telemt_me_refill_failed_total 2597
telemt_me_writer_restored_same_endpoint_total 789
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1770166
telemt_user_connections_current{user="hello"} 1272
telemt_user_octets_from_client{user="hello"} 51770563284 (48.22 GB)
telemt_user_octets_to_client{user="hello"} 759788027098 (707.61 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 687
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 14774.4 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152785
telemt_connections_bad_total 1371
telemt_connections_current 340
telemt_connections_me_current 340
telemt_handshake_timeouts_total 3649
telemt_upstream_connect_attempt_total 6669
telemt_upstream_connect_success_total 6652
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3759
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 134
telemt_me_reconnect_success_total 88
telemt_me_reader_eof_total 89
telemt_me_idle_close_by_peer_total 89
telemt_me_route_drop_no_conn_total 43575
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133690
telemt_me_endpoint_quarantine_total 130
telemt_me_single_endpoint_shadow_rotate_total 132
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 956
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 718
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 16
telemt_pool_force_close_total 381
telemt_me_writer_close_signal_drop_total 18
telemt_me_draining_writers_reap_progress_total 5961
telemt_me_writer_removed_unexpected_total 87
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 398
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5652
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 379
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5580
telemt_me_writer_teardown_success_total{mode="normal"} 6050
telemt_me_writer_teardown_noop_total 5961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12011
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.734507
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12011
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 18
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 133496
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 2491948156 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 78715333736 (73.31 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 96971.9 (26h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6956359
telemt_connections_bad_total 707807
telemt_connections_current 1827
telemt_connections_me_current 1827
telemt_handshake_timeouts_total 197988
telemt_upstream_connect_attempt_total 36958
telemt_upstream_connect_success_total 36813
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 36921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18480
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_reconnect_attempts_total 1483
telemt_me_reconnect_success_total 771
telemt_me_reader_eof_total 749
telemt_me_idle_close_by_peer_total 749
telemt_me_route_drop_no_conn_total 2089647
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5276360
telemt_me_endpoint_quarantine_total 654
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 742
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 20314
telemt_desync_full_logged_total 6784
telemt_desync_suppressed_total 13530
telemt_desync_frames_bucket_total{bucket="1_2"} 4951
telemt_desync_frames_bucket_total{bucket="3_10"} 7370
telemt_desync_frames_bucket_total{bucket="gt_10"} 7993
telemt_pool_swap_total 107
telemt_pool_force_close_total 2924
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 363
telemt_me_draining_writers_reap_progress_total 33255
telemt_me_writer_removed_unexpected_total 725
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2689
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31305
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2836
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30331
telemt_me_writer_teardown_success_total{mode="normal"} 33994
telemt_me_writer_teardown_noop_total 33257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67251
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.511646
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67251
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 363
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 687
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 5251617
telemt_user_connections_current{user="hello"} 1827
telemt_user_octets_from_client{user="hello"} 105390699440 (98.15 GB)
telemt_user_octets_to_client{user="hello"} 2466629422832 (2.24 TB)
telemt_user_unique_ips_current{user="hello"} 785
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 96968.5 (26h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5968572
telemt_connections_bad_total 582826
telemt_connections_current 1767
telemt_connections_me_current 1767
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 166342
telemt_upstream_connect_attempt_total 53002
telemt_upstream_connect_success_total 52603
telemt_upstream_connect_fail_total 340
telemt_upstream_connect_attempts_per_request{bucket="1"} 52943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20276
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 340
telemt_me_reconnect_attempts_total 5283
telemt_me_reconnect_success_total 1074
telemt_me_reader_eof_total 950
telemt_me_idle_close_by_peer_total 950
telemt_me_seq_mismatch_total 41
telemt_me_route_drop_no_conn_total 2143310
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4647011
telemt_me_endpoint_quarantine_total 759
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 737
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
telemt_me_writers_active_current 44
telemt_desync_total 19093
telemt_desync_full_logged_total 6420
telemt_desync_suppressed_total 12673
telemt_desync_frames_bucket_total{bucket="1_2"} 4780
telemt_desync_frames_bucket_total{bucket="3_10"} 6953
telemt_desync_frames_bucket_total{bucket="gt_10"} 7360
telemt_pool_swap_total 105
telemt_pool_force_close_total 2883
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 364
telemt_me_draining_writers_reap_progress_total 32086
telemt_me_writer_removed_unexpected_total 963
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3173
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29919
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2660
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29203
telemt_me_writer_teardown_success_total{mode="normal"} 33092
telemt_me_writer_teardown_noop_total 32090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65182
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.726547
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65182
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 364
telemt_me_refill_failed_total 243
telemt_me_writer_restored_same_endpoint_total 832
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 4650355
telemt_user_connections_current{user="hello"} 1767
telemt_user_octets_from_client{user="hello"} 88409310937 (82.34 GB)
telemt_user_octets_to_client{user="hello"} 1999181388064 (1.82 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 806
telemt_user_unique_ips_recent_window{user="hello"} 181
```
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

# Server Metrics 2026-03-22 13:46:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 59978.4 (16h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1882345
telemt_connections_bad_total 82464
telemt_connections_current 1777
telemt_connections_me_current 1777
telemt_handshake_timeouts_total 79499
telemt_upstream_connect_attempt_total 22479
telemt_upstream_connect_success_total 22478
telemt_upstream_connect_attempts_per_request{bucket="1"} 22478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14636
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 914
telemt_me_reconnect_success_total 367
telemt_me_reader_eof_total 371
telemt_me_idle_close_by_peer_total 371
telemt_me_route_drop_no_conn_total 1316694
telemt_me_route_drop_channel_closed_total 602
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1600821
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 412
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 474
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
telemt_me_writers_active_current 43
telemt_desync_total 8801
telemt_desync_full_logged_total 2694
telemt_desync_suppressed_total 6107
telemt_desync_frames_bucket_total{bucket="1_2"} 2453
telemt_desync_frames_bucket_total{bucket="3_10"} 3303
telemt_desync_frames_bucket_total{bucket="gt_10"} 3045
telemt_pool_swap_total 66
telemt_pool_force_close_total 1977
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 322
telemt_me_draining_writers_reap_progress_total 20493
telemt_me_writer_removed_unexpected_total 362
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1463
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19251
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1941
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18516
telemt_me_writer_teardown_success_total{mode="normal"} 20714
telemt_me_writer_teardown_noop_total 20497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41211
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 156.275627
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41211
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 322
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 326
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 1597882
telemt_user_connections_current{user="hello"} 1777
telemt_user_octets_from_client{user="hello"} 25131317140 (23.41 GB)
telemt_user_octets_to_client{user="hello"} 467224238188 (435.14 GB)
telemt_user_unique_ips_current{user="hello"} 664
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 73344.7 (20h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3053995
telemt_connections_bad_total 284644
telemt_connections_current 2155
telemt_connections_me_current 2155
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 71974
telemt_upstream_connect_attempt_total 47060
telemt_upstream_connect_success_total 46499
telemt_upstream_connect_fail_total 496
telemt_upstream_connect_attempts_per_request{bucket="1"} 46995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 496
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3694
telemt_me_reconnect_success_total 1672
telemt_me_reader_eof_total 1546
telemt_me_idle_close_by_peer_total 1546
telemt_me_route_drop_no_conn_total 2859048
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2403602
telemt_me_endpoint_quarantine_total 612
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 574
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
telemt_me_writers_active_current 83
telemt_desync_total 9485
telemt_desync_full_logged_total 5292
telemt_desync_suppressed_total 4193
telemt_desync_frames_bucket_total{bucket="1_2"} 2226
telemt_desync_frames_bucket_total{bucket="3_10"} 3728
telemt_desync_frames_bucket_total{bucket="gt_10"} 3531
telemt_pool_swap_total 72
telemt_pool_force_close_total 2070
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 172
telemt_me_draining_writers_reap_progress_total 28875
telemt_me_writer_removed_unexpected_total 1503
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3187
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27192
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1824
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 246
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26805
telemt_me_writer_teardown_success_total{mode="normal"} 30379
telemt_me_writer_teardown_noop_total 28875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59254
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.769466
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59254
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 172
telemt_me_refill_failed_total 91
telemt_me_writer_restored_same_endpoint_total 1393
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 2415173
telemt_user_connections_current{user="hello"} 2155
telemt_user_octets_from_client{user="hello"} 29089711711 (27.09 GB)
telemt_user_octets_to_client{user="hello"} 553131464306 (515.14 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1343
telemt_user_unique_ips_recent_window{user="hello"} 577
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 148204.7 (41h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13893596
telemt_connections_bad_total 1218387
telemt_connections_current 4520
telemt_connections_me_current 4520
telemt_handshake_timeouts_total 350128
telemt_upstream_connect_attempt_total 53795
telemt_upstream_connect_success_total 53713
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 53721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29149
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2457
telemt_me_reconnect_success_total 1281
telemt_me_reader_eof_total 1224
telemt_me_idle_close_by_peer_total 1223
telemt_me_route_drop_no_conn_total 12098028
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11145341
telemt_me_endpoint_quarantine_total 942
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1104
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
telemt_desync_total 45275
telemt_desync_full_logged_total 14379
telemt_desync_suppressed_total 30896
telemt_desync_frames_bucket_total{bucket="1_2"} 10254
telemt_desync_frames_bucket_total{bucket="3_10"} 17713
telemt_desync_frames_bucket_total{bucket="gt_10"} 17308
telemt_pool_swap_total 159
telemt_pool_force_close_total 5440
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 862
telemt_me_draining_writers_reap_progress_total 49057
telemt_me_writer_removed_unexpected_total 1180
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4259
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45313
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5008
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 432
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43617
telemt_me_writer_teardown_success_total{mode="normal"} 49572
telemt_me_writer_teardown_noop_total 49106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98678
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 252.534729
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98678
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 862
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1103
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 11133246
telemt_user_connections_current{user="hello"} 4520
telemt_user_octets_from_client{user="hello"} 160164216376 (149.16 GB)
telemt_user_octets_to_client{user="hello"} 2968450135052 (2.70 TB)
telemt_user_unique_ips_current{user="hello"} 1819
telemt_user_unique_ips_recent_window{user="hello"} 796
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 148206.0 (41h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10312316
telemt_connections_bad_total 974984
telemt_connections_current 4288
telemt_connections_me_current 4288
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 308345
telemt_upstream_connect_attempt_total 80140
telemt_upstream_connect_success_total 79000
telemt_upstream_connect_fail_total 819
telemt_upstream_connect_attempts_per_request{bucket="1"} 79819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31695
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3678
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 819
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3692
telemt_me_reconnect_success_total 1465
telemt_me_reader_eof_total 1339
telemt_me_idle_close_by_peer_total 1339
telemt_me_route_drop_no_conn_total 4105023
telemt_me_route_drop_channel_closed_total 441
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7694976
telemt_me_endpoint_quarantine_total 928
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1122
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
telemt_me_writers_active_current 43
telemt_desync_total 34394
telemt_desync_full_logged_total 11570
telemt_desync_suppressed_total 22824
telemt_desync_frames_bucket_total{bucket="1_2"} 8485
telemt_desync_frames_bucket_total{bucket="3_10"} 13221
telemt_desync_frames_bucket_total{bucket="gt_10"} 12688
telemt_pool_swap_total 158
telemt_pool_force_close_total 4877
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 612
telemt_me_draining_writers_reap_progress_total 47251
telemt_me_writer_removed_unexpected_total 1372
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4290
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44189
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4455
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 422
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42374
telemt_me_writer_teardown_success_total{mode="normal"} 48479
telemt_me_writer_teardown_noop_total 47266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95745
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 90.194496
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95745
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 612
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1242
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 7634544
telemt_user_connections_current{user="hello"} 4288
telemt_user_octets_from_client{user="hello"} 194263209001 (180.92 GB)
telemt_user_octets_to_client{user="hello"} 3447797469722 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1784
telemt_user_unique_ips_recent_window{user="hello"} 622
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 148170.0 (41h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9769312
telemt_connections_bad_total 819717
telemt_connections_current 4088
telemt_connections_me_current 4088
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 316067
telemt_upstream_connect_attempt_total 65593
telemt_upstream_connect_success_total 64690
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 64871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30408
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2013
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4173
telemt_me_reconnect_success_total 1801
telemt_me_reader_eof_total 1566
telemt_me_idle_close_by_peer_total 1565
telemt_me_route_drop_no_conn_total 4831529
telemt_me_route_drop_channel_closed_total 328
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7374246
telemt_me_endpoint_quarantine_total 1018
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1088
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
telemt_me_writers_active_current 43
telemt_desync_total 34118
telemt_desync_full_logged_total 11332
telemt_desync_suppressed_total 22786
telemt_desync_frames_bucket_total{bucket="1_2"} 8655
telemt_desync_frames_bucket_total{bucket="3_10"} 13068
telemt_desync_frames_bucket_total{bucket="gt_10"} 12395
telemt_pool_swap_total 154
telemt_pool_force_close_total 4809
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 653
telemt_me_draining_writers_reap_progress_total 47899
telemt_me_writer_removed_unexpected_total 1713
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4790
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44744
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4294
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 515
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43090
telemt_me_writer_teardown_success_total{mode="normal"} 49534
telemt_me_writer_teardown_noop_total 47966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97500
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3153.753274
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97500
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 653
telemt_me_refill_failed_total 122
telemt_me_writer_restored_same_endpoint_total 1571
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 7368236
telemt_user_connections_current{user="hello"} 4088
telemt_user_octets_from_client{user="hello"} 172883707197 (161.01 GB)
telemt_user_octets_to_client{user="hello"} 3075926563597 (2.80 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1763
telemt_user_unique_ips_recent_window{user="hello"} 602
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 18450.1 (5h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7782528
telemt_connections_bad_total 494824
telemt_connections_current 6619
telemt_connections_me_current 6619
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 123941
telemt_upstream_connect_attempt_total 28102
telemt_upstream_connect_success_total 26731
telemt_upstream_connect_fail_total 1018
telemt_upstream_connect_attempts_per_request{bucket="1"} 27749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6505
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4719
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1018
telemt_me_keepalive_timeout_total 691
telemt_me_reconnect_attempts_total 2690
telemt_me_reconnect_success_total 512
telemt_me_reader_eof_total 316
telemt_me_idle_close_by_peer_total 316
telemt_me_route_drop_no_conn_total 18972840
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6474462
telemt_me_endpoint_quarantine_total 115
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 61
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 61
telemt_me_single_endpoint_shadow_rotate_total 146
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_me_writers_active_current 58
telemt_desync_total 9428
telemt_desync_full_logged_total 2418
telemt_desync_suppressed_total 7010
telemt_desync_frames_bucket_total{bucket="1_2"} 1687
telemt_desync_frames_bucket_total{bucket="3_10"} 3858
telemt_desync_frames_bucket_total{bucket="gt_10"} 3883
telemt_pool_swap_total 17
telemt_pool_force_close_total 697
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 257
telemt_me_draining_writers_reap_progress_total 4825
telemt_me_writer_removed_unexpected_total 446
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 847
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4383
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 505
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4128
telemt_me_writer_teardown_success_total{mode="normal"} 5230
telemt_me_writer_teardown_noop_total 4828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 9067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 9427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 9981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 10052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 10058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 10058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 10058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 10058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 10058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 10058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 10058
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.825179
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 10058
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 257
telemt_me_refill_failed_total 114
telemt_me_writer_restored_same_endpoint_total 349
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 2805
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 6489492
telemt_user_connections_current{user="hello"} 6619
telemt_user_octets_from_client{user="hello"} 36373021327 (33.88 GB)
telemt_user_octets_to_client{user="hello"} 190818300276 (177.71 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2501
telemt_user_unique_ips_recent_window{user="hello"} 1341
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 148177.1 (41h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9476923
telemt_connections_bad_total 785749
telemt_connections_current 5225
telemt_connections_me_current 5225
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 204558
telemt_upstream_connect_attempt_total 89886
telemt_upstream_connect_success_total 88981
telemt_upstream_connect_fail_total 782
telemt_upstream_connect_attempts_per_request{bucket="1"} 89763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32344
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 782
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71348
telemt_me_reconnect_success_total 2420
telemt_me_reader_eof_total 2150
telemt_me_idle_close_by_peer_total 2149
telemt_me_route_drop_no_conn_total 4605412
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7482078
telemt_me_endpoint_quarantine_total 996
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1107
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 38313
telemt_desync_full_logged_total 13093
telemt_desync_suppressed_total 25220
telemt_desync_frames_bucket_total{bucket="1_2"} 7784
telemt_desync_frames_bucket_total{bucket="3_10"} 14819
telemt_desync_frames_bucket_total{bucket="gt_10"} 15710
telemt_pool_swap_total 152
telemt_pool_force_close_total 4500
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 547
telemt_me_draining_writers_reap_progress_total 50533
telemt_me_writer_removed_unexpected_total 2177
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5338
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47389
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3885
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 615
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46033
telemt_me_writer_teardown_success_total{mode="normal"} 52727
telemt_me_writer_teardown_noop_total 50534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103261
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.716200
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103261
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 547
telemt_me_refill_failed_total 4253
telemt_me_writer_restored_same_endpoint_total 2028
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 7483359
telemt_user_connections_current{user="hello"} 5225
telemt_user_octets_from_client{user="hello"} 172731500439 (160.87 GB)
telemt_user_octets_to_client{user="hello"} 2849379065313 (2.59 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2030
telemt_user_unique_ips_recent_window{user="hello"} 680
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 85013.1 (23h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9443246
telemt_connections_bad_total 338161
telemt_connections_current 4141
telemt_connections_me_current 4141
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3973492
telemt_upstream_connect_attempt_total 42155
telemt_upstream_connect_success_total 41850
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 42148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17789
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_reconnect_attempts_total 47924
telemt_me_reconnect_success_total 1439
telemt_me_reader_eof_total 1107
telemt_me_idle_close_by_peer_total 1107
telemt_me_route_drop_no_conn_total 3454816
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4549529
telemt_me_endpoint_quarantine_total 559
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 641
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
telemt_desync_total 24900
telemt_desync_full_logged_total 8345
telemt_desync_suppressed_total 16555
telemt_desync_frames_bucket_total{bucket="1_2"} 5033
telemt_desync_frames_bucket_total{bucket="3_10"} 9833
telemt_desync_frames_bucket_total{bucket="gt_10"} 10034
telemt_pool_swap_total 89
telemt_pool_force_close_total 2769
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 287
telemt_me_draining_writers_reap_progress_total 29539
telemt_me_writer_removed_unexpected_total 1172
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2674
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28065
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2363
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 406
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26770
telemt_me_writer_teardown_success_total{mode="normal"} 30739
telemt_me_writer_teardown_noop_total 29546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60285
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.138526
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60285
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 287
telemt_me_refill_failed_total 2702
telemt_me_writer_restored_same_endpoint_total 1286
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4544104
telemt_user_connections_current{user="hello"} 4141
telemt_user_octets_from_client{user="hello"} 99836820488 (92.98 GB)
telemt_user_octets_to_client{user="hello"} 1739339008050 (1.58 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1671
telemt_user_unique_ips_recent_window{user="hello"} 636
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 65983.4 (18h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 781560
telemt_connections_bad_total 10119
telemt_connections_current 1046
telemt_connections_me_current 1046
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 14852
telemt_upstream_connect_attempt_total 33479
telemt_upstream_connect_success_total 33395
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 33464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17667
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 418
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 1516
telemt_me_reconnect_success_total 652
telemt_me_reader_eof_total 628
telemt_me_idle_close_by_peer_total 628
telemt_me_route_drop_no_conn_total 262929
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 700903
telemt_me_endpoint_quarantine_total 596
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 552
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
telemt_me_writers_active_current 44
telemt_desync_total 3873
telemt_desync_full_logged_total 1162
telemt_desync_suppressed_total 2711
telemt_desync_frames_bucket_total{bucket="1_2"} 944
telemt_desync_frames_bucket_total{bucket="3_10"} 1545
telemt_desync_frames_bucket_total{bucket="gt_10"} 1384
telemt_pool_swap_total 70
telemt_pool_force_close_total 1738
telemt_me_writer_close_signal_drop_total 102
telemt_me_draining_writers_reap_progress_total 27507
telemt_me_writer_removed_unexpected_total 607
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2118
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26019
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1660
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25769
telemt_me_writer_teardown_success_total{mode="normal"} 28137
telemt_me_writer_teardown_noop_total 27509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55646
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.031560
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55646
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 102
telemt_me_refill_failed_total 47
telemt_me_writer_restored_same_endpoint_total 558
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 702385
telemt_user_connections_current{user="hello"} 1046
telemt_user_octets_from_client{user="hello"} 13213741469 (12.31 GB)
telemt_user_octets_to_client{user="hello"} 331365035691 (308.61 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 383
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 148181.2 (41h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11566550
telemt_connections_bad_total 1352535
telemt_connections_current 5816
telemt_connections_me_current 5816
telemt_handshake_timeouts_total 314518
telemt_upstream_connect_attempt_total 55879
telemt_upstream_connect_success_total 55663
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 55831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28175
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_reconnect_attempts_total 2191
telemt_me_reconnect_success_total 1167
telemt_me_reader_eof_total 1132
telemt_me_idle_close_by_peer_total 1132
telemt_me_route_drop_no_conn_total 3657629
telemt_me_route_drop_channel_closed_total 99
telemt_me_route_drop_queue_full_total 32
telemt_me_route_drop_queue_full_profile_total{profile="high"} 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8693672
telemt_me_endpoint_quarantine_total 1016
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1111
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
telemt_desync_total 35688
telemt_desync_full_logged_total 11699
telemt_desync_suppressed_total 23989
telemt_desync_frames_bucket_total{bucket="1_2"} 8492
telemt_desync_frames_bucket_total{bucket="3_10"} 13228
telemt_desync_frames_bucket_total{bucket="gt_10"} 13968
telemt_pool_swap_total 164
telemt_pool_force_close_total 4516
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 565
telemt_me_draining_writers_reap_progress_total 50339
telemt_me_writer_removed_unexpected_total 1087
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4126
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47330
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4362
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 154
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45823
telemt_me_writer_teardown_success_total{mode="normal"} 51456
telemt_me_writer_teardown_noop_total 50341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101797
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.443426
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101797
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 565
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1023
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 8664183
telemt_user_connections_current{user="hello"} 5816
telemt_user_octets_from_client{user="hello"} 167542979304 (156.04 GB)
telemt_user_octets_to_client{user="hello"} 3904119335288 (3.55 TB)
telemt_user_unique_ips_current{user="hello"} 2159
telemt_user_unique_ips_recent_window{user="hello"} 743
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 148178.4 (41h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9984910
telemt_connections_bad_total 1119201
telemt_connections_current 4917
telemt_connections_me_current 4917
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 261623
telemt_upstream_connect_attempt_total 81467
telemt_upstream_connect_success_total 80870
telemt_upstream_connect_fail_total 516
telemt_upstream_connect_attempts_per_request{bucket="1"} 81386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2008
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 516
telemt_me_reconnect_attempts_total 8570
telemt_me_reconnect_success_total 1936
telemt_me_reader_eof_total 1805
telemt_me_idle_close_by_peer_total 1805
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 4482288
telemt_me_route_drop_channel_closed_total 318
telemt_me_route_drop_queue_full_total 16
telemt_me_route_drop_queue_full_profile_total{profile="high"} 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7686501
telemt_me_endpoint_quarantine_total 1134
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1112
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 34908
telemt_desync_full_logged_total 11369
telemt_desync_suppressed_total 23539
telemt_desync_frames_bucket_total{bucket="1_2"} 8616
telemt_desync_frames_bucket_total{bucket="3_10"} 13006
telemt_desync_frames_bucket_total{bucket="gt_10"} 13286
telemt_pool_swap_total 157
telemt_pool_force_close_total 4374
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 563
telemt_me_draining_writers_reap_progress_total 49677
telemt_me_writer_removed_unexpected_total 1830
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5145
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46429
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3976
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 398
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45303
telemt_me_writer_teardown_success_total{mode="normal"} 51574
telemt_me_writer_teardown_noop_total 49681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101255
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.276032
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101255
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 563
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 1574
telemt_me_writer_restored_fallback_total 96
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 7693521
telemt_user_connections_current{user="hello"} 4917
telemt_user_octets_from_client{user="hello"} 135842354429 (126.51 GB)
telemt_user_octets_to_client{user="hello"} 3029933728371 (2.76 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1960
telemt_user_unique_ips_recent_window{user="hello"} 697
```
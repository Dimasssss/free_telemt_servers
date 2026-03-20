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

# Server Metrics 2026-03-20 15:58:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 6200.9 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 298083
telemt_connections_bad_total 13652
telemt_connections_current 1569
telemt_connections_me_current 1569
telemt_handshake_timeouts_total 6395
telemt_upstream_connect_attempt_total 2484
telemt_upstream_connect_success_total 2474
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1533
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 469
telemt_me_reconnect_success_total 199
telemt_me_reader_eof_total 209
telemt_me_idle_close_by_peer_total 209
telemt_me_route_drop_no_conn_total 312631
telemt_me_route_drop_channel_closed_total 119
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 260895
telemt_me_endpoint_quarantine_total 38
telemt_me_single_endpoint_shadow_rotate_total 45
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
telemt_desync_total 986
telemt_desync_full_logged_total 309
telemt_desync_suppressed_total 677
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 435
telemt_desync_frames_bucket_total{bucket="gt_10"} 363
telemt_pool_swap_total 4
telemt_pool_force_close_total 167
telemt_me_writer_close_signal_drop_total 61
telemt_me_draining_writers_reap_progress_total 2050
telemt_me_writer_removed_unexpected_total 208
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 325
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1924
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 116
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1883
telemt_me_writer_teardown_success_total{mode="normal"} 2249
telemt_me_writer_teardown_noop_total 2050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4299
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.240241
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4299
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 61
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 192
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 260686
telemt_user_connections_current{user="hello"} 1569
telemt_user_octets_from_client{user="hello"} 2653619508 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 51645657060 (48.10 GB)
telemt_user_unique_ips_current{user="hello"} 565
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 6210.3 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 765748
telemt_connections_bad_total 43733
telemt_connections_current 4583
telemt_connections_me_current 4583
telemt_handshake_timeouts_total 11848
telemt_upstream_connect_attempt_total 2054
telemt_upstream_connect_success_total 2032
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 149
telemt_me_reconnect_success_total 87
telemt_me_reader_eof_total 72
telemt_me_idle_close_by_peer_total 72
telemt_me_route_drop_no_conn_total 280223
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 574422
telemt_me_endpoint_quarantine_total 26
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_desync_total 1914
telemt_desync_full_logged_total 668
telemt_desync_suppressed_total 1246
telemt_desync_frames_bucket_total{bucket="1_2"} 413
telemt_desync_frames_bucket_total{bucket="3_10"} 757
telemt_desync_frames_bucket_total{bucket="gt_10"} 744
telemt_pool_swap_total 5
telemt_pool_force_close_total 230
telemt_me_writer_close_signal_drop_total 35
telemt_me_draining_writers_reap_progress_total 1756
telemt_me_writer_removed_unexpected_total 72
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 194
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1606
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 57
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1526
telemt_me_writer_teardown_success_total{mode="normal"} 1800
telemt_me_writer_teardown_noop_total 1762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3562
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.662747
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3562
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 35
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 78
telemt_me_writer_restored_fallback_total 1
telemt_me_no_writer_failfast_total 41
telemt_me_async_recovery_trigger_total 396
telemt_user_connections_total{user="hello"} 573965
telemt_user_connections_current{user="hello"} 4583
telemt_user_octets_from_client{user="hello"} 7036413096 (6.55 GB)
telemt_user_octets_to_client{user="hello"} 172120814588 (160.30 GB)
telemt_user_unique_ips_current{user="hello"} 1586
telemt_user_unique_ips_recent_window{user="hello"} 650
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 6204.4 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 547123
telemt_connections_bad_total 31515
telemt_connections_current 3829
telemt_connections_me_current 3829
telemt_handshake_timeouts_total 7732
telemt_upstream_connect_attempt_total 2589
telemt_upstream_connect_success_total 2533
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 2586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 300
telemt_me_reconnect_success_total 187
telemt_me_reader_eof_total 150
telemt_me_idle_close_by_peer_total 150
telemt_me_route_drop_no_conn_total 211594
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 463922
telemt_me_endpoint_quarantine_total 44
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_me_writers_active_current 51
telemt_desync_total 1409
telemt_desync_full_logged_total 485
telemt_desync_suppressed_total 924
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 577
telemt_desync_frames_bucket_total{bucket="gt_10"} 580
telemt_pool_swap_total 4
telemt_pool_force_close_total 236
telemt_pool_stale_pick_total 1363
telemt_me_writer_close_signal_drop_total 38
telemt_me_draining_writers_reap_progress_total 2178
telemt_me_writer_removed_unexpected_total 147
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 295
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1995
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 119
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 117
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1942
telemt_me_writer_teardown_success_total{mode="normal"} 2290
telemt_me_writer_teardown_noop_total 2178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4468
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.623326
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4468
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 38
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 173
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 463552
telemt_user_connections_current{user="hello"} 3829
telemt_user_octets_from_client{user="hello"} 8164441116 (7.60 GB)
telemt_user_octets_to_client{user="hello"} 161792222600 (150.68 GB)
telemt_user_unique_ips_current{user="hello"} 1432
telemt_user_unique_ips_recent_window{user="hello"} 552
```

## koara.io

```
telemt 3.3.27

telemt_uptime_seconds 20262.5 (5h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3562573
telemt_connections_bad_total 357789
telemt_connections_current 5427
telemt_connections_me_current 5427
telemt_handshake_timeouts_total 65094
telemt_upstream_connect_attempt_total 6637
telemt_upstream_connect_success_total 6597
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 6626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3573
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 656
telemt_me_reconnect_success_total 417
telemt_me_reader_eof_total 424
telemt_me_idle_close_by_peer_total 424
telemt_me_route_drop_no_conn_total 2327045
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2832383
telemt_me_writer_pick_total{mode="p2c",result="full"} 1
telemt_me_endpoint_quarantine_total 87
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 131
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
telemt_me_writers_active_current 44
telemt_desync_total 7571
telemt_desync_full_logged_total 2170
telemt_desync_suppressed_total 5401
telemt_desync_frames_bucket_total{bucket="1_2"} 1877
telemt_desync_frames_bucket_total{bucket="3_10"} 2936
telemt_desync_frames_bucket_total{bucket="gt_10"} 2758
telemt_pool_swap_total 15
telemt_pool_force_close_total 800
telemt_me_writer_close_signal_drop_total 194
telemt_me_draining_writers_reap_progress_total 5691
telemt_me_writer_removed_unexpected_total 420
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 784
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5250
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 463
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 337
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4891
telemt_me_writer_teardown_success_total{mode="normal"} 6034
telemt_me_writer_teardown_noop_total 5701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11735
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 57.662785
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11735
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 194
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 400
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 2829246
telemt_user_connections_current{user="hello"} 5427
telemt_user_octets_from_client{user="hello"} 30989760084 (28.86 GB)
telemt_user_octets_to_client{user="hello"} 758570590028 (706.47 GB)
telemt_user_unique_ips_current{user="hello"} 1848
telemt_user_unique_ips_recent_window{user="hello"} 710
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 6203.1 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2342980
telemt_connections_bad_total 52951
telemt_connections_current 5364
telemt_connections_me_current 5364
telemt_handshake_timeouts_total 26966
telemt_upstream_connect_attempt_total 8243
telemt_upstream_connect_success_total 7850
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 8133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1825
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_keepalive_timeout_total 185
telemt_me_reconnect_attempts_total 387
telemt_me_reconnect_success_total 230
telemt_me_reader_eof_total 191
telemt_me_idle_close_by_peer_total 191
telemt_me_route_drop_no_conn_total 4746504
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2122837
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 47
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_me_writers_active_current 49
telemt_desync_total 2795
telemt_desync_full_logged_total 786
telemt_desync_suppressed_total 2009
telemt_desync_frames_bucket_total{bucket="1_2"} 591
telemt_desync_frames_bucket_total{bucket="3_10"} 1247
telemt_desync_frames_bucket_total{bucket="gt_10"} 957
telemt_pool_swap_total 4
telemt_pool_force_close_total 183
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 59
telemt_me_draining_writers_reap_progress_total 1805
telemt_me_writer_removed_unexpected_total 234
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 360
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1677
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 120
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 63
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1622
telemt_me_writer_teardown_success_total{mode="normal"} 2037
telemt_me_writer_teardown_noop_total 1806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3843
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.397684
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3843
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 59
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 192
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 2127968
telemt_user_connections_current{user="hello"} 5364
telemt_user_octets_from_client{user="hello"} 9248749552 (8.61 GB)
telemt_user_octets_to_client{user="hello"} 66837506190 (62.25 GB)
telemt_user_msgs_from_client{user="hello"} 4517
telemt_user_msgs_to_client{user="hello"} 3964
telemt_user_unique_ips_current{user="hello"} 1722
telemt_user_unique_ips_recent_window{user="hello"} 993
```

## rdp-onedash.ru

```
telemt 3.3.28

telemt_uptime_seconds 6208.0 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1975228
telemt_connections_bad_total 135809
telemt_connections_current 6114
telemt_connections_me_current 6114
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 18507
telemt_upstream_connect_attempt_total 18930
telemt_upstream_connect_success_total 18923
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 18930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5417
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 722
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 194
telemt_me_reconnect_success_total 58
telemt_me_reader_eof_total 56
telemt_me_idle_close_by_peer_total 56
telemt_me_route_drop_no_conn_total 3298728
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1670126
telemt_me_endpoint_quarantine_total 32
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 2746
telemt_desync_full_logged_total 800
telemt_desync_suppressed_total 1946
telemt_desync_frames_bucket_total{bucket="1_2"} 689
telemt_desync_frames_bucket_total{bucket="3_10"} 1178
telemt_desync_frames_bucket_total{bucket="gt_10"} 879
telemt_pool_swap_total 6
telemt_pool_force_close_total 176
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 60
telemt_me_draining_writers_reap_progress_total 1388
telemt_me_writer_removed_unexpected_total 54
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 157
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1254
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 152
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1212
telemt_me_writer_teardown_success_total{mode="normal"} 1411
telemt_me_writer_teardown_noop_total 1392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2803
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 113.965673
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2803
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 60
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 1684523
telemt_user_connections_current{user="hello"} 6114
telemt_user_octets_from_client{user="hello"} 13224779404 (12.32 GB)
telemt_user_octets_to_client{user="hello"} 128337048319 (119.52 GB)
telemt_user_msgs_from_client{user="hello"} 75809
telemt_user_msgs_to_client{user="hello"} 92195
telemt_user_unique_ips_current{user="hello"} 1940
telemt_user_unique_ips_recent_window{user="hello"} 952
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 5634.8 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112047
telemt_connections_bad_total 1201
telemt_connections_current 670
telemt_connections_me_current 670
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 1924
telemt_upstream_connect_attempt_total 3765
telemt_upstream_connect_success_total 3762
telemt_upstream_connect_attempts_per_request{bucket="1"} 3762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2674
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 106
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 209
telemt_me_reconnect_success_total 50
telemt_me_reader_eof_total 46
telemt_me_idle_close_by_peer_total 46
telemt_me_route_drop_no_conn_total 91872
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100358
telemt_me_endpoint_quarantine_total 42
telemt_me_single_endpoint_shadow_rotate_total 47
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
telemt_me_writers_active_current 43
telemt_desync_total 277
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 175
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 6
telemt_pool_force_close_total 165
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 45
telemt_me_draining_writers_reap_progress_total 1799
telemt_me_writer_removed_unexpected_total 46
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 196
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1634
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 164
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1634
telemt_me_writer_teardown_success_total{mode="normal"} 1830
telemt_me_writer_teardown_noop_total 1800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3630
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.276422
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3630
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 45
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 36
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 101368
telemt_user_connections_current{user="hello"} 670
telemt_user_octets_from_client{user="hello"} 1036945998 (988.91 MB)
telemt_user_octets_to_client{user="hello"} 19396166533 (18.06 GB)
telemt_user_msgs_from_client{user="hello"} 5317
telemt_user_msgs_to_client{user="hello"} 6420
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## 4vps.su

```
telemt 3.3.28

telemt_uptime_seconds 6205.9 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1065058
telemt_connections_bad_total 70976
telemt_connections_current 7342
telemt_connections_me_current 7342
telemt_handshake_timeouts_total 36892
telemt_upstream_connect_attempt_total 1854
telemt_upstream_connect_success_total 1852
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 997
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 65
telemt_me_reconnect_success_total 65
telemt_me_reader_eof_total 66
telemt_me_idle_close_by_peer_total 66
telemt_me_route_drop_no_conn_total 468517
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 896265
telemt_me_endpoint_quarantine_total 28
telemt_me_single_endpoint_shadow_rotate_total 39
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_desync_total 3326
telemt_desync_full_logged_total 929
telemt_desync_suppressed_total 2397
telemt_desync_frames_bucket_total{bucket="1_2"} 829
telemt_desync_frames_bucket_total{bucket="3_10"} 1246
telemt_desync_frames_bucket_total{bucket="gt_10"} 1251
telemt_pool_swap_total 5
telemt_pool_force_close_total 196
telemt_me_writer_close_signal_drop_total 24
telemt_me_draining_writers_reap_progress_total 1547
telemt_me_writer_removed_unexpected_total 66
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 168
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1447
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 151
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1351
telemt_me_writer_teardown_success_total{mode="normal"} 1615
telemt_me_writer_teardown_noop_total 1548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3163
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.979119
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3163
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 24
telemt_me_writer_restored_same_endpoint_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 895451
telemt_user_connections_current{user="hello"} 7342
telemt_user_octets_from_client{user="hello"} 12416129952 (11.56 GB)
telemt_user_octets_to_client{user="hello"} 289682179936 (269.79 GB)
telemt_user_unique_ips_current{user="hello"} 2223
telemt_user_unique_ips_recent_window{user="hello"} 907
```
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

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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

## rdp-onedash.ru (2 сервера)
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

# Server Metrics 2026-03-21 09:00:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 44685.9 (12h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1174156
telemt_connections_bad_total 59303
telemt_connections_current 1718
telemt_connections_me_current 1718
telemt_handshake_timeouts_total 50805
telemt_upstream_connect_attempt_total 17656
telemt_upstream_connect_success_total 17575
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 17632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11234
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 757
telemt_me_reconnect_success_total 315
telemt_me_reader_eof_total 321
telemt_me_idle_close_by_peer_total 321
telemt_me_route_drop_no_conn_total 492691
telemt_me_route_drop_channel_closed_total 173
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 872593
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_endpoint_quarantine_total 317
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 361
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
telemt_me_writers_active_current 43
telemt_desync_total 3811
telemt_desync_full_logged_total 1332
telemt_desync_suppressed_total 2479
telemt_desync_frames_bucket_total{bucket="1_2"} 800
telemt_desync_frames_bucket_total{bucket="3_10"} 1461
telemt_desync_frames_bucket_total{bucket="gt_10"} 1550
telemt_pool_swap_total 49
telemt_pool_force_close_total 1343
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 178
telemt_me_draining_writers_reap_progress_total 15781
telemt_me_writer_removed_unexpected_total 301
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1236
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14778
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1322
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14438
telemt_me_writer_teardown_success_total{mode="normal"} 16014
telemt_me_writer_teardown_noop_total 15782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31796
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 66.673096
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31796
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 178
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 275
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 871902
telemt_user_connections_current{user="hello"} 1718
telemt_user_octets_from_client{user="hello"} 12852878499 (11.97 GB)
telemt_user_octets_to_client{user="hello"} 253155601719 (235.77 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 587
telemt_user_unique_ips_recent_window{user="hello"} 305
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 44687.1 (12h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2916193
telemt_connections_bad_total 332751
telemt_connections_current 4766
telemt_connections_me_current 4766
telemt_handshake_timeouts_total 86321
telemt_upstream_connect_attempt_total 16247
telemt_upstream_connect_success_total 16172
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 16223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9413
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 971
telemt_me_reconnect_success_total 364
telemt_me_reader_eof_total 359
telemt_me_idle_close_by_peer_total 358
telemt_me_route_drop_no_conn_total 833365
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1890625
telemt_me_endpoint_quarantine_total 290
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 348
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
telemt_me_writers_active_current 42
telemt_desync_total 8447
telemt_desync_full_logged_total 2872
telemt_desync_suppressed_total 5575
telemt_desync_frames_bucket_total{bucket="1_2"} 1715
telemt_desync_frames_bucket_total{bucket="3_10"} 3299
telemt_desync_frames_bucket_total{bucket="gt_10"} 3433
telemt_pool_swap_total 48
telemt_pool_force_close_total 1448
telemt_me_writer_close_signal_drop_total 170
telemt_me_draining_writers_reap_progress_total 14525
telemt_me_writer_removed_unexpected_total 336
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1333
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13524
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1366
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 82
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13077
telemt_me_writer_teardown_success_total{mode="normal"} 14857
telemt_me_writer_teardown_noop_total 14525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29382
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.940590
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29382
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 170
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 292
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 1887036
telemt_user_connections_current{user="hello"} 4766
telemt_user_octets_from_client{user="hello"} 27985250664 (26.06 GB)
telemt_user_octets_to_client{user="hello"} 715085550520 (665.98 GB)
telemt_user_unique_ips_current{user="hello"} 1722
telemt_user_unique_ips_recent_window{user="hello"} 828
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 44683.6 (12h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2131572
telemt_connections_bad_total 257541
telemt_connections_current 4520
telemt_connections_me_current 4520
telemt_handshake_timeouts_total 76127
telemt_upstream_connect_attempt_total 17637
telemt_upstream_connect_success_total 17627
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9586
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 585
telemt_me_reconnect_success_total 334
telemt_me_reader_eof_total 346
telemt_me_idle_close_by_peer_total 346
telemt_me_route_drop_no_conn_total 709239
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1651590
telemt_me_endpoint_quarantine_total 300
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 352
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
telemt_me_writers_active_current 46
telemt_desync_total 7009
telemt_desync_full_logged_total 2461
telemt_desync_suppressed_total 4548
telemt_desync_frames_bucket_total{bucket="1_2"} 1524
telemt_desync_frames_bucket_total{bucket="3_10"} 2733
telemt_desync_frames_bucket_total{bucket="gt_10"} 2752
telemt_pool_swap_total 48
telemt_pool_force_close_total 1415
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 177
telemt_me_draining_writers_reap_progress_total 16038
telemt_me_writer_removed_unexpected_total 326
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1307
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14954
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1341
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 74
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14623
telemt_me_writer_teardown_success_total{mode="normal"} 16261
telemt_me_writer_teardown_noop_total 16048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32309
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 30.618451
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32309
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 177
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 297
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 1648813
telemt_user_connections_current{user="hello"} 4520
telemt_user_octets_from_client{user="hello"} 23470375184 (21.86 GB)
telemt_user_octets_to_client{user="hello"} 666710756872 (620.92 GB)
telemt_user_unique_ips_current{user="hello"} 1571
telemt_user_unique_ips_recent_window{user="hello"} 747
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 44684.8 (12h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1799316
telemt_connections_bad_total 219819
telemt_connections_current 3933
telemt_connections_me_current 3933
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 72626
telemt_upstream_connect_attempt_total 22535
telemt_upstream_connect_success_total 22304
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 22427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9998
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 381
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 910
telemt_me_reconnect_success_total 414
telemt_me_reader_eof_total 384
telemt_me_idle_close_by_peer_total 384
telemt_me_route_drop_no_conn_total 505221
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1236823
telemt_me_endpoint_quarantine_total 319
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 354
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
telemt_desync_total 5800
telemt_desync_full_logged_total 2006
telemt_desync_suppressed_total 3794
telemt_desync_frames_bucket_total{bucket="1_2"} 1416
telemt_desync_frames_bucket_total{bucket="3_10"} 2325
telemt_desync_frames_bucket_total{bucket="gt_10"} 2059
telemt_pool_swap_total 48
telemt_pool_force_close_total 1295
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 85
telemt_me_draining_writers_reap_progress_total 15915
telemt_me_writer_removed_unexpected_total 377
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1267
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15039
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1222
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 73
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14620
telemt_me_writer_teardown_success_total{mode="normal"} 16306
telemt_me_writer_teardown_noop_total 15916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32222
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.656097
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32222
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 85
telemt_me_refill_failed_total 26
telemt_me_writer_restored_same_endpoint_total 350
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1239076
telemt_user_connections_current{user="hello"} 3933
telemt_user_octets_from_client{user="hello"} 24502108785 (22.82 GB)
telemt_user_octets_to_client{user="hello"} 597430933115 (556.40 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1407
telemt_user_unique_ips_recent_window{user="hello"} 684
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 44648.8 (12h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1714024
telemt_connections_bad_total 210110
telemt_connections_current 3198
telemt_connections_me_current 3198
telemt_handshake_timeouts_total 53949
telemt_upstream_connect_attempt_total 18531
telemt_upstream_connect_success_total 18513
telemt_upstream_connect_attempts_per_request{bucket="1"} 18513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10209
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 470
telemt_me_reconnect_success_total 358
telemt_me_reader_eof_total 344
telemt_me_idle_close_by_peer_total 344
telemt_me_route_drop_no_conn_total 442816
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1234591
telemt_me_endpoint_quarantine_total 350
telemt_me_single_endpoint_shadow_rotate_total 346
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
telemt_me_writers_active_current 49
telemt_desync_total 5836
telemt_desync_full_logged_total 2045
telemt_desync_suppressed_total 3791
telemt_desync_frames_bucket_total{bucket="1_2"} 1508
telemt_desync_frames_bucket_total{bucket="3_10"} 2268
telemt_desync_frames_bucket_total{bucket="gt_10"} 2060
telemt_pool_swap_total 48
telemt_pool_force_close_total 1255
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 107
telemt_me_draining_writers_reap_progress_total 16695
telemt_me_writer_removed_unexpected_total 318
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1215
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15826
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1206
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 49
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15440
telemt_me_writer_teardown_success_total{mode="normal"} 17041
telemt_me_writer_teardown_noop_total 16698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33739
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.399503
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33739
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 107
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 315
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 1232432
telemt_user_connections_current{user="hello"} 3198
telemt_user_octets_from_client{user="hello"} 30439873396 (28.35 GB)
telemt_user_octets_to_client{user="hello"} 626708197824 (583.67 GB)
telemt_user_unique_ips_current{user="hello"} 1210
telemt_user_unique_ips_recent_window{user="hello"} 607
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 44688.2 (12h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4825659
telemt_connections_bad_total 266285
telemt_connections_current 5439
telemt_connections_me_current 5439
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 210366
telemt_upstream_connect_attempt_total 44181
telemt_upstream_connect_success_total 42186
telemt_upstream_connect_fail_total 1375
telemt_upstream_connect_attempts_per_request{bucket="1"} 43561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11585
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1279
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1375
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 2296
telemt_me_reconnect_success_total 831
telemt_me_reader_eof_total 561
telemt_me_idle_close_by_peer_total 560
telemt_me_route_drop_no_conn_total 7401292
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4043063
telemt_me_endpoint_quarantine_total 353
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 353
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_me_writers_active_current 90
telemt_desync_total 8527
telemt_desync_full_logged_total 2877
telemt_desync_suppressed_total 5650
telemt_desync_frames_bucket_total{bucket="1_2"} 1889
telemt_desync_frames_bucket_total{bucket="3_10"} 3675
telemt_desync_frames_bucket_total{bucket="gt_10"} 2963
telemt_pool_swap_total 46
telemt_pool_force_close_total 1353
telemt_me_writer_close_signal_drop_total 236
telemt_me_draining_writers_reap_progress_total 15030
telemt_me_writer_removed_unexpected_total 787
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1813
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13959
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1228
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 125
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13677
telemt_me_writer_teardown_success_total{mode="normal"} 15772
telemt_me_writer_teardown_noop_total 15036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30808
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 31.541312
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30808
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 236
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 562
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 217
telemt_user_connections_total{user="hello"} 4065126
telemt_user_connections_current{user="hello"} 5439
telemt_user_octets_from_client{user="hello"} 43565357922 (40.57 GB)
telemt_user_octets_to_client{user="hello"} 543688948898 (506.35 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1904
telemt_user_unique_ips_recent_window{user="hello"} 1071
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 44655.7 (12h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1782925
telemt_connections_bad_total 234073
telemt_connections_current 3500
telemt_connections_me_current 3500
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 34696
telemt_upstream_connect_attempt_total 20010
telemt_upstream_connect_success_total 19824
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 19991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10138
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_reconnect_attempts_total 1792
telemt_me_reconnect_success_total 553
telemt_me_reader_eof_total 567
telemt_me_idle_close_by_peer_total 567
telemt_me_route_drop_no_conn_total 493318
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1321088
telemt_me_endpoint_quarantine_total 273
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 353
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
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
telemt_desync_total 6000
telemt_desync_full_logged_total 2189
telemt_desync_suppressed_total 3811
telemt_desync_frames_bucket_total{bucket="1_2"} 1163
telemt_desync_frames_bucket_total{bucket="3_10"} 2451
telemt_desync_frames_bucket_total{bucket="gt_10"} 2386
telemt_pool_swap_total 47
telemt_pool_force_close_total 1217
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 16573
telemt_me_writer_removed_unexpected_total 545
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1446
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15694
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1143
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 74
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15356
telemt_me_writer_teardown_success_total{mode="normal"} 17140
telemt_me_writer_teardown_noop_total 16573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33713
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.459735
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33713
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 465
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 1317926
telemt_user_connections_current{user="hello"} 3500
telemt_user_octets_from_client{user="hello"} 23053256328 (21.47 GB)
telemt_user_octets_to_client{user="hello"} 617129424738 (574.75 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1335
telemt_user_unique_ips_recent_window{user="hello"} 633
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 44650.1 (12h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2382040
telemt_connections_bad_total 143178
telemt_connections_current 3532
telemt_connections_me_current 3532
telemt_handshake_timeouts_total 921518
telemt_upstream_connect_attempt_total 18869
telemt_upstream_connect_success_total 18835
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 18838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 278
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 468
telemt_me_reconnect_success_total 287
telemt_me_reader_eof_total 288
telemt_me_idle_close_by_peer_total 288
telemt_me_route_drop_no_conn_total 443784
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1166875
telemt_me_endpoint_quarantine_total 355
telemt_me_single_endpoint_shadow_rotate_total 356
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 5731
telemt_desync_full_logged_total 2030
telemt_desync_suppressed_total 3701
telemt_desync_frames_bucket_total{bucket="1_2"} 995
telemt_desync_frames_bucket_total{bucket="3_10"} 2304
telemt_desync_frames_bucket_total{bucket="gt_10"} 2432
telemt_pool_swap_total 49
telemt_pool_force_close_total 1180
telemt_me_writer_close_signal_drop_total 87
telemt_me_draining_writers_reap_progress_total 16896
telemt_me_writer_removed_unexpected_total 278
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1057
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16136
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1163
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15716
telemt_me_writer_teardown_success_total{mode="normal"} 17193
telemt_me_writer_teardown_noop_total 16896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34089
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.774119
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34089
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 87
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 256
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1162826
telemt_user_connections_current{user="hello"} 3532
telemt_user_octets_from_client{user="hello"} 20274426716 (18.88 GB)
telemt_user_octets_to_client{user="hello"} 584848668556 (544.68 GB)
telemt_user_unique_ips_current{user="hello"} 1336
telemt_user_unique_ips_recent_window{user="hello"} 617
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 42641.6 (11h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 504609
telemt_connections_bad_total 18938
telemt_connections_current 616
telemt_connections_me_current 616
telemt_handshake_timeouts_total 173876
telemt_upstream_connect_attempt_total 21067
telemt_upstream_connect_success_total 21065
telemt_upstream_connect_attempts_per_request{bucket="1"} 21065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 846
telemt_me_reconnect_success_total 349
telemt_me_reader_eof_total 344
telemt_me_idle_close_by_peer_total 344
telemt_me_route_drop_no_conn_total 109960
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 274452
telemt_me_endpoint_quarantine_total 418
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 367
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
telemt_me_writers_active_current 46
telemt_desync_total 1709
telemt_desync_full_logged_total 701
telemt_desync_suppressed_total 1008
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 699
telemt_desync_frames_bucket_total{bucket="gt_10"} 667
telemt_pool_swap_total 47
telemt_pool_force_close_total 1008
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 61
telemt_me_draining_writers_reap_progress_total 18791
telemt_me_writer_removed_unexpected_total 326
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1354
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17766
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1006
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17783
telemt_me_writer_teardown_success_total{mode="normal"} 19120
telemt_me_writer_teardown_noop_total 18791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37911
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.550305
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37911
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 61
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 285
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 274625
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 3907674935 (3.64 GB)
telemt_user_octets_to_client{user="hello"} 109030985253 (101.54 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 44660.0 (12h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1825509
telemt_connections_bad_total 160455
telemt_connections_current 4229
telemt_connections_me_current 4229
telemt_handshake_timeouts_total 46703
telemt_upstream_connect_attempt_total 19530
telemt_upstream_connect_success_total 19444
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 19501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9663
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 728
telemt_me_reconnect_success_total 419
telemt_me_reader_eof_total 387
telemt_me_idle_close_by_peer_total 387
telemt_me_route_drop_no_conn_total 437167
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1436280
telemt_me_endpoint_quarantine_total 356
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 356
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
telemt_desync_total 5737
telemt_desync_full_logged_total 1933
telemt_desync_suppressed_total 3804
telemt_desync_frames_bucket_total{bucket="1_2"} 1388
telemt_desync_frames_bucket_total{bucket="3_10"} 2168
telemt_desync_frames_bucket_total{bucket="gt_10"} 2181
telemt_pool_swap_total 49
telemt_pool_force_close_total 1195
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 107
telemt_me_draining_writers_reap_progress_total 17604
telemt_me_writer_removed_unexpected_total 386
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1294
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16705
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1173
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16409
telemt_me_writer_teardown_success_total{mode="normal"} 17999
telemt_me_writer_teardown_noop_total 17604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35603
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.237413
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35603
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 107
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 375
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1431023
telemt_user_connections_current{user="hello"} 4229
telemt_user_octets_from_client{user="hello"} 32051289664 (29.85 GB)
telemt_user_octets_to_client{user="hello"} 666575909392 (620.80 GB)
telemt_user_unique_ips_current{user="hello"} 1472
telemt_user_unique_ips_recent_window{user="hello"} 742
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 44657.0 (12h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1742552
telemt_connections_bad_total 144638
telemt_connections_current 4023
telemt_connections_me_current 4023
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 43312
telemt_upstream_connect_attempt_total 27955
telemt_upstream_connect_success_total 27755
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 27914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10078
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_reconnect_attempts_total 2795
telemt_me_reconnect_success_total 550
telemt_me_reader_eof_total 469
telemt_me_idle_close_by_peer_total 469
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 446793
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1389439
telemt_me_endpoint_quarantine_total 409
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 352
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
telemt_me_writers_active_current 47
telemt_desync_total 5409
telemt_desync_full_logged_total 1789
telemt_desync_suppressed_total 3620
telemt_desync_frames_bucket_total{bucket="1_2"} 1506
telemt_desync_frames_bucket_total{bucket="3_10"} 1985
telemt_desync_frames_bucket_total{bucket="gt_10"} 1918
telemt_pool_swap_total 49
telemt_pool_force_close_total 1177
telemt_me_writer_close_signal_drop_total 99
telemt_me_draining_writers_reap_progress_total 16694
telemt_me_writer_removed_unexpected_total 478
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1505
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15692
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1124
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15517
telemt_me_writer_teardown_success_total{mode="normal"} 17197
telemt_me_writer_teardown_noop_total 16695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33892
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.965734
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33892
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 99
telemt_me_refill_failed_total 127
telemt_me_writer_restored_same_endpoint_total 415
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 1393466
telemt_user_connections_current{user="hello"} 4023
telemt_user_octets_from_client{user="hello"} 21363957539 (19.90 GB)
telemt_user_octets_to_client{user="hello"} 620084226419 (577.50 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1417
telemt_user_unique_ips_recent_window{user="hello"} 700
```
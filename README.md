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

# Server Metrics 2026-03-21 12:50:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 58469.6 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1911417
telemt_connections_bad_total 95236
telemt_connections_current 1665
telemt_connections_me_current 1665
telemt_handshake_timeouts_total 70980
telemt_upstream_connect_attempt_total 22572
telemt_upstream_connect_success_total 22461
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 22534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14416
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1241
telemt_me_reconnect_success_total 517
telemt_me_reader_eof_total 500
telemt_me_idle_close_by_peer_total 500
telemt_me_route_drop_no_conn_total 1449304
telemt_me_route_drop_channel_closed_total 468
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1500087
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 411
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 461
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_desync_total 5814
telemt_desync_full_logged_total 2033
telemt_desync_suppressed_total 3781
telemt_desync_frames_bucket_total{bucket="1_2"} 1251
telemt_desync_frames_bucket_total{bucket="3_10"} 2234
telemt_desync_frames_bucket_total{bucket="gt_10"} 2329
telemt_pool_swap_total 63
telemt_pool_force_close_total 1849
telemt_pool_stale_pick_total 14
telemt_me_writer_close_signal_drop_total 357
telemt_me_draining_writers_reap_progress_total 20176
telemt_me_writer_removed_unexpected_total 481
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1663
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18846
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1784
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 65
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18327
telemt_me_writer_teardown_success_total{mode="normal"} 20509
telemt_me_writer_teardown_noop_total 20180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40689
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 154.660753
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40689
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 357
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 448
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1498988
telemt_user_connections_current{user="hello"} 1665
telemt_user_octets_from_client{user="hello"} 22164452415 (20.64 GB)
telemt_user_octets_to_client{user="hello"} 388540738215 (361.86 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 561
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 4114.6 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273136
telemt_connections_bad_total 16300
telemt_connections_current 2664
telemt_connections_me_current 2664
telemt_handshake_timeouts_total 15680
telemt_upstream_connect_attempt_total 1748
telemt_upstream_connect_success_total 1689
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 1730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 962
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 134
telemt_me_reconnect_success_total 102
telemt_me_reader_eof_total 101
telemt_me_idle_close_by_peer_total 101
telemt_me_route_drop_no_conn_total 220929
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222580
telemt_me_endpoint_quarantine_total 26
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 31
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
telemt_me_writers_active_current 85
telemt_desync_total 853
telemt_desync_full_logged_total 392
telemt_desync_suppressed_total 461
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 343
telemt_pool_swap_total 2
telemt_pool_force_close_total 80
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 1368
telemt_me_writer_removed_unexpected_total 109
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1285
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 59
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1288
telemt_me_writer_teardown_success_total{mode="normal"} 1477
telemt_me_writer_teardown_noop_total 1368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2845
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.219008
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2845
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_writer_restored_same_endpoint_total 95
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 222481
telemt_user_connections_current{user="hello"} 2664
telemt_user_octets_from_client{user="hello"} 3605154208 (3.36 GB)
telemt_user_octets_to_client{user="hello"} 58633300108 (54.61 GB)
telemt_user_unique_ips_current{user="hello"} 1319
telemt_user_unique_ips_recent_window{user="hello"} 571
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 58467.1 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3692089
telemt_connections_bad_total 379865
telemt_connections_current 4180
telemt_connections_me_current 4180
telemt_handshake_timeouts_total 144736
telemt_upstream_connect_attempt_total 22058
telemt_upstream_connect_success_total 22025
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 22030
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11992
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 816
telemt_me_reconnect_success_total 454
telemt_me_reader_eof_total 463
telemt_me_idle_close_by_peer_total 463
telemt_me_route_drop_no_conn_total 1771241
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2951389
telemt_me_endpoint_quarantine_total 374
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 446
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 12588
telemt_desync_full_logged_total 4268
telemt_desync_suppressed_total 8320
telemt_desync_frames_bucket_total{bucket="1_2"} 2672
telemt_desync_frames_bucket_total{bucket="3_10"} 4922
telemt_desync_frames_bucket_total{bucket="gt_10"} 4994
telemt_pool_swap_total 62
telemt_pool_force_close_total 1956
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 287
telemt_me_draining_writers_reap_progress_total 20038
telemt_me_writer_removed_unexpected_total 447
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1692
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18614
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 16
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1815
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 141
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18082
telemt_me_writer_teardown_success_total{mode="normal"} 20306
telemt_me_writer_teardown_noop_total 20054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40360
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 56.921292
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40360
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 287
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 410
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 2947582
telemt_user_connections_current{user="hello"} 4180
telemt_user_octets_from_client{user="hello"} 47819633444 (44.54 GB)
telemt_user_octets_to_client{user="hello"} 1034557308772 (963.51 GB)
telemt_user_unique_ips_current{user="hello"} 1654
telemt_user_unique_ips_recent_window{user="hello"} 549
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 58468.6 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3025670
telemt_connections_bad_total 330286
telemt_connections_current 3845
telemt_connections_me_current 3845
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 119257
telemt_upstream_connect_attempt_total 26780
telemt_upstream_connect_success_total 26508
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 26640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12190
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 476
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1143
telemt_me_reconnect_success_total 527
telemt_me_reader_eof_total 489
telemt_me_idle_close_by_peer_total 489
telemt_me_route_drop_no_conn_total 943396
telemt_me_route_drop_channel_closed_total 76
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2167324
telemt_me_endpoint_quarantine_total 389
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 448
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
telemt_me_writers_active_current 43
telemt_desync_total 9993
telemt_desync_full_logged_total 3389
telemt_desync_suppressed_total 6604
telemt_desync_frames_bucket_total{bucket="1_2"} 2484
telemt_desync_frames_bucket_total{bucket="3_10"} 3877
telemt_desync_frames_bucket_total{bucket="gt_10"} 3632
telemt_pool_swap_total 63
telemt_pool_force_close_total 1764
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 150
telemt_me_draining_writers_reap_progress_total 19549
telemt_me_writer_removed_unexpected_total 477
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1655
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18391
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1647
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 117
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17785
telemt_me_writer_teardown_success_total{mode="normal"} 20046
telemt_me_writer_teardown_noop_total 19550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39596
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.147381
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39596
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 150
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 442
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 2168378
telemt_user_connections_current{user="hello"} 3845
telemt_user_octets_from_client{user="hello"} 40996816693 (38.18 GB)
telemt_user_octets_to_client{user="hello"} 1027070742779 (956.53 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1482
telemt_user_unique_ips_recent_window{user="hello"} 505
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 58432.3 (16h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2944710
telemt_connections_bad_total 324875
telemt_connections_current 3285
telemt_connections_me_current 3285
telemt_handshake_timeouts_total 86661
telemt_upstream_connect_attempt_total 23430
telemt_upstream_connect_success_total 23338
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 23340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12689
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 46
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 941
telemt_me_reconnect_success_total 599
telemt_me_reader_eof_total 549
telemt_me_idle_close_by_peer_total 549
telemt_me_route_drop_no_conn_total 894631
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2144709
telemt_me_endpoint_quarantine_total 426
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 439
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 9939
telemt_desync_full_logged_total 3328
telemt_desync_suppressed_total 6611
telemt_desync_frames_bucket_total{bucket="1_2"} 2578
telemt_desync_frames_bucket_total{bucket="3_10"} 3780
telemt_desync_frames_bucket_total{bucket="gt_10"} 3581
telemt_pool_swap_total 61
telemt_pool_force_close_total 1740
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 200
telemt_me_draining_writers_reap_progress_total 20856
telemt_me_writer_removed_unexpected_total 523
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1743
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19675
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1588
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 152
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19116
telemt_me_writer_teardown_success_total{mode="normal"} 21418
telemt_me_writer_teardown_noop_total 20860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42278
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.164426
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42278
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 200
telemt_me_refill_failed_total 19
telemt_me_writer_restored_same_endpoint_total 523
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 2141517
telemt_user_connections_current{user="hello"} 3285
telemt_user_octets_from_client{user="hello"} 48030964504 (44.73 GB)
telemt_user_octets_to_client{user="hello"} 1023930207916 (953.61 GB)
telemt_user_unique_ips_current{user="hello"} 1326
telemt_user_unique_ips_recent_window{user="hello"} 492
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 58471.5 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9797954
telemt_connections_bad_total 662015
telemt_connections_current 5717
telemt_connections_me_current 5717
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 324145
telemt_upstream_connect_attempt_total 89117
telemt_upstream_connect_success_total 83936
telemt_upstream_connect_fail_total 4325
telemt_upstream_connect_attempts_per_request{bucket="1"} 88261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4325
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3485
telemt_me_reconnect_success_total 1180
telemt_me_reader_eof_total 832
telemt_me_idle_close_by_peer_total 831
telemt_me_route_drop_no_conn_total 17658633
telemt_me_route_drop_channel_closed_total 63
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8078204
telemt_me_endpoint_quarantine_total 448
telemt_me_single_endpoint_outage_enter_total 67
telemt_me_single_endpoint_outage_exit_total 67
telemt_me_single_endpoint_outage_reconnect_attempt_total 152
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 152
telemt_me_single_endpoint_shadow_rotate_total 460
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 15362
telemt_desync_full_logged_total 4932
telemt_desync_suppressed_total 10430
telemt_desync_frames_bucket_total{bucket="1_2"} 3273
telemt_desync_frames_bucket_total{bucket="3_10"} 6785
telemt_desync_frames_bucket_total{bucket="gt_10"} 5304
telemt_pool_swap_total 59
telemt_pool_force_close_total 1874
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 387
telemt_me_draining_writers_reap_progress_total 19072
telemt_me_writer_removed_unexpected_total 1142
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2471
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17625
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1603
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 271
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17198
telemt_me_writer_teardown_success_total{mode="normal"} 20096
telemt_me_writer_teardown_noop_total 19081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39177
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 51.448781
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39177
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 387
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 820
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 8135925
telemt_user_connections_current{user="hello"} 5717
telemt_user_octets_from_client{user="hello"} 63460940477 (59.10 GB)
telemt_user_octets_to_client{user="hello"} 695452086240 (647.69 GB)
telemt_user_msgs_from_client{user="hello"} 173886
telemt_user_msgs_to_client{user="hello"} 472410
telemt_user_unique_ips_current{user="hello"} 1988
telemt_user_unique_ips_recent_window{user="hello"} 1129
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 58439.3 (16h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2980012
telemt_connections_bad_total 351671
telemt_connections_current 3618
telemt_connections_me_current 3618
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 65204
telemt_upstream_connect_attempt_total 25076
telemt_upstream_connect_success_total 24796
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 25046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12850
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_reconnect_attempts_total 2417
telemt_me_reconnect_success_total 846
telemt_me_reader_eof_total 835
telemt_me_idle_close_by_peer_total 835
telemt_me_route_drop_no_conn_total 1094160
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2259035
telemt_me_endpoint_quarantine_total 370
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 445
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 10454
telemt_desync_full_logged_total 3664
telemt_desync_suppressed_total 6790
telemt_desync_frames_bucket_total{bucket="1_2"} 2054
telemt_desync_frames_bucket_total{bucket="3_10"} 4188
telemt_desync_frames_bucket_total{bucket="gt_10"} 4212
telemt_pool_swap_total 59
telemt_pool_force_close_total 1659
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 151
telemt_me_draining_writers_reap_progress_total 20910
telemt_me_writer_removed_unexpected_total 808
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1996
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19749
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1472
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 187
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19251
telemt_me_writer_teardown_success_total{mode="normal"} 21745
telemt_me_writer_teardown_noop_total 20911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42656
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.392748
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42656
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 151
telemt_me_refill_failed_total 86
telemt_me_writer_restored_same_endpoint_total 713
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 2243869
telemt_user_connections_current{user="hello"} 3618
telemt_user_octets_from_client{user="hello"} 42368123008 (39.46 GB)
telemt_user_octets_to_client{user="hello"} 987549485962 (919.73 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1472
telemt_user_unique_ips_recent_window{user="hello"} 534
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 58433.8 (16h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4529548
telemt_connections_bad_total 228887
telemt_connections_current 3465
telemt_connections_me_current 3465
telemt_handshake_timeouts_total 1994509
telemt_upstream_connect_attempt_total 23298
telemt_upstream_connect_success_total 23264
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 23267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 944
telemt_me_reconnect_success_total 418
telemt_me_reader_eof_total 424
telemt_me_idle_close_by_peer_total 424
telemt_me_route_drop_no_conn_total 986377
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2022348
telemt_me_endpoint_quarantine_total 441
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 456
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
telemt_me_writers_active_current 45
telemt_desync_total 9631
telemt_desync_full_logged_total 3427
telemt_desync_suppressed_total 6204
telemt_desync_frames_bucket_total{bucket="1_2"} 1770
telemt_desync_frames_bucket_total{bucket="3_10"} 3836
telemt_desync_frames_bucket_total{bucket="gt_10"} 4025
telemt_pool_swap_total 63
telemt_pool_force_close_total 1601
telemt_me_writer_close_signal_drop_total 136
telemt_me_draining_writers_reap_progress_total 20843
telemt_me_writer_removed_unexpected_total 408
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1419
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19857
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1546
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19242
telemt_me_writer_teardown_success_total{mode="normal"} 21276
telemt_me_writer_teardown_noop_total 20843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42119
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.229215
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42119
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 136
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 365
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 2015782
telemt_user_connections_current{user="hello"} 3465
telemt_user_octets_from_client{user="hello"} 37293576116 (34.73 GB)
telemt_user_octets_to_client{user="hello"} 955330408608 (889.72 GB)
telemt_user_unique_ips_current{user="hello"} 1430
telemt_user_unique_ips_recent_window{user="hello"} 506
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 56425.0 (15h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 965235
telemt_connections_bad_total 110487
telemt_connections_current 685
telemt_connections_me_current 685
telemt_handshake_timeouts_total 340759
telemt_upstream_connect_attempt_total 26731
telemt_upstream_connect_success_total 26729
telemt_upstream_connect_attempts_per_request{bucket="1"} 26729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1120
telemt_me_reconnect_success_total 435
telemt_me_reader_eof_total 434
telemt_me_idle_close_by_peer_total 434
telemt_me_route_drop_no_conn_total 199229
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 448369
telemt_me_endpoint_quarantine_total 516
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 478
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_desync_total 3083
telemt_desync_full_logged_total 1155
telemt_desync_suppressed_total 1928
telemt_desync_frames_bucket_total{bucket="1_2"} 540
telemt_desync_frames_bucket_total{bucket="3_10"} 1099
telemt_desync_frames_bucket_total{bucket="gt_10"} 1444
telemt_pool_swap_total 62
telemt_pool_force_close_total 1393
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 99
telemt_me_draining_writers_reap_progress_total 23976
telemt_me_writer_removed_unexpected_total 411
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1746
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22649
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1390
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22583
telemt_me_writer_teardown_success_total{mode="normal"} 24395
telemt_me_writer_teardown_noop_total 23976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48371
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.032527
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48371
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 99
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 354
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 448189
telemt_user_connections_current{user="hello"} 685
telemt_user_octets_from_client{user="hello"} 7249153951 (6.75 GB)
telemt_user_octets_to_client{user="hello"} 171028345561 (159.28 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 58443.6 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3206941
telemt_connections_bad_total 312608
telemt_connections_current 4184
telemt_connections_me_current 4184
telemt_handshake_timeouts_total 93729
telemt_upstream_connect_attempt_total 24120
telemt_upstream_connect_success_total 24020
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 24089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12051
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 973
telemt_me_reconnect_success_total 550
telemt_me_reader_eof_total 514
telemt_me_idle_close_by_peer_total 514
telemt_me_route_drop_no_conn_total 873621
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2519386
telemt_me_endpoint_quarantine_total 445
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 450
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 10270
telemt_desync_full_logged_total 3373
telemt_desync_suppressed_total 6897
telemt_desync_frames_bucket_total{bucket="1_2"} 2454
telemt_desync_frames_bucket_total{bucket="3_10"} 3840
telemt_desync_frames_bucket_total{bucket="gt_10"} 3976
telemt_pool_swap_total 64
telemt_pool_force_close_total 1626
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 174
telemt_me_draining_writers_reap_progress_total 21651
telemt_me_writer_removed_unexpected_total 505
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1673
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20500
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1596
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20025
telemt_me_writer_teardown_success_total{mode="normal"} 22173
telemt_me_writer_teardown_noop_total 21651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43824
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.467819
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43824
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 174
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 490
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 2512347
telemt_user_connections_current{user="hello"} 4184
telemt_user_octets_from_client{user="hello"} 53014643288 (49.37 GB)
telemt_user_octets_to_client{user="hello"} 1183592107424 (1.08 TB)
telemt_user_unique_ips_current{user="hello"} 1558
telemt_user_unique_ips_recent_window{user="hello"} 532
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 58440.2 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2887333
telemt_connections_bad_total 240964
telemt_connections_current 3713
telemt_connections_me_current 3713
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 82079
telemt_upstream_connect_attempt_total 40331
telemt_upstream_connect_success_total 40072
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 40287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13711
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 586
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_reconnect_attempts_total 3413
telemt_me_reconnect_success_total 726
telemt_me_reader_eof_total 627
telemt_me_idle_close_by_peer_total 627
telemt_me_seq_mismatch_total 29
telemt_me_route_drop_no_conn_total 934356
telemt_me_route_drop_channel_closed_total 68
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2321786
telemt_me_endpoint_quarantine_total 503
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 449
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_me_writers_active_current 50
telemt_desync_total 8946
telemt_desync_full_logged_total 3048
telemt_desync_suppressed_total 5898
telemt_desync_frames_bucket_total{bucket="1_2"} 2303
telemt_desync_frames_bucket_total{bucket="3_10"} 3288
telemt_desync_frames_bucket_total{bucket="gt_10"} 3355
telemt_pool_swap_total 63
telemt_pool_force_close_total 1587
telemt_me_writer_close_signal_drop_total 152
telemt_me_draining_writers_reap_progress_total 20859
telemt_me_writer_removed_unexpected_total 640
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1965
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19562
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1483
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 104
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19272
telemt_me_writer_teardown_success_total{mode="normal"} 21527
telemt_me_writer_teardown_noop_total 20860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42387
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.564823
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42387
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 152
telemt_me_refill_failed_total 152
telemt_me_writer_restored_same_endpoint_total 551
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 2331944
telemt_user_connections_current{user="hello"} 3713
telemt_user_octets_from_client{user="hello"} 43491650973 (40.50 GB)
telemt_user_octets_to_client{user="hello"} 1022363398068 (952.15 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1458
telemt_user_unique_ips_recent_window{user="hello"} 513
```
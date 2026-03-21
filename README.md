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

# Server Metrics 2026-03-21 06:43:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 36439.0 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 780120
telemt_connections_bad_total 42795
telemt_connections_current 1300
telemt_connections_me_current 1300
telemt_handshake_timeouts_total 38792
telemt_upstream_connect_attempt_total 14762
telemt_upstream_connect_success_total 14695
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 14739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9548
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 456
telemt_me_reconnect_success_total 235
telemt_me_reader_eof_total 247
telemt_me_idle_close_by_peer_total 247
telemt_me_route_drop_no_conn_total 258611
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 582270
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 258
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 303
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_me_writers_active_current 44
telemt_desync_total 2533
telemt_desync_full_logged_total 910
telemt_desync_suppressed_total 1623
telemt_desync_frames_bucket_total{bucket="1_2"} 527
telemt_desync_frames_bucket_total{bucket="3_10"} 1002
telemt_desync_frames_bucket_total{bucket="gt_10"} 1004
telemt_pool_swap_total 40
telemt_pool_force_close_total 1096
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 100
telemt_me_draining_writers_reap_progress_total 13318
telemt_me_writer_removed_unexpected_total 232
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 980
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12528
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1092
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12222
telemt_me_writer_teardown_success_total{mode="normal"} 13508
telemt_me_writer_teardown_noop_total 13319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26827
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 41.717977
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26827
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 100
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 212
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 581521
telemt_user_connections_current{user="hello"} 1300
telemt_user_octets_from_client{user="hello"} 6918194344 (6.44 GB)
telemt_user_octets_to_client{user="hello"} 182780266964 (170.23 GB)
telemt_user_unique_ips_current{user="hello"} 517
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 36440.3 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1972449
telemt_connections_bad_total 223971
telemt_connections_current 3965
telemt_connections_me_current 3965
telemt_handshake_timeouts_total 60914
telemt_upstream_connect_attempt_total 13768
telemt_upstream_connect_success_total 13705
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 13749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8045
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_reconnect_attempts_total 770
telemt_me_reconnect_success_total 276
telemt_me_reader_eof_total 285
telemt_me_idle_close_by_peer_total 285
telemt_me_route_drop_no_conn_total 383738
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1173947
telemt_me_endpoint_quarantine_total 241
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 295
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
telemt_me_writers_active_current 43
telemt_desync_total 4984
telemt_desync_full_logged_total 1741
telemt_desync_suppressed_total 3243
telemt_desync_frames_bucket_total{bucket="1_2"} 1018
telemt_desync_frames_bucket_total{bucket="3_10"} 1980
telemt_desync_frames_bucket_total{bucket="gt_10"} 1986
telemt_pool_swap_total 39
telemt_pool_force_close_total 1160
telemt_me_writer_close_signal_drop_total 118
telemt_me_draining_writers_reap_progress_total 12363
telemt_me_writer_removed_unexpected_total 266
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1087
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11534
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1107
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11203
telemt_me_writer_teardown_success_total{mode="normal"} 12621
telemt_me_writer_teardown_noop_total 12363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24984
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.936745
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24984
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 118
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 233
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 1170952
telemt_user_connections_current{user="hello"} 3965
telemt_user_octets_from_client{user="hello"} 16162999832 (15.05 GB)
telemt_user_octets_to_client{user="hello"} 483188377180 (450.00 GB)
telemt_user_unique_ips_current{user="hello"} 1412
telemt_user_unique_ips_recent_window{user="hello"} 508
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 36436.7 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1303307
telemt_connections_bad_total 159134
telemt_connections_current 3224
telemt_connections_me_current 3224
telemt_handshake_timeouts_total 60175
telemt_upstream_connect_attempt_total 14860
telemt_upstream_connect_success_total 14850
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 411
telemt_me_reconnect_success_total 240
telemt_me_reader_eof_total 250
telemt_me_idle_close_by_peer_total 250
telemt_me_route_drop_no_conn_total 314857
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1008342
telemt_me_endpoint_quarantine_total 259
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 294
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 4060
telemt_desync_full_logged_total 1472
telemt_desync_suppressed_total 2588
telemt_desync_frames_bucket_total{bucket="1_2"} 910
telemt_desync_frames_bucket_total{bucket="3_10"} 1566
telemt_desync_frames_bucket_total{bucket="gt_10"} 1584
telemt_pool_swap_total 40
telemt_pool_force_close_total 1095
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 124
telemt_me_draining_writers_reap_progress_total 13543
telemt_me_writer_removed_unexpected_total 231
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1051
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12660
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1089
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12448
telemt_me_writer_teardown_success_total{mode="normal"} 13711
telemt_me_writer_teardown_noop_total 13546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27257
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.920645
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27257
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 124
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 206
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1006168
telemt_user_connections_current{user="hello"} 3224
telemt_user_octets_from_client{user="hello"} 13903075408 (12.95 GB)
telemt_user_octets_to_client{user="hello"} 445142994428 (414.57 GB)
telemt_user_unique_ips_current{user="hello"} 1206
telemt_user_unique_ips_recent_window{user="hello"} 442
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 36437.9 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1128310
telemt_connections_bad_total 152692
telemt_connections_current 2537
telemt_connections_me_current 2537
telemt_handshake_timeouts_total 55532
telemt_upstream_connect_attempt_total 14998
telemt_upstream_connect_success_total 14909
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 14950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8313
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 653
telemt_me_reconnect_success_total 268
telemt_me_reader_eof_total 268
telemt_me_idle_close_by_peer_total 268
telemt_me_route_drop_no_conn_total 245060
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 762940
telemt_me_endpoint_quarantine_total 260
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 297
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
telemt_desync_total 3418
telemt_desync_full_logged_total 1266
telemt_desync_suppressed_total 2152
telemt_desync_frames_bucket_total{bucket="1_2"} 744
telemt_desync_frames_bucket_total{bucket="3_10"} 1472
telemt_desync_frames_bucket_total{bucket="gt_10"} 1202
telemt_pool_swap_total 40
telemt_pool_force_close_total 1040
telemt_me_writer_close_signal_drop_total 51
telemt_me_draining_writers_reap_progress_total 13462
telemt_me_writer_removed_unexpected_total 256
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 975
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12757
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1022
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12422
telemt_me_writer_teardown_success_total{mode="normal"} 13732
telemt_me_writer_teardown_noop_total 13463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27195
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.159719
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27195
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 51
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 229
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 761587
telemt_user_connections_current{user="hello"} 2537
telemt_user_octets_from_client{user="hello"} 13848534336 (12.90 GB)
telemt_user_octets_to_client{user="hello"} 369364485980 (344.00 GB)
telemt_user_unique_ips_current{user="hello"} 976
telemt_user_unique_ips_recent_window{user="hello"} 336
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 36401.9 (10h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1076572
telemt_connections_bad_total 135097
telemt_connections_current 2482
telemt_connections_me_current 2482
telemt_handshake_timeouts_total 39540
telemt_upstream_connect_attempt_total 15502
telemt_upstream_connect_success_total 15493
telemt_upstream_connect_attempts_per_request{bucket="1"} 15493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8604
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 275
telemt_me_reconnect_success_total 231
telemt_me_reader_eof_total 228
telemt_me_idle_close_by_peer_total 228
telemt_me_route_drop_no_conn_total 216613
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 758846
telemt_me_endpoint_quarantine_total 305
telemt_me_single_endpoint_shadow_rotate_total 293
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 3513
telemt_desync_full_logged_total 1322
telemt_desync_suppressed_total 2191
telemt_desync_frames_bucket_total{bucket="1_2"} 866
telemt_desync_frames_bucket_total{bucket="3_10"} 1373
telemt_desync_frames_bucket_total{bucket="gt_10"} 1274
telemt_pool_swap_total 40
telemt_pool_force_close_total 996
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 61
telemt_me_draining_writers_reap_progress_total 14056
telemt_me_writer_removed_unexpected_total 209
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 927
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13358
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 986
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13060
telemt_me_writer_teardown_success_total{mode="normal"} 14285
telemt_me_writer_teardown_noop_total 14057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28342
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.454312
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28342
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 61
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 205
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 757345
telemt_user_connections_current{user="hello"} 2482
telemt_user_octets_from_client{user="hello"} 18216133912 (16.97 GB)
telemt_user_octets_to_client{user="hello"} 394412071396 (367.32 GB)
telemt_user_unique_ips_current{user="hello"} 933
telemt_user_unique_ips_recent_window{user="hello"} 344
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 36441.1 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2252716
telemt_connections_bad_total 166668
telemt_connections_current 4249
telemt_connections_me_current 4249
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 148811
telemt_upstream_connect_attempt_total 40998
telemt_upstream_connect_success_total 39160
telemt_upstream_connect_fail_total 1324
telemt_upstream_connect_attempts_per_request{bucket="1"} 40484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9927
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1324
telemt_me_reconnect_attempts_total 1778
telemt_me_reconnect_success_total 577
telemt_me_reader_eof_total 386
telemt_me_idle_close_by_peer_total 385
telemt_me_route_drop_no_conn_total 1798131
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1771786
telemt_me_endpoint_quarantine_total 294
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 78
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 78
telemt_me_single_endpoint_shadow_rotate_total 295
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
telemt_me_writers_active_current 44
telemt_desync_total 4417
telemt_desync_full_logged_total 1647
telemt_desync_suppressed_total 2770
telemt_desync_frames_bucket_total{bucket="1_2"} 999
telemt_desync_frames_bucket_total{bucket="3_10"} 1865
telemt_desync_frames_bucket_total{bucket="gt_10"} 1553
telemt_pool_swap_total 39
telemt_pool_force_close_total 1084
telemt_me_writer_close_signal_drop_total 158
telemt_me_draining_writers_reap_progress_total 12516
telemt_me_writer_removed_unexpected_total 557
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1414
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11628
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1018
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 66
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11432
telemt_me_writer_teardown_success_total{mode="normal"} 13042
telemt_me_writer_teardown_noop_total 12520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25562
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.969024
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25562
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 158
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 371
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 1795001
telemt_user_connections_current{user="hello"} 4249
telemt_user_octets_from_client{user="hello"} 32342203870 (30.12 GB)
telemt_user_octets_to_client{user="hello"} 450582682098 (419.64 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1518
telemt_user_unique_ips_recent_window{user="hello"} 625
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 36408.7 (10h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1152339
telemt_connections_bad_total 161336
telemt_connections_current 2371
telemt_connections_me_current 2371
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 24618
telemt_upstream_connect_attempt_total 16986
telemt_upstream_connect_success_total 16835
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 16971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_reconnect_attempts_total 1395
telemt_me_reconnect_success_total 335
telemt_me_reader_eof_total 345
telemt_me_idle_close_by_peer_total 345
telemt_me_route_drop_no_conn_total 275473
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 830326
telemt_me_endpoint_quarantine_total 245
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 296
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
telemt_me_writers_active_current 42
telemt_desync_total 3368
telemt_desync_full_logged_total 1279
telemt_desync_suppressed_total 2089
telemt_desync_frames_bucket_total{bucket="1_2"} 639
telemt_desync_frames_bucket_total{bucket="3_10"} 1385
telemt_desync_frames_bucket_total{bucket="gt_10"} 1344
telemt_pool_swap_total 40
telemt_pool_force_close_total 956
telemt_me_writer_close_signal_drop_total 59
telemt_me_draining_writers_reap_progress_total 14007
telemt_me_writer_removed_unexpected_total 325
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1055
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13297
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 949
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13051
telemt_me_writer_teardown_success_total{mode="normal"} 14352
telemt_me_writer_teardown_noop_total 14007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28359
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.059858
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28359
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 59
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 256
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 827940
telemt_user_connections_current{user="hello"} 2371
telemt_user_octets_from_client{user="hello"} 13784272008 (12.84 GB)
telemt_user_octets_to_client{user="hello"} 414377921010 (385.92 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 970
telemt_user_unique_ips_recent_window{user="hello"} 371
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 36403.1 (10h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1461480
telemt_connections_bad_total 91835
telemt_connections_current 2318
telemt_connections_me_current 2318
telemt_handshake_timeouts_total 521785
telemt_upstream_connect_attempt_total 16168
telemt_upstream_connect_success_total 16141
telemt_upstream_connect_attempts_per_request{bucket="1"} 16141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8650
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 259
telemt_me_reconnect_attempts_total 343
telemt_me_reconnect_success_total 238
telemt_me_reader_eof_total 246
telemt_me_idle_close_by_peer_total 246
telemt_me_route_drop_no_conn_total 241503
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 738567
telemt_me_endpoint_quarantine_total 313
telemt_me_single_endpoint_shadow_rotate_total 301
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
telemt_desync_total 3281
telemt_desync_full_logged_total 1164
telemt_desync_suppressed_total 2117
telemt_desync_frames_bucket_total{bucket="1_2"} 599
telemt_desync_frames_bucket_total{bucket="3_10"} 1334
telemt_desync_frames_bucket_total{bucket="gt_10"} 1348
telemt_pool_swap_total 40
telemt_pool_force_close_total 918
telemt_me_writer_close_signal_drop_total 53
telemt_me_draining_writers_reap_progress_total 14498
telemt_me_writer_removed_unexpected_total 230
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 855
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13890
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 910
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13580
telemt_me_writer_teardown_success_total{mode="normal"} 14745
telemt_me_writer_teardown_noop_total 14498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29243
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.515852
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29243
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 53
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 213
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 735626
telemt_user_connections_current{user="hello"} 2318
telemt_user_octets_from_client{user="hello"} 11897184256 (11.08 GB)
telemt_user_octets_to_client{user="hello"} 381638833092 (355.43 GB)
telemt_user_unique_ips_current{user="hello"} 940
telemt_user_unique_ips_recent_window{user="hello"} 377
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 34394.7 (9h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279495
telemt_connections_bad_total 11173
telemt_connections_current 483
telemt_connections_me_current 483
telemt_handshake_timeouts_total 74580
telemt_upstream_connect_attempt_total 17578
telemt_upstream_connect_success_total 17577
telemt_upstream_connect_attempts_per_request{bucket="1"} 17577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 539
telemt_me_reconnect_success_total 251
telemt_me_reader_eof_total 264
telemt_me_idle_close_by_peer_total 264
telemt_me_route_drop_no_conn_total 67258
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180473
telemt_me_endpoint_quarantine_total 339
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 298
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_me_writers_active_current 42
telemt_desync_total 1105
telemt_desync_full_logged_total 528
telemt_desync_suppressed_total 577
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 459
telemt_desync_frames_bucket_total{bucket="gt_10"} 436
telemt_pool_swap_total 38
telemt_pool_force_close_total 778
telemt_me_writer_close_signal_drop_total 47
telemt_me_draining_writers_reap_progress_total 15692
telemt_me_writer_removed_unexpected_total 248
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1086
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14855
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 778
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14914
telemt_me_writer_teardown_success_total{mode="normal"} 15941
telemt_me_writer_teardown_noop_total 15692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31633
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.994829
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31633
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 47
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 220
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 180706
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 1974126359 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 75926305965 (70.71 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 36413.1 (10h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1176326
telemt_connections_bad_total 88204
telemt_connections_current 3283
telemt_connections_me_current 3283
telemt_handshake_timeouts_total 31134
telemt_upstream_connect_attempt_total 16634
telemt_upstream_connect_success_total 16559
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 16605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8238
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_reconnect_attempts_total 576
telemt_me_reconnect_success_total 331
telemt_me_reader_eof_total 316
telemt_me_idle_close_by_peer_total 316
telemt_me_route_drop_no_conn_total 252274
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 913126
telemt_me_endpoint_quarantine_total 305
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 295
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
telemt_desync_total 3614
telemt_desync_full_logged_total 1207
telemt_desync_suppressed_total 2407
telemt_desync_frames_bucket_total{bucket="1_2"} 960
telemt_desync_frames_bucket_total{bucket="3_10"} 1367
telemt_desync_frames_bucket_total{bucket="gt_10"} 1287
telemt_pool_swap_total 40
telemt_pool_force_close_total 934
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 70
telemt_me_draining_writers_reap_progress_total 15024
telemt_me_writer_removed_unexpected_total 317
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1050
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14298
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 933
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14090
telemt_me_writer_teardown_success_total{mode="normal"} 15348
telemt_me_writer_teardown_noop_total 15024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30372
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.006251
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30372
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 70
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 303
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 908826
telemt_user_connections_current{user="hello"} 3283
telemt_user_octets_from_client{user="hello"} 13825686900 (12.88 GB)
telemt_user_octets_to_client{user="hello"} 412239331824 (383.93 GB)
telemt_user_unique_ips_current{user="hello"} 1191
telemt_user_unique_ips_recent_window{user="hello"} 400
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 36409.8 (10h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1122226
telemt_connections_bad_total 73324
telemt_connections_current 2544
telemt_connections_me_current 2544
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 29556
telemt_upstream_connect_attempt_total 25187
telemt_upstream_connect_success_total 25009
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 25147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_reconnect_attempts_total 2478
telemt_me_reconnect_success_total 455
telemt_me_reader_eof_total 393
telemt_me_idle_close_by_peer_total 393
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 258923
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 891665
telemt_me_endpoint_quarantine_total 372
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 295
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
telemt_me_writers_active_current 44
telemt_desync_total 3419
telemt_desync_full_logged_total 1086
telemt_desync_suppressed_total 2333
telemt_desync_frames_bucket_total{bucket="1_2"} 1026
telemt_desync_frames_bucket_total{bucket="3_10"} 1248
telemt_desync_frames_bucket_total{bucket="gt_10"} 1145
telemt_pool_swap_total 40
telemt_pool_force_close_total 904
telemt_me_writer_close_signal_drop_total 76
telemt_me_draining_writers_reap_progress_total 14240
telemt_me_writer_removed_unexpected_total 405
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1252
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13415
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 884
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13336
telemt_me_writer_teardown_success_total{mode="normal"} 14667
telemt_me_writer_teardown_noop_total 14240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28907
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.452583
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28907
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 76
telemt_me_refill_failed_total 115
telemt_me_writer_restored_same_endpoint_total 336
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 896293
telemt_user_connections_current{user="hello"} 2544
telemt_user_octets_from_client{user="hello"} 11478521683 (10.69 GB)
telemt_user_octets_to_client{user="hello"} 393903799631 (366.85 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 991
telemt_user_unique_ips_recent_window{user="hello"} 393
```
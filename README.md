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

# Server Metrics 2026-03-21 08:04:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 41330.0 (11h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1006042
telemt_connections_bad_total 52611
telemt_connections_current 1656
telemt_connections_me_current 1656
telemt_handshake_timeouts_total 46326
telemt_upstream_connect_attempt_total 16330
telemt_upstream_connect_success_total 16258
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 16307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10564
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 535
telemt_me_reconnect_success_total 264
telemt_me_reader_eof_total 281
telemt_me_idle_close_by_peer_total 281
telemt_me_route_drop_no_conn_total 315509
telemt_me_route_drop_channel_closed_total 124
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 726276
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 284
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 335
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
telemt_me_writers_active_current 46
telemt_desync_total 3162
telemt_desync_full_logged_total 1139
telemt_desync_suppressed_total 2023
telemt_desync_frames_bucket_total{bucket="1_2"} 660
telemt_desync_frames_bucket_total{bucket="3_10"} 1216
telemt_desync_frames_bucket_total{bucket="gt_10"} 1286
telemt_pool_swap_total 45
telemt_pool_force_close_total 1250
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 123
telemt_me_draining_writers_reap_progress_total 14738
telemt_me_writer_removed_unexpected_total 263
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1106
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13840
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13488
telemt_me_writer_teardown_success_total{mode="normal"} 14946
telemt_me_writer_teardown_noop_total 14739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29685
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 50.117452
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29685
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 123
telemt_me_refill_failed_total 15
telemt_me_writer_restored_same_endpoint_total 240
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 725513
telemt_user_connections_current{user="hello"} 1656
telemt_user_octets_from_client{user="hello"} 10051872616 (9.36 GB)
telemt_user_octets_to_client{user="hello"} 226165258532 (210.63 GB)
telemt_user_unique_ips_current{user="hello"} 580
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 41331.2 (11h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2475278
telemt_connections_bad_total 275491
telemt_connections_current 4815
telemt_connections_me_current 4815
telemt_handshake_timeouts_total 71842
telemt_upstream_connect_attempt_total 15267
telemt_upstream_connect_success_total 15195
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 15243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_reconnect_attempts_total 898
telemt_me_reconnect_success_total 342
telemt_me_reader_eof_total 336
telemt_me_idle_close_by_peer_total 335
telemt_me_route_drop_no_conn_total 586303
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1564557
telemt_me_endpoint_quarantine_total 274
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 325
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
telemt_me_writers_active_current 44
telemt_desync_total 6810
telemt_desync_full_logged_total 2355
telemt_desync_suppressed_total 4455
telemt_desync_frames_bucket_total{bucket="1_2"} 1397
telemt_desync_frames_bucket_total{bucket="3_10"} 2669
telemt_desync_frames_bucket_total{bucket="gt_10"} 2744
telemt_pool_swap_total 44
telemt_pool_force_close_total 1320
telemt_me_writer_close_signal_drop_total 142
telemt_me_draining_writers_reap_progress_total 13673
telemt_me_writer_removed_unexpected_total 314
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1239
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12743
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1247
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 73
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12353
telemt_me_writer_teardown_success_total{mode="normal"} 13982
telemt_me_writer_teardown_noop_total 13673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27655
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.868892
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27655
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 142
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 273
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 1561235
telemt_user_connections_current{user="hello"} 4815
telemt_user_octets_from_client{user="hello"} 21332137560 (19.87 GB)
telemt_user_octets_to_client{user="hello"} 622574017264 (579.82 GB)
telemt_user_unique_ips_current{user="hello"} 1701
telemt_user_unique_ips_recent_window{user="hello"} 658
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 41327.7 (11h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1768877
telemt_connections_bad_total 203541
telemt_connections_current 4516
telemt_connections_me_current 4516
telemt_handshake_timeouts_total 72341
telemt_upstream_connect_attempt_total 16346
telemt_upstream_connect_success_total 16336
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 16337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8853
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 496
telemt_me_reconnect_success_total 264
telemt_me_reader_eof_total 273
telemt_me_idle_close_by_peer_total 273
telemt_me_route_drop_no_conn_total 540254
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1370029
telemt_me_endpoint_quarantine_total 286
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 328
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
telemt_desync_total 5639
telemt_desync_full_logged_total 1983
telemt_desync_suppressed_total 3656
telemt_desync_frames_bucket_total{bucket="1_2"} 1265
telemt_desync_frames_bucket_total{bucket="3_10"} 2164
telemt_desync_frames_bucket_total{bucket="gt_10"} 2210
telemt_pool_swap_total 45
telemt_pool_force_close_total 1277
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 14889
telemt_me_writer_removed_unexpected_total 255
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1166
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13892
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1254
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13612
telemt_me_writer_teardown_success_total{mode="normal"} 15058
telemt_me_writer_teardown_noop_total 14893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29951
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.088365
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29951
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 227
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1367537
telemt_user_connections_current{user="hello"} 4516
telemt_user_octets_from_client{user="hello"} 18942403416 (17.64 GB)
telemt_user_octets_to_client{user="hello"} 574100526748 (534.67 GB)
telemt_user_unique_ips_current{user="hello"} 1619
telemt_user_unique_ips_recent_window{user="hello"} 639
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 41328.9 (11h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1504798
telemt_connections_bad_total 189215
telemt_connections_current 3391
telemt_connections_me_current 3391
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 65274
telemt_upstream_connect_attempt_total 21219
telemt_upstream_connect_success_total 20991
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 21111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9315
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 378
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 739
telemt_me_reconnect_success_total 319
telemt_me_reader_eof_total 303
telemt_me_idle_close_by_peer_total 303
telemt_me_route_drop_no_conn_total 423826
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1030377
telemt_me_endpoint_quarantine_total 295
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 329
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
telemt_desync_total 4722
telemt_desync_full_logged_total 1665
telemt_desync_suppressed_total 3057
telemt_desync_frames_bucket_total{bucket="1_2"} 1093
telemt_desync_frames_bucket_total{bucket="3_10"} 1946
telemt_desync_frames_bucket_total{bucket="gt_10"} 1683
telemt_pool_swap_total 45
telemt_pool_force_close_total 1166
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 14776
telemt_me_writer_removed_unexpected_total 295
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1123
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13962
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1135
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13610
telemt_me_writer_teardown_success_total{mode="normal"} 15085
telemt_me_writer_teardown_noop_total 14777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29862
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.629897
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29862
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 268
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1032940
telemt_user_connections_current{user="hello"} 3391
telemt_user_octets_from_client{user="hello"} 18151116313 (16.90 GB)
telemt_user_octets_to_client{user="hello"} 494614919131 (460.65 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1222
telemt_user_unique_ips_recent_window{user="hello"} 475
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 41293.0 (11h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1420565
telemt_connections_bad_total 160833
telemt_connections_current 3461
telemt_connections_me_current 3461
telemt_handshake_timeouts_total 48611
telemt_upstream_connect_attempt_total 17182
telemt_upstream_connect_success_total 17172
telemt_upstream_connect_attempts_per_request{bucket="1"} 17172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9521
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 342
telemt_me_reconnect_success_total 262
telemt_me_reader_eof_total 259
telemt_me_idle_close_by_peer_total 259
telemt_me_route_drop_no_conn_total 315823
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1023892
telemt_me_endpoint_quarantine_total 328
telemt_me_single_endpoint_shadow_rotate_total 323
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
telemt_me_writers_active_current 45
telemt_desync_total 4986
telemt_desync_full_logged_total 1768
telemt_desync_suppressed_total 3218
telemt_desync_frames_bucket_total{bucket="1_2"} 1275
telemt_desync_frames_bucket_total{bucket="3_10"} 1936
telemt_desync_frames_bucket_total{bucket="gt_10"} 1775
telemt_pool_swap_total 45
telemt_pool_force_close_total 1136
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 78
telemt_me_draining_writers_reap_progress_total 15555
telemt_me_writer_removed_unexpected_total 238
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1043
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14773
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1125
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14419
telemt_me_writer_teardown_success_total{mode="normal"} 15816
telemt_me_writer_teardown_noop_total 15558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31374
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.564847
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31374
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 78
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 232
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1022073
telemt_user_connections_current{user="hello"} 3461
telemt_user_octets_from_client{user="hello"} 26666359352 (24.83 GB)
telemt_user_octets_to_client{user="hello"} 530420984576 (493.99 GB)
telemt_user_unique_ips_current{user="hello"} 1280
telemt_user_unique_ips_recent_window{user="hello"} 490
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 41332.2 (11h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3678213
telemt_connections_bad_total 214764
telemt_connections_current 6032
telemt_connections_me_current 6032
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 185357
telemt_upstream_connect_attempt_total 42892
telemt_upstream_connect_success_total 40951
telemt_upstream_connect_fail_total 1360
telemt_upstream_connect_attempts_per_request{bucket="1"} 42311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10919
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1255
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1360
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 2085
telemt_me_reconnect_success_total 730
telemt_me_reader_eof_total 479
telemt_me_idle_close_by_peer_total 478
telemt_me_route_drop_no_conn_total 4806558
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3028918
telemt_me_endpoint_quarantine_total 323
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 84
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 84
telemt_me_single_endpoint_shadow_rotate_total 330
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_me_writers_active_current 89
telemt_desync_total 6847
telemt_desync_full_logged_total 2361
telemt_desync_suppressed_total 4486
telemt_desync_frames_bucket_total{bucket="1_2"} 1517
telemt_desync_frames_bucket_total{bucket="3_10"} 2924
telemt_desync_frames_bucket_total{bucket="gt_10"} 2406
telemt_pool_swap_total 43
telemt_pool_force_close_total 1220
telemt_me_writer_close_signal_drop_total 205
telemt_me_draining_writers_reap_progress_total 13972
telemt_me_writer_removed_unexpected_total 702
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1664
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12974
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1139
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12752
telemt_me_writer_teardown_success_total{mode="normal"} 14638
telemt_me_writer_teardown_noop_total 13977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28615
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.509605
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28615
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 205
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 482
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 3051345
telemt_user_connections_current{user="hello"} 6031
telemt_user_octets_from_client{user="hello"} 38826203058 (36.16 GB)
telemt_user_octets_to_client{user="hello"} 508355432750 (473.44 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1954
telemt_user_unique_ips_recent_window{user="hello"} 1184
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 41299.6 (11h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1507410
telemt_connections_bad_total 211113
telemt_connections_current 3431
telemt_connections_me_current 3431
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 29773
telemt_upstream_connect_attempt_total 18996
telemt_upstream_connect_success_total 18826
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 18979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9568
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_reconnect_attempts_total 1653
telemt_me_reconnect_success_total 526
telemt_me_reader_eof_total 539
telemt_me_idle_close_by_peer_total 539
telemt_me_route_drop_no_conn_total 387588
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1105970
telemt_me_endpoint_quarantine_total 257
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 329
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
telemt_me_writers_active_current 45
telemt_desync_total 4799
telemt_desync_full_logged_total 1793
telemt_desync_suppressed_total 3006
telemt_desync_frames_bucket_total{bucket="1_2"} 929
telemt_desync_frames_bucket_total{bucket="3_10"} 1935
telemt_desync_frames_bucket_total{bucket="gt_10"} 1935
telemt_pool_swap_total 43
telemt_pool_force_close_total 1090
telemt_me_writer_close_signal_drop_total 68
telemt_me_draining_writers_reap_progress_total 15671
telemt_me_writer_removed_unexpected_total 518
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1349
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14861
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1028
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 62
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14581
telemt_me_writer_teardown_success_total{mode="normal"} 16210
telemt_me_writer_teardown_noop_total 15671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31881
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.135762
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31881
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 68
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 444
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 1103212
telemt_user_connections_current{user="hello"} 3431
telemt_user_octets_from_client{user="hello"} 18573551808 (17.30 GB)
telemt_user_octets_to_client{user="hello"} 526945457342 (490.76 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1334
telemt_user_unique_ips_recent_window{user="hello"} 529
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 41294.3 (11h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1967220
telemt_connections_bad_total 127525
telemt_connections_current 3192
telemt_connections_me_current 3192
telemt_handshake_timeouts_total 732158
telemt_upstream_connect_attempt_total 17786
telemt_upstream_connect_success_total 17752
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 17755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 274
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 417
telemt_me_reconnect_success_total 270
telemt_me_reader_eof_total 271
telemt_me_idle_close_by_peer_total 271
telemt_me_route_drop_no_conn_total 348711
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 977123
telemt_me_endpoint_quarantine_total 341
telemt_me_single_endpoint_shadow_rotate_total 332
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
telemt_desync_total 4798
telemt_desync_full_logged_total 1705
telemt_desync_suppressed_total 3093
telemt_desync_frames_bucket_total{bucket="1_2"} 832
telemt_desync_frames_bucket_total{bucket="3_10"} 1957
telemt_desync_frames_bucket_total{bucket="gt_10"} 2009
telemt_pool_swap_total 45
telemt_pool_force_close_total 1068
telemt_me_writer_close_signal_drop_total 75
telemt_me_draining_writers_reap_progress_total 15927
telemt_me_writer_removed_unexpected_total 261
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 973
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15234
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1055
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 13
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14859
telemt_me_writer_teardown_success_total{mode="normal"} 16207
telemt_me_writer_teardown_noop_total 15927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32134
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.622514
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32134
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 75
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 241
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 973804
telemt_user_connections_current{user="hello"} 3192
telemt_user_octets_from_client{user="hello"} 16727741532 (15.58 GB)
telemt_user_octets_to_client{user="hello"} 497129571700 (462.99 GB)
telemt_user_unique_ips_current{user="hello"} 1256
telemt_user_unique_ips_recent_window{user="hello"} 512
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 39285.9 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 409948
telemt_connections_bad_total 13349
telemt_connections_current 666
telemt_connections_me_current 666
telemt_handshake_timeouts_total 132792
telemt_upstream_connect_attempt_total 19609
telemt_upstream_connect_success_total 19607
telemt_upstream_connect_attempts_per_request{bucket="1"} 19607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11349
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 736
telemt_me_reconnect_success_total 305
telemt_me_reader_eof_total 308
telemt_me_idle_close_by_peer_total 308
telemt_me_route_drop_no_conn_total 91510
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 236248
telemt_me_endpoint_quarantine_total 382
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 340
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
telemt_desync_total 1475
telemt_desync_full_logged_total 637
telemt_desync_suppressed_total 838
telemt_desync_frames_bucket_total{bucket="1_2"} 292
telemt_desync_frames_bucket_total{bucket="3_10"} 607
telemt_desync_frames_bucket_total{bucket="gt_10"} 576
telemt_pool_swap_total 43
telemt_pool_force_close_total 906
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 53
telemt_me_draining_writers_reap_progress_total 17508
telemt_me_writer_removed_unexpected_total 290
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1234
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16567
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 904
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16602
telemt_me_writer_teardown_success_total{mode="normal"} 17801
telemt_me_writer_teardown_noop_total 17508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35309
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.376161
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35309
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 53
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 256
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 236465
telemt_user_connections_current{user="hello"} 666
telemt_user_octets_from_client{user="hello"} 3103335871 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 99171022201 (92.36 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 266
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 41304.1 (11h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1535226
telemt_connections_bad_total 121139
telemt_connections_current 4106
telemt_connections_me_current 4106
telemt_handshake_timeouts_total 39613
telemt_upstream_connect_attempt_total 18345
telemt_upstream_connect_success_total 18262
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 18316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9069
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_reconnect_attempts_total 619
telemt_me_reconnect_success_total 378
telemt_me_reader_eof_total 352
telemt_me_idle_close_by_peer_total 352
telemt_me_route_drop_no_conn_total 354538
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1207727
telemt_me_endpoint_quarantine_total 331
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 331
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
telemt_desync_total 4846
telemt_desync_full_logged_total 1621
telemt_desync_suppressed_total 3225
telemt_desync_frames_bucket_total{bucket="1_2"} 1211
telemt_desync_frames_bucket_total{bucket="3_10"} 1823
telemt_desync_frames_bucket_total{bucket="gt_10"} 1812
telemt_pool_swap_total 45
telemt_pool_force_close_total 1076
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 86
telemt_me_draining_writers_reap_progress_total 16541
telemt_me_writer_removed_unexpected_total 352
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1181
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15720
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1063
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 13
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15465
telemt_me_writer_teardown_success_total{mode="normal"} 16901
telemt_me_writer_teardown_noop_total 16541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33442
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.713874
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33442
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 86
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 341
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1202886
telemt_user_connections_current{user="hello"} 4106
telemt_user_octets_from_client{user="hello"} 22818521648 (21.25 GB)
telemt_user_octets_to_client{user="hello"} 556724937392 (518.49 GB)
telemt_user_unique_ips_current{user="hello"} 1435
telemt_user_unique_ips_recent_window{user="hello"} 563
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 41300.8 (11h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1474444
telemt_connections_bad_total 111355
telemt_connections_current 3308
telemt_connections_me_current 3308
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 38099
telemt_upstream_connect_attempt_total 26757
telemt_upstream_connect_success_total 26565
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 26717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9468
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 2666
telemt_me_reconnect_success_total 497
telemt_me_reader_eof_total 430
telemt_me_idle_close_by_peer_total 430
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 359462
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1172939
telemt_me_endpoint_quarantine_total 390
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 327
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
telemt_me_writers_active_current 52
telemt_desync_total 4691
telemt_desync_full_logged_total 1497
telemt_desync_suppressed_total 3194
telemt_desync_frames_bucket_total{bucket="1_2"} 1316
telemt_desync_frames_bucket_total{bucket="3_10"} 1709
telemt_desync_frames_bucket_total{bucket="gt_10"} 1666
telemt_pool_swap_total 45
telemt_pool_force_close_total 1046
telemt_me_writer_close_signal_drop_total 84
telemt_me_draining_writers_reap_progress_total 15622
telemt_me_writer_removed_unexpected_total 441
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1376
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14710
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1019
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14576
telemt_me_writer_teardown_success_total{mode="normal"} 16086
telemt_me_writer_teardown_noop_total 15622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31708
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.046947
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31708
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 84
telemt_me_refill_failed_total 123
telemt_me_writer_restored_same_endpoint_total 373
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 41
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 1177355
telemt_user_connections_current{user="hello"} 3308
telemt_user_octets_from_client{user="hello"} 17332989647 (16.14 GB)
telemt_user_octets_to_client{user="hello"} 521699543755 (485.87 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1261
telemt_user_unique_ips_recent_window{user="hello"} 527
```
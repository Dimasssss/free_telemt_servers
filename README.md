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

# Server Metrics 2026-03-21 07:34:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 39501.3 (10h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 920271
telemt_connections_bad_total 48377
telemt_connections_current 1594
telemt_connections_me_current 1594
telemt_handshake_timeouts_total 42823
telemt_upstream_connect_attempt_total 15724
telemt_upstream_connect_success_total 15653
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 15701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10182
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 506
telemt_me_reconnect_success_total 250
telemt_me_reader_eof_total 265
telemt_me_idle_close_by_peer_total 265
telemt_me_route_drop_no_conn_total 293708
telemt_me_route_drop_channel_closed_total 109
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 670764
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 277
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 322
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 2968
telemt_desync_full_logged_total 1063
telemt_desync_suppressed_total 1905
telemt_desync_frames_bucket_total{bucket="1_2"} 612
telemt_desync_frames_bucket_total{bucket="3_10"} 1164
telemt_desync_frames_bucket_total{bucket="gt_10"} 1192
telemt_pool_swap_total 43
telemt_pool_force_close_total 1192
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 114
telemt_me_draining_writers_reap_progress_total 14185
telemt_me_writer_removed_unexpected_total 249
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1051
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13338
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1185
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12993
telemt_me_writer_teardown_success_total{mode="normal"} 14389
telemt_me_writer_teardown_noop_total 14186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28575
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.017373
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28575
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 114
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 227
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 669996
telemt_user_connections_current{user="hello"} 1594
telemt_user_octets_from_client{user="hello"} 8088492132 (7.53 GB)
telemt_user_octets_to_client{user="hello"} 210679538832 (196.21 GB)
telemt_user_unique_ips_current{user="hello"} 546
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 39502.6 (10h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2266857
telemt_connections_bad_total 253666
telemt_connections_current 4332
telemt_connections_me_current 4332
telemt_handshake_timeouts_total 68281
telemt_upstream_connect_attempt_total 14692
telemt_upstream_connect_success_total 14625
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 14671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_reconnect_attempts_total 863
telemt_me_reconnect_success_total 294
telemt_me_reader_eof_total 302
telemt_me_idle_close_by_peer_total 301
telemt_me_route_drop_no_conn_total 484127
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1402225
telemt_me_endpoint_quarantine_total 253
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 313
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
telemt_me_writers_active_current 43
telemt_desync_total 6084
telemt_desync_full_logged_total 2117
telemt_desync_suppressed_total 3967
telemt_desync_frames_bucket_total{bucket="1_2"} 1251
telemt_desync_frames_bucket_total{bucket="3_10"} 2381
telemt_desync_frames_bucket_total{bucket="gt_10"} 2452
telemt_pool_swap_total 42
telemt_pool_force_close_total 1250
telemt_me_writer_close_signal_drop_total 127
telemt_me_draining_writers_reap_progress_total 13173
telemt_me_writer_removed_unexpected_total 283
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1166
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12282
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1192
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 58
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11923
telemt_me_writer_teardown_success_total{mode="normal"} 13448
telemt_me_writer_teardown_noop_total 13173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26621
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.071677
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26621
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 127
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 245
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1399108
telemt_user_connections_current{user="hello"} 4332
telemt_user_octets_from_client{user="hello"} 19193576840 (17.88 GB)
telemt_user_octets_to_client{user="hello"} 571968334336 (532.69 GB)
telemt_user_unique_ips_current{user="hello"} 1575
telemt_user_unique_ips_recent_window{user="hello"} 580
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 39499.0 (10h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1536690
telemt_connections_bad_total 165907
telemt_connections_current 3467
telemt_connections_me_current 3467
telemt_handshake_timeouts_total 68334
telemt_upstream_connect_attempt_total 15801
telemt_upstream_connect_success_total 15791
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 489
telemt_me_reconnect_success_total 258
telemt_me_reader_eof_total 267
telemt_me_idle_close_by_peer_total 267
telemt_me_route_drop_no_conn_total 406413
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1203997
telemt_me_endpoint_quarantine_total 279
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 313
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
telemt_me_writers_active_current 43
telemt_desync_total 4918
telemt_desync_full_logged_total 1755
telemt_desync_suppressed_total 3163
telemt_desync_frames_bucket_total{bucket="1_2"} 1087
telemt_desync_frames_bucket_total{bucket="3_10"} 1878
telemt_desync_frames_bucket_total{bucket="gt_10"} 1953
telemt_pool_swap_total 43
telemt_pool_force_close_total 1214
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 139
telemt_me_draining_writers_reap_progress_total 14393
telemt_me_writer_removed_unexpected_total 249
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1117
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13439
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1196
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13179
telemt_me_writer_teardown_success_total{mode="normal"} 14556
telemt_me_writer_teardown_noop_total 14396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28952
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.061316
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28952
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 139
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 221
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1201606
telemt_user_connections_current{user="hello"} 3467
telemt_user_octets_from_client{user="hello"} 16398938992 (15.27 GB)
telemt_user_octets_to_client{user="hello"} 528039836176 (491.78 GB)
telemt_user_unique_ips_current{user="hello"} 1336
telemt_user_unique_ips_recent_window{user="hello"} 483
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 39500.3 (10h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1331732
telemt_connections_bad_total 160697
telemt_connections_current 2782
telemt_connections_me_current 2782
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 61069
telemt_upstream_connect_attempt_total 20656
telemt_upstream_connect_success_total 20429
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 20548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 378
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 734
telemt_me_reconnect_success_total 315
telemt_me_reader_eof_total 299
telemt_me_idle_close_by_peer_total 299
telemt_me_route_drop_no_conn_total 379784
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 924257
telemt_me_endpoint_quarantine_total 285
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 317
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
telemt_desync_total 4240
telemt_desync_full_logged_total 1522
telemt_desync_suppressed_total 2718
telemt_desync_frames_bucket_total{bucket="1_2"} 972
telemt_desync_frames_bucket_total{bucket="3_10"} 1787
telemt_desync_frames_bucket_total{bucket="gt_10"} 1481
telemt_pool_swap_total 43
telemt_pool_force_close_total 1102
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 62
telemt_me_draining_writers_reap_progress_total 14264
telemt_me_writer_removed_unexpected_total 291
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1085
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13484
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1076
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 26
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13162
telemt_me_writer_teardown_success_total{mode="normal"} 14569
telemt_me_writer_teardown_noop_total 14265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28834
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.676683
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28834
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 62
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 264
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 927123
telemt_user_connections_current{user="hello"} 2782
telemt_user_octets_from_client{user="hello"} 16180268281 (15.07 GB)
telemt_user_octets_to_client{user="hello"} 433137359903 (403.39 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1030
telemt_user_unique_ips_recent_window{user="hello"} 373
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 39463.9 (10h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1284476
telemt_connections_bad_total 149993
telemt_connections_current 2564
telemt_connections_me_current 2564
telemt_handshake_timeouts_total 45315
telemt_upstream_connect_attempt_total 16592
telemt_upstream_connect_success_total 16583
telemt_upstream_connect_attempts_per_request{bucket="1"} 16583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9191
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 326
telemt_me_reconnect_success_total 248
telemt_me_reader_eof_total 245
telemt_me_idle_close_by_peer_total 245
telemt_me_route_drop_no_conn_total 275496
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 915607
telemt_me_endpoint_quarantine_total 317
telemt_me_single_endpoint_shadow_rotate_total 311
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
telemt_desync_total 4405
telemt_desync_full_logged_total 1594
telemt_desync_suppressed_total 2811
telemt_desync_frames_bucket_total{bucket="1_2"} 1093
telemt_desync_frames_bucket_total{bucket="3_10"} 1710
telemt_desync_frames_bucket_total{bucket="gt_10"} 1602
telemt_pool_swap_total 43
telemt_pool_force_close_total 1077
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 74
telemt_me_draining_writers_reap_progress_total 15033
telemt_me_writer_removed_unexpected_total 224
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1003
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14276
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1067
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13956
telemt_me_writer_teardown_success_total{mode="normal"} 15279
telemt_me_writer_teardown_noop_total 15036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30315
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.126434
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30315
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 74
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 218
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 913977
telemt_user_connections_current{user="hello"} 2564
telemt_user_octets_from_client{user="hello"} 24537806084 (22.85 GB)
telemt_user_octets_to_client{user="hello"} 475888190344 (443.21 GB)
telemt_user_unique_ips_current{user="hello"} 1041
telemt_user_unique_ips_recent_window{user="hello"} 389
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 39503.5 (10h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3037148
telemt_connections_bad_total 191051
telemt_connections_current 4856
telemt_connections_me_current 4856
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 172662
telemt_upstream_connect_attempt_total 42068
telemt_upstream_connect_success_total 40162
telemt_upstream_connect_fail_total 1352
telemt_upstream_connect_attempts_per_request{bucket="1"} 41514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10479
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1352
telemt_me_reconnect_attempts_total 1974
telemt_me_reconnect_success_total 670
telemt_me_reader_eof_total 421
telemt_me_idle_close_by_peer_total 420
telemt_me_route_drop_no_conn_total 3390480
telemt_me_route_drop_channel_closed_total 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2460725
telemt_me_endpoint_quarantine_total 316
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 84
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 84
telemt_me_single_endpoint_shadow_rotate_total 317
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
telemt_me_writers_active_current 45
telemt_desync_total 5844
telemt_desync_full_logged_total 2085
telemt_desync_suppressed_total 3759
telemt_desync_frames_bucket_total{bucket="1_2"} 1341
telemt_desync_frames_bucket_total{bucket="3_10"} 2468
telemt_desync_frames_bucket_total{bucket="gt_10"} 2035
telemt_pool_swap_total 42
telemt_pool_force_close_total 1184
telemt_me_writer_close_signal_drop_total 189
telemt_me_draining_writers_reap_progress_total 13339
telemt_me_writer_removed_unexpected_total 637
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1557
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12388
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1104
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 80
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12155
telemt_me_writer_teardown_success_total{mode="normal"} 13945
telemt_me_writer_teardown_noop_total 13344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27289
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 24.480643
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27289
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 189
telemt_me_refill_failed_total 48
telemt_me_writer_restored_same_endpoint_total 424
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 2483216
telemt_user_connections_current{user="hello"} 4856
telemt_user_octets_from_client{user="hello"} 36094380874 (33.62 GB)
telemt_user_octets_to_client{user="hello"} 486455615414 (453.05 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1677
telemt_user_unique_ips_recent_window{user="hello"} 903
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 39470.8 (10h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1368102
telemt_connections_bad_total 196990
telemt_connections_current 2842
telemt_connections_me_current 2842
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 28124
telemt_upstream_connect_attempt_total 18391
telemt_upstream_connect_success_total 18228
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 18375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_reconnect_attempts_total 1636
telemt_me_reconnect_success_total 509
telemt_me_reader_eof_total 524
telemt_me_idle_close_by_peer_total 524
telemt_me_route_drop_no_conn_total 340761
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 991720
telemt_me_endpoint_quarantine_total 245
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 315
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
telemt_me_writers_active_current 46
telemt_desync_total 4170
telemt_desync_full_logged_total 1583
telemt_desync_suppressed_total 2587
telemt_desync_frames_bucket_total{bucket="1_2"} 797
telemt_desync_frames_bucket_total{bucket="3_10"} 1685
telemt_desync_frames_bucket_total{bucket="gt_10"} 1688
telemt_pool_swap_total 41
telemt_pool_force_close_total 1029
telemt_me_writer_close_signal_drop_total 63
telemt_me_draining_writers_reap_progress_total 15142
telemt_me_writer_removed_unexpected_total 503
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1289
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14377
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 971
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 58
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14113
telemt_me_writer_teardown_success_total{mode="normal"} 15666
telemt_me_writer_teardown_noop_total 15142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30808
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.097118
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30808
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 63
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 430
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 989228
telemt_user_connections_current{user="hello"} 2842
telemt_user_octets_from_client{user="hello"} 16556836340 (15.42 GB)
telemt_user_octets_to_client{user="hello"} 480654975818 (447.64 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1134
telemt_user_unique_ips_recent_window{user="hello"} 416
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 39465.3 (10h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1760325
telemt_connections_bad_total 116727
telemt_connections_current 2536
telemt_connections_me_current 2536
telemt_handshake_timeouts_total 641332
telemt_upstream_connect_attempt_total 17201
telemt_upstream_connect_success_total 17173
telemt_upstream_connect_attempts_per_request{bucket="1"} 17173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9177
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 267
telemt_me_reconnect_attempts_total 364
telemt_me_reconnect_success_total 255
telemt_me_reader_eof_total 264
telemt_me_idle_close_by_peer_total 264
telemt_me_route_drop_no_conn_total 307198
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 879535
telemt_me_endpoint_quarantine_total 332
telemt_me_single_endpoint_shadow_rotate_total 319
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
telemt_desync_total 4194
telemt_desync_full_logged_total 1488
telemt_desync_suppressed_total 2706
telemt_desync_frames_bucket_total{bucket="1_2"} 725
telemt_desync_frames_bucket_total{bucket="3_10"} 1717
telemt_desync_frames_bucket_total{bucket="gt_10"} 1752
telemt_pool_swap_total 43
telemt_pool_force_close_total 1005
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 15410
telemt_me_writer_removed_unexpected_total 247
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 925
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14750
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 997
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14405
telemt_me_writer_teardown_success_total{mode="normal"} 15675
telemt_me_writer_teardown_noop_total 15410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31085
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.551546
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31085
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 229
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 876459
telemt_user_connections_current{user="hello"} 2536
telemt_user_octets_from_client{user="hello"} 14851863640 (13.83 GB)
telemt_user_octets_to_client{user="hello"} 449570175652 (418.69 GB)
telemt_user_unique_ips_current{user="hello"} 1060
telemt_user_unique_ips_recent_window{user="hello"} 406
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 37456.8 (10h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354279
telemt_connections_bad_total 12169
telemt_connections_current 620
telemt_connections_me_current 620
telemt_handshake_timeouts_total 103322
telemt_upstream_connect_attempt_total 18846
telemt_upstream_connect_success_total 18845
telemt_upstream_connect_attempts_per_request{bucket="1"} 18845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10870
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 710
telemt_me_reconnect_success_total 294
telemt_me_reader_eof_total 298
telemt_me_idle_close_by_peer_total 298
telemt_me_route_drop_no_conn_total 81865
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214183
telemt_me_endpoint_quarantine_total 372
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 325
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
telemt_me_writers_active_current 44
telemt_desync_total 1342
telemt_desync_full_logged_total 600
telemt_desync_suppressed_total 742
telemt_desync_frames_bucket_total{bucket="1_2"} 263
telemt_desync_frames_bucket_total{bucket="3_10"} 550
telemt_desync_frames_bucket_total{bucket="gt_10"} 529
telemt_pool_swap_total 41
telemt_pool_force_close_total 850
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 50
telemt_me_draining_writers_reap_progress_total 16804
telemt_me_writer_removed_unexpected_total 280
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1177
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15910
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 850
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15954
telemt_me_writer_teardown_success_total{mode="normal"} 17087
telemt_me_writer_teardown_noop_total 16804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33891
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.283395
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33891
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 50
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 247
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 214383
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 2726011103 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 91898304101 (85.59 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 39475.2 (10h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1390527
telemt_connections_bad_total 110409
telemt_connections_current 3159
telemt_connections_me_current 3159
telemt_handshake_timeouts_total 36076
telemt_upstream_connect_attempt_total 17670
telemt_upstream_connect_success_total 17590
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 17641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8750
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 597
telemt_me_reconnect_success_total 353
telemt_me_reader_eof_total 334
telemt_me_idle_close_by_peer_total 334
telemt_me_route_drop_no_conn_total 311823
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1089458
telemt_me_endpoint_quarantine_total 323
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 316
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
telemt_me_writers_active_current 47
telemt_desync_total 4362
telemt_desync_full_logged_total 1458
telemt_desync_suppressed_total 2904
telemt_desync_frames_bucket_total{bucket="1_2"} 1115
telemt_desync_frames_bucket_total{bucket="3_10"} 1638
telemt_desync_frames_bucket_total{bucket="gt_10"} 1609
telemt_pool_swap_total 43
telemt_pool_force_close_total 1018
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 81
telemt_me_draining_writers_reap_progress_total 15955
telemt_me_writer_removed_unexpected_total 335
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1127
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15170
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1013
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14937
telemt_me_writer_teardown_success_total{mode="normal"} 16297
telemt_me_writer_teardown_noop_total 15955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32252
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.641044
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32252
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 81
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 320
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 1084877
telemt_user_connections_current{user="hello"} 3159
telemt_user_octets_from_client{user="hello"} 17719390408 (16.50 GB)
telemt_user_octets_to_client{user="hello"} 497662904112 (463.48 GB)
telemt_user_unique_ips_current{user="hello"} 1232
telemt_user_unique_ips_recent_window{user="hello"} 449
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 39472.0 (10h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1326015
telemt_connections_bad_total 95664
telemt_connections_current 3210
telemt_connections_me_current 3210
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 34194
telemt_upstream_connect_attempt_total 26156
telemt_upstream_connect_success_total 25968
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 26116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_reconnect_attempts_total 2590
telemt_me_reconnect_success_total 468
telemt_me_reader_eof_total 411
telemt_me_idle_close_by_peer_total 411
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 316631
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1057711
telemt_me_endpoint_quarantine_total 384
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 312
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
telemt_me_writers_active_current 42
telemt_desync_total 4249
telemt_desync_full_logged_total 1334
telemt_desync_suppressed_total 2915
telemt_desync_frames_bucket_total{bucket="1_2"} 1224
telemt_desync_frames_bucket_total{bucket="3_10"} 1554
telemt_desync_frames_bucket_total{bucket="gt_10"} 1471
telemt_pool_swap_total 43
telemt_pool_force_close_total 985
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 15108
telemt_me_writer_removed_unexpected_total 423
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1325
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14228
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 965
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14123
telemt_me_writer_teardown_success_total{mode="normal"} 15553
telemt_me_writer_teardown_noop_total 15108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30661
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.585238
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30661
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 348
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 1062349
telemt_user_connections_current{user="hello"} 3210
telemt_user_octets_from_client{user="hello"} 13874934967 (12.92 GB)
telemt_user_octets_to_client{user="hello"} 471781423739 (439.38 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1192
telemt_user_unique_ips_recent_window{user="hello"} 462
```
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

# Server Metrics 2026-03-21 08:19:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 42244.6 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1079744
telemt_connections_bad_total 54541
telemt_connections_current 1614
telemt_connections_me_current 1614
telemt_handshake_timeouts_total 47538
telemt_upstream_connect_attempt_total 16807
telemt_upstream_connect_success_total 16733
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 16783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10742
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 662
telemt_me_reconnect_success_total 298
telemt_me_reader_eof_total 302
telemt_me_idle_close_by_peer_total 302
telemt_me_route_drop_no_conn_total 447765
telemt_me_route_drop_channel_closed_total 149
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 792256
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 297
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 343
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
telemt_me_writers_active_current 45
telemt_desync_total 3317
telemt_desync_full_logged_total 1188
telemt_desync_suppressed_total 2129
telemt_desync_frames_bucket_total{bucket="1_2"} 696
telemt_desync_frames_bucket_total{bucket="3_10"} 1275
telemt_desync_frames_bucket_total{bucket="gt_10"} 1346
telemt_pool_swap_total 46
telemt_pool_force_close_total 1254
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 158
telemt_me_draining_writers_reap_progress_total 15017
telemt_me_writer_removed_unexpected_total 284
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1161
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14070
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13763
telemt_me_writer_teardown_success_total{mode="normal"} 15231
telemt_me_writer_teardown_noop_total 15018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30249
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 59.616418
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30249
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 158
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 262
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 791626
telemt_user_connections_current{user="hello"} 1614
telemt_user_octets_from_client{user="hello"} 10985049971 (10.23 GB)
telemt_user_octets_to_client{user="hello"} 230993231687 (215.13 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 552
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 42245.8 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2612727
telemt_connections_bad_total 295339
telemt_connections_current 4106
telemt_connections_me_current 4106
telemt_handshake_timeouts_total 74288
telemt_upstream_connect_attempt_total 15505
telemt_upstream_connect_success_total 15432
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 15481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6400
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8982
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 936
telemt_me_reconnect_success_total 346
telemt_me_reader_eof_total 341
telemt_me_idle_close_by_peer_total 340
telemt_me_route_drop_no_conn_total 692518
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1664379
telemt_me_endpoint_quarantine_total 277
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 330
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
telemt_desync_total 7342
telemt_desync_full_logged_total 2508
telemt_desync_suppressed_total 4834
telemt_desync_frames_bucket_total{bucket="1_2"} 1482
telemt_desync_frames_bucket_total{bucket="3_10"} 2886
telemt_desync_frames_bucket_total{bucket="gt_10"} 2974
telemt_pool_swap_total 45
telemt_pool_force_close_total 1351
telemt_me_writer_close_signal_drop_total 147
telemt_me_draining_writers_reap_progress_total 13892
telemt_me_writer_removed_unexpected_total 319
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1261
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12945
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1276
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 75
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12541
telemt_me_writer_teardown_success_total{mode="normal"} 14206
telemt_me_writer_teardown_noop_total 13892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28098
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.688407
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28098
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 147
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 276
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1660972
telemt_user_connections_current{user="hello"} 4106
telemt_user_octets_from_client{user="hello"} 23631867904 (22.01 GB)
telemt_user_octets_to_client{user="hello"} 646194748532 (601.82 GB)
telemt_user_unique_ips_current{user="hello"} 1533
telemt_user_unique_ips_recent_window{user="hello"} 595
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 42242.2 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1868483
telemt_connections_bad_total 221810
telemt_connections_current 4325
telemt_connections_me_current 4325
telemt_handshake_timeouts_total 73349
telemt_upstream_connect_attempt_total 16831
telemt_upstream_connect_success_total 16820
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 16821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9124
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 547
telemt_me_reconnect_success_total 313
telemt_me_reader_eof_total 322
telemt_me_idle_close_by_peer_total 322
telemt_me_route_drop_no_conn_total 592936
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1444323
telemt_me_endpoint_quarantine_total 287
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 333
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
telemt_me_writers_active_current 87
telemt_desync_total 5998
telemt_desync_full_logged_total 2116
telemt_desync_suppressed_total 3882
telemt_desync_frames_bucket_total{bucket="1_2"} 1341
telemt_desync_frames_bucket_total{bucket="3_10"} 2308
telemt_desync_frames_bucket_total{bucket="gt_10"} 2349
telemt_pool_swap_total 45
telemt_pool_force_close_total 1277
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 152
telemt_me_draining_writers_reap_progress_total 15254
telemt_me_writer_removed_unexpected_total 304
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1228
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14244
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1254
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13977
telemt_me_writer_teardown_success_total{mode="normal"} 15472
telemt_me_writer_teardown_noop_total 15258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30730
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.205965
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30730
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 152
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 276
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1441833
telemt_user_connections_current{user="hello"} 4325
telemt_user_octets_from_client{user="hello"} 20120253228 (18.74 GB)
telemt_user_octets_to_client{user="hello"} 600342998856 (559.11 GB)
telemt_user_unique_ips_current{user="hello"} 1719
telemt_user_unique_ips_recent_window{user="hello"} 552
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 42243.4 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1591578
telemt_connections_bad_total 198207
telemt_connections_current 3273
telemt_connections_me_current 3273
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 66579
telemt_upstream_connect_attempt_total 21529
telemt_upstream_connect_success_total 21300
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 21421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9468
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 379
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 783
telemt_me_reconnect_success_total 343
telemt_me_reader_eof_total 319
telemt_me_idle_close_by_peer_total 319
telemt_me_route_drop_no_conn_total 447462
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1087238
telemt_me_endpoint_quarantine_total 303
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 336
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
telemt_me_writers_active_current 46
telemt_desync_total 5075
telemt_desync_full_logged_total 1768
telemt_desync_suppressed_total 3307
telemt_desync_frames_bucket_total{bucket="1_2"} 1212
telemt_desync_frames_bucket_total{bucket="3_10"} 2077
telemt_desync_frames_bucket_total{bucket="gt_10"} 1786
telemt_pool_swap_total 46
telemt_pool_force_close_total 1203
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 70
telemt_me_draining_writers_reap_progress_total 15045
telemt_me_writer_removed_unexpected_total 311
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1154
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14216
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1165
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 38
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13842
telemt_me_writer_teardown_success_total{mode="normal"} 15370
telemt_me_writer_teardown_noop_total 15046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30416
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.254941
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30416
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 70
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 287
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1089709
telemt_user_connections_current{user="hello"} 3273
telemt_user_octets_from_client{user="hello"} 19491698205 (18.15 GB)
telemt_user_octets_to_client{user="hello"} 524978131387 (488.92 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1151
telemt_user_unique_ips_recent_window{user="hello"} 457
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 42207.3 (11h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1509368
telemt_connections_bad_total 187234
telemt_connections_current 3461
telemt_connections_me_current 3461
telemt_handshake_timeouts_total 50189
telemt_upstream_connect_attempt_total 17653
telemt_upstream_connect_success_total 17641
telemt_upstream_connect_attempts_per_request{bucket="1"} 17641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9767
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 405
telemt_me_reconnect_success_total 307
telemt_me_reader_eof_total 307
telemt_me_idle_close_by_peer_total 307
telemt_me_route_drop_no_conn_total 339256
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1080267
telemt_me_endpoint_quarantine_total 330
telemt_me_single_endpoint_shadow_rotate_total 329
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
telemt_me_writers_active_current 87
telemt_desync_total 5262
telemt_desync_full_logged_total 1850
telemt_desync_suppressed_total 3412
telemt_desync_frames_bucket_total{bucket="1_2"} 1361
telemt_desync_frames_bucket_total{bucket="3_10"} 2039
telemt_desync_frames_bucket_total{bucket="gt_10"} 1862
telemt_pool_swap_total 45
telemt_pool_force_close_total 1136
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 15911
telemt_me_writer_removed_unexpected_total 285
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1103
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15117
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1125
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14775
telemt_me_writer_teardown_success_total{mode="normal"} 16220
telemt_me_writer_teardown_noop_total 15914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32134
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.582121
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32134
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 277
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1078436
telemt_user_connections_current{user="hello"} 3461
telemt_user_octets_from_client{user="hello"} 27869784344 (25.96 GB)
telemt_user_octets_to_client{user="hello"} 559237815164 (520.83 GB)
telemt_user_unique_ips_current{user="hello"} 1354
telemt_user_unique_ips_recent_window{user="hello"} 399
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 42247.6 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4053559
telemt_connections_bad_total 228542
telemt_connections_current 6222
telemt_connections_me_current 6222
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 192938
telemt_upstream_connect_attempt_total 43197
telemt_upstream_connect_success_total 41237
telemt_upstream_connect_fail_total 1363
telemt_upstream_connect_attempts_per_request{bucket="1"} 42600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11084
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1363
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 2109
telemt_me_reconnect_success_total 736
telemt_me_reader_eof_total 486
telemt_me_idle_close_by_peer_total 485
telemt_me_route_drop_no_conn_total 5855463
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3363609
telemt_me_endpoint_quarantine_total 331
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 84
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 84
telemt_me_single_endpoint_shadow_rotate_total 335
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
telemt_me_writers_active_current 42
telemt_desync_total 7313
telemt_desync_full_logged_total 2495
telemt_desync_suppressed_total 4818
telemt_desync_frames_bucket_total{bucket="1_2"} 1632
telemt_desync_frames_bucket_total{bucket="3_10"} 3147
telemt_desync_frames_bucket_total{bucket="gt_10"} 2534
telemt_pool_swap_total 44
telemt_pool_force_close_total 1282
telemt_me_writer_close_signal_drop_total 220
telemt_me_draining_writers_reap_progress_total 14284
telemt_me_writer_removed_unexpected_total 710
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1702
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13250
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1164
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 118
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13002
telemt_me_writer_teardown_success_total{mode="normal"} 14952
telemt_me_writer_teardown_noop_total 14290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29242
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 28.380121
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29242
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 220
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 486
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 3385852
telemt_user_connections_current{user="hello"} 6222
telemt_user_octets_from_client{user="hello"} 40114469290 (37.36 GB)
telemt_user_octets_to_client{user="hello"} 516909555570 (481.41 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1750
telemt_user_unique_ips_recent_window{user="hello"} 1187
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 42214.1 (11h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1581500
telemt_connections_bad_total 218491
telemt_connections_current 3266
telemt_connections_me_current 3266
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 30881
telemt_upstream_connect_attempt_total 19232
telemt_upstream_connect_success_total 19060
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 19215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_reconnect_attempts_total 1688
telemt_me_reconnect_success_total 529
telemt_me_reader_eof_total 544
telemt_me_idle_close_by_peer_total 544
telemt_me_route_drop_no_conn_total 413780
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1167040
telemt_me_endpoint_quarantine_total 263
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 334
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
telemt_me_writers_active_current 42
telemt_desync_total 5127
telemt_desync_full_logged_total 1904
telemt_desync_suppressed_total 3223
telemt_desync_frames_bucket_total{bucket="1_2"} 984
telemt_desync_frames_bucket_total{bucket="3_10"} 2085
telemt_desync_frames_bucket_total{bucket="gt_10"} 2058
telemt_pool_swap_total 44
telemt_pool_force_close_total 1118
telemt_me_writer_close_signal_drop_total 72
telemt_me_draining_writers_reap_progress_total 15893
telemt_me_writer_removed_unexpected_total 523
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1372
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15065
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1056
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 62
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14775
telemt_me_writer_teardown_success_total{mode="normal"} 16437
telemt_me_writer_teardown_noop_total 15893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32330
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.202510
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32330
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 72
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 447
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1164210
telemt_user_connections_current{user="hello"} 3266
telemt_user_octets_from_client{user="hello"} 19965893448 (18.59 GB)
telemt_user_octets_to_client{user="hello"} 550954625318 (513.12 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1295
telemt_user_unique_ips_recent_window{user="hello"} 443
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 42208.5 (11h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2072621
telemt_connections_bad_total 131426
telemt_connections_current 2911
telemt_connections_me_current 2911
telemt_handshake_timeouts_total 779105
telemt_upstream_connect_attempt_total 18058
telemt_upstream_connect_success_total 18024
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 18027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9639
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 274
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 456
telemt_me_reconnect_success_total 275
telemt_me_reader_eof_total 277
telemt_me_idle_close_by_peer_total 277
telemt_me_route_drop_no_conn_total 373063
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1028668
telemt_me_endpoint_quarantine_total 346
telemt_me_single_endpoint_shadow_rotate_total 338
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
telemt_desync_total 5126
telemt_desync_full_logged_total 1814
telemt_desync_suppressed_total 3312
telemt_desync_frames_bucket_total{bucket="1_2"} 889
telemt_desync_frames_bucket_total{bucket="3_10"} 2067
telemt_desync_frames_bucket_total{bucket="gt_10"} 2170
telemt_pool_swap_total 46
telemt_pool_force_close_total 1098
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 16172
telemt_me_writer_removed_unexpected_total 267
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 999
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15459
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1081
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15074
telemt_me_writer_teardown_success_total{mode="normal"} 16458
telemt_me_writer_teardown_noop_total 16172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32630
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.660633
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32630
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 245
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1025186
telemt_user_connections_current{user="hello"} 2911
telemt_user_octets_from_client{user="hello"} 17474749788 (16.27 GB)
telemt_user_octets_to_client{user="hello"} 521776947312 (485.94 GB)
telemt_user_unique_ips_current{user="hello"} 1203
telemt_user_unique_ips_recent_window{user="hello"} 421
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 40199.9 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 433230
telemt_connections_bad_total 14024
telemt_connections_current 569
telemt_connections_me_current 569
telemt_handshake_timeouts_total 143239
telemt_upstream_connect_attempt_total 19991
telemt_upstream_connect_success_total 19989
telemt_upstream_connect_attempts_per_request{bucket="1"} 19989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11575
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 741
telemt_me_reconnect_success_total 309
telemt_me_reader_eof_total 312
telemt_me_idle_close_by_peer_total 312
telemt_me_route_drop_no_conn_total 96915
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 247034
telemt_me_endpoint_quarantine_total 390
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 346
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
telemt_desync_total 1576
telemt_desync_full_logged_total 665
telemt_desync_suppressed_total 911
telemt_desync_frames_bucket_total{bucket="1_2"} 319
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 610
telemt_pool_swap_total 44
telemt_pool_force_close_total 936
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 54
telemt_me_draining_writers_reap_progress_total 17857
telemt_me_writer_removed_unexpected_total 294
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1259
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16895
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 934
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16921
telemt_me_writer_teardown_success_total{mode="normal"} 18154
telemt_me_writer_teardown_noop_total 17857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36011
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.395429
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36011
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 54
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 260
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 247231
telemt_user_connections_current{user="hello"} 569
telemt_user_octets_from_client{user="hello"} 3315934255 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 101972270273 (94.97 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 42218.5 (11h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1618101
telemt_connections_bad_total 135245
telemt_connections_current 3798
telemt_connections_me_current 3798
telemt_handshake_timeouts_total 41519
telemt_upstream_connect_attempt_total 18635
telemt_upstream_connect_success_total 18551
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 18606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9221
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 623
telemt_me_reconnect_success_total 381
telemt_me_reader_eof_total 355
telemt_me_idle_close_by_peer_total 355
telemt_me_route_drop_no_conn_total 380478
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1271163
telemt_me_endpoint_quarantine_total 337
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
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
telemt_me_writers_active_current 45
telemt_desync_total 5092
telemt_desync_full_logged_total 1712
telemt_desync_suppressed_total 3380
telemt_desync_frames_bucket_total{bucket="1_2"} 1239
telemt_desync_frames_bucket_total{bucket="3_10"} 1923
telemt_desync_frames_bucket_total{bucket="gt_10"} 1930
telemt_pool_swap_total 46
telemt_pool_force_close_total 1106
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 89
telemt_me_draining_writers_reap_progress_total 16811
telemt_me_writer_removed_unexpected_total 355
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1207
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15967
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1090
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 16
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15705
telemt_me_writer_teardown_success_total{mode="normal"} 17174
telemt_me_writer_teardown_noop_total 16811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33985
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.959959
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33985
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 89
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 344
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1266180
telemt_user_connections_current{user="hello"} 3798
telemt_user_octets_from_client{user="hello"} 28408134744 (26.46 GB)
telemt_user_octets_to_client{user="hello"} 584805072820 (544.64 GB)
telemt_user_unique_ips_current{user="hello"} 1365
telemt_user_unique_ips_recent_window{user="hello"} 468
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 42215.4 (11h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1550707
telemt_connections_bad_total 125182
telemt_connections_current 3291
telemt_connections_me_current 3291
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 39376
telemt_upstream_connect_attempt_total 27090
telemt_upstream_connect_success_total 26897
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 27049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 2765
telemt_me_reconnect_success_total 526
telemt_me_reader_eof_total 446
telemt_me_idle_close_by_peer_total 446
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 388539
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1231182
telemt_me_endpoint_quarantine_total 396
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 333
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
telemt_me_writers_active_current 54
telemt_desync_total 4882
telemt_desync_full_logged_total 1577
telemt_desync_suppressed_total 3305
telemt_desync_frames_bucket_total{bucket="1_2"} 1365
telemt_desync_frames_bucket_total{bucket="3_10"} 1768
telemt_desync_frames_bucket_total{bucket="gt_10"} 1749
telemt_pool_swap_total 46
telemt_pool_force_close_total 1082
telemt_me_writer_close_signal_drop_total 91
telemt_me_draining_writers_reap_progress_total 15908
telemt_me_writer_removed_unexpected_total 457
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1418
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14970
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1041
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14826
telemt_me_writer_teardown_success_total{mode="normal"} 16388
telemt_me_writer_teardown_noop_total 15908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32296
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.164956
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32296
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 91
telemt_me_refill_failed_total 127
telemt_me_writer_restored_same_endpoint_total 397
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 1235395
telemt_user_connections_current{user="hello"} 3291
telemt_user_octets_from_client{user="hello"} 18998599551 (17.69 GB)
telemt_user_octets_to_client{user="hello"} 547897143987 (510.27 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1302
telemt_user_unique_ips_recent_window{user="hello"} 469
```
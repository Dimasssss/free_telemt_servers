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

# Server Metrics 2026-03-21 08:14:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 41939.5 (11h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1051243
telemt_connections_bad_total 53798
telemt_connections_current 2506
telemt_connections_me_current 2506
telemt_handshake_timeouts_total 47064
telemt_upstream_connect_attempt_total 16742
telemt_upstream_connect_success_total 16668
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 16718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10702
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 662
telemt_me_reconnect_success_total 298
telemt_me_reader_eof_total 302
telemt_me_idle_close_by_peer_total 302
telemt_me_route_drop_no_conn_total 371005
telemt_me_route_drop_channel_closed_total 141
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 766258
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
telemt_desync_total 3262
telemt_desync_full_logged_total 1172
telemt_desync_suppressed_total 2090
telemt_desync_frames_bucket_total{bucket="1_2"} 680
telemt_desync_frames_bucket_total{bucket="3_10"} 1251
telemt_desync_frames_bucket_total{bucket="gt_10"} 1331
telemt_pool_swap_total 46
telemt_pool_force_close_total 1254
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 158
telemt_me_draining_writers_reap_progress_total 14952
telemt_me_writer_removed_unexpected_total 284
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1161
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14005
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13698
telemt_me_writer_teardown_success_total{mode="normal"} 15166
telemt_me_writer_teardown_noop_total 14953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30119
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 57.376229
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30119
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 158
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 262
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 765646
telemt_user_connections_current{user="hello"} 2506
telemt_user_octets_from_client{user="hello"} 10680313603 (9.95 GB)
telemt_user_octets_to_client{user="hello"} 229800362243 (214.02 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 606
telemt_user_unique_ips_recent_window{user="hello"} 348
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 41940.6 (11h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2574377
telemt_connections_bad_total 291881
telemt_connections_current 4311
telemt_connections_me_current 4311
telemt_handshake_timeouts_total 73363
telemt_upstream_connect_attempt_total 15460
telemt_upstream_connect_success_total 15387
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 15436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8958
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 936
telemt_me_reconnect_success_total 346
telemt_me_reader_eof_total 341
telemt_me_idle_close_by_peer_total 340
telemt_me_route_drop_no_conn_total 669139
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1636220
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
telemt_desync_total 7192
telemt_desync_full_logged_total 2457
telemt_desync_suppressed_total 4735
telemt_desync_frames_bucket_total{bucket="1_2"} 1453
telemt_desync_frames_bucket_total{bucket="3_10"} 2834
telemt_desync_frames_bucket_total{bucket="gt_10"} 2905
telemt_pool_swap_total 45
telemt_pool_force_close_total 1351
telemt_me_writer_close_signal_drop_total 147
telemt_me_draining_writers_reap_progress_total 13847
telemt_me_writer_removed_unexpected_total 319
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1261
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12900
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1276
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 75
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12496
telemt_me_writer_teardown_success_total{mode="normal"} 14161
telemt_me_writer_teardown_noop_total 13847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28008
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.685594
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28008
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 147
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 276
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1632841
telemt_user_connections_current{user="hello"} 4311
telemt_user_octets_from_client{user="hello"} 23253595176 (21.66 GB)
telemt_user_octets_to_client{user="hello"} 637971864144 (594.16 GB)
telemt_user_unique_ips_current{user="hello"} 1488
telemt_user_unique_ips_recent_window{user="hello"} 590
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 41937.2 (11h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1831992
telemt_connections_bad_total 211954
telemt_connections_current 4665
telemt_connections_me_current 4665
telemt_handshake_timeouts_total 73002
telemt_upstream_connect_attempt_total 16693
telemt_upstream_connect_success_total 16683
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 16684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9036
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 547
telemt_me_reconnect_success_total 313
telemt_me_reader_eof_total 322
telemt_me_idle_close_by_peer_total 322
telemt_me_route_drop_no_conn_total 574893
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1420209
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
telemt_desync_total 5869
telemt_desync_full_logged_total 2076
telemt_desync_suppressed_total 3793
telemt_desync_frames_bucket_total{bucket="1_2"} 1307
telemt_desync_frames_bucket_total{bucket="3_10"} 2257
telemt_desync_frames_bucket_total{bucket="gt_10"} 2305
telemt_pool_swap_total 45
telemt_pool_force_close_total 1277
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 152
telemt_me_draining_writers_reap_progress_total 15118
telemt_me_writer_removed_unexpected_total 304
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1226
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14110
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1254
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13841
telemt_me_writer_teardown_success_total{mode="normal"} 15336
telemt_me_writer_teardown_noop_total 15122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30458
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.143459
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30458
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 152
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 276
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1417724
telemt_user_connections_current{user="hello"} 4665
telemt_user_octets_from_client{user="hello"} 19661229176 (18.31 GB)
telemt_user_octets_to_client{user="hello"} 591132767264 (550.54 GB)
telemt_user_unique_ips_current{user="hello"} 1720
telemt_user_unique_ips_recent_window{user="hello"} 540
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 41938.7 (11h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1563870
telemt_connections_bad_total 196122
telemt_connections_current 3031
telemt_connections_me_current 3031
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 66036
telemt_upstream_connect_attempt_total 21462
telemt_upstream_connect_success_total 21233
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 21354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9431
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 378
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 783
telemt_me_reconnect_success_total 343
telemt_me_reader_eof_total 319
telemt_me_idle_close_by_peer_total 319
telemt_me_route_drop_no_conn_total 440233
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1068483
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
telemt_desync_total 4945
telemt_desync_full_logged_total 1731
telemt_desync_suppressed_total 3214
telemt_desync_frames_bucket_total{bucket="1_2"} 1178
telemt_desync_frames_bucket_total{bucket="3_10"} 2022
telemt_desync_frames_bucket_total{bucket="gt_10"} 1745
telemt_pool_swap_total 46
telemt_pool_force_close_total 1203
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 70
telemt_me_draining_writers_reap_progress_total 14981
telemt_me_writer_removed_unexpected_total 311
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1154
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14152
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1165
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 38
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13778
telemt_me_writer_teardown_success_total{mode="normal"} 15306
telemt_me_writer_teardown_noop_total 14982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30288
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.253981
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30288
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 70
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 287
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1070935
telemt_user_connections_current{user="hello"} 3031
telemt_user_octets_from_client{user="hello"} 18984533793 (17.68 GB)
telemt_user_octets_to_client{user="hello"} 514789318979 (479.43 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1078
telemt_user_unique_ips_recent_window{user="hello"} 440
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 41902.3 (11h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1481551
telemt_connections_bad_total 178690
telemt_connections_current 3620
telemt_connections_me_current 3620
telemt_handshake_timeouts_total 49652
telemt_upstream_connect_attempt_total 17494
telemt_upstream_connect_success_total 17483
telemt_upstream_connect_attempts_per_request{bucket="1"} 17483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9679
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 405
telemt_me_reconnect_success_total 307
telemt_me_reader_eof_total 307
telemt_me_idle_close_by_peer_total 307
telemt_me_route_drop_no_conn_total 332442
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1062820
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
telemt_desync_total 5178
telemt_desync_full_logged_total 1823
telemt_desync_suppressed_total 3355
telemt_desync_frames_bucket_total{bucket="1_2"} 1337
telemt_desync_frames_bucket_total{bucket="3_10"} 2000
telemt_desync_frames_bucket_total{bucket="gt_10"} 1841
telemt_pool_swap_total 45
telemt_pool_force_close_total 1136
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 15754
telemt_me_writer_removed_unexpected_total 285
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1098
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14965
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1125
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14618
telemt_me_writer_teardown_success_total{mode="normal"} 16063
telemt_me_writer_teardown_noop_total 15757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31820
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.576210
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31820
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 277
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1060989
telemt_user_connections_current{user="hello"} 3620
telemt_user_octets_from_client{user="hello"} 27572499120 (25.68 GB)
telemt_user_octets_to_client{user="hello"} 551017889056 (513.18 GB)
telemt_user_unique_ips_current{user="hello"} 1398
telemt_user_unique_ips_recent_window{user="hello"} 435
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 41941.9 (11h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3918826
telemt_connections_bad_total 222681
telemt_connections_current 5337
telemt_connections_me_current 5337
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 190872
telemt_upstream_connect_attempt_total 43134
telemt_upstream_connect_success_total 41178
telemt_upstream_connect_fail_total 1363
telemt_upstream_connect_attempts_per_request{bucket="1"} 42541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11042
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1260
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1363
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 2108
telemt_me_reconnect_success_total 736
telemt_me_reader_eof_total 486
telemt_me_idle_close_by_peer_total 485
telemt_me_route_drop_no_conn_total 5427314
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3242290
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
telemt_me_writers_active_current 43
telemt_desync_total 7213
telemt_desync_full_logged_total 2458
telemt_desync_suppressed_total 4755
telemt_desync_frames_bucket_total{bucket="1_2"} 1608
telemt_desync_frames_bucket_total{bucket="3_10"} 3110
telemt_desync_frames_bucket_total{bucket="gt_10"} 2495
telemt_pool_swap_total 44
telemt_pool_force_close_total 1282
telemt_me_writer_close_signal_drop_total 219
telemt_me_draining_writers_reap_progress_total 14227
telemt_me_writer_removed_unexpected_total 709
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1701
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13193
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1164
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 118
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12945
telemt_me_writer_teardown_success_total{mode="normal"} 14894
telemt_me_writer_teardown_noop_total 14233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29127
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 28.353566
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29127
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 219
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 486
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 215
telemt_user_connections_total{user="hello"} 3264543
telemt_user_connections_current{user="hello"} 5337
telemt_user_octets_from_client{user="hello"} 39771184450 (37.04 GB)
telemt_user_octets_to_client{user="hello"} 514466140786 (479.13 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1833
telemt_user_unique_ips_recent_window{user="hello"} 1027
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 41909.0 (11h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1557194
telemt_connections_bad_total 215757
telemt_connections_current 3284
telemt_connections_me_current 3284
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 30308
telemt_upstream_connect_attempt_total 19185
telemt_upstream_connect_success_total 19013
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 19168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9680
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_reconnect_attempts_total 1688
telemt_me_reconnect_success_total 529
telemt_me_reader_eof_total 544
telemt_me_idle_close_by_peer_total 544
telemt_me_route_drop_no_conn_total 406132
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1148022
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
telemt_desync_total 5005
telemt_desync_full_logged_total 1866
telemt_desync_suppressed_total 3139
telemt_desync_frames_bucket_total{bucket="1_2"} 965
telemt_desync_frames_bucket_total{bucket="3_10"} 2026
telemt_desync_frames_bucket_total{bucket="gt_10"} 2014
telemt_pool_swap_total 44
telemt_pool_force_close_total 1118
telemt_me_writer_close_signal_drop_total 72
telemt_me_draining_writers_reap_progress_total 15847
telemt_me_writer_removed_unexpected_total 523
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1372
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15019
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1056
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 62
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14729
telemt_me_writer_teardown_success_total{mode="normal"} 16391
telemt_me_writer_teardown_noop_total 15847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32238
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.202159
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32238
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 72
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 447
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1145190
telemt_user_connections_current{user="hello"} 3284
telemt_user_octets_from_client{user="hello"} 19525278976 (18.18 GB)
telemt_user_octets_to_client{user="hello"} 542991479998 (505.70 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1272
telemt_user_unique_ips_recent_window{user="hello"} 454
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 41903.5 (11h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2041091
telemt_connections_bad_total 130776
telemt_connections_current 2894
telemt_connections_me_current 2894
telemt_handshake_timeouts_total 765950
telemt_upstream_connect_attempt_total 17993
telemt_upstream_connect_success_total 17959
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 17962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 274
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 456
telemt_me_reconnect_success_total 275
telemt_me_reader_eof_total 277
telemt_me_idle_close_by_peer_total 277
telemt_me_route_drop_no_conn_total 366242
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1012173
telemt_me_endpoint_quarantine_total 346
telemt_me_single_endpoint_shadow_rotate_total 337
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
telemt_desync_total 5041
telemt_desync_full_logged_total 1788
telemt_desync_suppressed_total 3253
telemt_desync_frames_bucket_total{bucket="1_2"} 874
telemt_desync_frames_bucket_total{bucket="3_10"} 2044
telemt_desync_frames_bucket_total{bucket="gt_10"} 2123
telemt_pool_swap_total 46
telemt_pool_force_close_total 1098
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 16109
telemt_me_writer_removed_unexpected_total 267
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 998
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15397
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1081
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15011
telemt_me_writer_teardown_success_total{mode="normal"} 16395
telemt_me_writer_teardown_noop_total 16109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32504
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.660296
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32504
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 245
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1008678
telemt_user_connections_current{user="hello"} 2894
telemt_user_octets_from_client{user="hello"} 17226903468 (16.04 GB)
telemt_user_octets_to_client{user="hello"} 514029435260 (478.73 GB)
telemt_user_unique_ips_current{user="hello"} 1190
telemt_user_unique_ips_recent_window{user="hello"} 450
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 39895.2 (11h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 426061
telemt_connections_bad_total 13838
telemt_connections_current 590
telemt_connections_me_current 590
telemt_handshake_timeouts_total 140420
telemt_upstream_connect_attempt_total 19891
telemt_upstream_connect_success_total 19889
telemt_upstream_connect_attempts_per_request{bucket="1"} 19889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11508
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 741
telemt_me_reconnect_success_total 309
telemt_me_reader_eof_total 312
telemt_me_idle_close_by_peer_total 312
telemt_me_route_drop_no_conn_total 95523
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 243751
telemt_me_endpoint_quarantine_total 390
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 345
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
telemt_desync_total 1531
telemt_desync_full_logged_total 653
telemt_desync_suppressed_total 878
telemt_desync_frames_bucket_total{bucket="1_2"} 307
telemt_desync_frames_bucket_total{bucket="3_10"} 630
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 44
telemt_pool_force_close_total 936
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 54
telemt_me_draining_writers_reap_progress_total 17757
telemt_me_writer_removed_unexpected_total 294
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1256
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16798
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 934
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16821
telemt_me_writer_teardown_success_total{mode="normal"} 18054
telemt_me_writer_teardown_noop_total 17757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35811
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.390285
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35811
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 54
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 260
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 243946
telemt_user_connections_current{user="hello"} 590
telemt_user_octets_from_client{user="hello"} 3264249883 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 100965143845 (94.03 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 41913.4 (11h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1588338
telemt_connections_bad_total 127027
telemt_connections_current 3697
telemt_connections_me_current 3697
telemt_handshake_timeouts_total 40755
telemt_upstream_connect_attempt_total 18569
telemt_upstream_connect_success_total 18485
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 18540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9183
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 623
telemt_me_reconnect_success_total 381
telemt_me_reader_eof_total 355
telemt_me_idle_close_by_peer_total 355
telemt_me_route_drop_no_conn_total 371855
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1251335
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
telemt_desync_total 4998
telemt_desync_full_logged_total 1674
telemt_desync_suppressed_total 3324
telemt_desync_frames_bucket_total{bucket="1_2"} 1227
telemt_desync_frames_bucket_total{bucket="3_10"} 1879
telemt_desync_frames_bucket_total{bucket="gt_10"} 1892
telemt_pool_swap_total 46
telemt_pool_force_close_total 1106
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 89
telemt_me_draining_writers_reap_progress_total 16745
telemt_me_writer_removed_unexpected_total 355
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1204
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15904
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1090
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 16
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15639
telemt_me_writer_teardown_success_total{mode="normal"} 17108
telemt_me_writer_teardown_noop_total 16745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33853
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.959334
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33853
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 89
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 344
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1246357
telemt_user_connections_current{user="hello"} 3697
telemt_user_octets_from_client{user="hello"} 26871651860 (25.03 GB)
telemt_user_octets_to_client{user="hello"} 576283239332 (536.71 GB)
telemt_user_unique_ips_current{user="hello"} 1342
telemt_user_unique_ips_recent_window{user="hello"} 564
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 41910.2 (11h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1528223
telemt_connections_bad_total 122077
telemt_connections_current 3471
telemt_connections_me_current 3471
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 39093
telemt_upstream_connect_attempt_total 27009
telemt_upstream_connect_success_total 26816
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 26968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 2765
telemt_me_reconnect_success_total 526
telemt_me_reader_eof_total 446
telemt_me_idle_close_by_peer_total 446
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 379322
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1213140
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
telemt_desync_total 4797
telemt_desync_full_logged_total 1545
telemt_desync_suppressed_total 3252
telemt_desync_frames_bucket_total{bucket="1_2"} 1345
telemt_desync_frames_bucket_total{bucket="3_10"} 1742
telemt_desync_frames_bucket_total{bucket="gt_10"} 1710
telemt_pool_swap_total 46
telemt_pool_force_close_total 1082
telemt_me_writer_close_signal_drop_total 91
telemt_me_draining_writers_reap_progress_total 15828
telemt_me_writer_removed_unexpected_total 457
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1417
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14891
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1041
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14746
telemt_me_writer_teardown_success_total{mode="normal"} 16308
telemt_me_writer_teardown_noop_total 15828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32136
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.163559
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32136
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 91
telemt_me_refill_failed_total 127
telemt_me_writer_restored_same_endpoint_total 397
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 1217357
telemt_user_connections_current{user="hello"} 3471
telemt_user_octets_from_client{user="hello"} 18723163427 (17.44 GB)
telemt_user_octets_to_client{user="hello"} 539100142287 (502.08 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1305
telemt_user_unique_ips_recent_window{user="hello"} 520
```
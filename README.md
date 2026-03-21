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

# Server Metrics 2026-03-21 09:05:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 44991.7 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1215875
telemt_connections_bad_total 60467
telemt_connections_current 2220
telemt_connections_me_current 2220
telemt_handshake_timeouts_total 51289
telemt_upstream_connect_attempt_total 17712
telemt_upstream_connect_success_total 17631
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 17688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11267
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 757
telemt_me_reconnect_success_total 315
telemt_me_reader_eof_total 321
telemt_me_idle_close_by_peer_total 321
telemt_me_route_drop_no_conn_total 599851
telemt_me_route_drop_channel_closed_total 177
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 911599
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
telemt_desync_total 3934
telemt_desync_full_logged_total 1356
telemt_desync_suppressed_total 2578
telemt_desync_frames_bucket_total{bucket="1_2"} 827
telemt_desync_frames_bucket_total{bucket="3_10"} 1530
telemt_desync_frames_bucket_total{bucket="gt_10"} 1577
telemt_pool_swap_total 49
telemt_pool_force_close_total 1343
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 178
telemt_me_draining_writers_reap_progress_total 15838
telemt_me_writer_removed_unexpected_total 301
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1236
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14835
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1322
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14495
telemt_me_writer_teardown_success_total{mode="normal"} 16071
telemt_me_writer_teardown_noop_total 15839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31910
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 68.998422
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31910
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 178
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 275
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 910907
telemt_user_connections_current{user="hello"} 2220
telemt_user_octets_from_client{user="hello"} 13091875187 (12.19 GB)
telemt_user_octets_to_client{user="hello"} 254646931219 (237.16 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 664
telemt_user_unique_ips_recent_window{user="hello"} 546
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 44992.8 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3005396
telemt_connections_bad_total 334220
telemt_connections_current 4656
telemt_connections_me_current 4656
telemt_handshake_timeouts_total 87266
telemt_upstream_connect_attempt_total 16292
telemt_upstream_connect_success_total 16217
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 16268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 971
telemt_me_reconnect_success_total 364
telemt_me_reader_eof_total 359
telemt_me_idle_close_by_peer_total 358
telemt_me_route_drop_no_conn_total 1058150
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1970422
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
telemt_desync_total 8626
telemt_desync_full_logged_total 2917
telemt_desync_suppressed_total 5709
telemt_desync_frames_bucket_total{bucket="1_2"} 1767
telemt_desync_frames_bucket_total{bucket="3_10"} 3369
telemt_desync_frames_bucket_total{bucket="gt_10"} 3490
telemt_pool_swap_total 48
telemt_pool_force_close_total 1448
telemt_me_writer_close_signal_drop_total 171
telemt_me_draining_writers_reap_progress_total 14570
telemt_me_writer_removed_unexpected_total 336
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1335
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13567
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1366
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 82
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13122
telemt_me_writer_teardown_success_total{mode="normal"} 14902
telemt_me_writer_teardown_noop_total 14570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29472
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.944562
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29472
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 171
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 292
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 1966832
telemt_user_connections_current{user="hello"} 4656
telemt_user_octets_from_client{user="hello"} 28288399992 (26.35 GB)
telemt_user_octets_to_client{user="hello"} 721954192548 (672.37 GB)
telemt_user_unique_ips_current{user="hello"} 1551
telemt_user_unique_ips_recent_window{user="hello"} 1126
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 44989.3 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2170436
telemt_connections_bad_total 264616
telemt_connections_current 5353
telemt_connections_me_current 5353
telemt_handshake_timeouts_total 79016
telemt_upstream_connect_attempt_total 17701
telemt_upstream_connect_success_total 17691
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9628
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 585
telemt_me_reconnect_success_total 334
telemt_me_reader_eof_total 346
telemt_me_idle_close_by_peer_total 346
telemt_me_route_drop_no_conn_total 729130
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1681526
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
telemt_desync_total 7140
telemt_desync_full_logged_total 2509
telemt_desync_suppressed_total 4631
telemt_desync_frames_bucket_total{bucket="1_2"} 1555
telemt_desync_frames_bucket_total{bucket="3_10"} 2790
telemt_desync_frames_bucket_total{bucket="gt_10"} 2795
telemt_pool_swap_total 48
telemt_pool_force_close_total 1415
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 178
telemt_me_draining_writers_reap_progress_total 16098
telemt_me_writer_removed_unexpected_total 326
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1310
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15011
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1341
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 74
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14683
telemt_me_writer_teardown_success_total{mode="normal"} 16321
telemt_me_writer_teardown_noop_total 16108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32429
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 30.624926
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32429
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 178
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 297
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 1678728
telemt_user_connections_current{user="hello"} 5353
telemt_user_octets_from_client{user="hello"} 24316973300 (22.65 GB)
telemt_user_octets_to_client{user="hello"} 675557709132 (629.16 GB)
telemt_user_unique_ips_current{user="hello"} 1972
telemt_user_unique_ips_recent_window{user="hello"} 727
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 44990.7 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1829171
telemt_connections_bad_total 222242
telemt_connections_current 4039
telemt_connections_me_current 4039
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 75016
telemt_upstream_connect_attempt_total 22607
telemt_upstream_connect_success_total 22376
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 22499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10032
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 381
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 910
telemt_me_reconnect_success_total 414
telemt_me_reader_eof_total 384
telemt_me_idle_close_by_peer_total 384
telemt_me_route_drop_no_conn_total 518233
telemt_me_route_drop_channel_closed_total 38
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1258726
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
telemt_desync_total 5906
telemt_desync_full_logged_total 2039
telemt_desync_suppressed_total 3867
telemt_desync_frames_bucket_total{bucket="1_2"} 1445
telemt_desync_frames_bucket_total{bucket="3_10"} 2366
telemt_desync_frames_bucket_total{bucket="gt_10"} 2095
telemt_pool_swap_total 48
telemt_pool_force_close_total 1295
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 85
telemt_me_draining_writers_reap_progress_total 15979
telemt_me_writer_removed_unexpected_total 377
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1269
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15101
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1222
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 73
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14684
telemt_me_writer_teardown_success_total{mode="normal"} 16370
telemt_me_writer_teardown_noop_total 15980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32350
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.672188
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32350
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 85
telemt_me_refill_failed_total 26
telemt_me_writer_restored_same_endpoint_total 350
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1260976
telemt_user_connections_current{user="hello"} 4039
telemt_user_octets_from_client{user="hello"} 24752250181 (23.05 GB)
telemt_user_octets_to_client{user="hello"} 608733281935 (566.93 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1578
telemt_user_unique_ips_recent_window{user="hello"} 640
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 44954.6 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1741469
telemt_connections_bad_total 210937
telemt_connections_current 3023
telemt_connections_me_current 3023
telemt_handshake_timeouts_total 54434
telemt_upstream_connect_attempt_total 18597
telemt_upstream_connect_success_total 18579
telemt_upstream_connect_attempts_per_request{bucket="1"} 18579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10246
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 470
telemt_me_reconnect_success_total 358
telemt_me_reader_eof_total 344
telemt_me_idle_close_by_peer_total 344
telemt_me_route_drop_no_conn_total 471585
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1257410
telemt_me_endpoint_quarantine_total 350
telemt_me_single_endpoint_shadow_rotate_total 347
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
telemt_desync_total 5930
telemt_desync_full_logged_total 2077
telemt_desync_suppressed_total 3853
telemt_desync_frames_bucket_total{bucket="1_2"} 1540
telemt_desync_frames_bucket_total{bucket="3_10"} 2302
telemt_desync_frames_bucket_total{bucket="gt_10"} 2088
telemt_pool_swap_total 48
telemt_pool_force_close_total 1255
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 107
telemt_me_draining_writers_reap_progress_total 16762
telemt_me_writer_removed_unexpected_total 318
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1215
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15893
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1206
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 49
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15507
telemt_me_writer_teardown_success_total{mode="normal"} 17108
telemt_me_writer_teardown_noop_total 16765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33873
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.404075
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33873
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 107
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 315
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 1255253
telemt_user_connections_current{user="hello"} 3023
telemt_user_octets_from_client{user="hello"} 30683425624 (28.58 GB)
telemt_user_octets_to_client{user="hello"} 636143779272 (592.46 GB)
telemt_user_unique_ips_current{user="hello"} 1126
telemt_user_unique_ips_recent_window{user="hello"} 671
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 44993.8 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4940914
telemt_connections_bad_total 269177
telemt_connections_current 6141
telemt_connections_me_current 6141
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 213096
telemt_upstream_connect_attempt_total 44320
telemt_upstream_connect_success_total 42322
telemt_upstream_connect_fail_total 1375
telemt_upstream_connect_attempts_per_request{bucket="1"} 43697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11671
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1280
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1375
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 2296
telemt_me_reconnect_success_total 831
telemt_me_reader_eof_total 561
telemt_me_idle_close_by_peer_total 560
telemt_me_route_drop_no_conn_total 7665745
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4147124
telemt_me_endpoint_quarantine_total 354
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 354
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
telemt_desync_total 8743
telemt_desync_full_logged_total 2945
telemt_desync_suppressed_total 5798
telemt_desync_frames_bucket_total{bucket="1_2"} 1928
telemt_desync_frames_bucket_total{bucket="3_10"} 3762
telemt_desync_frames_bucket_total{bucket="gt_10"} 3053
telemt_pool_swap_total 46
telemt_pool_force_close_total 1353
telemt_me_writer_close_signal_drop_total 238
telemt_me_draining_writers_reap_progress_total 15165
telemt_me_writer_removed_unexpected_total 787
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1818
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14089
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1228
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 125
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13812
telemt_me_writer_teardown_success_total{mode="normal"} 15907
telemt_me_writer_teardown_noop_total 15171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31078
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 31.651207
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31078
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 238
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 562
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 217
telemt_user_connections_total{user="hello"} 4169180
telemt_user_connections_current{user="hello"} 6142
telemt_user_octets_from_client{user="hello"} 43897699742 (40.88 GB)
telemt_user_octets_to_client{user="hello"} 547226620046 (509.64 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1986
telemt_user_unique_ips_recent_window{user="hello"} 1233
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 44961.4 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1808019
telemt_connections_bad_total 235311
telemt_connections_current 3886
telemt_connections_me_current 3886
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 35057
telemt_upstream_connect_attempt_total 20083
telemt_upstream_connect_success_total 19897
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 20064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_reconnect_attempts_total 1792
telemt_me_reconnect_success_total 553
telemt_me_reader_eof_total 567
telemt_me_idle_close_by_peer_total 567
telemt_me_route_drop_no_conn_total 509281
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1343655
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
telemt_desync_total 6102
telemt_desync_full_logged_total 2222
telemt_desync_suppressed_total 3880
telemt_desync_frames_bucket_total{bucket="1_2"} 1186
telemt_desync_frames_bucket_total{bucket="3_10"} 2481
telemt_desync_frames_bucket_total{bucket="gt_10"} 2435
telemt_pool_swap_total 47
telemt_pool_force_close_total 1217
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 16645
telemt_me_writer_removed_unexpected_total 545
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1447
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15765
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1143
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 74
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15428
telemt_me_writer_teardown_success_total{mode="normal"} 17212
telemt_me_writer_teardown_noop_total 16645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33857
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.460935
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33857
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 465
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 1340492
telemt_user_connections_current{user="hello"} 3886
telemt_user_octets_from_client{user="hello"} 23542321532 (21.93 GB)
telemt_user_octets_to_client{user="hello"} 625460185366 (582.51 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1458
telemt_user_unique_ips_recent_window{user="hello"} 606
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 44955.8 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2432719
telemt_connections_bad_total 145614
telemt_connections_current 3436
telemt_connections_me_current 3436
telemt_handshake_timeouts_total 948935
telemt_upstream_connect_attempt_total 18930
telemt_upstream_connect_success_total 18896
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 18899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 279
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 468
telemt_me_reconnect_success_total 287
telemt_me_reader_eof_total 288
telemt_me_idle_close_by_peer_total 288
telemt_me_route_drop_no_conn_total 455478
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1187136
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
telemt_desync_total 5839
telemt_desync_full_logged_total 2073
telemt_desync_suppressed_total 3766
telemt_desync_frames_bucket_total{bucket="1_2"} 1024
telemt_desync_frames_bucket_total{bucket="3_10"} 2348
telemt_desync_frames_bucket_total{bucket="gt_10"} 2467
telemt_pool_swap_total 49
telemt_pool_force_close_total 1180
telemt_me_writer_close_signal_drop_total 87
telemt_me_draining_writers_reap_progress_total 16957
telemt_me_writer_removed_unexpected_total 278
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1058
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16196
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1163
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15777
telemt_me_writer_teardown_success_total{mode="normal"} 17254
telemt_me_writer_teardown_noop_total 16957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34211
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.774710
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34211
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 87
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 256
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1183088
telemt_user_connections_current{user="hello"} 3436
telemt_user_octets_from_client{user="hello"} 20719311388 (19.30 GB)
telemt_user_octets_to_client{user="hello"} 593261083644 (552.52 GB)
telemt_user_unique_ips_current{user="hello"} 1359
telemt_user_unique_ips_recent_window{user="hello"} 599
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 42947.2 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 516633
telemt_connections_bad_total 19102
telemt_connections_current 606
telemt_connections_me_current 606
telemt_handshake_timeouts_total 181004
telemt_upstream_connect_attempt_total 21171
telemt_upstream_connect_success_total 21168
telemt_upstream_connect_attempts_per_request{bucket="1"} 21168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 846
telemt_me_reconnect_success_total 349
telemt_me_reader_eof_total 344
telemt_me_idle_close_by_peer_total 344
telemt_me_route_drop_no_conn_total 111860
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 278125
telemt_me_endpoint_quarantine_total 418
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 368
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
telemt_desync_total 1720
telemt_desync_full_logged_total 706
telemt_desync_suppressed_total 1014
telemt_desync_frames_bucket_total{bucket="1_2"} 346
telemt_desync_frames_bucket_total{bucket="3_10"} 701
telemt_desync_frames_bucket_total{bucket="gt_10"} 673
telemt_pool_swap_total 47
telemt_pool_force_close_total 1008
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 61
telemt_me_draining_writers_reap_progress_total 18892
telemt_me_writer_removed_unexpected_total 326
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1356
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17865
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1006
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17884
telemt_me_writer_teardown_success_total{mode="normal"} 19221
telemt_me_writer_teardown_noop_total 18892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38113
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.552837
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38113
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 61
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 285
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 278296
telemt_user_connections_current{user="hello"} 606
telemt_user_octets_from_client{user="hello"} 3946589487 (3.68 GB)
telemt_user_octets_to_client{user="hello"} 110472551853 (102.89 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 44965.7 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1855971
telemt_connections_bad_total 163828
telemt_connections_current 4307
telemt_connections_me_current 4307
telemt_handshake_timeouts_total 47323
telemt_upstream_connect_attempt_total 19593
telemt_upstream_connect_success_total 19507
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 19564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9703
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 728
telemt_me_reconnect_success_total 419
telemt_me_reader_eof_total 387
telemt_me_idle_close_by_peer_total 387
telemt_me_route_drop_no_conn_total 447960
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1460781
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
telemt_desync_total 5835
telemt_desync_full_logged_total 1959
telemt_desync_suppressed_total 3876
telemt_desync_frames_bucket_total{bucket="1_2"} 1428
telemt_desync_frames_bucket_total{bucket="3_10"} 2203
telemt_desync_frames_bucket_total{bucket="gt_10"} 2204
telemt_pool_swap_total 49
telemt_pool_force_close_total 1195
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 107
telemt_me_draining_writers_reap_progress_total 17658
telemt_me_writer_removed_unexpected_total 386
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1295
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16758
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1173
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16463
telemt_me_writer_teardown_success_total{mode="normal"} 18053
telemt_me_writer_teardown_noop_total 17658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35711
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.241787
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35711
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 107
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 375
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1455468
telemt_user_connections_current{user="hello"} 4307
telemt_user_octets_from_client{user="hello"} 33170898556 (30.89 GB)
telemt_user_octets_to_client{user="hello"} 678784030724 (632.17 GB)
telemt_user_unique_ips_current{user="hello"} 1536
telemt_user_unique_ips_recent_window{user="hello"} 675
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 44962.5 (12h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1767347
telemt_connections_bad_total 145841
telemt_connections_current 3919
telemt_connections_me_current 3919
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 44031
telemt_upstream_connect_attempt_total 28044
telemt_upstream_connect_success_total 27844
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 28003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10127
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_reconnect_attempts_total 2796
telemt_me_reconnect_success_total 550
telemt_me_reader_eof_total 470
telemt_me_idle_close_by_peer_total 470
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 458361
telemt_me_route_drop_channel_closed_total 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1411446
telemt_me_endpoint_quarantine_total 409
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 354
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
telemt_desync_total 5504
telemt_desync_full_logged_total 1823
telemt_desync_suppressed_total 3681
telemt_desync_frames_bucket_total{bucket="1_2"} 1533
telemt_desync_frames_bucket_total{bucket="3_10"} 2021
telemt_desync_frames_bucket_total{bucket="gt_10"} 1950
telemt_pool_swap_total 49
telemt_pool_force_close_total 1177
telemt_me_writer_close_signal_drop_total 99
telemt_me_draining_writers_reap_progress_total 16768
telemt_me_writer_removed_unexpected_total 479
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1506
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15766
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1124
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15591
telemt_me_writer_teardown_success_total{mode="normal"} 17272
telemt_me_writer_teardown_noop_total 16769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34041
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.968613
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34041
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 99
telemt_me_refill_failed_total 127
telemt_me_writer_restored_same_endpoint_total 415
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 1415468
telemt_user_connections_current{user="hello"} 3919
telemt_user_octets_from_client{user="hello"} 22136184723 (20.62 GB)
telemt_user_octets_to_client{user="hello"} 629552081195 (586.32 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1438
telemt_user_unique_ips_recent_window{user="hello"} 627
```
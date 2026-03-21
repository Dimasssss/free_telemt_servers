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

# Server Metrics 2026-03-21 08:50:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 44074.5 (12h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1149530
telemt_connections_bad_total 57584
telemt_connections_current 1592
telemt_connections_me_current 1592
telemt_handshake_timeouts_total 50086
telemt_upstream_connect_attempt_total 17424
telemt_upstream_connect_success_total 17346
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 17400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11093
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 723
telemt_me_reconnect_success_total 314
telemt_me_reader_eof_total 317
telemt_me_idle_close_by_peer_total 317
telemt_me_route_drop_no_conn_total 483038
telemt_me_route_drop_channel_closed_total 167
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 851705
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_endpoint_quarantine_total 311
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 355
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
telemt_desync_total 3668
telemt_desync_full_logged_total 1294
telemt_desync_suppressed_total 2374
telemt_desync_frames_bucket_total{bucket="1_2"} 770
telemt_desync_frames_bucket_total{bucket="3_10"} 1395
telemt_desync_frames_bucket_total{bucket="gt_10"} 1503
telemt_pool_swap_total 48
telemt_pool_force_close_total 1314
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 175
telemt_me_draining_writers_reap_progress_total 15576
telemt_me_writer_removed_unexpected_total 298
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1213
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14592
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1293
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14262
telemt_me_writer_teardown_success_total{mode="normal"} 15805
telemt_me_writer_teardown_noop_total 15577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31382
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 65.100512
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31382
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 175
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 274
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 851019
telemt_user_connections_current{user="hello"} 1592
telemt_user_octets_from_client{user="hello"} 12366043711 (11.52 GB)
telemt_user_octets_to_client{user="hello"} 246604333647 (229.67 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 576
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 44075.8 (12h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2842510
telemt_connections_bad_total 321159
telemt_connections_current 4702
telemt_connections_me_current 4702
telemt_handshake_timeouts_total 79232
telemt_upstream_connect_attempt_total 16030
telemt_upstream_connect_success_total 15955
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 16006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9276
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 951
telemt_me_reconnect_success_total 361
telemt_me_reader_eof_total 354
telemt_me_idle_close_by_peer_total 353
telemt_me_route_drop_no_conn_total 803510
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1838577
telemt_me_endpoint_quarantine_total 281
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 343
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
telemt_me_writers_active_current 46
telemt_desync_total 8234
telemt_desync_full_logged_total 2800
telemt_desync_suppressed_total 5434
telemt_desync_frames_bucket_total{bucket="1_2"} 1670
telemt_desync_frames_bucket_total{bucket="3_10"} 3222
telemt_desync_frames_bucket_total{bucket="gt_10"} 3342
telemt_pool_swap_total 47
telemt_pool_force_close_total 1414
telemt_me_writer_close_signal_drop_total 163
telemt_me_draining_writers_reap_progress_total 14339
telemt_me_writer_removed_unexpected_total 332
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1309
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13357
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1335
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 79
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12925
telemt_me_writer_teardown_success_total{mode="normal"} 14666
telemt_me_writer_teardown_noop_total 14339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29005
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.899450
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29005
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 163
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 289
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1835049
telemt_user_connections_current{user="hello"} 4702
telemt_user_octets_from_client{user="hello"} 27262655272 (25.39 GB)
telemt_user_octets_to_client{user="hello"} 698620854572 (650.64 GB)
telemt_user_unique_ips_current{user="hello"} 1747
telemt_user_unique_ips_recent_window{user="hello"} 640
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 44072.3 (12h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2074949
telemt_connections_bad_total 254285
telemt_connections_current 4332
telemt_connections_me_current 4332
telemt_handshake_timeouts_total 75381
telemt_upstream_connect_attempt_total 17413
telemt_upstream_connect_success_total 17403
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9469
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 575
telemt_me_reconnect_success_total 324
telemt_me_reader_eof_total 336
telemt_me_idle_close_by_peer_total 336
telemt_me_route_drop_no_conn_total 688595
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1602629
telemt_me_endpoint_quarantine_total 298
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 344
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
telemt_me_writers_active_current 45
telemt_desync_total 6722
telemt_desync_full_logged_total 2359
telemt_desync_suppressed_total 4363
telemt_desync_frames_bucket_total{bucket="1_2"} 1488
telemt_desync_frames_bucket_total{bucket="3_10"} 2613
telemt_desync_frames_bucket_total{bucket="gt_10"} 2621
telemt_pool_swap_total 47
telemt_pool_force_close_total 1383
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 175
telemt_me_draining_writers_reap_progress_total 15844
telemt_me_writer_removed_unexpected_total 316
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1284
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14779
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1309
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 74
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14461
telemt_me_writer_teardown_success_total{mode="normal"} 16063
telemt_me_writer_teardown_noop_total 15853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31916
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 28.405019
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31916
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 175
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 287
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 1599912
telemt_user_connections_current{user="hello"} 4332
telemt_user_octets_from_client{user="hello"} 22444565968 (20.90 GB)
telemt_user_octets_to_client{user="hello"} 650682829980 (606.00 GB)
telemt_user_unique_ips_current{user="hello"} 1532
telemt_user_unique_ips_recent_window{user="hello"} 603
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 44073.4 (12h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1738971
telemt_connections_bad_total 211424
telemt_connections_current 3899
telemt_connections_me_current 3899
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 69270
telemt_upstream_connect_attempt_total 22247
telemt_upstream_connect_success_total 22016
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 22139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9858
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 381
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 872
telemt_me_reconnect_success_total 397
telemt_me_reader_eof_total 372
telemt_me_idle_close_by_peer_total 372
telemt_me_route_drop_no_conn_total 491515
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1198033
telemt_me_endpoint_quarantine_total 308
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
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
telemt_me_writers_active_current 88
telemt_desync_total 5668
telemt_desync_full_logged_total 1947
telemt_desync_suppressed_total 3721
telemt_desync_frames_bucket_total{bucket="1_2"} 1384
telemt_desync_frames_bucket_total{bucket="3_10"} 2280
telemt_desync_frames_bucket_total{bucket="gt_10"} 2004
telemt_pool_swap_total 47
telemt_pool_force_close_total 1237
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 76
telemt_me_draining_writers_reap_progress_total 15617
telemt_me_writer_removed_unexpected_total 365
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1228
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14768
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1195
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14380
telemt_me_writer_teardown_success_total{mode="normal"} 15996
telemt_me_writer_teardown_noop_total 15618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31614
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.436050
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31614
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 76
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 339
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1200428
telemt_user_connections_current{user="hello"} 3899
telemt_user_octets_from_client{user="hello"} 22787280381 (21.22 GB)
telemt_user_octets_to_client{user="hello"} 579596486755 (539.79 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1444
telemt_user_unique_ips_recent_window{user="hello"} 490
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 44037.6 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1670049
telemt_connections_bad_total 208288
telemt_connections_current 2662
telemt_connections_me_current 2662
telemt_handshake_timeouts_total 52056
telemt_upstream_connect_attempt_total 18276
telemt_upstream_connect_success_total 18260
telemt_upstream_connect_attempts_per_request{bucket="1"} 18260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10080
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 442
telemt_me_reconnect_success_total 321
telemt_me_reader_eof_total 322
telemt_me_idle_close_by_peer_total 322
telemt_me_route_drop_no_conn_total 426895
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1197331
telemt_me_endpoint_quarantine_total 342
telemt_me_single_endpoint_shadow_rotate_total 340
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
telemt_desync_total 5729
telemt_desync_full_logged_total 2009
telemt_desync_suppressed_total 3720
telemt_desync_frames_bucket_total{bucket="1_2"} 1485
telemt_desync_frames_bucket_total{bucket="3_10"} 2231
telemt_desync_frames_bucket_total{bucket="gt_10"} 2013
telemt_pool_swap_total 47
telemt_pool_force_close_total 1221
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 102
telemt_me_draining_writers_reap_progress_total 16493
telemt_me_writer_removed_unexpected_total 298
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1166
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15651
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1182
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 39
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15272
telemt_me_writer_teardown_success_total{mode="normal"} 16817
telemt_me_writer_teardown_noop_total 16496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33313
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.010238
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33313
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 102
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 289
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 1195339
telemt_user_connections_current{user="hello"} 2662
telemt_user_octets_from_client{user="hello"} 29929559328 (27.87 GB)
telemt_user_octets_to_client{user="hello"} 609185377488 (567.35 GB)
telemt_user_unique_ips_current{user="hello"} 1039
telemt_user_unique_ips_recent_window{user="hello"} 469
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 44076.7 (12h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4655651
telemt_connections_bad_total 261037
telemt_connections_current 5308
telemt_connections_me_current 5308
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 206317
telemt_upstream_connect_attempt_total 43831
telemt_upstream_connect_success_total 41845
telemt_upstream_connect_fail_total 1369
telemt_upstream_connect_attempts_per_request{bucket="1"} 43214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11398
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1278
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1369
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 2244
telemt_me_reconnect_success_total 784
telemt_me_reader_eof_total 513
telemt_me_idle_close_by_peer_total 512
telemt_me_route_drop_no_conn_total 7064346
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3891379
telemt_me_endpoint_quarantine_total 353
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 348
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
telemt_me_writers_active_current 46
telemt_desync_total 8238
telemt_desync_full_logged_total 2782
telemt_desync_suppressed_total 5456
telemt_desync_frames_bucket_total{bucket="1_2"} 1823
telemt_desync_frames_bucket_total{bucket="3_10"} 3549
telemt_desync_frames_bucket_total{bucket="gt_10"} 2866
telemt_pool_swap_total 46
telemt_pool_force_close_total 1353
telemt_me_writer_close_signal_drop_total 233
telemt_me_draining_writers_reap_progress_total 14807
telemt_me_writer_removed_unexpected_total 739
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1753
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13748
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1228
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 125
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13454
telemt_me_writer_teardown_success_total{mode="normal"} 15501
telemt_me_writer_teardown_noop_total 14813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30314
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 31.244963
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30314
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 233
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 515
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 3913456
telemt_user_connections_current{user="hello"} 5308
telemt_user_octets_from_client{user="hello"} 42475239454 (39.56 GB)
telemt_user_octets_to_client{user="hello"} 536612321926 (499.76 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1821
telemt_user_unique_ips_recent_window{user="hello"} 944
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 44044.4 (12h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1735619
telemt_connections_bad_total 231363
telemt_connections_current 3402
telemt_connections_me_current 3402
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 33778
telemt_upstream_connect_attempt_total 19770
telemt_upstream_connect_success_total 19588
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 19751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10011
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_reconnect_attempts_total 1708
telemt_me_reconnect_success_total 543
telemt_me_reader_eof_total 557
telemt_me_idle_close_by_peer_total 557
telemt_me_route_drop_no_conn_total 472507
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1283878
telemt_me_endpoint_quarantine_total 269
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 347
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
telemt_me_writers_active_current 46
telemt_desync_total 5800
telemt_desync_full_logged_total 2126
telemt_desync_suppressed_total 3674
telemt_desync_frames_bucket_total{bucket="1_2"} 1117
telemt_desync_frames_bucket_total{bucket="3_10"} 2353
telemt_desync_frames_bucket_total{bucket="gt_10"} 2330
telemt_pool_swap_total 46
telemt_pool_force_close_total 1186
telemt_me_writer_close_signal_drop_total 77
telemt_me_draining_writers_reap_progress_total 16370
telemt_me_writer_removed_unexpected_total 535
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1417
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15510
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1116
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15184
telemt_me_writer_teardown_success_total{mode="normal"} 16927
telemt_me_writer_teardown_noop_total 16370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33297
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.266152
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33297
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 77
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 459
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1280857
telemt_user_connections_current{user="hello"} 3402
telemt_user_octets_from_client{user="hello"} 22467873264 (20.92 GB)
telemt_user_octets_to_client{user="hello"} 600048515478 (558.84 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1337
telemt_user_unique_ips_recent_window{user="hello"} 478
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 44038.6 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2300553
telemt_connections_bad_total 140634
telemt_connections_current 3289
telemt_connections_me_current 3289
telemt_handshake_timeouts_total 878717
telemt_upstream_connect_attempt_total 18651
telemt_upstream_connect_success_total 18617
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 18620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9962
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 277
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 466
telemt_me_reconnect_success_total 285
telemt_me_reader_eof_total 286
telemt_me_idle_close_by_peer_total 286
telemt_me_route_drop_no_conn_total 429423
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1132618
telemt_me_endpoint_quarantine_total 352
telemt_me_single_endpoint_shadow_rotate_total 350
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
telemt_me_writers_active_current 46
telemt_desync_total 5607
telemt_desync_full_logged_total 1983
telemt_desync_suppressed_total 3624
telemt_desync_frames_bucket_total{bucket="1_2"} 972
telemt_desync_frames_bucket_total{bucket="3_10"} 2264
telemt_desync_frames_bucket_total{bucket="gt_10"} 2371
telemt_pool_swap_total 48
telemt_pool_force_close_total 1151
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 16695
telemt_me_writer_removed_unexpected_total 276
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1041
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15949
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1134
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15544
telemt_me_writer_teardown_success_total{mode="normal"} 16990
telemt_me_writer_teardown_noop_total 16695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33685
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.672463
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33685
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 254
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1128602
telemt_user_connections_current{user="hello"} 3289
telemt_user_octets_from_client{user="hello"} 19782513000 (18.42 GB)
telemt_user_octets_to_client{user="hello"} 569758792580 (530.63 GB)
telemt_user_unique_ips_current{user="hello"} 1308
telemt_user_unique_ips_recent_window{user="hello"} 485
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 42030.3 (11h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 483876
telemt_connections_bad_total 18256
telemt_connections_current 558
telemt_connections_me_current 558
telemt_handshake_timeouts_total 164052
telemt_upstream_connect_attempt_total 20774
telemt_upstream_connect_success_total 20772
telemt_upstream_connect_attempts_per_request{bucket="1"} 20772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12055
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 775
telemt_me_reconnect_success_total 329
telemt_me_reader_eof_total 328
telemt_me_idle_close_by_peer_total 328
telemt_me_route_drop_no_conn_total 106304
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 267000
telemt_me_endpoint_quarantine_total 408
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 362
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 1691
telemt_desync_full_logged_total 694
telemt_desync_suppressed_total 997
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 695
telemt_desync_frames_bucket_total{bucket="gt_10"} 657
telemt_pool_swap_total 46
telemt_pool_force_close_total 984
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 59
telemt_me_draining_writers_reap_progress_total 18555
telemt_me_writer_removed_unexpected_total 310
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1320
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17548
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 982
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17571
telemt_me_writer_teardown_success_total{mode="normal"} 18868
telemt_me_writer_teardown_noop_total 18555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37423
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.518598
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37423
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 59
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 272
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 267179
telemt_user_connections_current{user="hello"} 558
telemt_user_octets_from_client{user="hello"} 3821434303 (3.56 GB)
telemt_user_octets_to_client{user="hello"} 107213649861 (99.85 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 44048.7 (12h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1773573
telemt_connections_bad_total 156639
telemt_connections_current 3718
telemt_connections_me_current 3718
telemt_handshake_timeouts_total 45458
telemt_upstream_connect_attempt_total 19284
telemt_upstream_connect_success_total 19199
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 19255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9538
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 688
telemt_me_reconnect_success_total 411
telemt_me_reader_eof_total 378
telemt_me_idle_close_by_peer_total 378
telemt_me_route_drop_no_conn_total 424274
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1393785
telemt_me_endpoint_quarantine_total 350
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 350
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
telemt_me_writers_active_current 45
telemt_desync_total 5612
telemt_desync_full_logged_total 1882
telemt_desync_suppressed_total 3730
telemt_desync_frames_bucket_total{bucket="1_2"} 1366
telemt_desync_frames_bucket_total{bucket="3_10"} 2111
telemt_desync_frames_bucket_total{bucket="gt_10"} 2135
telemt_pool_swap_total 48
telemt_pool_force_close_total 1170
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 105
telemt_me_draining_writers_reap_progress_total 17389
telemt_me_writer_removed_unexpected_total 377
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1269
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16506
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1148
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16219
telemt_me_writer_teardown_success_total{mode="normal"} 17775
telemt_me_writer_teardown_noop_total 17389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35164
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.211729
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35164
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 105
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 368
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 1388596
telemt_user_connections_current{user="hello"} 3718
telemt_user_octets_from_client{user="hello"} 31340287232 (29.19 GB)
telemt_user_octets_to_client{user="hello"} 646216188212 (601.84 GB)
telemt_user_unique_ips_current{user="hello"} 1379
telemt_user_unique_ips_recent_window{user="hello"} 559
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 44045.4 (12h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1694896
telemt_connections_bad_total 142347
telemt_connections_current 3635
telemt_connections_me_current 3635
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 41860
telemt_upstream_connect_attempt_total 27704
telemt_upstream_connect_success_total 27509
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 27663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_reconnect_attempts_total 2786
telemt_me_reconnect_success_total 540
telemt_me_reader_eof_total 460
telemt_me_idle_close_by_peer_total 460
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 432898
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1347584
telemt_me_endpoint_quarantine_total 406
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
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
telemt_me_writers_active_current 45
telemt_desync_total 5287
telemt_desync_full_logged_total 1742
telemt_desync_suppressed_total 3545
telemt_desync_frames_bucket_total{bucket="1_2"} 1469
telemt_desync_frames_bucket_total{bucket="3_10"} 1938
telemt_desync_frames_bucket_total{bucket="gt_10"} 1880
telemt_pool_swap_total 48
telemt_pool_force_close_total 1146
telemt_me_writer_close_signal_drop_total 98
telemt_me_draining_writers_reap_progress_total 16479
telemt_me_writer_removed_unexpected_total 469
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1476
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15497
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1095
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15333
telemt_me_writer_teardown_success_total{mode="normal"} 16973
telemt_me_writer_teardown_noop_total 16480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33453
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.590217
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33453
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 98
telemt_me_refill_failed_total 127
telemt_me_writer_restored_same_endpoint_total 408
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 1351648
telemt_user_connections_current{user="hello"} 3635
telemt_user_octets_from_client{user="hello"} 20718050475 (19.30 GB)
telemt_user_octets_to_client{user="hello"} 602668753491 (561.28 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1369
telemt_user_unique_ips_recent_window{user="hello"} 495
```
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

# Server Metrics 2026-03-21 09:56:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 48042.4 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1360955
telemt_connections_bad_total 70533
telemt_connections_current 1569
telemt_connections_me_current 1569
telemt_handshake_timeouts_total 55183
telemt_upstream_connect_attempt_total 19022
telemt_upstream_connect_success_total 18941
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 18998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12067
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 865
telemt_me_reconnect_success_total 370
telemt_me_reader_eof_total 381
telemt_me_idle_close_by_peer_total 381
telemt_me_route_drop_no_conn_total 739504
telemt_me_route_drop_channel_closed_total 261
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1030938
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 340
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 386
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
telemt_desync_total 4316
telemt_desync_full_logged_total 1489
telemt_desync_suppressed_total 2827
telemt_desync_frames_bucket_total{bucket="1_2"} 905
telemt_desync_frames_bucket_total{bucket="3_10"} 1676
telemt_desync_frames_bucket_total{bucket="gt_10"} 1735
telemt_pool_swap_total 52
telemt_pool_force_close_total 1485
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 223
telemt_me_draining_writers_reap_progress_total 17051
telemt_me_writer_removed_unexpected_total 360
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1351
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15958
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1432
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15566
telemt_me_writer_teardown_success_total{mode="normal"} 17309
telemt_me_writer_teardown_noop_total 17053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34362
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 85.862844
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34362
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 223
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 330
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1030130
telemt_user_connections_current{user="hello"} 1569
telemt_user_octets_from_client{user="hello"} 14619742563 (13.62 GB)
telemt_user_octets_to_client{user="hello"} 293809436947 (273.63 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 548
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 48043.7 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3473709
telemt_connections_bad_total 368507
telemt_connections_current 4501
telemt_connections_me_current 4501
telemt_handshake_timeouts_total 101504
telemt_upstream_connect_attempt_total 17229
telemt_upstream_connect_success_total 17150
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 17204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_reconnect_attempts_total 1031
telemt_me_reconnect_success_total 387
telemt_me_reader_eof_total 382
telemt_me_idle_close_by_peer_total 381
telemt_me_route_drop_no_conn_total 1478893
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2340268
telemt_me_endpoint_quarantine_total 301
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 372
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
telemt_me_writers_active_current 44
telemt_desync_total 10064
telemt_desync_full_logged_total 3383
telemt_desync_suppressed_total 6681
telemt_desync_frames_bucket_total{bucket="1_2"} 2058
telemt_desync_frames_bucket_total{bucket="3_10"} 3973
telemt_desync_frames_bucket_total{bucket="gt_10"} 4033
telemt_pool_swap_total 52
telemt_pool_force_close_total 1595
telemt_me_writer_close_signal_drop_total 190
telemt_me_draining_writers_reap_progress_total 15420
telemt_me_writer_removed_unexpected_total 358
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1429
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14333
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1500
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 95
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13825
telemt_me_writer_teardown_success_total{mode="normal"} 15762
telemt_me_writer_teardown_noop_total 15420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31182
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.881826
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31182
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 190
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 311
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 2335898
telemt_user_connections_current{user="hello"} 4501
telemt_user_octets_from_client{user="hello"} 33017971876 (30.75 GB)
telemt_user_octets_to_client{user="hello"} 792462057596 (738.04 GB)
telemt_user_unique_ips_current{user="hello"} 1614
telemt_user_unique_ips_recent_window{user="hello"} 622
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 48040.2 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2545553
telemt_connections_bad_total 301225
telemt_connections_current 4067
telemt_connections_me_current 4067
telemt_handshake_timeouts_total 96006
telemt_upstream_connect_attempt_total 18724
telemt_upstream_connect_success_total 18712
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 18713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 624
telemt_me_reconnect_success_total 354
telemt_me_reader_eof_total 368
telemt_me_idle_close_by_peer_total 368
telemt_me_route_drop_no_conn_total 1033996
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1990853
telemt_me_endpoint_quarantine_total 318
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 378
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
telemt_me_writers_active_current 44
telemt_desync_total 8645
telemt_desync_full_logged_total 2982
telemt_desync_suppressed_total 5663
telemt_desync_frames_bucket_total{bucket="1_2"} 1815
telemt_desync_frames_bucket_total{bucket="3_10"} 3429
telemt_desync_frames_bucket_total{bucket="gt_10"} 3401
telemt_pool_swap_total 52
telemt_pool_force_close_total 1562
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 209
telemt_me_draining_writers_reap_progress_total 17035
telemt_me_writer_removed_unexpected_total 347
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1409
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15855
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1477
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15473
telemt_me_writer_teardown_success_total{mode="normal"} 17264
telemt_me_writer_teardown_noop_total 17046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34310
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 37.869478
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34310
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 209
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 317
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 1987669
telemt_user_connections_current{user="hello"} 4067
telemt_user_octets_from_client{user="hello"} 30936925952 (28.81 GB)
telemt_user_octets_to_client{user="hello"} 752336963312 (700.67 GB)
telemt_user_unique_ips_current{user="hello"} 1495
telemt_user_unique_ips_recent_window{user="hello"} 588
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 48041.5 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2084076
telemt_connections_bad_total 238565
telemt_connections_current 3273
telemt_connections_me_current 3273
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 88983
telemt_upstream_connect_attempt_total 23662
telemt_upstream_connect_success_total 23425
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 23551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10559
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 390
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 1015
telemt_me_reconnect_success_total 441
telemt_me_reader_eof_total 409
telemt_me_idle_close_by_peer_total 409
telemt_me_route_drop_no_conn_total 602273
telemt_me_route_drop_channel_closed_total 43
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1454978
telemt_me_endpoint_quarantine_total 337
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 379
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
telemt_desync_total 6800
telemt_desync_full_logged_total 2336
telemt_desync_suppressed_total 4464
telemt_desync_frames_bucket_total{bucket="1_2"} 1681
telemt_desync_frames_bucket_total{bucket="3_10"} 2696
telemt_desync_frames_bucket_total{bucket="gt_10"} 2423
telemt_pool_swap_total 52
telemt_pool_force_close_total 1415
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 92
telemt_me_draining_writers_reap_progress_total 16913
telemt_me_writer_removed_unexpected_total 402
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1364
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15965
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1333
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 82
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15498
telemt_me_writer_teardown_success_total{mode="normal"} 17329
telemt_me_writer_teardown_noop_total 16914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34243
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.620290
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34243
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 92
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 371
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1456920
telemt_user_connections_current{user="hello"} 3273
telemt_user_octets_from_client{user="hello"} 29321855669 (27.31 GB)
telemt_user_octets_to_client{user="hello"} 701036679415 (652.89 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1267
telemt_user_unique_ips_recent_window{user="hello"} 450
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 48005.4 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2015093
telemt_connections_bad_total 225561
telemt_connections_current 3291
telemt_connections_me_current 3291
telemt_handshake_timeouts_total 63910
telemt_upstream_connect_attempt_total 20009
telemt_upstream_connect_success_total 19969
telemt_upstream_connect_attempts_per_request{bucket="1"} 19969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10907
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 626
telemt_me_reconnect_success_total 447
telemt_me_reader_eof_total 409
telemt_me_idle_close_by_peer_total 409
telemt_me_route_drop_no_conn_total 560184
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1453886
telemt_me_endpoint_quarantine_total 369
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 370
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
telemt_desync_total 6764
telemt_desync_full_logged_total 2349
telemt_desync_suppressed_total 4415
telemt_desync_frames_bucket_total{bucket="1_2"} 1778
telemt_desync_frames_bucket_total{bucket="3_10"} 2599
telemt_desync_frames_bucket_total{bucket="gt_10"} 2387
telemt_pool_swap_total 51
telemt_pool_force_close_total 1398
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 127
telemt_me_draining_writers_reap_progress_total 18013
telemt_me_writer_removed_unexpected_total 384
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1360
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17067
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1289
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 109
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16615
telemt_me_writer_teardown_success_total{mode="normal"} 18427
telemt_me_writer_teardown_noop_total 18016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36443
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.222037
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36443
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 127
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 399
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1451487
telemt_user_connections_current{user="hello"} 3291
telemt_user_octets_from_client{user="hello"} 34148034568 (31.80 GB)
telemt_user_octets_to_client{user="hello"} 717116055016 (667.87 GB)
telemt_user_unique_ips_current{user="hello"} 1217
telemt_user_unique_ips_recent_window{user="hello"} 469
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 48059.4 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5981649
telemt_connections_bad_total 318105
telemt_connections_current 4966
telemt_connections_me_current 4966
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 233640
telemt_upstream_connect_attempt_total 59117
telemt_upstream_connect_success_total 56525
telemt_upstream_connect_fail_total 1916
telemt_upstream_connect_attempts_per_request{bucket="1"} 58441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2013
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1916
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 2903
telemt_me_reconnect_success_total 987
telemt_me_reader_eof_total 689
telemt_me_idle_close_by_peer_total 688
telemt_me_route_drop_no_conn_total 9826012
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5047171
telemt_me_endpoint_quarantine_total 382
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 116
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 116
telemt_me_single_endpoint_shadow_rotate_total 382
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 10243
telemt_desync_full_logged_total 3331
telemt_desync_suppressed_total 6912
telemt_desync_frames_bucket_total{bucket="1_2"} 2248
telemt_desync_frames_bucket_total{bucket="3_10"} 4434
telemt_desync_frames_bucket_total{bucket="gt_10"} 3561
telemt_pool_swap_total 49
telemt_pool_force_close_total 1525
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 302
telemt_me_draining_writers_reap_progress_total 16259
telemt_me_writer_removed_unexpected_total 953
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2075
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15066
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1313
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 212
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14734
telemt_me_writer_teardown_success_total{mode="normal"} 17141
telemt_me_writer_teardown_noop_total 16265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33406
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 39.187397
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33406
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 302
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 681
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 5081739
telemt_user_connections_current{user="hello"} 4966
telemt_user_octets_from_client{user="hello"} 47793727432 (44.51 GB)
telemt_user_octets_to_client{user="hello"} 580931646767 (541.03 GB)
telemt_user_msgs_from_client{user="hello"} 126757
telemt_user_msgs_to_client{user="hello"} 447030
telemt_user_unique_ips_current{user="hello"} 1761
telemt_user_unique_ips_recent_window{user="hello"} 918
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 48012.2 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2042556
telemt_connections_bad_total 259190
telemt_connections_current 3391
telemt_connections_me_current 3391
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 39848
telemt_upstream_connect_attempt_total 21336
telemt_upstream_connect_success_total 21123
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 21317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10835
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_reconnect_attempts_total 1998
telemt_me_reconnect_success_total 638
telemt_me_reader_eof_total 648
telemt_me_idle_close_by_peer_total 648
telemt_me_route_drop_no_conn_total 620151
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1533833
telemt_me_endpoint_quarantine_total 298
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 375
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
telemt_me_writers_active_current 43
telemt_desync_total 6989
telemt_desync_full_logged_total 2554
telemt_desync_suppressed_total 4435
telemt_desync_frames_bucket_total{bucket="1_2"} 1345
telemt_desync_frames_bucket_total{bucket="3_10"} 2838
telemt_desync_frames_bucket_total{bucket="gt_10"} 2806
telemt_pool_swap_total 50
telemt_pool_force_close_total 1335
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 100
telemt_me_draining_writers_reap_progress_total 17720
telemt_me_writer_removed_unexpected_total 625
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1601
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16767
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1225
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 110
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16385
telemt_me_writer_teardown_success_total{mode="normal"} 18368
telemt_me_writer_teardown_noop_total 17720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36088
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.608093
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36088
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 100
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 541
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 1529668
telemt_user_connections_current{user="hello"} 3391
telemt_user_octets_from_client{user="hello"} 28007501856 (26.08 GB)
telemt_user_octets_to_client{user="hello"} 707541513666 (658.95 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1295
telemt_user_unique_ips_recent_window{user="hello"} 548
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 48006.7 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2884816
telemt_connections_bad_total 164859
telemt_connections_current 3215
telemt_connections_me_current 3215
telemt_handshake_timeouts_total 1187385
telemt_upstream_connect_attempt_total 19947
telemt_upstream_connect_success_total 19913
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 19916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 281
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 522
telemt_me_reconnect_success_total 302
telemt_me_reader_eof_total 303
telemt_me_idle_close_by_peer_total 303
telemt_me_route_drop_no_conn_total 535422
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1369197
telemt_me_endpoint_quarantine_total 368
telemt_me_single_endpoint_shadow_rotate_total 380
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
telemt_desync_total 6801
telemt_desync_full_logged_total 2395
telemt_desync_suppressed_total 4406
telemt_desync_frames_bucket_total{bucket="1_2"} 1211
telemt_desync_frames_bucket_total{bucket="3_10"} 2727
telemt_desync_frames_bucket_total{bucket="gt_10"} 2863
telemt_pool_swap_total 53
telemt_pool_force_close_total 1292
telemt_me_writer_close_signal_drop_total 102
telemt_me_draining_writers_reap_progress_total 17884
telemt_me_writer_removed_unexpected_total 293
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1143
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17053
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1275
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16592
telemt_me_writer_teardown_success_total{mode="normal"} 18196
telemt_me_writer_teardown_noop_total 17884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36080
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.946598
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36080
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 102
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 269
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1364895
telemt_user_connections_current{user="hello"} 3215
telemt_user_octets_from_client{user="hello"} 24354064372 (22.68 GB)
telemt_user_octets_to_client{user="hello"} 674075538948 (627.78 GB)
telemt_user_unique_ips_current{user="hello"} 1286
telemt_user_unique_ips_recent_window{user="hello"} 464
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 45998.2 (12h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 606427
telemt_connections_bad_total 21670
telemt_connections_current 701
telemt_connections_me_current 701
telemt_handshake_timeouts_total 224816
telemt_upstream_connect_attempt_total 22458
telemt_upstream_connect_success_total 22456
telemt_upstream_connect_attempts_per_request{bucket="1"} 22456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13084
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 918
telemt_me_reconnect_success_total 367
telemt_me_reader_eof_total 363
telemt_me_idle_close_by_peer_total 363
telemt_me_route_drop_no_conn_total 128289
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 313569
telemt_me_endpoint_quarantine_total 445
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 390
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 42
telemt_desync_total 1988
telemt_desync_full_logged_total 797
telemt_desync_suppressed_total 1191
telemt_desync_frames_bucket_total{bucket="1_2"} 364
telemt_desync_frames_bucket_total{bucket="3_10"} 770
telemt_desync_frames_bucket_total{bucket="gt_10"} 854
telemt_pool_swap_total 51
telemt_pool_force_close_total 1087
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 20049
telemt_me_writer_removed_unexpected_total 344
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1437
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18960
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1084
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18962
telemt_me_writer_teardown_success_total{mode="normal"} 20397
telemt_me_writer_teardown_noop_total 20049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40446
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.889032
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40446
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 300
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 313721
telemt_user_connections_current{user="hello"} 701
telemt_user_octets_from_client{user="hello"} 4604787563 (4.29 GB)
telemt_user_octets_to_client{user="hello"} 123719304741 (115.22 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 48016.5 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2142769
telemt_connections_bad_total 195179
telemt_connections_current 3845
telemt_connections_me_current 3845
telemt_handshake_timeouts_total 53463
telemt_upstream_connect_attempt_total 20640
telemt_upstream_connect_success_total 20551
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 20610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10236
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_reconnect_attempts_total 768
telemt_me_reconnect_success_total 441
telemt_me_reader_eof_total 410
telemt_me_idle_close_by_peer_total 410
telemt_me_route_drop_no_conn_total 533285
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1685688
telemt_me_endpoint_quarantine_total 377
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 380
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
telemt_me_writers_active_current 44
telemt_desync_total 6667
telemt_desync_full_logged_total 2231
telemt_desync_suppressed_total 4436
telemt_desync_frames_bucket_total{bucket="1_2"} 1627
telemt_desync_frames_bucket_total{bucket="3_10"} 2477
telemt_desync_frames_bucket_total{bucket="gt_10"} 2563
telemt_pool_swap_total 53
telemt_pool_force_close_total 1314
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 129
telemt_me_draining_writers_reap_progress_total 18603
telemt_me_writer_removed_unexpected_total 409
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1385
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17636
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1291
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17289
telemt_me_writer_teardown_success_total{mode="normal"} 19021
telemt_me_writer_teardown_noop_total 18603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37624
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.619945
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37624
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 129
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 397
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1680044
telemt_user_connections_current{user="hello"} 3845
telemt_user_octets_from_client{user="hello"} 38043297072 (35.43 GB)
telemt_user_octets_to_client{user="hello"} 786273267288 (732.27 GB)
telemt_user_unique_ips_current{user="hello"} 1412
telemt_user_unique_ips_recent_window{user="hello"} 557
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 48013.2 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1994842
telemt_connections_bad_total 163531
telemt_connections_current 3406
telemt_connections_me_current 3406
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 48620
telemt_upstream_connect_attempt_total 29282
telemt_upstream_connect_success_total 29070
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 29240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10761
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_reconnect_attempts_total 2993
telemt_me_reconnect_success_total 604
telemt_me_reader_eof_total 529
telemt_me_idle_close_by_peer_total 529
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 544315
telemt_me_route_drop_channel_closed_total 30
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1603922
telemt_me_endpoint_quarantine_total 427
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 378
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
telemt_desync_total 6103
telemt_desync_full_logged_total 2046
telemt_desync_suppressed_total 4057
telemt_desync_frames_bucket_total{bucket="1_2"} 1684
telemt_desync_frames_bucket_total{bucket="3_10"} 2244
telemt_desync_frames_bucket_total{bucket="gt_10"} 2175
telemt_pool_swap_total 52
telemt_pool_force_close_total 1289
telemt_me_writer_close_signal_drop_total 116
telemt_me_draining_writers_reap_progress_total 17877
telemt_me_writer_removed_unexpected_total 539
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1628
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16814
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16588
telemt_me_writer_teardown_success_total{mode="normal"} 18442
telemt_me_writer_teardown_noop_total 17878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36320
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.463534
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36320
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 116
telemt_me_refill_failed_total 136
telemt_me_writer_restored_same_endpoint_total 466
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 1607608
telemt_user_connections_current{user="hello"} 3406
telemt_user_octets_from_client{user="hello"} 26945278711 (25.09 GB)
telemt_user_octets_to_client{user="hello"} 716695279367 (667.47 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1242
telemt_user_unique_ips_recent_window{user="hello"} 479
```
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

# Server Metrics 2026-03-21 10:12:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 48970.9 (13h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1403142
telemt_connections_bad_total 72852
telemt_connections_current 1540
telemt_connections_me_current 1540
telemt_handshake_timeouts_total 56766
telemt_upstream_connect_attempt_total 19353
telemt_upstream_connect_success_total 19270
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 19329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12282
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 908
telemt_me_reconnect_success_total 378
telemt_me_reader_eof_total 391
telemt_me_idle_close_by_peer_total 391
telemt_me_route_drop_no_conn_total 763954
telemt_me_route_drop_channel_closed_total 281
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1065861
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 343
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 393
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
telemt_me_writers_active_current 44
telemt_desync_total 4455
telemt_desync_full_logged_total 1543
telemt_desync_suppressed_total 2912
telemt_desync_frames_bucket_total{bucket="1_2"} 931
telemt_desync_frames_bucket_total{bucket="3_10"} 1729
telemt_desync_frames_bucket_total{bucket="gt_10"} 1795
telemt_pool_swap_total 53
telemt_pool_force_close_total 1511
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 239
telemt_me_draining_writers_reap_progress_total 17332
telemt_me_writer_removed_unexpected_total 369
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1382
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16215
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1458
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15821
telemt_me_writer_teardown_success_total{mode="normal"} 17597
telemt_me_writer_teardown_noop_total 17334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34931
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 90.434426
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34931
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 239
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 337
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1065031
telemt_user_connections_current{user="hello"} 1540
telemt_user_octets_from_client{user="hello"} 14981674227 (13.95 GB)
telemt_user_octets_to_client{user="hello"} 303272699555 (282.44 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 572
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 48972.1 (13h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3583362
telemt_connections_bad_total 374557
telemt_connections_current 4582
telemt_connections_me_current 4582
telemt_handshake_timeouts_total 103859
telemt_upstream_connect_attempt_total 17525
telemt_upstream_connect_success_total 17443
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 17500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10132
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 1086
telemt_me_reconnect_success_total 400
telemt_me_reader_eof_total 393
telemt_me_idle_close_by_peer_total 392
telemt_me_route_drop_no_conn_total 1538487
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2430066
telemt_me_endpoint_quarantine_total 312
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 378
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
telemt_me_writers_active_current 44
telemt_desync_total 10538
telemt_desync_full_logged_total 3532
telemt_desync_suppressed_total 7006
telemt_desync_frames_bucket_total{bucket="1_2"} 2158
telemt_desync_frames_bucket_total{bucket="3_10"} 4149
telemt_desync_frames_bucket_total{bucket="gt_10"} 4231
telemt_pool_swap_total 53
telemt_pool_force_close_total 1626
telemt_me_writer_close_signal_drop_total 197
telemt_me_draining_writers_reap_progress_total 15676
telemt_me_writer_removed_unexpected_total 367
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1461
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14568
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1529
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 97
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14050
telemt_me_writer_teardown_success_total{mode="normal"} 16029
telemt_me_writer_teardown_noop_total 15676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31705
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.062077
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31705
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 197
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 318
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2425515
telemt_user_connections_current{user="hello"} 4582
telemt_user_octets_from_client{user="hello"} 34104268848 (31.76 GB)
telemt_user_octets_to_client{user="hello"} 820338079776 (764.00 GB)
telemt_user_unique_ips_current{user="hello"} 1635
telemt_user_unique_ips_recent_window{user="hello"} 622
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 48968.6 (13h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2640858
telemt_connections_bad_total 308666
telemt_connections_current 4073
telemt_connections_me_current 4073
telemt_handshake_timeouts_total 98733
telemt_upstream_connect_attempt_total 18997
telemt_upstream_connect_success_total 18984
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 18985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 629
telemt_me_reconnect_success_total 358
telemt_me_reader_eof_total 372
telemt_me_idle_close_by_peer_total 372
telemt_me_route_drop_no_conn_total 1072312
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2070371
telemt_me_endpoint_quarantine_total 323
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 385
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
telemt_me_writers_active_current 43
telemt_desync_total 8997
telemt_desync_full_logged_total 3089
telemt_desync_suppressed_total 5908
telemt_desync_frames_bucket_total{bucket="1_2"} 1875
telemt_desync_frames_bucket_total{bucket="3_10"} 3578
telemt_desync_frames_bucket_total{bucket="gt_10"} 3544
telemt_pool_swap_total 53
telemt_pool_force_close_total 1595
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 216
telemt_me_draining_writers_reap_progress_total 17275
telemt_me_writer_removed_unexpected_total 351
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1423
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16085
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1509
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 86
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15680
telemt_me_writer_teardown_success_total{mode="normal"} 17508
telemt_me_writer_teardown_noop_total 17287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34795
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 39.602599
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34795
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 216
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 321
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 2067145
telemt_user_connections_current{user="hello"} 4073
telemt_user_octets_from_client{user="hello"} 32755113152 (30.51 GB)
telemt_user_octets_to_client{user="hello"} 779970250276 (726.40 GB)
telemt_user_unique_ips_current{user="hello"} 1553
telemt_user_unique_ips_recent_window{user="hello"} 574
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 48969.9 (13h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2168904
telemt_connections_bad_total 246662
telemt_connections_current 3403
telemt_connections_me_current 3403
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 92310
telemt_upstream_connect_attempt_total 23958
telemt_upstream_connect_success_total 23716
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 23842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10705
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 393
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 1020
telemt_me_reconnect_success_total 446
telemt_me_reader_eof_total 414
telemt_me_idle_close_by_peer_total 414
telemt_me_route_drop_no_conn_total 634671
telemt_me_route_drop_channel_closed_total 47
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1517905
telemt_me_endpoint_quarantine_total 339
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 383
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_me_writers_active_current 45
telemt_desync_total 7028
telemt_desync_full_logged_total 2419
telemt_desync_suppressed_total 4609
telemt_desync_frames_bucket_total{bucket="1_2"} 1744
telemt_desync_frames_bucket_total{bucket="3_10"} 2784
telemt_desync_frames_bucket_total{bucket="gt_10"} 2500
telemt_pool_swap_total 53
telemt_pool_force_close_total 1446
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 98
telemt_me_draining_writers_reap_progress_total 17153
telemt_me_writer_removed_unexpected_total 407
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1387
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16187
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1363
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15707
telemt_me_writer_teardown_success_total{mode="normal"} 17574
telemt_me_writer_teardown_noop_total 17154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34728
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.677124
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34728
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 98
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 376
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1519782
telemt_user_connections_current{user="hello"} 3403
telemt_user_octets_from_client{user="hello"} 30514886125 (28.42 GB)
telemt_user_octets_to_client{user="hello"} 729502154231 (679.40 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1248
telemt_user_unique_ips_recent_window{user="hello"} 466
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 48933.8 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2109668
telemt_connections_bad_total 235644
telemt_connections_current 3242
telemt_connections_me_current 3242
telemt_handshake_timeouts_total 65429
telemt_upstream_connect_attempt_total 20327
telemt_upstream_connect_success_total 20284
telemt_upstream_connect_attempts_per_request{bucket="1"} 20284
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11066
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_me_reconnect_attempts_total 678
telemt_me_reconnect_success_total 462
telemt_me_reader_eof_total 425
telemt_me_idle_close_by_peer_total 425
telemt_me_route_drop_no_conn_total 587944
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1515673
telemt_me_endpoint_quarantine_total 373
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 376
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
telemt_desync_total 7191
telemt_desync_full_logged_total 2460
telemt_desync_suppressed_total 4731
telemt_desync_frames_bucket_total{bucket="1_2"} 1903
telemt_desync_frames_bucket_total{bucket="3_10"} 2754
telemt_desync_frames_bucket_total{bucket="gt_10"} 2534
telemt_pool_swap_total 52
telemt_pool_force_close_total 1428
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 135
telemt_me_draining_writers_reap_progress_total 18262
telemt_me_writer_removed_unexpected_total 400
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1400
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17293
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1319
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 109
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16834
telemt_me_writer_teardown_success_total{mode="normal"} 18693
telemt_me_writer_teardown_noop_total 18265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36958
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.277469
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36958
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 135
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 412
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1513197
telemt_user_connections_current{user="hello"} 3242
telemt_user_octets_from_client{user="hello"} 36079743328 (33.60 GB)
telemt_user_octets_to_client{user="hello"} 745066115840 (693.90 GB)
telemt_user_unique_ips_current{user="hello"} 1226
telemt_user_unique_ips_recent_window{user="hello"} 489
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 48972.9 (13h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6318805
telemt_connections_bad_total 336781
telemt_connections_current 5347
telemt_connections_me_current 5347
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 240541
telemt_upstream_connect_attempt_total 59409
telemt_upstream_connect_success_total 56798
telemt_upstream_connect_fail_total 1922
telemt_upstream_connect_attempts_per_request{bucket="1"} 58720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2020
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1922
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 2911
telemt_me_reconnect_success_total 994
telemt_me_reader_eof_total 694
telemt_me_idle_close_by_peer_total 693
telemt_me_route_drop_no_conn_total 10475287
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5336841
telemt_me_endpoint_quarantine_total 386
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 116
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 116
telemt_me_single_endpoint_shadow_rotate_total 389
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
telemt_me_writers_active_current 44
telemt_desync_total 10693
telemt_desync_full_logged_total 3457
telemt_desync_suppressed_total 7236
telemt_desync_frames_bucket_total{bucket="1_2"} 2364
telemt_desync_frames_bucket_total{bucket="3_10"} 4631
telemt_desync_frames_bucket_total{bucket="gt_10"} 3698
telemt_pool_swap_total 50
telemt_pool_force_close_total 1556
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 314
telemt_me_draining_writers_reap_progress_total 16502
telemt_me_writer_removed_unexpected_total 959
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2103
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15287
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1340
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 216
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14946
telemt_me_writer_teardown_success_total{mode="normal"} 17390
telemt_me_writer_teardown_noop_total 16509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33899
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 40.337529
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33899
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 314
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 687
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 5371294
telemt_user_connections_current{user="hello"} 5347
telemt_user_octets_from_client{user="hello"} 49302628928 (45.92 GB)
telemt_user_octets_to_client{user="hello"} 591156288755 (550.56 GB)
telemt_user_msgs_from_client{user="hello"} 126757
telemt_user_msgs_to_client{user="hello"} 447030
telemt_user_unique_ips_current{user="hello"} 1893
telemt_user_unique_ips_recent_window{user="hello"} 1046
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 48940.7 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2118239
telemt_connections_bad_total 263230
telemt_connections_current 3831
telemt_connections_me_current 3831
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 40980
telemt_upstream_connect_attempt_total 21627
telemt_upstream_connect_success_total 21412
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 21608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11012
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_reconnect_attempts_total 2089
telemt_me_reconnect_success_total 679
telemt_me_reader_eof_total 693
telemt_me_idle_close_by_peer_total 693
telemt_me_route_drop_no_conn_total 683013
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1600149
telemt_me_endpoint_quarantine_total 299
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 381
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
telemt_me_writers_active_current 83
telemt_desync_total 7373
telemt_desync_full_logged_total 2686
telemt_desync_suppressed_total 4687
telemt_desync_frames_bucket_total{bucket="1_2"} 1395
telemt_desync_frames_bucket_total{bucket="3_10"} 2993
telemt_desync_frames_bucket_total{bucket="gt_10"} 2985
telemt_pool_swap_total 50
telemt_pool_force_close_total 1335
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 101
telemt_me_draining_writers_reap_progress_total 17899
telemt_me_writer_removed_unexpected_total 670
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1653
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16939
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1225
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 110
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16564
telemt_me_writer_teardown_success_total{mode="normal"} 18592
telemt_me_writer_teardown_noop_total 17899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36491
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.611428
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36491
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 101
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 582
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 1592665
telemt_user_connections_current{user="hello"} 3831
telemt_user_octets_from_client{user="hello"} 28990565880 (27.00 GB)
telemt_user_octets_to_client{user="hello"} 732858297830 (682.53 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1584
telemt_user_unique_ips_recent_window{user="hello"} 448
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 48935.2 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3014445
telemt_connections_bad_total 168341
telemt_connections_current 2751
telemt_connections_me_current 2751
telemt_handshake_timeouts_total 1249497
telemt_upstream_connect_attempt_total 20232
telemt_upstream_connect_success_total 20198
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 20201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10842
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 282
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 540
telemt_me_reconnect_success_total 303
telemt_me_reader_eof_total 306
telemt_me_idle_close_by_peer_total 306
telemt_me_route_drop_no_conn_total 563865
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1425779
telemt_me_endpoint_quarantine_total 374
telemt_me_single_endpoint_shadow_rotate_total 386
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
telemt_me_writers_active_current 42
telemt_desync_total 7014
telemt_desync_full_logged_total 2484
telemt_desync_suppressed_total 4530
telemt_desync_frames_bucket_total{bucket="1_2"} 1242
telemt_desync_frames_bucket_total{bucket="3_10"} 2806
telemt_desync_frames_bucket_total{bucket="gt_10"} 2966
telemt_pool_swap_total 54
telemt_pool_force_close_total 1320
telemt_me_writer_close_signal_drop_total 104
telemt_me_draining_writers_reap_progress_total 18144
telemt_me_writer_removed_unexpected_total 295
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1157
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17302
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1302
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16824
telemt_me_writer_teardown_success_total{mode="normal"} 18459
telemt_me_writer_teardown_noop_total 18144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36603
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.952978
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36603
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 104
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 270
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1421367
telemt_user_connections_current{user="hello"} 2751
telemt_user_octets_from_client{user="hello"} 25399606856 (23.66 GB)
telemt_user_octets_to_client{user="hello"} 699765101392 (651.71 GB)
telemt_user_unique_ips_current{user="hello"} 1101
telemt_user_unique_ips_recent_window{user="hello"} 485
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 46926.8 (13h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 632098
telemt_connections_bad_total 22030
telemt_connections_current 757
telemt_connections_me_current 757
telemt_handshake_timeouts_total 235392
telemt_upstream_connect_attempt_total 22848
telemt_upstream_connect_success_total 22846
telemt_upstream_connect_attempts_per_request{bucket="1"} 22846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1018
telemt_me_reconnect_success_total 370
telemt_me_reader_eof_total 372
telemt_me_idle_close_by_peer_total 372
telemt_me_route_drop_no_conn_total 134336
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 326598
telemt_me_endpoint_quarantine_total 452
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 400
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
telemt_me_writers_active_current 41
telemt_desync_total 2116
telemt_desync_full_logged_total 839
telemt_desync_suppressed_total 1277
telemt_desync_frames_bucket_total{bucket="1_2"} 376
telemt_desync_frames_bucket_total{bucket="3_10"} 804
telemt_desync_frames_bucket_total{bucket="gt_10"} 936
telemt_pool_swap_total 52
telemt_pool_force_close_total 1112
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 68
telemt_me_draining_writers_reap_progress_total 20411
telemt_me_writer_removed_unexpected_total 353
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1476
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19292
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1109
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19299
telemt_me_writer_teardown_success_total{mode="normal"} 20768
telemt_me_writer_teardown_noop_total 20411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41179
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.942254
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41179
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 68
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 303
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 326743
telemt_user_connections_current{user="hello"} 757
telemt_user_octets_from_client{user="hello"} 4881734271 (4.55 GB)
telemt_user_octets_to_client{user="hello"} 127949462653 (119.16 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 48944.8 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2236503
telemt_connections_bad_total 205485
telemt_connections_current 4077
telemt_connections_me_current 4077
telemt_handshake_timeouts_total 55479
telemt_upstream_connect_attempt_total 20974
telemt_upstream_connect_success_total 20884
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 20944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10407
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 827
telemt_me_reconnect_success_total 470
telemt_me_reader_eof_total 432
telemt_me_idle_close_by_peer_total 432
telemt_me_route_drop_no_conn_total 577636
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1760596
telemt_me_endpoint_quarantine_total 390
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 387
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
telemt_me_writers_active_current 49
telemt_desync_total 6895
telemt_desync_full_logged_total 2308
telemt_desync_suppressed_total 4587
telemt_desync_frames_bucket_total{bucket="1_2"} 1677
telemt_desync_frames_bucket_total{bucket="3_10"} 2566
telemt_desync_frames_bucket_total{bucket="gt_10"} 2652
telemt_pool_swap_total 54
telemt_pool_force_close_total 1342
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 132
telemt_me_draining_writers_reap_progress_total 18869
telemt_me_writer_removed_unexpected_total 428
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1421
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17888
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1319
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17527
telemt_me_writer_teardown_success_total{mode="normal"} 19309
telemt_me_writer_teardown_noop_total 18869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38178
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.758717
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38178
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 132
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 419
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 1754616
telemt_user_connections_current{user="hello"} 4077
telemt_user_octets_from_client{user="hello"} 39089789104 (36.41 GB)
telemt_user_octets_to_client{user="hello"} 822252470792 (765.78 GB)
telemt_user_unique_ips_current{user="hello"} 1386
telemt_user_unique_ips_recent_window{user="hello"} 532
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 48941.6 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2071160
telemt_connections_bad_total 169954
telemt_connections_current 3677
telemt_connections_me_current 3677
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 50611
telemt_upstream_connect_attempt_total 29558
telemt_upstream_connect_success_total 29343
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 29516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10919
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_reconnect_attempts_total 3031
telemt_me_reconnect_success_total 609
telemt_me_reader_eof_total 536
telemt_me_idle_close_by_peer_total 536
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 574212
telemt_me_route_drop_channel_closed_total 35
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1669034
telemt_me_endpoint_quarantine_total 430
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 384
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
telemt_desync_total 6412
telemt_desync_full_logged_total 2162
telemt_desync_suppressed_total 4250
telemt_desync_frames_bucket_total{bucket="1_2"} 1734
telemt_desync_frames_bucket_total{bucket="3_10"} 2384
telemt_desync_frames_bucket_total{bucket="gt_10"} 2294
telemt_pool_swap_total 53
telemt_pool_force_close_total 1319
telemt_me_writer_close_signal_drop_total 120
telemt_me_draining_writers_reap_progress_total 18102
telemt_me_writer_removed_unexpected_total 546
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1655
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17019
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1238
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16783
telemt_me_writer_teardown_success_total{mode="normal"} 18674
telemt_me_writer_teardown_noop_total 18103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36777
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.502347
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36777
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 120
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 471
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 1672622
telemt_user_connections_current{user="hello"} 3677
telemt_user_octets_from_client{user="hello"} 28012348455 (26.09 GB)
telemt_user_octets_to_client{user="hello"} 745266881595 (694.08 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1319
telemt_user_unique_ips_recent_window{user="hello"} 479
```
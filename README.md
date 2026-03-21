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

# Server Metrics 2026-03-21 10:58:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 51739.6 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1532923
telemt_connections_bad_total 77738
telemt_connections_current 1467
telemt_connections_me_current 1467
telemt_handshake_timeouts_total 61446
telemt_upstream_connect_attempt_total 20307
telemt_upstream_connect_success_total 20201
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 20269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12907
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 989
telemt_me_reconnect_success_total 432
telemt_me_reader_eof_total 431
telemt_me_idle_close_by_peer_total 431
telemt_me_route_drop_no_conn_total 882568
telemt_me_route_drop_channel_closed_total 333
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1171458
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 360
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 412
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
telemt_me_writers_active_current 43
telemt_desync_total 4830
telemt_desync_full_logged_total 1684
telemt_desync_suppressed_total 3146
telemt_desync_frames_bucket_total{bucket="1_2"} 1002
telemt_desync_frames_bucket_total{bucket="3_10"} 1876
telemt_desync_frames_bucket_total{bucket="gt_10"} 1952
telemt_pool_swap_total 56
telemt_pool_force_close_total 1620
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 278
telemt_me_draining_writers_reap_progress_total 18148
telemt_me_writer_removed_unexpected_total 411
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1474
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16967
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1559
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16528
telemt_me_writer_teardown_success_total{mode="normal"} 18441
telemt_me_writer_teardown_noop_total 18150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36591
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 108.928682
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36591
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 278
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 381
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1170576
telemt_user_connections_current{user="hello"} 1467
telemt_user_octets_from_client{user="hello"} 16436757471 (15.31 GB)
telemt_user_octets_to_client{user="hello"} 326865427375 (304.42 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 521
telemt_user_unique_ips_recent_window{user="hello"} 259
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 51721.9 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3926040
telemt_connections_bad_total 388008
telemt_connections_current 4522
telemt_connections_me_current 4522
telemt_handshake_timeouts_total 113966
telemt_upstream_connect_attempt_total 18369
telemt_upstream_connect_success_total 18283
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 18342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10609
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_reconnect_attempts_total 1156
telemt_me_reconnect_success_total 426
telemt_me_reader_eof_total 420
telemt_me_idle_close_by_peer_total 419
telemt_me_route_drop_no_conn_total 1846960
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2729553
telemt_me_endpoint_quarantine_total 328
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 400
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
telemt_desync_total 11618
telemt_desync_full_logged_total 3869
telemt_desync_suppressed_total 7749
telemt_desync_frames_bucket_total{bucket="1_2"} 2375
telemt_desync_frames_bucket_total{bucket="3_10"} 4589
telemt_desync_frames_bucket_total{bucket="gt_10"} 4654
telemt_pool_swap_total 56
telemt_pool_force_close_total 1719
telemt_me_writer_close_signal_drop_total 214
telemt_me_draining_writers_reap_progress_total 16418
telemt_me_writer_removed_unexpected_total 393
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1540
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15258
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1616
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 103
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14699
telemt_me_writer_teardown_success_total{mode="normal"} 16798
telemt_me_writer_teardown_noop_total 16418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33216
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.047907
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33216
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 214
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 341
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 2724715
telemt_user_connections_current{user="hello"} 4522
telemt_user_octets_from_client{user="hello"} 37544962884 (34.97 GB)
telemt_user_octets_to_client{user="hello"} 897167659700 (835.55 GB)
telemt_user_unique_ips_current{user="hello"} 1708
telemt_user_unique_ips_recent_window{user="hello"} 663
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 51718.3 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2906756
telemt_connections_bad_total 325984
telemt_connections_current 3954
telemt_connections_me_current 3954
telemt_handshake_timeouts_total 106654
telemt_upstream_connect_attempt_total 19825
telemt_upstream_connect_success_total 19812
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 19813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 653
telemt_me_reconnect_success_total 367
telemt_me_reader_eof_total 383
telemt_me_idle_close_by_peer_total 383
telemt_me_route_drop_no_conn_total 1201509
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2299148
telemt_me_endpoint_quarantine_total 336
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 403
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
telemt_desync_total 9912
telemt_desync_full_logged_total 3413
telemt_desync_suppressed_total 6499
telemt_desync_frames_bucket_total{bucket="1_2"} 2051
telemt_desync_frames_bucket_total{bucket="3_10"} 3919
telemt_desync_frames_bucket_total{bucket="gt_10"} 3942
telemt_pool_swap_total 56
telemt_pool_force_close_total 1711
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 238
telemt_me_draining_writers_reap_progress_total 18052
telemt_me_writer_removed_unexpected_total 360
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1483
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16789
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 13
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1619
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 92
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16341
telemt_me_writer_teardown_success_total{mode="normal"} 18272
telemt_me_writer_teardown_noop_total 18065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36337
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.003260
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36337
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 238
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 329
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 2295800
telemt_user_connections_current{user="hello"} 3954
telemt_user_octets_from_client{user="hello"} 37090668304 (34.54 GB)
telemt_user_octets_to_client{user="hello"} 858180917844 (799.24 GB)
telemt_user_unique_ips_current{user="hello"} 1480
telemt_user_unique_ips_recent_window{user="hello"} 481
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 51719.5 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2414015
telemt_connections_bad_total 269226
telemt_connections_current 3487
telemt_connections_me_current 3487
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 100949
telemt_upstream_connect_attempt_total 24831
telemt_upstream_connect_success_total 24578
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 24708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11145
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 422
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1049
telemt_me_reconnect_success_total 476
telemt_me_reader_eof_total 440
telemt_me_idle_close_by_peer_total 440
telemt_me_route_drop_no_conn_total 704818
telemt_me_route_drop_channel_closed_total 56
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1699010
telemt_me_endpoint_quarantine_total 353
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 401
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
telemt_desync_total 7783
telemt_desync_full_logged_total 2661
telemt_desync_suppressed_total 5122
telemt_desync_frames_bucket_total{bucket="1_2"} 1952
telemt_desync_frames_bucket_total{bucket="3_10"} 3049
telemt_desync_frames_bucket_total{bucket="gt_10"} 2782
telemt_pool_swap_total 56
telemt_pool_force_close_total 1543
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 116
telemt_me_draining_writers_reap_progress_total 17898
telemt_me_writer_removed_unexpected_total 434
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1483
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16863
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1449
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 94
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16355
telemt_me_writer_teardown_success_total{mode="normal"} 18346
telemt_me_writer_teardown_noop_total 17899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36245
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.778275
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36245
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 116
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 398
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 1700666
telemt_user_connections_current{user="hello"} 3487
telemt_user_octets_from_client{user="hello"} 32823505661 (30.57 GB)
telemt_user_octets_to_client{user="hello"} 816360411839 (760.29 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1343
telemt_user_unique_ips_recent_window{user="hello"} 456
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 51683.5 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2358583
telemt_connections_bad_total 265273
telemt_connections_current 3031
telemt_connections_me_current 3031
telemt_handshake_timeouts_total 70452
telemt_upstream_connect_attempt_total 21193
telemt_upstream_connect_success_total 21140
telemt_upstream_connect_attempts_per_request{bucket="1"} 21140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11517
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 761
telemt_me_reconnect_success_total 511
telemt_me_reader_eof_total 457
telemt_me_idle_close_by_peer_total 457
telemt_me_route_drop_no_conn_total 683260
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1692030
telemt_me_endpoint_quarantine_total 400
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 397
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
telemt_desync_total 7951
telemt_desync_full_logged_total 2706
telemt_desync_suppressed_total 5245
telemt_desync_frames_bucket_total{bucket="1_2"} 2112
telemt_desync_frames_bucket_total{bucket="3_10"} 3021
telemt_desync_frames_bucket_total{bucket="gt_10"} 2818
telemt_pool_swap_total 55
telemt_pool_force_close_total 1519
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 145
telemt_me_draining_writers_reap_progress_total 19005
telemt_me_writer_removed_unexpected_total 433
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1490
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17979
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1406
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 113
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17486
telemt_me_writer_teardown_success_total{mode="normal"} 19469
telemt_me_writer_teardown_noop_total 19008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38477
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.057104
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38477
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 145
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 443
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1689370
telemt_user_connections_current{user="hello"} 3031
telemt_user_octets_from_client{user="hello"} 39237485404 (36.54 GB)
telemt_user_octets_to_client{user="hello"} 824257752036 (767.65 GB)
telemt_user_unique_ips_current{user="hello"} 1181
telemt_user_unique_ips_recent_window{user="hello"} 446
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 51722.7 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7345029
telemt_connections_bad_total 494728
telemt_connections_current 4980
telemt_connections_me_current 4980
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 264567
telemt_upstream_connect_attempt_total 63144
telemt_upstream_connect_success_total 59470
telemt_upstream_connect_fail_total 2939
telemt_upstream_connect_attempts_per_request{bucket="1"} 62409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2939
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3123
telemt_me_reconnect_success_total 1073
telemt_me_reader_eof_total 775
telemt_me_idle_close_by_peer_total 774
telemt_me_route_drop_no_conn_total 12442471
telemt_me_route_drop_channel_closed_total 50
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6115005
telemt_me_endpoint_quarantine_total 406
telemt_me_single_endpoint_outage_enter_total 57
telemt_me_single_endpoint_outage_exit_total 57
telemt_me_single_endpoint_outage_reconnect_attempt_total 120
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 120
telemt_me_single_endpoint_shadow_rotate_total 410
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 11820
telemt_desync_full_logged_total 3781
telemt_desync_suppressed_total 8039
telemt_desync_frames_bucket_total{bucket="1_2"} 2590
telemt_desync_frames_bucket_total{bucket="3_10"} 5168
telemt_desync_frames_bucket_total{bucket="gt_10"} 4062
telemt_pool_swap_total 52
telemt_pool_force_close_total 1631
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 337
telemt_me_draining_writers_reap_progress_total 17388
telemt_me_writer_removed_unexpected_total 1040
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2251
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16073
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1387
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 244
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15757
telemt_me_writer_teardown_success_total{mode="normal"} 18324
telemt_me_writer_teardown_noop_total 17397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35721
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 44.587773
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35721
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 337
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 754
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 6150939
telemt_user_connections_current{user="hello"} 4980
telemt_user_octets_from_client{user="hello"} 53123277652 (49.47 GB)
telemt_user_octets_to_client{user="hello"} 621766560183 (579.07 GB)
telemt_user_msgs_from_client{user="hello"} 129175
telemt_user_msgs_to_client{user="hello"} 449473
telemt_user_unique_ips_current{user="hello"} 1798
telemt_user_unique_ips_recent_window{user="hello"} 949
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 51690.3 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2354805
telemt_connections_bad_total 279627
telemt_connections_current 3633
telemt_connections_me_current 3633
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 48742
telemt_upstream_connect_attempt_total 22637
telemt_upstream_connect_success_total 22404
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 22615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11563
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_reconnect_attempts_total 2185
telemt_me_reconnect_success_total 716
telemt_me_reader_eof_total 722
telemt_me_idle_close_by_peer_total 722
telemt_me_route_drop_no_conn_total 805848
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1786573
telemt_me_endpoint_quarantine_total 325
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 400
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
telemt_me_writers_active_current 41
telemt_desync_total 8241
telemt_desync_full_logged_total 2983
telemt_desync_suppressed_total 5258
telemt_desync_frames_bucket_total{bucket="1_2"} 1577
telemt_desync_frames_bucket_total{bucket="3_10"} 3335
telemt_desync_frames_bucket_total{bucket="gt_10"} 3329
telemt_pool_swap_total 53
telemt_pool_force_close_total 1451
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 124
telemt_me_draining_writers_reap_progress_total 18834
telemt_me_writer_removed_unexpected_total 699
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1754
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17802
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1305
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 146
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17383
telemt_me_writer_teardown_success_total{mode="normal"} 19556
telemt_me_writer_teardown_noop_total 18834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38390
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.873055
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38390
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 124
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 607
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 1772475
telemt_user_connections_current{user="hello"} 3633
telemt_user_octets_from_client{user="hello"} 32702450972 (30.46 GB)
telemt_user_octets_to_client{user="hello"} 803753376050 (748.55 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1432
telemt_user_unique_ips_recent_window{user="hello"} 455
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 51684.7 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3452747
telemt_connections_bad_total 183948
telemt_connections_current 3064
telemt_connections_me_current 3064
telemt_handshake_timeouts_total 1466101
telemt_upstream_connect_attempt_total 21032
telemt_upstream_connect_success_total 20998
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 21001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 692
telemt_me_reconnect_success_total 342
telemt_me_reader_eof_total 338
telemt_me_idle_close_by_peer_total 338
telemt_me_route_drop_no_conn_total 636062
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1590550
telemt_me_endpoint_quarantine_total 402
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 409
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
telemt_me_writers_active_current 43
telemt_desync_total 7759
telemt_desync_full_logged_total 2775
telemt_desync_suppressed_total 4984
telemt_desync_frames_bucket_total{bucket="1_2"} 1402
telemt_desync_frames_bucket_total{bucket="3_10"} 3093
telemt_desync_frames_bucket_total{bucket="gt_10"} 3264
telemt_pool_swap_total 57
telemt_pool_force_close_total 1407
telemt_me_writer_close_signal_drop_total 112
telemt_me_draining_writers_reap_progress_total 18836
telemt_me_writer_removed_unexpected_total 326
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1228
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17955
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1386
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17429
telemt_me_writer_teardown_success_total{mode="normal"} 19183
telemt_me_writer_teardown_noop_total 18836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38019
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.030705
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38019
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 112
telemt_me_refill_failed_total 19
telemt_me_writer_restored_same_endpoint_total 294
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 1585885
telemt_user_connections_current{user="hello"} 3064
telemt_user_octets_from_client{user="hello"} 28371008088 (26.42 GB)
telemt_user_octets_to_client{user="hello"} 771897625036 (718.89 GB)
telemt_user_unique_ips_current{user="hello"} 1246
telemt_user_unique_ips_recent_window{user="hello"} 488
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 49676.4 (13h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 702772
telemt_connections_bad_total 22757
telemt_connections_current 687
telemt_connections_me_current 687
telemt_handshake_timeouts_total 262751
telemt_upstream_connect_attempt_total 24051
telemt_upstream_connect_success_total 24049
telemt_upstream_connect_attempts_per_request{bucket="1"} 24049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14015
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1058
telemt_me_reconnect_success_total 387
telemt_me_reader_eof_total 387
telemt_me_idle_close_by_peer_total 387
telemt_me_route_drop_no_conn_total 151155
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360065
telemt_me_endpoint_quarantine_total 472
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 422
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
telemt_desync_total 2376
telemt_desync_full_logged_total 931
telemt_desync_suppressed_total 1445
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 863
telemt_desync_frames_bucket_total{bucket="gt_10"} 1124
telemt_pool_swap_total 55
telemt_pool_force_close_total 1188
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 21506
telemt_me_writer_removed_unexpected_total 368
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1561
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20317
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1185
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20318
telemt_me_writer_teardown_success_total{mode="normal"} 21878
telemt_me_writer_teardown_noop_total 21506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43384
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.322545
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43384
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 315
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 360185
telemt_user_connections_current{user="hello"} 687
telemt_user_octets_from_client{user="hello"} 5365622527 (5.00 GB)
telemt_user_octets_to_client{user="hello"} 139145664773 (129.59 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 274
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 51694.6 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2503413
telemt_connections_bad_total 234517
telemt_connections_current 4247
telemt_connections_me_current 4247
telemt_handshake_timeouts_total 60470
telemt_upstream_connect_attempt_total 21951
telemt_upstream_connect_success_total 21857
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 21921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10911
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_reconnect_attempts_total 863
telemt_me_reconnect_success_total 488
telemt_me_reader_eof_total 453
telemt_me_idle_close_by_peer_total 453
telemt_me_route_drop_no_conn_total 655337
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1976625
telemt_me_endpoint_quarantine_total 408
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 406
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
telemt_desync_total 7773
telemt_desync_full_logged_total 2613
telemt_desync_suppressed_total 5160
telemt_desync_frames_bucket_total{bucket="1_2"} 1884
telemt_desync_frames_bucket_total{bucket="3_10"} 2921
telemt_desync_frames_bucket_total{bucket="gt_10"} 2968
telemt_pool_swap_total 57
telemt_pool_force_close_total 1425
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 145
telemt_me_draining_writers_reap_progress_total 19752
telemt_me_writer_removed_unexpected_total 447
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1489
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18724
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1401
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18327
telemt_me_writer_teardown_success_total{mode="normal"} 20213
telemt_me_writer_teardown_noop_total 19752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39965
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.209340
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39965
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 145
telemt_me_refill_failed_total 19
telemt_me_writer_restored_same_endpoint_total 436
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1970498
telemt_user_connections_current{user="hello"} 4247
telemt_user_octets_from_client{user="hello"} 42245136044 (39.34 GB)
telemt_user_octets_to_client{user="hello"} 924552166004 (861.06 GB)
telemt_user_unique_ips_current{user="hello"} 1501
telemt_user_unique_ips_recent_window{user="hello"} 513
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 51691.4 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2290518
telemt_connections_bad_total 181503
telemt_connections_current 3360
telemt_connections_me_current 3360
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 56642
telemt_upstream_connect_attempt_total 38132
telemt_upstream_connect_success_total 37900
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 38089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12561
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 581
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_reconnect_attempts_total 3149
telemt_me_reconnect_success_total 646
telemt_me_reader_eof_total 565
telemt_me_idle_close_by_peer_total 565
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 650784
telemt_me_route_drop_channel_closed_total 43
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1851427
telemt_me_endpoint_quarantine_total 455
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 406
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
telemt_desync_total 6937
telemt_desync_full_logged_total 2367
telemt_desync_suppressed_total 4570
telemt_desync_frames_bucket_total{bucket="1_2"} 1836
telemt_desync_frames_bucket_total{bucket="3_10"} 2576
telemt_desync_frames_bucket_total{bucket="gt_10"} 2525
telemt_pool_swap_total 56
telemt_pool_force_close_total 1375
telemt_me_writer_close_signal_drop_total 126
telemt_me_draining_writers_reap_progress_total 18938
telemt_me_writer_removed_unexpected_total 575
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1757
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17783
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1289
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 86
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17563
telemt_me_writer_teardown_success_total{mode="normal"} 19540
telemt_me_writer_teardown_noop_total 18939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38479
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.580593
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38479
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 126
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 492
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 1862447
telemt_user_connections_current{user="hello"} 3360
telemt_user_octets_from_client{user="hello"} 33848613265 (31.52 GB)
telemt_user_octets_to_client{user="hello"} 824039461292 (767.45 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1265
telemt_user_unique_ips_recent_window{user="hello"} 493
```
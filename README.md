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

# Server Metrics 2026-03-21 10:47:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 51111.6 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1501291
telemt_connections_bad_total 76584
telemt_connections_current 2151
telemt_connections_me_current 2151
telemt_handshake_timeouts_total 60192
telemt_upstream_connect_attempt_total 20055
telemt_upstream_connect_success_total 19965
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 20031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12771
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 961
telemt_me_reconnect_success_total 421
telemt_me_reader_eof_total 419
telemt_me_idle_close_by_peer_total 419
telemt_me_route_drop_no_conn_total 821612
telemt_me_route_drop_channel_closed_total 317
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1147372
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 356
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 407
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
telemt_desync_total 4776
telemt_desync_full_logged_total 1666
telemt_desync_suppressed_total 3110
telemt_desync_frames_bucket_total{bucket="1_2"} 988
telemt_desync_frames_bucket_total{bucket="3_10"} 1857
telemt_desync_frames_bucket_total{bucket="gt_10"} 1931
telemt_pool_swap_total 55
telemt_pool_force_close_total 1577
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 269
telemt_me_draining_writers_reap_progress_total 17939
telemt_me_writer_removed_unexpected_total 397
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1449
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16783
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1516
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16362
telemt_me_writer_teardown_success_total{mode="normal"} 18232
telemt_me_writer_teardown_noop_total 17941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36173
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 102.603452
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36173
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 269
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 371
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1146448
telemt_user_connections_current{user="hello"} 2151
telemt_user_octets_from_client{user="hello"} 16064618111 (14.96 GB)
telemt_user_octets_to_client{user="hello"} 322343253787 (300.21 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 629
telemt_user_unique_ips_recent_window{user="hello"} 422
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 51112.8 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3856782
telemt_connections_bad_total 385434
telemt_connections_current 4755
telemt_connections_me_current 4755
telemt_handshake_timeouts_total 112378
telemt_upstream_connect_attempt_total 18158
telemt_upstream_connect_success_total 18073
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 18131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1110
telemt_me_reconnect_success_total 421
telemt_me_reader_eof_total 415
telemt_me_idle_close_by_peer_total 414
telemt_me_route_drop_no_conn_total 1805860
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2667782
telemt_me_endpoint_quarantine_total 321
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 393
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
telemt_desync_total 11360
telemt_desync_full_logged_total 3802
telemt_desync_suppressed_total 7558
telemt_desync_frames_bucket_total{bucket="1_2"} 2324
telemt_desync_frames_bucket_total{bucket="3_10"} 4493
telemt_desync_frames_bucket_total{bucket="gt_10"} 4543
telemt_pool_swap_total 55
telemt_pool_force_close_total 1687
telemt_me_writer_close_signal_drop_total 210
telemt_me_draining_writers_reap_progress_total 16229
telemt_me_writer_removed_unexpected_total 388
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1523
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15081
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1587
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 100
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14542
telemt_me_writer_teardown_success_total{mode="normal"} 16604
telemt_me_writer_teardown_noop_total 16229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32833
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.933681
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32833
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 210
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 338
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 2663009
telemt_user_connections_current{user="hello"} 4755
telemt_user_octets_from_client{user="hello"} 36633535608 (34.12 GB)
telemt_user_octets_to_client{user="hello"} 880663199020 (820.18 GB)
telemt_user_unique_ips_current{user="hello"} 1735
telemt_user_unique_ips_recent_window{user="hello"} 690
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 51109.2 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2848641
telemt_connections_bad_total 321989
telemt_connections_current 4189
telemt_connections_me_current 4189
telemt_handshake_timeouts_total 104691
telemt_upstream_connect_attempt_total 19615
telemt_upstream_connect_success_total 19602
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 19603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 634
telemt_me_reconnect_success_total 364
telemt_me_reader_eof_total 379
telemt_me_idle_close_by_peer_total 379
telemt_me_route_drop_no_conn_total 1174685
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2249037
telemt_me_endpoint_quarantine_total 334
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 396
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
telemt_desync_total 9694
telemt_desync_full_logged_total 3338
telemt_desync_suppressed_total 6356
telemt_desync_frames_bucket_total{bucket="1_2"} 2002
telemt_desync_frames_bucket_total{bucket="3_10"} 3841
telemt_desync_frames_bucket_total{bucket="gt_10"} 3851
telemt_pool_swap_total 55
telemt_pool_force_close_total 1681
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 232
telemt_me_draining_writers_reap_progress_total 17865
telemt_me_writer_removed_unexpected_total 356
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1464
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16617
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 13
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1591
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 90
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16184
telemt_me_writer_teardown_success_total{mode="normal"} 18081
telemt_me_writer_teardown_noop_total 17878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35959
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 43.363707
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35959
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 232
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 326
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 2245741
telemt_user_connections_current{user="hello"} 4189
telemt_user_octets_from_client{user="hello"} 36547829996 (34.04 GB)
telemt_user_octets_to_client{user="hello"} 840900503696 (783.15 GB)
telemt_user_unique_ips_current{user="hello"} 1585
telemt_user_unique_ips_recent_window{user="hello"} 583
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 51110.6 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2359199
telemt_connections_bad_total 265366
telemt_connections_current 3599
telemt_connections_me_current 3599
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 99476
telemt_upstream_connect_attempt_total 24638
telemt_upstream_connect_success_total 24386
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 24515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11051
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 422
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1045
telemt_me_reconnect_success_total 472
telemt_me_reader_eof_total 436
telemt_me_idle_close_by_peer_total 436
telemt_me_route_drop_no_conn_total 690112
telemt_me_route_drop_channel_closed_total 55
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1656824
telemt_me_endpoint_quarantine_total 349
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 398
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
telemt_desync_total 7596
telemt_desync_full_logged_total 2604
telemt_desync_suppressed_total 4992
telemt_desync_frames_bucket_total{bucket="1_2"} 1900
telemt_desync_frames_bucket_total{bucket="3_10"} 2983
telemt_desync_frames_bucket_total{bucket="gt_10"} 2713
telemt_pool_swap_total 55
telemt_pool_force_close_total 1514
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 107
telemt_me_draining_writers_reap_progress_total 17717
telemt_me_writer_removed_unexpected_total 430
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1454
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16707
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1423
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 91
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16203
telemt_me_writer_teardown_success_total{mode="normal"} 18161
telemt_me_writer_teardown_noop_total 17718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35879
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.918635
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35879
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 107
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 395
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1658558
telemt_user_connections_current{user="hello"} 3599
telemt_user_octets_from_client{user="hello"} 32324240277 (30.10 GB)
telemt_user_octets_to_client{user="hello"} 797363770263 (742.60 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1385
telemt_user_unique_ips_recent_window{user="hello"} 493
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 51074.4 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2306358
telemt_connections_bad_total 257804
telemt_connections_current 3185
telemt_connections_me_current 3185
telemt_handshake_timeouts_total 69428
telemt_upstream_connect_attempt_total 20985
telemt_upstream_connect_success_total 20933
telemt_upstream_connect_attempts_per_request{bucket="1"} 20933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11410
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 746
telemt_me_reconnect_success_total 502
telemt_me_reader_eof_total 452
telemt_me_idle_close_by_peer_total 452
telemt_me_route_drop_no_conn_total 664486
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1654983
telemt_me_endpoint_quarantine_total 393
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 392
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
telemt_desync_total 7801
telemt_desync_full_logged_total 2660
telemt_desync_suppressed_total 5141
telemt_desync_frames_bucket_total{bucket="1_2"} 2077
telemt_desync_frames_bucket_total{bucket="3_10"} 2964
telemt_desync_frames_bucket_total{bucket="gt_10"} 2760
telemt_pool_swap_total 54
telemt_pool_force_close_total 1489
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 138
telemt_me_draining_writers_reap_progress_total 18807
telemt_me_writer_removed_unexpected_total 428
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1465
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17801
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1376
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 113
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17318
telemt_me_writer_teardown_success_total{mode="normal"} 19266
telemt_me_writer_teardown_noop_total 18810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38076
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.726892
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38076
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 138
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 438
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1652413
telemt_user_connections_current{user="hello"} 3185
telemt_user_octets_from_client{user="hello"} 38753038068 (36.09 GB)
telemt_user_octets_to_client{user="hello"} 807043266252 (751.62 GB)
telemt_user_unique_ips_current{user="hello"} 1229
telemt_user_unique_ips_recent_window{user="hello"} 492
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 51113.7 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7130088
telemt_connections_bad_total 458620
telemt_connections_current 5040
telemt_connections_me_current 5040
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 258847
telemt_upstream_connect_attempt_total 60199
telemt_upstream_connect_success_total 57523
telemt_upstream_connect_fail_total 1950
telemt_upstream_connect_attempts_per_request{bucket="1"} 59473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14934
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2056
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1950
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 2985
telemt_me_reconnect_success_total 1052
telemt_me_reader_eof_total 757
telemt_me_idle_close_by_peer_total 756
telemt_me_route_drop_no_conn_total 12071401
telemt_me_route_drop_channel_closed_total 46
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5955655
telemt_me_endpoint_quarantine_total 392
telemt_me_single_endpoint_outage_enter_total 55
telemt_me_single_endpoint_outage_exit_total 55
telemt_me_single_endpoint_outage_reconnect_attempt_total 117
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 117
telemt_me_single_endpoint_shadow_rotate_total 404
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_me_writers_active_current 79
telemt_desync_total 11593
telemt_desync_full_logged_total 3705
telemt_desync_suppressed_total 7888
telemt_desync_frames_bucket_total{bucket="1_2"} 2545
telemt_desync_frames_bucket_total{bucket="3_10"} 5078
telemt_desync_frames_bucket_total{bucket="gt_10"} 3970
telemt_pool_swap_total 51
telemt_pool_force_close_total 1607
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 321
telemt_me_draining_writers_reap_progress_total 17092
telemt_me_writer_removed_unexpected_total 1022
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2196
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15829
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1387
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 220
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15485
telemt_me_writer_teardown_success_total{mode="normal"} 18025
telemt_me_writer_teardown_noop_total 17101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35126
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 42.235350
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35126
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 321
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 742
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 5990013
telemt_user_connections_current{user="hello"} 5040
telemt_user_octets_from_client{user="hello"} 52133648028 (48.55 GB)
telemt_user_octets_to_client{user="hello"} 614910135523 (572.68 GB)
telemt_user_msgs_from_client{user="hello"} 126757
telemt_user_msgs_to_client{user="hello"} 447030
telemt_user_unique_ips_current{user="hello"} 1824
telemt_user_unique_ips_recent_window{user="hello"} 885
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 51081.2 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2304888
telemt_connections_bad_total 275977
telemt_connections_current 3520
telemt_connections_me_current 3520
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 47573
telemt_upstream_connect_attempt_total 22432
telemt_upstream_connect_success_total 22202
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 22410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11452
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_reconnect_attempts_total 2115
telemt_me_reconnect_success_total 704
telemt_me_reader_eof_total 713
telemt_me_idle_close_by_peer_total 713
telemt_me_route_drop_no_conn_total 789755
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1745246
telemt_me_endpoint_quarantine_total 314
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 393
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
telemt_me_writers_active_current 46
telemt_desync_total 8040
telemt_desync_full_logged_total 2920
telemt_desync_suppressed_total 5120
telemt_desync_frames_bucket_total{bucket="1_2"} 1538
telemt_desync_frames_bucket_total{bucket="3_10"} 3254
telemt_desync_frames_bucket_total{bucket="gt_10"} 3248
telemt_pool_swap_total 52
telemt_pool_force_close_total 1420
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 118
telemt_me_draining_writers_reap_progress_total 18638
telemt_me_writer_removed_unexpected_total 690
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1724
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17627
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1276
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 144
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17218
telemt_me_writer_teardown_success_total{mode="normal"} 19351
telemt_me_writer_teardown_noop_total 18638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37989
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.774826
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37989
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 118
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 601
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 1731248
telemt_user_connections_current{user="hello"} 3520
telemt_user_octets_from_client{user="hello"} 31868615296 (29.68 GB)
telemt_user_octets_to_client{user="hello"} 789298635686 (735.09 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1416
telemt_user_unique_ips_recent_window{user="hello"} 545
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 51075.7 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3363957
telemt_connections_bad_total 179332
telemt_connections_current 3497
telemt_connections_me_current 3497
telemt_handshake_timeouts_total 1428035
telemt_upstream_connect_attempt_total 20822
telemt_upstream_connect_success_total 20788
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 20791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 283
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 615
telemt_me_reconnect_success_total 312
telemt_me_reader_eof_total 319
telemt_me_idle_close_by_peer_total 319
telemt_me_route_drop_no_conn_total 622302
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1554010
telemt_me_endpoint_quarantine_total 384
telemt_me_single_endpoint_shadow_rotate_total 403
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
telemt_desync_total 7628
telemt_desync_full_logged_total 2714
telemt_desync_suppressed_total 4914
telemt_desync_frames_bucket_total{bucket="1_2"} 1366
telemt_desync_frames_bucket_total{bucket="3_10"} 3045
telemt_desync_frames_bucket_total{bucket="gt_10"} 3217
telemt_pool_swap_total 56
telemt_pool_force_close_total 1379
telemt_me_writer_close_signal_drop_total 106
telemt_me_draining_writers_reap_progress_total 18670
telemt_me_writer_removed_unexpected_total 307
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1189
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17809
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1361
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17291
telemt_me_writer_teardown_success_total{mode="normal"} 18998
telemt_me_writer_teardown_noop_total 18670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37668
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.016464
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37668
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 106
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 278
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1549420
telemt_user_connections_current{user="hello"} 3497
telemt_user_octets_from_client{user="hello"} 27714230568 (25.81 GB)
telemt_user_octets_to_client{user="hello"} 755886553856 (703.97 GB)
telemt_user_unique_ips_current{user="hello"} 1343
telemt_user_unique_ips_recent_window{user="hello"} 513
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 49067.4 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 686454
telemt_connections_bad_total 22552
telemt_connections_current 656
telemt_connections_me_current 656
telemt_handshake_timeouts_total 255753
telemt_upstream_connect_attempt_total 23771
telemt_upstream_connect_success_total 23769
telemt_upstream_connect_attempts_per_request{bucket="1"} 23769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13852
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1039
telemt_me_reconnect_success_total 386
telemt_me_reader_eof_total 386
telemt_me_idle_close_by_peer_total 386
telemt_me_route_drop_no_conn_total 147431
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 352976
telemt_me_endpoint_quarantine_total 463
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 421
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_me_writers_active_current 46
telemt_desync_total 2300
telemt_desync_full_logged_total 905
telemt_desync_suppressed_total 1395
telemt_desync_frames_bucket_total{bucket="1_2"} 385
telemt_desync_frames_bucket_total{bucket="3_10"} 845
telemt_desync_frames_bucket_total{bucket="gt_10"} 1070
telemt_pool_swap_total 54
telemt_pool_force_close_total 1188
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 21254
telemt_me_writer_removed_unexpected_total 367
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1549
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20076
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1185
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20066
telemt_me_writer_teardown_success_total{mode="normal"} 21625
telemt_me_writer_teardown_noop_total 21254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42879
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.283968
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42879
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 315
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 353097
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 5250713191 (4.89 GB)
telemt_user_octets_to_client{user="hello"} 135928310797 (126.59 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 51085.8 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2442976
telemt_connections_bad_total 226211
telemt_connections_current 4149
telemt_connections_me_current 4149
telemt_handshake_timeouts_total 59262
telemt_upstream_connect_attempt_total 21713
telemt_upstream_connect_success_total 21619
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 21683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10788
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_reconnect_attempts_total 859
telemt_me_reconnect_success_total 484
telemt_me_reader_eof_total 449
telemt_me_idle_close_by_peer_total 449
telemt_me_route_drop_no_conn_total 638949
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1928822
telemt_me_endpoint_quarantine_total 402
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 400
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
telemt_me_writers_active_current 44
telemt_desync_total 7569
telemt_desync_full_logged_total 2546
telemt_desync_suppressed_total 5023
telemt_desync_frames_bucket_total{bucket="1_2"} 1829
telemt_desync_frames_bucket_total{bucket="3_10"} 2856
telemt_desync_frames_bucket_total{bucket="gt_10"} 2884
telemt_pool_swap_total 56
telemt_pool_force_close_total 1401
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 139
telemt_me_draining_writers_reap_progress_total 19527
telemt_me_writer_removed_unexpected_total 443
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1465
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18519
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1377
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18126
telemt_me_writer_teardown_success_total{mode="normal"} 19984
telemt_me_writer_teardown_noop_total 19527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39511
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.107793
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39511
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 139
telemt_me_refill_failed_total 19
telemt_me_writer_restored_same_endpoint_total 433
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1922740
telemt_user_connections_current{user="hello"} 4149
telemt_user_octets_from_client{user="hello"} 41533331660 (38.68 GB)
telemt_user_octets_to_client{user="hello"} 901956459244 (840.01 GB)
telemt_user_unique_ips_current{user="hello"} 1462
telemt_user_unique_ips_recent_window{user="hello"} 593
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 51082.5 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2241804
telemt_connections_bad_total 177978
telemt_connections_current 3676
telemt_connections_me_current 3676
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 55165
telemt_upstream_connect_attempt_total 37915
telemt_upstream_connect_success_total 37691
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 37872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12456
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 580
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_reconnect_attempts_total 3093
telemt_me_reconnect_success_total 628
telemt_me_reader_eof_total 554
telemt_me_idle_close_by_peer_total 554
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 636877
telemt_me_route_drop_channel_closed_total 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1810265
telemt_me_endpoint_quarantine_total 443
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 399
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
telemt_desync_total 6794
telemt_desync_full_logged_total 2316
telemt_desync_suppressed_total 4478
telemt_desync_frames_bucket_total{bucket="1_2"} 1813
telemt_desync_frames_bucket_total{bucket="3_10"} 2515
telemt_desync_frames_bucket_total{bucket="gt_10"} 2466
telemt_pool_swap_total 55
telemt_pool_force_close_total 1350
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 18739
telemt_me_writer_removed_unexpected_total 564
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1725
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17605
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1267
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17389
telemt_me_writer_teardown_success_total{mode="normal"} 19330
telemt_me_writer_teardown_noop_total 18740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38070
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.553400
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38070
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 485
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 1821384
telemt_user_connections_current{user="hello"} 3676
telemt_user_octets_from_client{user="hello"} 33174763961 (30.90 GB)
telemt_user_octets_to_client{user="hello"} 807174053480 (751.74 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1369
telemt_user_unique_ips_recent_window{user="hello"} 513
```
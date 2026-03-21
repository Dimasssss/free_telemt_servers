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

# Server Metrics 2026-03-21 10:01:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 48360.8 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1374172
telemt_connections_bad_total 71059
telemt_connections_current 1691
telemt_connections_me_current 1691
telemt_handshake_timeouts_total 55683
telemt_upstream_connect_attempt_total 19119
telemt_upstream_connect_success_total 19038
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 19095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 868
telemt_me_reconnect_success_total 372
telemt_me_reader_eof_total 383
telemt_me_idle_close_by_peer_total 383
telemt_me_route_drop_no_conn_total 745064
telemt_me_route_drop_channel_closed_total 265
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1042098
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
telemt_desync_total 4372
telemt_desync_full_logged_total 1510
telemt_desync_suppressed_total 2862
telemt_desync_frames_bucket_total{bucket="1_2"} 919
telemt_desync_frames_bucket_total{bucket="3_10"} 1695
telemt_desync_frames_bucket_total{bucket="gt_10"} 1758
telemt_pool_swap_total 52
telemt_pool_force_close_total 1485
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 225
telemt_me_draining_writers_reap_progress_total 17126
telemt_me_writer_removed_unexpected_total 362
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1356
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16030
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1432
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15641
telemt_me_writer_teardown_success_total{mode="normal"} 17386
telemt_me_writer_teardown_noop_total 17128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34514
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 86.862908
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34514
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 225
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 332
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1041294
telemt_user_connections_current{user="hello"} 1691
telemt_user_octets_from_client{user="hello"} 14720015831 (13.71 GB)
telemt_user_octets_to_client{user="hello"} 297414642259 (276.99 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 580
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 48362.2 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3512466
telemt_connections_bad_total 370641
telemt_connections_current 4706
telemt_connections_me_current 4706
telemt_handshake_timeouts_total 102545
telemt_upstream_connect_attempt_total 17310
telemt_upstream_connect_success_total 17231
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 17285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10020
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_reconnect_attempts_total 1033
telemt_me_reconnect_success_total 387
telemt_me_reader_eof_total 384
telemt_me_idle_close_by_peer_total 383
telemt_me_route_drop_no_conn_total 1495296
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2370158
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
telemt_desync_total 10258
telemt_desync_full_logged_total 3447
telemt_desync_suppressed_total 6811
telemt_desync_frames_bucket_total{bucket="1_2"} 2098
telemt_desync_frames_bucket_total{bucket="3_10"} 4047
telemt_desync_frames_bucket_total{bucket="gt_10"} 4113
telemt_pool_swap_total 52
telemt_pool_force_close_total 1595
telemt_me_writer_close_signal_drop_total 190
telemt_me_draining_writers_reap_progress_total 15478
telemt_me_writer_removed_unexpected_total 360
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1432
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14390
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1500
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 95
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13883
telemt_me_writer_teardown_success_total{mode="normal"} 15822
telemt_me_writer_teardown_noop_total 15478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31300
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.884215
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31300
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 190
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 311
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2365785
telemt_user_connections_current{user="hello"} 4706
telemt_user_octets_from_client{user="hello"} 33474335064 (31.18 GB)
telemt_user_octets_to_client{user="hello"} 802408233604 (747.30 GB)
telemt_user_unique_ips_current{user="hello"} 1725
telemt_user_unique_ips_recent_window{user="hello"} 728
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 48358.5 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2577583
telemt_connections_bad_total 303751
telemt_connections_current 4417
telemt_connections_me_current 4417
telemt_handshake_timeouts_total 96604
telemt_upstream_connect_attempt_total 18799
telemt_upstream_connect_success_total 18787
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 18788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 627
telemt_me_reconnect_success_total 357
telemt_me_reader_eof_total 371
telemt_me_idle_close_by_peer_total 371
telemt_me_route_drop_no_conn_total 1046054
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2018528
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
telemt_desync_total 8807
telemt_desync_full_logged_total 3027
telemt_desync_suppressed_total 5780
telemt_desync_frames_bucket_total{bucket="1_2"} 1851
telemt_desync_frames_bucket_total{bucket="3_10"} 3492
telemt_desync_frames_bucket_total{bucket="gt_10"} 3464
telemt_pool_swap_total 52
telemt_pool_force_close_total 1562
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 209
telemt_me_draining_writers_reap_progress_total 17090
telemt_me_writer_removed_unexpected_total 350
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1412
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15910
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1477
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15528
telemt_me_writer_teardown_success_total{mode="normal"} 17322
telemt_me_writer_teardown_noop_total 17101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34423
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 37.879563
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34423
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 209
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 320
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 2015348
telemt_user_connections_current{user="hello"} 4417
telemt_user_octets_from_client{user="hello"} 31676211020 (29.50 GB)
telemt_user_octets_to_client{user="hello"} 762066371172 (709.73 GB)
telemt_user_unique_ips_current{user="hello"} 1656
telemt_user_unique_ips_recent_window{user="hello"} 711
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 48359.8 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2111297
telemt_connections_bad_total 240321
telemt_connections_current 3708
telemt_connections_me_current 3708
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 90199
telemt_upstream_connect_attempt_total 23742
telemt_upstream_connect_success_total 23505
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 23631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10597
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 390
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 1018
telemt_me_reconnect_success_total 444
telemt_me_reader_eof_total 412
telemt_me_idle_close_by_peer_total 412
telemt_me_route_drop_no_conn_total 612390
telemt_me_route_drop_channel_closed_total 44
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1476233
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
telemt_desync_total 6901
telemt_desync_full_logged_total 2370
telemt_desync_suppressed_total 4531
telemt_desync_frames_bucket_total{bucket="1_2"} 1702
telemt_desync_frames_bucket_total{bucket="3_10"} 2737
telemt_desync_frames_bucket_total{bucket="gt_10"} 2462
telemt_pool_swap_total 52
telemt_pool_force_close_total 1415
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 92
telemt_me_draining_writers_reap_progress_total 16971
telemt_me_writer_removed_unexpected_total 405
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1368
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16022
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1333
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 82
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15556
telemt_me_writer_teardown_success_total{mode="normal"} 17390
telemt_me_writer_teardown_noop_total 16972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34362
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.624430
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34362
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 92
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 374
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1478181
telemt_user_connections_current{user="hello"} 3708
telemt_user_octets_from_client{user="hello"} 29635188445 (27.60 GB)
telemt_user_octets_to_client{user="hello"} 710896165791 (662.07 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1406
telemt_user_unique_ips_recent_window{user="hello"} 572
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 48323.6 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2046746
telemt_connections_bad_total 226510
telemt_connections_current 3579
telemt_connections_me_current 3579
telemt_handshake_timeouts_total 64315
telemt_upstream_connect_attempt_total 20092
telemt_upstream_connect_success_total 20052
telemt_upstream_connect_attempts_per_request{bucket="1"} 20052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10952
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 630
telemt_me_reconnect_success_total 451
telemt_me_reader_eof_total 413
telemt_me_idle_close_by_peer_total 413
telemt_me_route_drop_no_conn_total 567682
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1474220
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
telemt_me_writers_active_current 44
telemt_desync_total 6919
telemt_desync_full_logged_total 2384
telemt_desync_suppressed_total 4535
telemt_desync_frames_bucket_total{bucket="1_2"} 1834
telemt_desync_frames_bucket_total{bucket="3_10"} 2659
telemt_desync_frames_bucket_total{bucket="gt_10"} 2426
telemt_pool_swap_total 51
telemt_pool_force_close_total 1398
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 127
telemt_me_draining_writers_reap_progress_total 18074
telemt_me_writer_removed_unexpected_total 388
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1365
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17127
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1289
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 109
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16676
telemt_me_writer_teardown_success_total{mode="normal"} 18492
telemt_me_writer_teardown_noop_total 18077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36569
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.223122
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36569
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 127
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 403
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1471819
telemt_user_connections_current{user="hello"} 3579
telemt_user_octets_from_client{user="hello"} 34609940524 (32.23 GB)
telemt_user_octets_to_client{user="hello"} 726395278848 (676.51 GB)
telemt_user_unique_ips_current{user="hello"} 1338
telemt_user_unique_ips_recent_window{user="hello"} 496
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 48362.9 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6076100
telemt_connections_bad_total 323272
telemt_connections_current 6930
telemt_connections_me_current 6930
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 235786
telemt_upstream_connect_attempt_total 59194
telemt_upstream_connect_success_total 56599
telemt_upstream_connect_fail_total 1917
telemt_upstream_connect_attempts_per_request{bucket="1"} 58516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2013
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1917
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 2907
telemt_me_reconnect_success_total 990
telemt_me_reader_eof_total 692
telemt_me_idle_close_by_peer_total 691
telemt_me_route_drop_no_conn_total 10002567
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5127851
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
telemt_desync_total 10379
telemt_desync_full_logged_total 3373
telemt_desync_suppressed_total 7006
telemt_desync_frames_bucket_total{bucket="1_2"} 2273
telemt_desync_frames_bucket_total{bucket="3_10"} 4484
telemt_desync_frames_bucket_total{bucket="gt_10"} 3622
telemt_pool_swap_total 49
telemt_pool_force_close_total 1525
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 302
telemt_me_draining_writers_reap_progress_total 16312
telemt_me_writer_removed_unexpected_total 956
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2079
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15118
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1313
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 212
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14787
telemt_me_writer_teardown_success_total{mode="normal"} 17197
telemt_me_writer_teardown_noop_total 16318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33515
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 39.204667
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33515
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 302
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 684
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 5162408
telemt_user_connections_current{user="hello"} 6930
telemt_user_octets_from_client{user="hello"} 48204478364 (44.89 GB)
telemt_user_octets_to_client{user="hello"} 584367193063 (544.23 GB)
telemt_user_msgs_from_client{user="hello"} 126757
telemt_user_msgs_to_client{user="hello"} 447030
telemt_user_unique_ips_current{user="hello"} 1957
telemt_user_unique_ips_recent_window{user="hello"} 1111
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 48330.6 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2070121
telemt_connections_bad_total 260828
telemt_connections_current 3702
telemt_connections_me_current 3702
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 40202
telemt_upstream_connect_attempt_total 21394
telemt_upstream_connect_success_total 21181
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 21375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10877
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_reconnect_attempts_total 2000
telemt_me_reconnect_success_total 640
telemt_me_reader_eof_total 650
telemt_me_idle_close_by_peer_total 650
telemt_me_route_drop_no_conn_total 633983
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1556201
telemt_me_endpoint_quarantine_total 298
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 376
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
telemt_desync_total 7140
telemt_desync_full_logged_total 2605
telemt_desync_suppressed_total 4535
telemt_desync_frames_bucket_total{bucket="1_2"} 1367
telemt_desync_frames_bucket_total{bucket="3_10"} 2896
telemt_desync_frames_bucket_total{bucket="gt_10"} 2877
telemt_pool_swap_total 50
telemt_pool_force_close_total 1335
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 100
telemt_me_draining_writers_reap_progress_total 17760
telemt_me_writer_removed_unexpected_total 627
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1603
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16807
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1225
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 110
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16425
telemt_me_writer_teardown_success_total{mode="normal"} 18410
telemt_me_writer_teardown_noop_total 17760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36170
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.608421
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36170
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 100
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 543
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 1551581
telemt_user_connections_current{user="hello"} 3702
telemt_user_octets_from_client{user="hello"} 28356111424 (26.41 GB)
telemt_user_octets_to_client{user="hello"} 715787172346 (666.63 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1457
telemt_user_unique_ips_recent_window{user="hello"} 603
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 48325.1 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2924780
telemt_connections_bad_total 166884
telemt_connections_current 3392
telemt_connections_me_current 3392
telemt_handshake_timeouts_total 1202435
telemt_upstream_connect_attempt_total 20027
telemt_upstream_connect_success_total 19993
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 19996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 282
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 524
telemt_me_reconnect_success_total 303
telemt_me_reader_eof_total 304
telemt_me_idle_close_by_peer_total 304
telemt_me_route_drop_no_conn_total 546109
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1388762
telemt_me_endpoint_quarantine_total 368
telemt_me_single_endpoint_shadow_rotate_total 381
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
telemt_desync_total 6882
telemt_desync_full_logged_total 2427
telemt_desync_suppressed_total 4455
telemt_desync_frames_bucket_total{bucket="1_2"} 1220
telemt_desync_frames_bucket_total{bucket="3_10"} 2758
telemt_desync_frames_bucket_total{bucket="gt_10"} 2904
telemt_pool_swap_total 53
telemt_pool_force_close_total 1292
telemt_me_writer_close_signal_drop_total 102
telemt_me_draining_writers_reap_progress_total 17942
telemt_me_writer_removed_unexpected_total 294
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1144
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17111
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1275
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16650
telemt_me_writer_teardown_success_total{mode="normal"} 18255
telemt_me_writer_teardown_noop_total 17942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36197
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.947046
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36197
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 102
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 270
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1384474
telemt_user_connections_current{user="hello"} 3392
telemt_user_octets_from_client{user="hello"} 24703577296 (23.01 GB)
telemt_user_octets_to_client{user="hello"} 683007223568 (636.10 GB)
telemt_user_unique_ips_current{user="hello"} 1351
telemt_user_unique_ips_recent_window{user="hello"} 539
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 46316.5 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 615064
telemt_connections_bad_total 21728
telemt_connections_current 760
telemt_connections_me_current 760
telemt_handshake_timeouts_total 228712
telemt_upstream_connect_attempt_total 22591
telemt_upstream_connect_success_total 22589
telemt_upstream_connect_attempts_per_request{bucket="1"} 22589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 951
telemt_me_reconnect_success_total 368
telemt_me_reader_eof_total 366
telemt_me_idle_close_by_peer_total 366
telemt_me_route_drop_no_conn_total 130143
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 318284
telemt_me_endpoint_quarantine_total 445
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 398
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
telemt_desync_total 2048
telemt_desync_full_logged_total 818
telemt_desync_suppressed_total 1230
telemt_desync_frames_bucket_total{bucket="1_2"} 373
telemt_desync_frames_bucket_total{bucket="3_10"} 783
telemt_desync_frames_bucket_total{bucket="gt_10"} 892
telemt_pool_swap_total 51
telemt_pool_force_close_total 1112
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 67
telemt_me_draining_writers_reap_progress_total 20193
telemt_me_writer_removed_unexpected_total 347
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1461
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19083
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1109
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19081
telemt_me_writer_teardown_success_total{mode="normal"} 20544
telemt_me_writer_teardown_noop_total 20193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40737
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.927865
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40737
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 67
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 301
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 318430
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 4697119295 (4.37 GB)
telemt_user_octets_to_client{user="hello"} 125052585285 (116.46 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 48334.9 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2175906
telemt_connections_bad_total 200623
telemt_connections_current 4129
telemt_connections_me_current 4129
telemt_handshake_timeouts_total 54220
telemt_upstream_connect_attempt_total 20722
telemt_upstream_connect_success_total 20633
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 20692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10286
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_reconnect_attempts_total 770
telemt_me_reconnect_success_total 442
telemt_me_reader_eof_total 414
telemt_me_idle_close_by_peer_total 414
telemt_me_route_drop_no_conn_total 542291
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1709325
telemt_me_endpoint_quarantine_total 377
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 381
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
telemt_desync_total 6730
telemt_desync_full_logged_total 2253
telemt_desync_suppressed_total 4477
telemt_desync_frames_bucket_total{bucket="1_2"} 1641
telemt_desync_frames_bucket_total{bucket="3_10"} 2505
telemt_desync_frames_bucket_total{bucket="gt_10"} 2584
telemt_pool_swap_total 53
telemt_pool_force_close_total 1314
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 129
telemt_me_draining_writers_reap_progress_total 18665
telemt_me_writer_removed_unexpected_total 410
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1390
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17697
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1291
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17351
telemt_me_writer_teardown_success_total{mode="normal"} 19087
telemt_me_writer_teardown_noop_total 18665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37752
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.622139
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37752
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 129
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 398
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1703675
telemt_user_connections_current{user="hello"} 4129
telemt_user_octets_from_client{user="hello"} 38431151892 (35.79 GB)
telemt_user_octets_to_client{user="hello"} 799152214996 (744.27 GB)
telemt_user_unique_ips_current{user="hello"} 1484
telemt_user_unique_ips_recent_window{user="hello"} 577
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 48331.6 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2020550
telemt_connections_bad_total 165173
telemt_connections_current 3968
telemt_connections_me_current 3968
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 49429
telemt_upstream_connect_attempt_total 29355
telemt_upstream_connect_success_total 29143
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 29313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10808
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_reconnect_attempts_total 2996
telemt_me_reconnect_success_total 607
telemt_me_reader_eof_total 532
telemt_me_idle_close_by_peer_total 532
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 552663
telemt_me_route_drop_channel_closed_total 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1626137
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
telemt_desync_total 6226
telemt_desync_full_logged_total 2096
telemt_desync_suppressed_total 4130
telemt_desync_frames_bucket_total{bucket="1_2"} 1702
telemt_desync_frames_bucket_total{bucket="3_10"} 2302
telemt_desync_frames_bucket_total{bucket="gt_10"} 2222
telemt_pool_swap_total 52
telemt_pool_force_close_total 1289
telemt_me_writer_close_signal_drop_total 116
telemt_me_draining_writers_reap_progress_total 17929
telemt_me_writer_removed_unexpected_total 542
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1633
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16864
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16640
telemt_me_writer_teardown_success_total{mode="normal"} 18497
telemt_me_writer_teardown_noop_total 17930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36427
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.468694
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36427
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 116
telemt_me_refill_failed_total 136
telemt_me_writer_restored_same_endpoint_total 469
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 1629811
telemt_user_connections_current{user="hello"} 3968
telemt_user_octets_from_client{user="hello"} 27200350203 (25.33 GB)
telemt_user_octets_to_client{user="hello"} 725991510983 (676.13 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1425
telemt_user_unique_ips_recent_window{user="hello"} 564
```
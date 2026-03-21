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

# Server Metrics 2026-03-21 11:03:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 52044.2 (14h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1554363
telemt_connections_bad_total 78326
telemt_connections_current 1680
telemt_connections_me_current 1680
telemt_handshake_timeouts_total 62436
telemt_upstream_connect_attempt_total 20374
telemt_upstream_connect_success_total 20268
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 20336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12957
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 992
telemt_me_reconnect_success_total 435
telemt_me_reader_eof_total 433
telemt_me_idle_close_by_peer_total 433
telemt_me_route_drop_no_conn_total 917408
telemt_me_route_drop_channel_closed_total 345
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1189732
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 360
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 413
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
telemt_desync_total 4882
telemt_desync_full_logged_total 1703
telemt_desync_suppressed_total 3179
telemt_desync_frames_bucket_total{bucket="1_2"} 1017
telemt_desync_frames_bucket_total{bucket="3_10"} 1894
telemt_desync_frames_bucket_total{bucket="gt_10"} 1971
telemt_pool_swap_total 56
telemt_pool_force_close_total 1620
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 279
telemt_me_draining_writers_reap_progress_total 18208
telemt_me_writer_removed_unexpected_total 414
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1479
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17024
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1559
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16588
telemt_me_writer_teardown_success_total{mode="normal"} 18503
telemt_me_writer_teardown_noop_total 18210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36713
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 109.590963
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36713
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 279
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 384
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1188834
telemt_user_connections_current{user="hello"} 1680
telemt_user_octets_from_client{user="hello"} 16619225963 (15.48 GB)
telemt_user_octets_to_client{user="hello"} 329822717491 (307.17 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 588
telemt_user_unique_ips_recent_window{user="hello"} 282
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 44.2 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9761
telemt_connections_bad_total 73
telemt_connections_current 3372
telemt_connections_me_current 3372
telemt_upstream_connect_attempt_total 70
telemt_upstream_connect_success_total 68
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 70
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_route_drop_no_conn_total 3279
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9149
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 4
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_user_connections_total{user="hello"} 9159
telemt_user_connections_current{user="hello"} 3372
telemt_user_octets_from_client{user="hello"} 37562392 (35.82 MB)
telemt_user_octets_to_client{user="hello"} 288452264 (275.09 MB)
telemt_user_unique_ips_current{user="hello"} 1176
telemt_user_unique_ips_recent_window{user="hello"} 1465
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 52042.0 (14h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2945653
telemt_connections_bad_total 327156
telemt_connections_current 5340
telemt_connections_me_current 5340
telemt_handshake_timeouts_total 108004
telemt_upstream_connect_attempt_total 19891
telemt_upstream_connect_success_total 19878
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 19879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10826
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 653
telemt_me_reconnect_success_total 367
telemt_me_reader_eof_total 383
telemt_me_idle_close_by_peer_total 383
telemt_me_route_drop_no_conn_total 1236244
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2333742
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
telemt_desync_total 10138
telemt_desync_full_logged_total 3470
telemt_desync_suppressed_total 6668
telemt_desync_frames_bucket_total{bucket="1_2"} 2111
telemt_desync_frames_bucket_total{bucket="3_10"} 3988
telemt_desync_frames_bucket_total{bucket="gt_10"} 4039
telemt_pool_swap_total 56
telemt_pool_force_close_total 1711
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 238
telemt_me_draining_writers_reap_progress_total 18119
telemt_me_writer_removed_unexpected_total 360
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1485
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16854
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 13
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1619
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 92
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16408
telemt_me_writer_teardown_success_total{mode="normal"} 18339
telemt_me_writer_teardown_noop_total 18132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36471
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.049031
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36471
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 238
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 329
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 2330418
telemt_user_connections_current{user="hello"} 5340
telemt_user_octets_from_client{user="hello"} 37401819848 (34.83 GB)
telemt_user_octets_to_client{user="hello"} 865393687512 (805.96 GB)
telemt_user_unique_ips_current{user="hello"} 1862
telemt_user_unique_ips_recent_window{user="hello"} 858
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 52043.3 (14h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2443664
telemt_connections_bad_total 272709
telemt_connections_current 3709
telemt_connections_me_current 3709
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 102125
telemt_upstream_connect_attempt_total 24894
telemt_upstream_connect_success_total 24641
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 24771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11179
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 422
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1049
telemt_me_reconnect_success_total 476
telemt_me_reader_eof_total 440
telemt_me_idle_close_by_peer_total 440
telemt_me_route_drop_no_conn_total 712512
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1720609
telemt_me_endpoint_quarantine_total 353
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 402
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
telemt_desync_total 7904
telemt_desync_full_logged_total 2705
telemt_desync_suppressed_total 5199
telemt_desync_frames_bucket_total{bucket="1_2"} 1974
telemt_desync_frames_bucket_total{bucket="3_10"} 3094
telemt_desync_frames_bucket_total{bucket="gt_10"} 2836
telemt_pool_swap_total 56
telemt_pool_force_close_total 1543
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 117
telemt_me_draining_writers_reap_progress_total 17959
telemt_me_writer_removed_unexpected_total 434
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1484
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16923
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1449
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 94
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16416
telemt_me_writer_teardown_success_total{mode="normal"} 18407
telemt_me_writer_teardown_noop_total 17960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36367
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.791637
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36367
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 117
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 398
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 1722266
telemt_user_connections_current{user="hello"} 3709
telemt_user_octets_from_client{user="hello"} 33105705129 (30.83 GB)
telemt_user_octets_to_client{user="hello"} 826930862923 (770.14 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1396
telemt_user_unique_ips_recent_window{user="hello"} 533
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 52006.9 (14h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2387770
telemt_connections_bad_total 269450
telemt_connections_current 3444
telemt_connections_me_current 3444
telemt_handshake_timeouts_total 71165
telemt_upstream_connect_attempt_total 21266
telemt_upstream_connect_success_total 21213
telemt_upstream_connect_attempts_per_request{bucket="1"} 21213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11558
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 761
telemt_me_reconnect_success_total 511
telemt_me_reader_eof_total 457
telemt_me_idle_close_by_peer_total 457
telemt_me_route_drop_no_conn_total 692719
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1713322
telemt_me_endpoint_quarantine_total 400
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 398
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
telemt_desync_total 8029
telemt_desync_full_logged_total 2734
telemt_desync_suppressed_total 5295
telemt_desync_frames_bucket_total{bucket="1_2"} 2135
telemt_desync_frames_bucket_total{bucket="3_10"} 3051
telemt_desync_frames_bucket_total{bucket="gt_10"} 2843
telemt_pool_swap_total 55
telemt_pool_force_close_total 1519
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 146
telemt_me_draining_writers_reap_progress_total 19064
telemt_me_writer_removed_unexpected_total 433
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1491
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18037
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1406
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 113
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17545
telemt_me_writer_teardown_success_total{mode="normal"} 19528
telemt_me_writer_teardown_noop_total 19067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38595
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.059822
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38595
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 146
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 443
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1710676
telemt_user_connections_current{user="hello"} 3444
telemt_user_octets_from_client{user="hello"} 39487479788 (36.78 GB)
telemt_user_octets_to_client{user="hello"} 834544798392 (777.23 GB)
telemt_user_unique_ips_current{user="hello"} 1341
telemt_user_unique_ips_recent_window{user="hello"} 517
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 52046.4 (14h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7472021
telemt_connections_bad_total 499207
telemt_connections_current 6146
telemt_connections_me_current 6146
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 267752
telemt_upstream_connect_attempt_total 63229
telemt_upstream_connect_success_total 59544
telemt_upstream_connect_fail_total 2939
telemt_upstream_connect_attempts_per_request{bucket="1"} 62483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15270
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2939
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3124
telemt_me_reconnect_success_total 1074
telemt_me_reader_eof_total 775
telemt_me_idle_close_by_peer_total 774
telemt_me_route_drop_no_conn_total 12656058
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6228942
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
telemt_desync_total 11974
telemt_desync_full_logged_total 3839
telemt_desync_suppressed_total 8135
telemt_desync_frames_bucket_total{bucket="1_2"} 2626
telemt_desync_frames_bucket_total{bucket="3_10"} 5241
telemt_desync_frames_bucket_total{bucket="gt_10"} 4107
telemt_pool_swap_total 52
telemt_pool_force_close_total 1631
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 337
telemt_me_draining_writers_reap_progress_total 17457
telemt_me_writer_removed_unexpected_total 1041
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2252
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16142
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1387
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 244
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15826
telemt_me_writer_teardown_success_total{mode="normal"} 18394
telemt_me_writer_teardown_noop_total 17466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35860
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 44.611711
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35860
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 337
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 755
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 6264845
telemt_user_connections_current{user="hello"} 6146
telemt_user_octets_from_client{user="hello"} 53482342192 (49.81 GB)
telemt_user_octets_to_client{user="hello"} 626129447007 (583.13 GB)
telemt_user_msgs_from_client{user="hello"} 129175
telemt_user_msgs_to_client{user="hello"} 449473
telemt_user_unique_ips_current{user="hello"} 1900
telemt_user_unique_ips_recent_window{user="hello"} 1106
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 52013.9 (14h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2383454
telemt_connections_bad_total 282985
telemt_connections_current 4127
telemt_connections_me_current 4127
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 49939
telemt_upstream_connect_attempt_total 22689
telemt_upstream_connect_success_total 22456
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 22667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11599
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_reconnect_attempts_total 2185
telemt_me_reconnect_success_total 716
telemt_me_reader_eof_total 722
telemt_me_idle_close_by_peer_total 722
telemt_me_route_drop_no_conn_total 815271
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1808331
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
telemt_desync_total 8349
telemt_desync_full_logged_total 3014
telemt_desync_suppressed_total 5335
telemt_desync_frames_bucket_total{bucket="1_2"} 1592
telemt_desync_frames_bucket_total{bucket="3_10"} 3383
telemt_desync_frames_bucket_total{bucket="gt_10"} 3374
telemt_pool_swap_total 53
telemt_pool_force_close_total 1451
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 124
telemt_me_draining_writers_reap_progress_total 18874
telemt_me_writer_removed_unexpected_total 699
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1756
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17840
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1305
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 146
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17423
telemt_me_writer_teardown_success_total{mode="normal"} 19596
telemt_me_writer_teardown_noop_total 18874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38470
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.873428
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38470
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 124
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 607
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 1794245
telemt_user_connections_current{user="hello"} 4127
telemt_user_octets_from_client{user="hello"} 32935095732 (30.67 GB)
telemt_user_octets_to_client{user="hello"} 812604414434 (756.80 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1560
telemt_user_unique_ips_recent_window{user="hello"} 604
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 52008.4 (14h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3508749
telemt_connections_bad_total 186124
telemt_connections_current 3372
telemt_connections_me_current 3372
telemt_handshake_timeouts_total 1493515
telemt_upstream_connect_attempt_total 21105
telemt_upstream_connect_success_total 21071
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 21074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 692
telemt_me_reconnect_success_total 342
telemt_me_reader_eof_total 338
telemt_me_idle_close_by_peer_total 338
telemt_me_route_drop_no_conn_total 647699
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1610631
telemt_me_endpoint_quarantine_total 402
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 410
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
telemt_desync_total 7839
telemt_desync_full_logged_total 2805
telemt_desync_suppressed_total 5034
telemt_desync_frames_bucket_total{bucket="1_2"} 1414
telemt_desync_frames_bucket_total{bucket="3_10"} 3121
telemt_desync_frames_bucket_total{bucket="gt_10"} 3304
telemt_pool_swap_total 57
telemt_pool_force_close_total 1407
telemt_me_writer_close_signal_drop_total 112
telemt_me_draining_writers_reap_progress_total 18908
telemt_me_writer_removed_unexpected_total 326
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1229
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18026
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1386
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17501
telemt_me_writer_teardown_success_total{mode="normal"} 19255
telemt_me_writer_teardown_noop_total 18908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38163
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.031041
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38163
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 112
telemt_me_refill_failed_total 19
telemt_me_writer_restored_same_endpoint_total 294
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 1605911
telemt_user_connections_current{user="hello"} 3372
telemt_user_octets_from_client{user="hello"} 28680233264 (26.71 GB)
telemt_user_octets_to_client{user="hello"} 780532743128 (726.93 GB)
telemt_user_unique_ips_current{user="hello"} 1345
telemt_user_unique_ips_recent_window{user="hello"} 542
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 49999.9 (13h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 710987
telemt_connections_bad_total 22846
telemt_connections_current 771
telemt_connections_me_current 771
telemt_handshake_timeouts_total 264988
telemt_upstream_connect_attempt_total 24155
telemt_upstream_connect_success_total 24152
telemt_upstream_connect_attempts_per_request{bucket="1"} 24152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14084
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1058
telemt_me_reconnect_success_total 387
telemt_me_reader_eof_total 387
telemt_me_idle_close_by_peer_total 387
telemt_me_route_drop_no_conn_total 152820
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 364899
telemt_me_endpoint_quarantine_total 472
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 429
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
telemt_me_writers_active_current 45
telemt_desync_total 2417
telemt_desync_full_logged_total 947
telemt_desync_suppressed_total 1470
telemt_desync_frames_bucket_total{bucket="1_2"} 390
telemt_desync_frames_bucket_total{bucket="3_10"} 871
telemt_desync_frames_bucket_total{bucket="gt_10"} 1156
telemt_pool_swap_total 55
telemt_pool_force_close_total 1215
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 84
telemt_me_draining_writers_reap_progress_total 21634
telemt_me_writer_removed_unexpected_total 368
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1572
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20434
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1212
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20419
telemt_me_writer_teardown_success_total{mode="normal"} 22006
telemt_me_writer_teardown_noop_total 21634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43640
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.438126
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43640
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 84
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 315
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 365005
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 5397501935 (5.03 GB)
telemt_user_octets_to_client{user="hello"} 141098439857 (131.41 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 52018.3 (14h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2535415
telemt_connections_bad_total 238686
telemt_connections_current 4562
telemt_connections_me_current 4562
telemt_handshake_timeouts_total 60873
telemt_upstream_connect_attempt_total 22029
telemt_upstream_connect_success_total 21935
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 21999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10955
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_reconnect_attempts_total 863
telemt_me_reconnect_success_total 488
telemt_me_reader_eof_total 453
telemt_me_idle_close_by_peer_total 453
telemt_me_route_drop_no_conn_total 666237
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2002922
telemt_me_endpoint_quarantine_total 408
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 408
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
telemt_desync_total 7897
telemt_desync_full_logged_total 2645
telemt_desync_suppressed_total 5252
telemt_desync_frames_bucket_total{bucket="1_2"} 1918
telemt_desync_frames_bucket_total{bucket="3_10"} 2965
telemt_desync_frames_bucket_total{bucket="gt_10"} 3014
telemt_pool_swap_total 57
telemt_pool_force_close_total 1425
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 145
telemt_me_draining_writers_reap_progress_total 19831
telemt_me_writer_removed_unexpected_total 447
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1490
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18802
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1401
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18406
telemt_me_writer_teardown_success_total{mode="normal"} 20292
telemt_me_writer_teardown_noop_total 19831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40123
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.210876
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40123
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 145
telemt_me_refill_failed_total 19
telemt_me_writer_restored_same_endpoint_total 436
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1996805
telemt_user_connections_current{user="hello"} 4562
telemt_user_octets_from_client{user="hello"} 42702756256 (39.77 GB)
telemt_user_octets_to_client{user="hello"} 936496377192 (872.18 GB)
telemt_user_unique_ips_current{user="hello"} 1607
telemt_user_unique_ips_recent_window{user="hello"} 673
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 52015.1 (14h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2320077
telemt_connections_bad_total 183518
telemt_connections_current 3820
telemt_connections_me_current 3820
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 57526
telemt_upstream_connect_attempt_total 38204
telemt_upstream_connect_success_total 37972
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 38161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12603
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 581
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_reconnect_attempts_total 3149
telemt_me_reconnect_success_total 646
telemt_me_reader_eof_total 565
telemt_me_idle_close_by_peer_total 565
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 669404
telemt_me_route_drop_channel_closed_total 45
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1876549
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
telemt_desync_total 7031
telemt_desync_full_logged_total 2405
telemt_desync_suppressed_total 4626
telemt_desync_frames_bucket_total{bucket="1_2"} 1856
telemt_desync_frames_bucket_total{bucket="3_10"} 2613
telemt_desync_frames_bucket_total{bucket="gt_10"} 2562
telemt_pool_swap_total 56
telemt_pool_force_close_total 1375
telemt_me_writer_close_signal_drop_total 126
telemt_me_draining_writers_reap_progress_total 18997
telemt_me_writer_removed_unexpected_total 575
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1758
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17841
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1289
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 86
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17622
telemt_me_writer_teardown_success_total{mode="normal"} 19599
telemt_me_writer_teardown_noop_total 18998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38597
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.587802
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38597
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 126
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 492
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 1887575
telemt_user_connections_current{user="hello"} 3820
telemt_user_octets_from_client{user="hello"} 34204127797 (31.86 GB)
telemt_user_octets_to_client{user="hello"} 833017287992 (775.81 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1455
telemt_user_unique_ips_recent_window{user="hello"} 596
```
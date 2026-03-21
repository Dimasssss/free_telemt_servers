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

# Server Metrics 2026-03-21 16:45:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 72547.4 (20h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2607282
telemt_connections_bad_total 154988
telemt_connections_current 1515
telemt_connections_me_current 1515
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 81321
telemt_upstream_connect_attempt_total 30491
telemt_upstream_connect_success_total 30359
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 30448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1745
telemt_me_reconnect_success_total 688
telemt_me_reader_eof_total 661
telemt_me_idle_close_by_peer_total 661
telemt_me_route_drop_no_conn_total 2217714
telemt_me_route_drop_channel_closed_total 695
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2081440
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 499
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 564
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 8295
telemt_desync_full_logged_total 2873
telemt_desync_suppressed_total 5422
telemt_desync_frames_bucket_total{bucket="1_2"} 1810
telemt_desync_frames_bucket_total{bucket="3_10"} 3153
telemt_desync_frames_bucket_total{bucket="gt_10"} 3332
telemt_pool_swap_total 78
telemt_pool_force_close_total 2363
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 536
telemt_me_draining_writers_reap_progress_total 24569
telemt_me_writer_removed_unexpected_total 639
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2108
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22884
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22206
telemt_me_writer_teardown_success_total{mode="normal"} 24992
telemt_me_writer_teardown_noop_total 24576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49568
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 235.650353
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49568
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 536
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 589
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2082627
telemt_user_connections_current{user="hello"} 1515
telemt_user_octets_from_client{user="hello"} 29656897553 (27.62 GB)
telemt_user_octets_to_client{user="hello"} 513705756870 (478.43 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 552
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 3672.6 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221399
telemt_connections_bad_total 10079
telemt_connections_current 904
telemt_connections_me_current 904
telemt_handshake_timeouts_total 5493
telemt_upstream_connect_attempt_total 1474
telemt_upstream_connect_success_total 1472
telemt_upstream_connect_attempts_per_request{bucket="1"} 1472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 13
telemt_me_reconnect_success_total 11
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 179050
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193309
telemt_me_endpoint_quarantine_total 23
telemt_me_single_endpoint_shadow_rotate_total 36
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_me_writers_warm_current 26
telemt_desync_total 760
telemt_desync_full_logged_total 350
telemt_desync_suppressed_total 410
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 310
telemt_desync_frames_bucket_total{bucket="gt_10"} 287
telemt_pool_swap_total 3
telemt_pool_force_close_total 56
telemt_me_writer_close_signal_drop_total 25
telemt_me_draining_writers_reap_progress_total 1266
telemt_me_writer_removed_unexpected_total 11
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 93
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1184
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1210
telemt_me_writer_teardown_success_total{mode="normal"} 1277
telemt_me_writer_teardown_noop_total 1266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2543
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.289165
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2543
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 25
telemt_me_writer_restored_same_endpoint_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 190761
telemt_user_connections_current{user="hello"} 904
telemt_user_octets_from_client{user="hello"} 1751627552 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 39640077660 (36.92 GB)
telemt_user_unique_ips_current{user="hello"} 632
telemt_user_unique_ips_recent_window{user="hello"} 420
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 72545.1 (20h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5425752
telemt_connections_bad_total 455376
telemt_connections_current 5178
telemt_connections_me_current 5178
telemt_handshake_timeouts_total 179746
telemt_upstream_connect_attempt_total 26623
telemt_upstream_connect_success_total 26565
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 26571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14505
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1178
telemt_me_reconnect_success_total 599
telemt_me_reader_eof_total 603
telemt_me_idle_close_by_peer_total 603
telemt_me_route_drop_no_conn_total 3387174
telemt_me_route_drop_channel_closed_total 48
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4469494
telemt_me_endpoint_quarantine_total 454
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 543
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
telemt_desync_total 18151
telemt_desync_full_logged_total 6107
telemt_desync_suppressed_total 12044
telemt_desync_frames_bucket_total{bucket="1_2"} 3839
telemt_desync_frames_bucket_total{bucket="3_10"} 7203
telemt_desync_frames_bucket_total{bucket="gt_10"} 7109
telemt_pool_swap_total 77
telemt_pool_force_close_total 2557
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 407
telemt_me_draining_writers_reap_progress_total 24216
telemt_me_writer_removed_unexpected_total 583
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2121
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22372
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 34
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2348
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 209
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21659
telemt_me_writer_teardown_success_total{mode="normal"} 24493
telemt_me_writer_teardown_noop_total 24250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48743
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 100.374538
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48743
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 407
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 540
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 4464145
telemt_user_connections_current{user="hello"} 5178
telemt_user_octets_from_client{user="hello"} 69632295804 (64.85 GB)
telemt_user_octets_to_client{user="hello"} 1408544283908 (1.28 TB)
telemt_user_unique_ips_current{user="hello"} 1988
telemt_user_unique_ips_recent_window{user="hello"} 611
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 72546.6 (20h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4322370
telemt_connections_bad_total 444502
telemt_connections_current 4207
telemt_connections_me_current 4207
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 148094
telemt_upstream_connect_attempt_total 30984
telemt_upstream_connect_success_total 30696
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 30837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14474
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 497
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1418
telemt_me_reconnect_success_total 621
telemt_me_reader_eof_total 586
telemt_me_idle_close_by_peer_total 586
telemt_me_route_drop_no_conn_total 1392291
telemt_me_route_drop_channel_closed_total 112
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3203640
telemt_me_endpoint_quarantine_total 457
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 553
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 15271
telemt_desync_full_logged_total 5054
telemt_desync_suppressed_total 10217
telemt_desync_frames_bucket_total{bucket="1_2"} 3786
telemt_desync_frames_bucket_total{bucket="3_10"} 5916
telemt_desync_frames_bucket_total{bucket="gt_10"} 5569
telemt_pool_swap_total 79
telemt_pool_force_close_total 2321
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 241
telemt_me_draining_writers_reap_progress_total 23320
telemt_me_writer_removed_unexpected_total 567
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2008
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21859
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2159
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 162
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20999
telemt_me_writer_teardown_success_total{mode="normal"} 23867
telemt_me_writer_teardown_noop_total 23323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47190
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.436012
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47190
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 241
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 525
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 3202748
telemt_user_connections_current{user="hello"} 4207
telemt_user_octets_from_client{user="hello"} 73600542217 (68.55 GB)
telemt_user_octets_to_client{user="hello"} 1466984256283 (1.33 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1582
telemt_user_unique_ips_recent_window{user="hello"} 567
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 72510.4 (20h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4264798
telemt_connections_bad_total 425644
telemt_connections_current 3752
telemt_connections_me_current 3752
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 128245
telemt_upstream_connect_attempt_total 36227
telemt_upstream_connect_success_total 35983
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 36116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15831
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 297
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 869
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 1502
telemt_me_reconnect_success_total 675
telemt_me_reader_eof_total 620
telemt_me_idle_close_by_peer_total 620
telemt_me_route_drop_no_conn_total 1520009
telemt_me_route_drop_channel_closed_total 50
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3183232
telemt_me_endpoint_quarantine_total 508
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 545
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 14876
telemt_desync_full_logged_total 4868
telemt_desync_suppressed_total 10008
telemt_desync_frames_bucket_total{bucket="1_2"} 3674
telemt_desync_frames_bucket_total{bucket="3_10"} 5619
telemt_desync_frames_bucket_total{bucket="gt_10"} 5583
telemt_pool_swap_total 77
telemt_pool_force_close_total 2242
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 266
telemt_me_draining_writers_reap_progress_total 24713
telemt_me_writer_removed_unexpected_total 589
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2096
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23229
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2052
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 190
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22471
telemt_me_writer_teardown_success_total{mode="normal"} 25325
telemt_me_writer_teardown_noop_total 24720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50045
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.180855
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50045
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 266
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 582
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 3186414
telemt_user_connections_current{user="hello"} 3752
telemt_user_octets_from_client{user="hello"} 78720733585 (73.31 GB)
telemt_user_octets_to_client{user="hello"} 1464857658360 (1.33 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1472
telemt_user_unique_ips_recent_window{user="hello"} 522
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 72549.5 (20h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14784101
telemt_connections_bad_total 950238
telemt_connections_current 5218
telemt_connections_me_current 5218
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 431400
telemt_upstream_connect_attempt_total 147297
telemt_upstream_connect_success_total 131545
telemt_upstream_connect_fail_total 14621
telemt_upstream_connect_attempts_per_request{bucket="1"} 146166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29722
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14621
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 4075
telemt_me_reconnect_success_total 1482
telemt_me_reader_eof_total 1008
telemt_me_idle_close_by_peer_total 1007
telemt_me_route_drop_no_conn_total 29245241
telemt_me_route_drop_channel_closed_total 94
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12181075
telemt_me_endpoint_quarantine_total 548
telemt_me_single_endpoint_outage_enter_total 86
telemt_me_single_endpoint_outage_exit_total 86
telemt_me_single_endpoint_outage_reconnect_attempt_total 195
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 195
telemt_me_single_endpoint_shadow_rotate_total 571
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 21447
telemt_desync_full_logged_total 6614
telemt_desync_suppressed_total 14833
telemt_desync_frames_bucket_total{bucket="1_2"} 4713
telemt_desync_frames_bucket_total{bucket="3_10"} 9345
telemt_desync_frames_bucket_total{bucket="gt_10"} 7389
telemt_pool_swap_total 74
telemt_pool_force_close_total 2439
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 550
telemt_me_draining_writers_reap_progress_total 22986
telemt_me_writer_removed_unexpected_total 1412
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3034
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21125
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2056
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 383
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20547
telemt_me_writer_teardown_success_total{mode="normal"} 24159
telemt_me_writer_teardown_noop_total 22998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47157
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 179.355499
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47157
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 550
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 1022
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 380
telemt_user_connections_total{user="hello"} 12279592
telemt_user_connections_current{user="hello"} 5218
telemt_user_octets_from_client{user="hello"} 99867459510 (93.01 GB)
telemt_user_octets_to_client{user="hello"} 837557931811 (780.04 GB)
telemt_user_msgs_from_client{user="hello"} 290173
telemt_user_msgs_to_client{user="hello"} 585212
telemt_user_unique_ips_current{user="hello"} 1867
telemt_user_unique_ips_recent_window{user="hello"} 1179
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 72517.2 (20h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4264058
telemt_connections_bad_total 451822
telemt_connections_current 4143
telemt_connections_me_current 4143
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 90212
telemt_upstream_connect_attempt_total 30169
telemt_upstream_connect_success_total 29805
telemt_upstream_connect_fail_total 316
telemt_upstream_connect_attempts_per_request{bucket="1"} 30121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15613
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 316
telemt_me_reconnect_attempts_total 3107
telemt_me_reconnect_success_total 1080
telemt_me_reader_eof_total 1068
telemt_me_idle_close_by_peer_total 1068
telemt_me_route_drop_no_conn_total 1826136
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3297451
telemt_me_endpoint_quarantine_total 442
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 539
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 15983
telemt_desync_full_logged_total 5548
telemt_desync_suppressed_total 10435
telemt_desync_frames_bucket_total{bucket="1_2"} 3120
telemt_desync_frames_bucket_total{bucket="3_10"} 6338
telemt_desync_frames_bucket_total{bucket="gt_10"} 6525
telemt_pool_swap_total 72
telemt_pool_force_close_total 2139
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 217
telemt_me_draining_writers_reap_progress_total 25340
telemt_me_writer_removed_unexpected_total 1035
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2540
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23871
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1833
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 306
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23201
telemt_me_writer_teardown_success_total{mode="normal"} 26411
telemt_me_writer_teardown_noop_total 25341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51752
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.709960
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51752
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 217
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 931
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 3280345
telemt_user_connections_current{user="hello"} 4143
telemt_user_octets_from_client{user="hello"} 85789756892 (79.90 GB)
telemt_user_octets_to_client{user="hello"} 1344331317722 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1656
telemt_user_unique_ips_recent_window{user="hello"} 548
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 9352.8 (2h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1429547
telemt_connections_bad_total 50053
telemt_connections_current 3670
telemt_connections_me_current 3670
telemt_handshake_timeouts_total 658662
telemt_upstream_connect_attempt_total 3150
telemt_upstream_connect_success_total 3094
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 3144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1672
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_reconnect_attempts_total 418
telemt_me_reconnect_success_total 111
telemt_me_reader_eof_total 104
telemt_me_idle_close_by_peer_total 104
telemt_me_route_drop_no_conn_total 515821
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 661944
telemt_me_endpoint_quarantine_total 39
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 3564
telemt_desync_full_logged_total 1124
telemt_desync_suppressed_total 2440
telemt_desync_frames_bucket_total{bucket="1_2"} 672
telemt_desync_frames_bucket_total{bucket="3_10"} 1313
telemt_desync_frames_bucket_total{bucket="gt_10"} 1579
telemt_pool_swap_total 9
telemt_pool_force_close_total 296
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 26
telemt_me_draining_writers_reap_progress_total 2684
telemt_me_writer_removed_unexpected_total 105
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 246
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2543
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 246
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 50
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2388
telemt_me_writer_teardown_success_total{mode="normal"} 2789
telemt_me_writer_teardown_noop_total 2684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5473
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.844822
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5473
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 26
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 93
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 660916
telemt_user_connections_current{user="hello"} 3670
telemt_user_octets_from_client{user="hello"} 15888505600 (14.80 GB)
telemt_user_octets_to_client{user="hello"} 249704553084 (232.56 GB)
telemt_user_unique_ips_current{user="hello"} 1399
telemt_user_unique_ips_recent_window{user="hello"} 560
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 70503.0 (19h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1348465
telemt_connections_bad_total 149272
telemt_connections_current 843
telemt_connections_me_current 843
telemt_handshake_timeouts_total 476881
telemt_upstream_connect_attempt_total 32532
telemt_upstream_connect_success_total 32523
telemt_upstream_connect_attempts_per_request{bucket="1"} 32523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1371
telemt_me_reconnect_success_total 578
telemt_me_reader_eof_total 579
telemt_me_idle_close_by_peer_total 579
telemt_me_route_drop_no_conn_total 299309
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 641343
telemt_me_endpoint_quarantine_total 620
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 587
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 3818
telemt_desync_full_logged_total 1370
telemt_desync_suppressed_total 2448
telemt_desync_frames_bucket_total{bucket="1_2"} 727
telemt_desync_frames_bucket_total{bucket="3_10"} 1363
telemt_desync_frames_bucket_total{bucket="gt_10"} 1728
telemt_pool_swap_total 77
telemt_pool_force_close_total 1828
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 115
telemt_me_draining_writers_reap_progress_total 29146
telemt_me_writer_removed_unexpected_total 546
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2222
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27489
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1798
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27318
telemt_me_writer_teardown_success_total{mode="normal"} 29711
telemt_me_writer_teardown_noop_total 29146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58857
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.799381
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58857
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 115
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 482
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 640882
telemt_user_connections_current{user="hello"} 843
telemt_user_octets_from_client{user="hello"} 13215146907 (12.31 GB)
telemt_user_octets_to_client{user="hello"} 246876163785 (229.92 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 72521.6 (20h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4767742
telemt_connections_bad_total 442950
telemt_connections_current 4813
telemt_connections_me_current 4813
telemt_handshake_timeouts_total 157321
telemt_upstream_connect_attempt_total 28484
telemt_upstream_connect_success_total 28366
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 28448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14295
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_reconnect_attempts_total 1208
telemt_me_reconnect_success_total 636
telemt_me_reader_eof_total 605
telemt_me_idle_close_by_peer_total 605
telemt_me_route_drop_no_conn_total 1459895
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3770520
telemt_me_endpoint_quarantine_total 514
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 555
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 14670
telemt_desync_full_logged_total 4857
telemt_desync_suppressed_total 9813
telemt_desync_frames_bucket_total{bucket="1_2"} 3468
telemt_desync_frames_bucket_total{bucket="3_10"} 5451
telemt_desync_frames_bucket_total{bucket="gt_10"} 5751
telemt_pool_swap_total 80
telemt_pool_force_close_total 2122
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 250
telemt_me_draining_writers_reap_progress_total 25557
telemt_me_writer_removed_unexpected_total 591
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2058
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24094
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2071
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23435
telemt_me_writer_teardown_success_total{mode="normal"} 26152
telemt_me_writer_teardown_noop_total 25558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51710
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.386798
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51710
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 250
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 565
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 3760829
telemt_user_connections_current{user="hello"} 4813
telemt_user_octets_from_client{user="hello"} 74649648576 (69.52 GB)
telemt_user_octets_to_client{user="hello"} 1758583086884 (1.60 TB)
telemt_user_unique_ips_current{user="hello"} 1672
telemt_user_unique_ips_recent_window{user="hello"} 622
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 72518.4 (20h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4197345
telemt_connections_bad_total 377536
telemt_connections_current 3906
telemt_connections_me_current 3906
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 129924
telemt_upstream_connect_attempt_total 44964
telemt_upstream_connect_success_total 44646
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 44908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16145
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 603
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_reconnect_attempts_total 4124
telemt_me_reconnect_success_total 908
telemt_me_reader_eof_total 788
telemt_me_idle_close_by_peer_total 788
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 1538157
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3348205
telemt_me_endpoint_quarantine_total 604
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 549
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
telemt_me_writers_active_current 43
telemt_desync_total 13138
telemt_desync_full_logged_total 4441
telemt_desync_suppressed_total 8697
telemt_desync_frames_bucket_total{bucket="1_2"} 3275
telemt_desync_frames_bucket_total{bucket="3_10"} 4878
telemt_desync_frames_bucket_total{bucket="gt_10"} 4985
telemt_pool_swap_total 78
telemt_pool_force_close_total 2067
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 236
telemt_me_draining_writers_reap_progress_total 24906
telemt_me_writer_removed_unexpected_total 801
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2459
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23281
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1892
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 175
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22839
telemt_me_writer_teardown_success_total{mode="normal"} 25740
telemt_me_writer_teardown_noop_total 24907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50647
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.033726
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50647
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 236
telemt_me_refill_failed_total 183
telemt_me_writer_restored_same_endpoint_total 697
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 3355956
telemt_user_connections_current{user="hello"} 3906
telemt_user_octets_from_client{user="hello"} 60861051917 (56.68 GB)
telemt_user_octets_to_client{user="hello"} 1420020985524 (1.29 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1541
telemt_user_unique_ips_recent_window{user="hello"} 579
```
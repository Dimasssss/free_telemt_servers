# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

**Принимаю донаты криптой для добавления и продления серверов:**  
- TON: 
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```
Этот сервер пользуется большим спросом. Я арендовал еще один такой же, чтобы распределить нагрузку.

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

## rdp-onedash.ru
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

## 4vps.su
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

# Server Metrics 2026-03-20 16:29:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 1046.4 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61094
telemt_connections_bad_total 2396
telemt_connections_current 1817
telemt_connections_direct_current 1817
telemt_relay_adaptive_promotions_total 39
telemt_relay_adaptive_demotions_total 2431
telemt_relay_adaptive_hard_promotions_total 38
telemt_handshake_timeouts_total 637
telemt_upstream_connect_attempt_total 53084
telemt_upstream_connect_success_total 53069
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 53084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2422
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53067
telemt_user_connections_current{user="hello"} 1817
telemt_user_octets_from_client{user="hello"} 980369369 (934.95 MB)
telemt_user_octets_to_client{user="hello"} 11282436913 (10.51 GB)
telemt_user_msgs_from_client{user="hello"} 709802
telemt_user_msgs_to_client{user="hello"} 743960
telemt_user_unique_ips_current{user="hello"} 538
telemt_user_unique_ips_recent_window{user="hello"} 301
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 8069.0 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 999107
telemt_connections_bad_total 49833
telemt_connections_current 4419
telemt_connections_me_current 4419
telemt_handshake_timeouts_total 15799
telemt_upstream_connect_attempt_total 2571
telemt_upstream_connect_success_total 2548
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1416
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 159
telemt_me_reconnect_success_total 95
telemt_me_reader_eof_total 80
telemt_me_idle_close_by_peer_total 80
telemt_me_route_drop_no_conn_total 412011
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 754530
telemt_me_endpoint_quarantine_total 33
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 59
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 2669
telemt_desync_full_logged_total 902
telemt_desync_suppressed_total 1767
telemt_desync_frames_bucket_total{bucket="1_2"} 564
telemt_desync_frames_bucket_total{bucket="3_10"} 1064
telemt_desync_frames_bucket_total{bucket="gt_10"} 1041
telemt_pool_swap_total 7
telemt_pool_force_close_total 297
telemt_me_writer_close_signal_drop_total 43
telemt_me_draining_writers_reap_progress_total 2215
telemt_me_writer_removed_unexpected_total 80
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 235
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2032
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 234
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 63
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1918
telemt_me_writer_teardown_success_total{mode="normal"} 2267
telemt_me_writer_teardown_noop_total 2221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4488
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.068979
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4488
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 43
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 86
telemt_me_writer_restored_fallback_total 1
telemt_me_no_writer_failfast_total 41
telemt_me_async_recovery_trigger_total 396
telemt_user_connections_total{user="hello"} 753775
telemt_user_connections_current{user="hello"} 4419
telemt_user_octets_from_client{user="hello"} 9522428668 (8.87 GB)
telemt_user_octets_to_client{user="hello"} 225544088448 (210.05 GB)
telemt_user_unique_ips_current{user="hello"} 1564
telemt_user_unique_ips_recent_window{user="hello"} 587
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 8063.0 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 718308
telemt_connections_bad_total 46900
telemt_connections_current 3968
telemt_connections_me_current 3968
telemt_handshake_timeouts_total 10493
telemt_upstream_connect_attempt_total 3333
telemt_upstream_connect_success_total 3262
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 3330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1730
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_reconnect_attempts_total 366
telemt_me_reconnect_success_total 236
telemt_me_reader_eof_total 203
telemt_me_idle_close_by_peer_total 203
telemt_me_route_drop_no_conn_total 295379
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 605356
telemt_me_endpoint_quarantine_total 48
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 54
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
telemt_me_writers_active_current 42
telemt_desync_total 2200
telemt_desync_full_logged_total 701
telemt_desync_suppressed_total 1499
telemt_desync_frames_bucket_total{bucket="1_2"} 420
telemt_desync_frames_bucket_total{bucket="3_10"} 905
telemt_desync_frames_bucket_total{bucket="gt_10"} 875
telemt_pool_swap_total 5
telemt_pool_force_close_total 324
telemt_pool_stale_pick_total 1363
telemt_me_writer_close_signal_drop_total 56
telemt_me_draining_writers_reap_progress_total 2843
telemt_me_writer_removed_unexpected_total 198
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 394
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2595
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 148
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 176
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2519
telemt_me_writer_teardown_success_total{mode="normal"} 2989
telemt_me_writer_teardown_noop_total 2843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5832
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 24.683410
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5832
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 56
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 221
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 604810
telemt_user_connections_current{user="hello"} 3968
telemt_user_octets_from_client{user="hello"} 10226475012 (9.52 GB)
telemt_user_octets_to_client{user="hello"} 216514648804 (201.64 GB)
telemt_user_unique_ips_current{user="hello"} 1453
telemt_user_unique_ips_recent_window{user="hello"} 501
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 8061.8 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2987479
telemt_connections_bad_total 76160
telemt_connections_current 5225
telemt_connections_me_current 5225
telemt_handshake_timeouts_total 33400
telemt_upstream_connect_attempt_total 11461
telemt_upstream_connect_success_total 10848
telemt_upstream_connect_fail_total 459
telemt_upstream_connect_attempts_per_request{bucket="1"} 11307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2695
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 459
telemt_me_keepalive_timeout_total 185
telemt_me_reconnect_attempts_total 650
telemt_me_reconnect_success_total 340
telemt_me_reader_eof_total 246
telemt_me_idle_close_by_peer_total 246
telemt_me_route_drop_no_conn_total 6108023
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2694059
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 63
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
telemt_me_writers_active_current 58
telemt_desync_total 3399
telemt_desync_full_logged_total 981
telemt_desync_suppressed_total 2418
telemt_desync_frames_bucket_total{bucket="1_2"} 692
telemt_desync_frames_bucket_total{bucket="3_10"} 1508
telemt_desync_frames_bucket_total{bucket="gt_10"} 1199
telemt_pool_swap_total 5
telemt_pool_force_close_total 218
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 93
telemt_me_draining_writers_reap_progress_total 2236
telemt_me_writer_removed_unexpected_total 374
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 527
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2081
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 147
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 71
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2018
telemt_me_writer_teardown_success_total{mode="normal"} 2608
telemt_me_writer_teardown_noop_total 2237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4845
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.856177
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4845
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 93
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 265
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 2701303
telemt_user_connections_current{user="hello"} 5226
telemt_user_octets_from_client{user="hello"} 11232192779 (10.46 GB)
telemt_user_octets_to_client{user="hello"} 86028921780 (80.12 GB)
telemt_user_msgs_from_client{user="hello"} 8736
telemt_user_msgs_to_client{user="hello"} 7574
telemt_user_unique_ips_current{user="hello"} 1765
telemt_user_unique_ips_recent_window{user="hello"} 991
```

## rdp-onedash.ru

```
telemt 3.3.28

telemt_uptime_seconds 8066.5 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2578555
telemt_connections_bad_total 178521
telemt_connections_current 6171
telemt_connections_me_current 6171
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 24075
telemt_upstream_connect_attempt_total 19381
telemt_upstream_connect_success_total 19373
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 19380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5687
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 724
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 222
telemt_me_reconnect_success_total 70
telemt_me_reader_eof_total 71
telemt_me_idle_close_by_peer_total 71
telemt_me_route_drop_no_conn_total 4309929
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2184040
telemt_me_endpoint_quarantine_total 47
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 54
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
telemt_me_writers_active_current 41
telemt_desync_total 3759
telemt_desync_full_logged_total 1106
telemt_desync_suppressed_total 2653
telemt_desync_frames_bucket_total{bucket="1_2"} 959
telemt_desync_frames_bucket_total{bucket="3_10"} 1598
telemt_desync_frames_bucket_total{bucket="gt_10"} 1202
telemt_pool_swap_total 8
telemt_pool_force_close_total 246
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 1778
telemt_me_writer_removed_unexpected_total 68
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1603
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 214
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1532
telemt_me_writer_teardown_success_total{mode="normal"} 1816
telemt_me_writer_teardown_noop_total 1782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3598
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 114.256597
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3598
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 51
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 2197543
telemt_user_connections_current{user="hello"} 6171
telemt_user_octets_from_client{user="hello"} 17430782760 (16.23 GB)
telemt_user_octets_to_client{user="hello"} 166964772735 (155.50 GB)
telemt_user_msgs_from_client{user="hello"} 75809
telemt_user_msgs_to_client{user="hello"} 92195
telemt_user_unique_ips_current{user="hello"} 1953
telemt_user_unique_ips_recent_window{user="hello"} 812
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 7489.4 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154543
telemt_connections_bad_total 1325
telemt_connections_current 697
telemt_connections_me_current 697
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 2656
telemt_upstream_connect_attempt_total 4404
telemt_upstream_connect_success_total 4401
telemt_upstream_connect_attempts_per_request{bucket="1"} 4401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3126
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 129
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 238
telemt_me_reconnect_success_total 60
telemt_me_reader_eof_total 57
telemt_me_idle_close_by_peer_total 57
telemt_me_route_drop_no_conn_total 127986
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134619
telemt_me_endpoint_quarantine_total 55
telemt_me_single_endpoint_shadow_rotate_total 61
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
telemt_me_writers_active_current 43
telemt_desync_total 479
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 328
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 202
telemt_pool_swap_total 8
telemt_pool_force_close_total 223
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 51
telemt_me_draining_writers_reap_progress_total 2369
telemt_me_writer_removed_unexpected_total 57
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 251
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2160
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 222
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2146
telemt_me_writer_teardown_success_total{mode="normal"} 2411
telemt_me_writer_teardown_noop_total 2370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4781
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.499707
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4781
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 51
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 45
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 135578
telemt_user_connections_current{user="hello"} 697
telemt_user_octets_from_client{user="hello"} 1669125062 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 25225737345 (23.49 GB)
telemt_user_msgs_from_client{user="hello"} 5317
telemt_user_msgs_to_client{user="hello"} 6420
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## 4vps.su

```
telemt 3.3.28

telemt_uptime_seconds 8064.6 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1418935
telemt_connections_bad_total 82896
telemt_connections_current 7401
telemt_connections_me_current 7401
telemt_handshake_timeouts_total 47813
telemt_upstream_connect_attempt_total 2367
telemt_upstream_connect_success_total 2365
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1269
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 151
telemt_me_reconnect_success_total 78
telemt_me_reader_eof_total 83
telemt_me_idle_close_by_peer_total 83
telemt_me_route_drop_no_conn_total 706538
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1208828
telemt_me_endpoint_quarantine_total 35
telemt_me_single_endpoint_shadow_rotate_total 52
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
telemt_desync_total 4404
telemt_desync_full_logged_total 1268
telemt_desync_suppressed_total 3136
telemt_desync_frames_bucket_total{bucket="1_2"} 1077
telemt_desync_frames_bucket_total{bucket="3_10"} 1658
telemt_desync_frames_bucket_total{bucket="gt_10"} 1669
telemt_pool_swap_total 7
telemt_pool_force_close_total 263
telemt_me_writer_close_signal_drop_total 43
telemt_me_draining_writers_reap_progress_total 2005
telemt_me_writer_removed_unexpected_total 80
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 224
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1866
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1742
telemt_me_writer_teardown_success_total{mode="normal"} 2090
telemt_me_writer_teardown_noop_total 2006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4096
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.375475
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4096
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 43
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 71
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 1207557
telemt_user_connections_current{user="hello"} 7401
telemt_user_octets_from_client{user="hello"} 15792429816 (14.71 GB)
telemt_user_octets_to_client{user="hello"} 369516522900 (344.14 GB)
telemt_user_unique_ips_current{user="hello"} 2251
telemt_user_unique_ips_recent_window{user="hello"} 933
```
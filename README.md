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

# Server Metrics 2026-03-21 15:02:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 66405.0 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2319860
telemt_connections_bad_total 115270
telemt_connections_current 1476
telemt_connections_me_current 1476
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 76152
telemt_upstream_connect_attempt_total 28442
telemt_upstream_connect_success_total 28317
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 28399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16423
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1642
telemt_me_reconnect_success_total 654
telemt_me_reader_eof_total 628
telemt_me_idle_close_by_peer_total 628
telemt_me_route_drop_no_conn_total 1964724
telemt_me_route_drop_channel_closed_total 618
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1855440
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 466
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 517
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 7228
telemt_desync_full_logged_total 2490
telemt_desync_suppressed_total 4738
telemt_desync_frames_bucket_total{bucket="1_2"} 1593
telemt_desync_frames_bucket_total{bucket="3_10"} 2755
telemt_desync_frames_bucket_total{bucket="gt_10"} 2880
telemt_pool_swap_total 71
telemt_pool_force_close_total 2156
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 489
telemt_me_draining_writers_reap_progress_total 22699
telemt_me_writer_removed_unexpected_total 606
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1953
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21138
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2040
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 116
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20543
telemt_me_writer_teardown_success_total{mode="normal"} 23091
telemt_me_writer_teardown_noop_total 22705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45796
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 212.127050
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45796
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 489
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 562
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1857017
telemt_user_connections_current{user="hello"} 1476
telemt_user_octets_from_client{user="hello"} 26390197981 (24.58 GB)
telemt_user_octets_to_client{user="hello"} 461735309146 (430.02 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 578
telemt_user_unique_ips_recent_window{user="hello"} 268
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 497.7 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2245
telemt_connections_bad_total 6
telemt_connections_current 275
telemt_connections_me_current 275
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 357
telemt_upstream_connect_success_total 353
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 3
telemt_me_route_drop_no_conn_total 776
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2111
telemt_me_endpoint_quarantine_total 1
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 11
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_force_close_total 1
telemt_me_draining_writers_reap_progress_total 264
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 260
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 263
telemt_me_writer_teardown_success_total{mode="normal"} 264
telemt_me_writer_teardown_noop_total 264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 528
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.002857
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 528
telemt_user_connections_total{user="hello"} 2098
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 22941068 (21.88 MB)
telemt_user_octets_to_client{user="hello"} 1136360456 (1.06 GB)
telemt_user_unique_ips_current{user="hello"} 187
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 66402.6 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4592818
telemt_connections_bad_total 412042
telemt_connections_current 5212
telemt_connections_me_current 5212
telemt_handshake_timeouts_total 168506
telemt_upstream_connect_attempt_total 24720
telemt_upstream_connect_success_total 24667
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 24672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13433
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1112
telemt_me_reconnect_success_total 571
telemt_me_reader_eof_total 573
telemt_me_idle_close_by_peer_total 573
telemt_me_route_drop_no_conn_total 2523290
telemt_me_route_drop_channel_closed_total 44
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3752468
telemt_me_endpoint_quarantine_total 421
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 501
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
telemt_desync_total 15381
telemt_desync_full_logged_total 5190
telemt_desync_suppressed_total 10191
telemt_desync_frames_bucket_total{bucket="1_2"} 3283
telemt_desync_frames_bucket_total{bucket="3_10"} 6059
telemt_desync_frames_bucket_total{bucket="gt_10"} 6039
telemt_pool_swap_total 70
telemt_pool_force_close_total 2265
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 357
telemt_me_draining_writers_reap_progress_total 22413
telemt_me_writer_removed_unexpected_total 554
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1965
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20784
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2071
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 194
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20148
telemt_me_writer_teardown_success_total{mode="normal"} 22749
telemt_me_writer_teardown_noop_total 22445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45194
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 74.591297
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45194
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 357
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 513
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 3747851
telemt_user_connections_current{user="hello"} 5212
telemt_user_octets_from_client{user="hello"} 60842438228 (56.66 GB)
telemt_user_octets_to_client{user="hello"} 1251182663452 (1.14 TB)
telemt_user_unique_ips_current{user="hello"} 1964
telemt_user_unique_ips_recent_window{user="hello"} 735
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 66404.1 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3752182
telemt_connections_bad_total 410524
telemt_connections_current 4555
telemt_connections_me_current 4555
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 136328
telemt_upstream_connect_attempt_total 29121
telemt_upstream_connect_success_total 28842
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 28979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13441
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 484
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1253
telemt_me_reconnect_success_total 570
telemt_me_reader_eof_total 541
telemt_me_idle_close_by_peer_total 541
telemt_me_route_drop_no_conn_total 1170613
telemt_me_route_drop_channel_closed_total 95
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2738848
telemt_me_endpoint_quarantine_total 427
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 506
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 12760
telemt_desync_full_logged_total 4291
telemt_desync_suppressed_total 8469
telemt_desync_frames_bucket_total{bucket="1_2"} 3187
telemt_desync_frames_bucket_total{bucket="3_10"} 4936
telemt_desync_frames_bucket_total{bucket="gt_10"} 4637
telemt_pool_swap_total 72
telemt_pool_force_close_total 2074
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 205
telemt_me_draining_writers_reap_progress_total 21632
telemt_me_writer_removed_unexpected_total 525
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1840
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20319
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1936
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 138
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19558
telemt_me_writer_teardown_success_total{mode="normal"} 22159
telemt_me_writer_teardown_noop_total 21633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43792
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.348839
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43792
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 205
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 483
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 2738828
telemt_user_connections_current{user="hello"} 4555
telemt_user_octets_from_client{user="hello"} 51389220977 (47.86 GB)
telemt_user_octets_to_client{user="hello"} 1278075090315 (1.16 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1818
telemt_user_unique_ips_recent_window{user="hello"} 689
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 66367.9 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3663340
telemt_connections_bad_total 388011
telemt_connections_current 3608
telemt_connections_me_current 3608
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 109696
telemt_upstream_connect_attempt_total 34364
telemt_upstream_connect_success_total 34129
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 34262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14827
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 850
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1311
telemt_me_reconnect_success_total 638
telemt_me_reader_eof_total 581
telemt_me_idle_close_by_peer_total 581
telemt_me_route_drop_no_conn_total 1155062
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2704058
telemt_me_endpoint_quarantine_total 476
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 496
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
telemt_me_writers_active_current 43
telemt_desync_total 12528
telemt_desync_full_logged_total 4193
telemt_desync_suppressed_total 8335
telemt_desync_frames_bucket_total{bucket="1_2"} 3137
telemt_desync_frames_bucket_total{bucket="3_10"} 4711
telemt_desync_frames_bucket_total{bucket="gt_10"} 4680
telemt_pool_swap_total 70
telemt_pool_force_close_total 2003
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 227
telemt_me_draining_writers_reap_progress_total 23054
telemt_me_writer_removed_unexpected_total 553
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1942
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21701
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1825
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 178
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21051
telemt_me_writer_teardown_success_total{mode="normal"} 23643
telemt_me_writer_teardown_noop_total 23059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46702
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.904752
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46702
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 227
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 555
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2708013
telemt_user_connections_current{user="hello"} 3608
telemt_user_octets_from_client{user="hello"} 58177695701 (54.18 GB)
telemt_user_octets_to_client{user="hello"} 1265209926368 (1.15 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1394
telemt_user_unique_ips_recent_window{user="hello"} 814
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 66407.1 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12587788
telemt_connections_bad_total 824578
telemt_connections_current 6308
telemt_connections_me_current 6308
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 386737
telemt_upstream_connect_attempt_total 115546
telemt_upstream_connect_success_total 105668
telemt_upstream_connect_fail_total 8847
telemt_upstream_connect_attempts_per_request{bucket="1"} 114515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25359
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8847
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 3840
telemt_me_reconnect_success_total 1377
telemt_me_reader_eof_total 964
telemt_me_idle_close_by_peer_total 963
telemt_me_route_drop_no_conn_total 23982203
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10332728
telemt_me_endpoint_quarantine_total 510
telemt_me_single_endpoint_outage_enter_total 77
telemt_me_single_endpoint_outage_exit_total 77
telemt_me_single_endpoint_outage_reconnect_attempt_total 173
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 173
telemt_me_single_endpoint_shadow_rotate_total 521
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 18370
telemt_desync_full_logged_total 5795
telemt_desync_suppressed_total 12575
telemt_desync_frames_bucket_total{bucket="1_2"} 4007
telemt_desync_frames_bucket_total{bucket="3_10"} 8070
telemt_desync_frames_bucket_total{bucket="gt_10"} 6293
telemt_pool_swap_total 67
telemt_pool_force_close_total 2175
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 471
telemt_me_draining_writers_reap_progress_total 21376
telemt_me_writer_removed_unexpected_total 1325
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2829
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19669
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1825
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 350
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19201
telemt_me_writer_teardown_success_total{mode="normal"} 22498
telemt_me_writer_teardown_noop_total 21386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43884
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 168.428420
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43884
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 471
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 960
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 97
telemt_me_writer_removed_unexpected_minus_restored_total 356
telemt_user_connections_total{user="hello"} 10408795
telemt_user_connections_current{user="hello"} 6308
telemt_user_octets_from_client{user="hello"} 74864150353 (69.72 GB)
telemt_user_octets_to_client{user="hello"} 784043092857 (730.20 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 2143
telemt_user_unique_ips_recent_window{user="hello"} 1331
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 66374.6 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3688943
telemt_connections_bad_total 413269
telemt_connections_current 4589
telemt_connections_me_current 4589
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 80589
telemt_upstream_connect_attempt_total 28056
telemt_upstream_connect_success_total 27748
telemt_upstream_connect_fail_total 264
telemt_upstream_connect_attempts_per_request{bucket="1"} 28012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14429
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 264
telemt_me_reconnect_attempts_total 2675
telemt_me_reconnect_success_total 971
telemt_me_reader_eof_total 966
telemt_me_idle_close_by_peer_total 966
telemt_me_route_drop_no_conn_total 1546838
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2837447
telemt_me_endpoint_quarantine_total 413
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 498
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
telemt_me_writers_active_current 44
telemt_desync_total 13469
telemt_desync_full_logged_total 4696
telemt_desync_suppressed_total 8773
telemt_desync_frames_bucket_total{bucket="1_2"} 2605
telemt_desync_frames_bucket_total{bucket="3_10"} 5329
telemt_desync_frames_bucket_total{bucket="gt_10"} 5535
telemt_pool_swap_total 66
telemt_pool_force_close_total 1918
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 193
telemt_me_draining_writers_reap_progress_total 23537
telemt_me_writer_removed_unexpected_total 936
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2315
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22190
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1663
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 255
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21619
telemt_me_writer_teardown_success_total{mode="normal"} 24505
telemt_me_writer_teardown_noop_total 23538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48043
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.323509
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48043
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 193
telemt_me_refill_failed_total 93
telemt_me_writer_restored_same_endpoint_total 832
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 2821162
telemt_user_connections_current{user="hello"} 4589
telemt_user_octets_from_client{user="hello"} 74083831440 (69.00 GB)
telemt_user_octets_to_client{user="hello"} 1183010636522 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1724
telemt_user_unique_ips_recent_window{user="hello"} 684
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 3210.3 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 517074
telemt_connections_bad_total 12312
telemt_connections_current 3899
telemt_connections_me_current 3899
telemt_handshake_timeouts_total 259058
telemt_upstream_connect_attempt_total 1281
telemt_upstream_connect_success_total 1252
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 1275
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 675
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 198
telemt_me_reconnect_success_total 67
telemt_me_reader_eof_total 60
telemt_me_idle_close_by_peer_total 60
telemt_me_route_drop_no_conn_total 209026
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 229899
telemt_me_endpoint_quarantine_total 14
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 26
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
telemt_me_writers_active_current 48
telemt_desync_total 1002
telemt_desync_full_logged_total 347
telemt_desync_suppressed_total 655
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 385
telemt_desync_frames_bucket_total{bucket="gt_10"} 453
telemt_pool_swap_total 2
telemt_pool_force_close_total 83
telemt_me_writer_close_signal_drop_total 7
telemt_me_draining_writers_reap_progress_total 1016
telemt_me_writer_removed_unexpected_total 61
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 120
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 957
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 933
telemt_me_writer_teardown_success_total{mode="normal"} 1077
telemt_me_writer_teardown_noop_total 1016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2093
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.402253
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2093
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 7
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 59
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 229609
telemt_user_connections_current{user="hello"} 3899
telemt_user_octets_from_client{user="hello"} 5456642016 (5.08 GB)
telemt_user_octets_to_client{user="hello"} 85642367092 (79.76 GB)
telemt_user_unique_ips_current{user="hello"} 1463
telemt_user_unique_ips_recent_window{user="hello"} 717
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 64360.6 (17h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1176445
telemt_connections_bad_total 136942
telemt_connections_current 825
telemt_connections_me_current 825
telemt_handshake_timeouts_total 414431
telemt_upstream_connect_attempt_total 30077
telemt_upstream_connect_success_total 30070
telemt_upstream_connect_attempts_per_request{bucket="1"} 30070
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17628
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1304
telemt_me_reconnect_success_total 536
telemt_me_reader_eof_total 534
telemt_me_idle_close_by_peer_total 534
telemt_me_route_drop_no_conn_total 255910
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 552899
telemt_me_endpoint_quarantine_total 575
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 540
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_me_writers_active_current 88
telemt_desync_total 3515
telemt_desync_full_logged_total 1288
telemt_desync_suppressed_total 2227
telemt_desync_frames_bucket_total{bucket="1_2"} 642
telemt_desync_frames_bucket_total{bucket="3_10"} 1256
telemt_desync_frames_bucket_total{bucket="gt_10"} 1617
telemt_pool_swap_total 70
telemt_pool_force_close_total 1603
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 109
telemt_me_draining_writers_reap_progress_total 26886
telemt_me_writer_removed_unexpected_total 508
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2013
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25393
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1600
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25283
telemt_me_writer_teardown_success_total{mode="normal"} 27406
telemt_me_writer_teardown_noop_total 26886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54292
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.945499
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54292
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 109
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 447
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 552591
telemt_user_connections_current{user="hello"} 825
telemt_user_octets_from_client{user="hello"} 11340813231 (10.56 GB)
telemt_user_octets_to_client{user="hello"} 209947678561 (195.53 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 66379.1 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4046275
telemt_connections_bad_total 369762
telemt_connections_current 4826
telemt_connections_me_current 4826
telemt_handshake_timeouts_total 131015
telemt_upstream_connect_attempt_total 26590
telemt_upstream_connect_success_total 26480
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 26556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13296
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_reconnect_attempts_total 1135
telemt_me_reconnect_success_total 604
telemt_me_reader_eof_total 569
telemt_me_idle_close_by_peer_total 569
telemt_me_route_drop_no_conn_total 1228272
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3218285
telemt_me_endpoint_quarantine_total 488
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 506
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
telemt_me_writers_active_current 40
telemt_desync_total 12719
telemt_desync_full_logged_total 4195
telemt_desync_suppressed_total 8524
telemt_desync_frames_bucket_total{bucket="1_2"} 3011
telemt_desync_frames_bucket_total{bucket="3_10"} 4741
telemt_desync_frames_bucket_total{bucket="gt_10"} 4967
telemt_pool_swap_total 73
telemt_pool_force_close_total 1908
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 215
telemt_me_draining_writers_reap_progress_total 23850
telemt_me_writer_removed_unexpected_total 559
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1899
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22510
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1867
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21942
telemt_me_writer_teardown_success_total{mode="normal"} 24409
telemt_me_writer_teardown_noop_total 23850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48259
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.585443
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48259
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 215
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 535
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 3210026
telemt_user_connections_current{user="hello"} 4826
telemt_user_octets_from_client{user="hello"} 65624441900 (61.12 GB)
telemt_user_octets_to_client{user="hello"} 1512675603640 (1.38 TB)
telemt_user_unique_ips_current{user="hello"} 1674
telemt_user_unique_ips_recent_window{user="hello"} 737
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 66375.7 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3604016
telemt_connections_bad_total 311848
telemt_connections_current 4202
telemt_connections_me_current 4202
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 109416
telemt_upstream_connect_attempt_total 43022
telemt_upstream_connect_success_total 42733
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 42971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15139
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 600
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_reconnect_attempts_total 3634
telemt_me_reconnect_success_total 811
telemt_me_reader_eof_total 717
telemt_me_idle_close_by_peer_total 717
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 1305065
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2902421
telemt_me_endpoint_quarantine_total 550
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 505
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
telemt_me_writers_active_current 44
telemt_desync_total 11264
telemt_desync_full_logged_total 3836
telemt_desync_suppressed_total 7428
telemt_desync_frames_bucket_total{bucket="1_2"} 2801
telemt_desync_frames_bucket_total{bucket="3_10"} 4184
telemt_desync_frames_bucket_total{bucket="gt_10"} 4279
telemt_pool_swap_total 71
telemt_pool_force_close_total 1847
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 207
telemt_me_draining_writers_reap_progress_total 23232
telemt_me_writer_removed_unexpected_total 730
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2245
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21748
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1699
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 148
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21385
telemt_me_writer_teardown_success_total{mode="normal"} 23993
telemt_me_writer_teardown_noop_total 23233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47226
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.856360
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47226
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 207
telemt_me_refill_failed_total 160
telemt_me_writer_restored_same_endpoint_total 631
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 2911147
telemt_user_connections_current{user="hello"} 4202
telemt_user_octets_from_client{user="hello"} 52513504917 (48.91 GB)
telemt_user_octets_to_client{user="hello"} 1250966100592 (1.14 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1633
telemt_user_unique_ips_recent_window{user="hello"} 639
```
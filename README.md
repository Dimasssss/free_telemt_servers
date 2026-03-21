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

# Server Metrics 2026-03-21 12:45:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 58163.3 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1899269
telemt_connections_bad_total 93465
telemt_connections_current 1560
telemt_connections_me_current 1560
telemt_handshake_timeouts_total 70905
telemt_upstream_connect_attempt_total 22503
telemt_upstream_connect_success_total 22392
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 22465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14362
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1241
telemt_me_reconnect_success_total 517
telemt_me_reader_eof_total 500
telemt_me_idle_close_by_peer_total 500
telemt_me_route_drop_no_conn_total 1445567
telemt_me_route_drop_channel_closed_total 466
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1490398
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 411
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 460
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
telemt_me_writers_active_current 42
telemt_desync_total 5775
telemt_desync_full_logged_total 2020
telemt_desync_suppressed_total 3755
telemt_desync_frames_bucket_total{bucket="1_2"} 1244
telemt_desync_frames_bucket_total{bucket="3_10"} 2223
telemt_desync_frames_bucket_total{bucket="gt_10"} 2308
telemt_pool_swap_total 63
telemt_pool_force_close_total 1849
telemt_pool_stale_pick_total 14
telemt_me_writer_close_signal_drop_total 357
telemt_me_draining_writers_reap_progress_total 20107
telemt_me_writer_removed_unexpected_total 481
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1662
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18778
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1784
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 65
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18258
telemt_me_writer_teardown_success_total{mode="normal"} 20440
telemt_me_writer_teardown_noop_total 20111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40551
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 154.423681
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40551
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 357
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 448
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1489299
telemt_user_connections_current{user="hello"} 1560
telemt_user_octets_from_client{user="hello"} 21987451107 (20.48 GB)
telemt_user_octets_to_client{user="hello"} 385793111083 (359.30 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 569
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 3808.2 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256640
telemt_connections_bad_total 15653
telemt_connections_current 2734
telemt_connections_me_current 2734
telemt_handshake_timeouts_total 15094
telemt_upstream_connect_attempt_total 1564
telemt_upstream_connect_success_total 1505
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 1546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 854
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 125
telemt_me_reconnect_success_total 94
telemt_me_reader_eof_total 91
telemt_me_idle_close_by_peer_total 91
telemt_me_route_drop_no_conn_total 212226
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 208194
telemt_me_endpoint_quarantine_total 26
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 31
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_me_writers_active_current 76
telemt_me_writers_warm_current 11
telemt_desync_total 786
telemt_desync_full_logged_total 360
telemt_desync_suppressed_total 426
telemt_desync_frames_bucket_total{bucket="1_2"} 159
telemt_desync_frames_bucket_total{bucket="3_10"} 309
telemt_desync_frames_bucket_total{bucket="gt_10"} 318
telemt_pool_swap_total 2
telemt_pool_force_close_total 80
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 1197
telemt_me_writer_removed_unexpected_total 99
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 175
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1121
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 59
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1117
telemt_me_writer_teardown_success_total{mode="normal"} 1296
telemt_me_writer_teardown_noop_total 1197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2493
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.213842
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2493
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_writer_restored_same_endpoint_total 87
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 208096
telemt_user_connections_current{user="hello"} 2734
telemt_user_octets_from_client{user="hello"} 3345985280 (3.12 GB)
telemt_user_octets_to_client{user="hello"} 52544494572 (48.94 GB)
telemt_user_unique_ips_current{user="hello"} 1393
telemt_user_unique_ips_recent_window{user="hello"} 518
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 58161.2 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3664322
telemt_connections_bad_total 378687
telemt_connections_current 4047
telemt_connections_me_current 4047
telemt_handshake_timeouts_total 143942
telemt_upstream_connect_attempt_total 22000
telemt_upstream_connect_success_total 21967
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 21972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11957
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 816
telemt_me_reconnect_success_total 454
telemt_me_reader_eof_total 463
telemt_me_idle_close_by_peer_total 463
telemt_me_route_drop_no_conn_total 1757246
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2926935
telemt_me_endpoint_quarantine_total 374
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 446
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
telemt_me_writers_active_current 45
telemt_desync_total 12469
telemt_desync_full_logged_total 4221
telemt_desync_suppressed_total 8248
telemt_desync_frames_bucket_total{bucket="1_2"} 2641
telemt_desync_frames_bucket_total{bucket="3_10"} 4880
telemt_desync_frames_bucket_total{bucket="gt_10"} 4948
telemt_pool_swap_total 62
telemt_pool_force_close_total 1956
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 287
telemt_me_draining_writers_reap_progress_total 19980
telemt_me_writer_removed_unexpected_total 447
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1692
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18556
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 16
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1815
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 141
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18024
telemt_me_writer_teardown_success_total{mode="normal"} 20248
telemt_me_writer_teardown_noop_total 19996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40244
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 56.910287
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40244
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 287
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 410
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 2923126
telemt_user_connections_current{user="hello"} 4047
telemt_user_octets_from_client{user="hello"} 47397823596 (44.14 GB)
telemt_user_octets_to_client{user="hello"} 1026459090280 (955.96 GB)
telemt_user_unique_ips_current{user="hello"} 1577
telemt_user_unique_ips_recent_window{user="hello"} 553
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 58162.0 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2999972
telemt_connections_bad_total 327661
telemt_connections_current 3901
telemt_connections_me_current 3901
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 118579
telemt_upstream_connect_attempt_total 26724
telemt_upstream_connect_success_total 26452
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 26584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12158
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 475
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1143
telemt_me_reconnect_success_total 527
telemt_me_reader_eof_total 489
telemt_me_idle_close_by_peer_total 489
telemt_me_route_drop_no_conn_total 936200
telemt_me_route_drop_channel_closed_total 76
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2146248
telemt_me_endpoint_quarantine_total 389
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 448
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
telemt_desync_total 9824
telemt_desync_full_logged_total 3352
telemt_desync_suppressed_total 6472
telemt_desync_frames_bucket_total{bucket="1_2"} 2456
telemt_desync_frames_bucket_total{bucket="3_10"} 3815
telemt_desync_frames_bucket_total{bucket="gt_10"} 3553
telemt_pool_swap_total 63
telemt_pool_force_close_total 1764
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 150
telemt_me_draining_writers_reap_progress_total 19494
telemt_me_writer_removed_unexpected_total 477
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1654
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18337
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1647
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 117
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17730
telemt_me_writer_teardown_success_total{mode="normal"} 19991
telemt_me_writer_teardown_noop_total 19495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39486
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.131298
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39486
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 150
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 442
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 2147307
telemt_user_connections_current{user="hello"} 3901
telemt_user_octets_from_client{user="hello"} 40404826461 (37.63 GB)
telemt_user_octets_to_client{user="hello"} 1016365822763 (946.56 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1444
telemt_user_unique_ips_recent_window{user="hello"} 504
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 58126.0 (16h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2917906
telemt_connections_bad_total 323532
telemt_connections_current 3356
telemt_connections_me_current 3356
telemt_handshake_timeouts_total 85873
telemt_upstream_connect_attempt_total 23355
telemt_upstream_connect_success_total 23265
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 23267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12643
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 45
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 938
telemt_me_reconnect_success_total 597
telemt_me_reader_eof_total 546
telemt_me_idle_close_by_peer_total 546
telemt_me_route_drop_no_conn_total 885033
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2125957
telemt_me_endpoint_quarantine_total 426
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 439
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
telemt_desync_total 9894
telemt_desync_full_logged_total 3309
telemt_desync_suppressed_total 6585
telemt_desync_frames_bucket_total{bucket="1_2"} 2568
telemt_desync_frames_bucket_total{bucket="3_10"} 3767
telemt_desync_frames_bucket_total{bucket="gt_10"} 3559
telemt_pool_swap_total 61
telemt_pool_force_close_total 1740
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 200
telemt_me_draining_writers_reap_progress_total 20803
telemt_me_writer_removed_unexpected_total 521
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1740
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19622
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1588
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 152
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19063
telemt_me_writer_teardown_success_total{mode="normal"} 21362
telemt_me_writer_teardown_noop_total 20807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42169
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.161163
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42169
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 200
telemt_me_refill_failed_total 19
telemt_me_writer_restored_same_endpoint_total 521
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 2122762
telemt_user_connections_current{user="hello"} 3356
telemt_user_octets_from_client{user="hello"} 47751003252 (44.47 GB)
telemt_user_octets_to_client{user="hello"} 1015703956776 (945.95 GB)
telemt_user_unique_ips_current{user="hello"} 1301
telemt_user_unique_ips_recent_window{user="hello"} 468
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 58165.3 (16h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9668157
telemt_connections_bad_total 659857
telemt_connections_current 5318
telemt_connections_me_current 5318
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 321910
telemt_upstream_connect_attempt_total 89065
telemt_upstream_connect_success_total 83888
telemt_upstream_connect_fail_total 4325
telemt_upstream_connect_attempts_per_request{bucket="1"} 88213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19997
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4325
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3485
telemt_me_reconnect_success_total 1180
telemt_me_reader_eof_total 832
telemt_me_idle_close_by_peer_total 831
telemt_me_route_drop_no_conn_total 17378787
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7963685
telemt_me_endpoint_quarantine_total 448
telemt_me_single_endpoint_outage_enter_total 67
telemt_me_single_endpoint_outage_exit_total 67
telemt_me_single_endpoint_outage_reconnect_attempt_total 152
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 152
telemt_me_single_endpoint_shadow_rotate_total 460
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 15174
telemt_desync_full_logged_total 4881
telemt_desync_suppressed_total 10293
telemt_desync_frames_bucket_total{bucket="1_2"} 3241
telemt_desync_frames_bucket_total{bucket="3_10"} 6717
telemt_desync_frames_bucket_total{bucket="gt_10"} 5216
telemt_pool_swap_total 59
telemt_pool_force_close_total 1874
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 387
telemt_me_draining_writers_reap_progress_total 19025
telemt_me_writer_removed_unexpected_total 1142
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2466
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17583
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1603
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 271
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17151
telemt_me_writer_teardown_success_total{mode="normal"} 20049
telemt_me_writer_teardown_noop_total 19034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39083
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 51.441182
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39083
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 387
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 820
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 8021408
telemt_user_connections_current{user="hello"} 5318
telemt_user_octets_from_client{user="hello"} 62719582097 (58.41 GB)
telemt_user_octets_to_client{user="hello"} 692097343256 (644.57 GB)
telemt_user_msgs_from_client{user="hello"} 173886
telemt_user_msgs_to_client{user="hello"} 472410
telemt_user_unique_ips_current{user="hello"} 1941
telemt_user_unique_ips_recent_window{user="hello"} 1084
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 58132.8 (16h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2956304
telemt_connections_bad_total 349865
telemt_connections_current 3508
telemt_connections_me_current 3508
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 64709
telemt_upstream_connect_attempt_total 24995
telemt_upstream_connect_success_total 24715
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 24965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_reconnect_attempts_total 2417
telemt_me_reconnect_success_total 846
telemt_me_reader_eof_total 835
telemt_me_idle_close_by_peer_total 835
telemt_me_route_drop_no_conn_total 1074055
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2239417
telemt_me_endpoint_quarantine_total 370
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 445
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
telemt_me_writers_active_current 48
telemt_desync_total 10299
telemt_desync_full_logged_total 3625
telemt_desync_suppressed_total 6674
telemt_desync_frames_bucket_total{bucket="1_2"} 2012
telemt_desync_frames_bucket_total{bucket="3_10"} 4133
telemt_desync_frames_bucket_total{bucket="gt_10"} 4154
telemt_pool_swap_total 59
telemt_pool_force_close_total 1659
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 151
telemt_me_draining_writers_reap_progress_total 20834
telemt_me_writer_removed_unexpected_total 808
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1995
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19674
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1472
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 187
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19175
telemt_me_writer_teardown_success_total{mode="normal"} 21669
telemt_me_writer_teardown_noop_total 20835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42504
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.392014
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42504
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 151
telemt_me_refill_failed_total 86
telemt_me_writer_restored_same_endpoint_total 713
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 2224285
telemt_user_connections_current{user="hello"} 3508
telemt_user_octets_from_client{user="hello"} 41839974108 (38.97 GB)
telemt_user_octets_to_client{user="hello"} 979289816550 (912.03 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1388
telemt_user_unique_ips_recent_window{user="hello"} 461
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 58127.5 (16h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4481503
telemt_connections_bad_total 227540
telemt_connections_current 3637
telemt_connections_me_current 3637
telemt_handshake_timeouts_total 1968497
telemt_upstream_connect_attempt_total 23221
telemt_upstream_connect_success_total 23187
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 23190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 944
telemt_me_reconnect_success_total 418
telemt_me_reader_eof_total 424
telemt_me_idle_close_by_peer_total 424
telemt_me_route_drop_no_conn_total 973711
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2003317
telemt_me_endpoint_quarantine_total 441
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 456
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
telemt_desync_total 9553
telemt_desync_full_logged_total 3400
telemt_desync_suppressed_total 6153
telemt_desync_frames_bucket_total{bucket="1_2"} 1754
telemt_desync_frames_bucket_total{bucket="3_10"} 3809
telemt_desync_frames_bucket_total{bucket="gt_10"} 3990
telemt_pool_swap_total 63
telemt_pool_force_close_total 1601
telemt_me_writer_close_signal_drop_total 136
telemt_me_draining_writers_reap_progress_total 20765
telemt_me_writer_removed_unexpected_total 408
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1419
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19779
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1546
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19164
telemt_me_writer_teardown_success_total{mode="normal"} 21198
telemt_me_writer_teardown_noop_total 20765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41963
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.228866
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41963
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 136
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 365
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 1996750
telemt_user_connections_current{user="hello"} 3637
telemt_user_octets_from_client{user="hello"} 36898144928 (34.36 GB)
telemt_user_octets_to_client{user="hello"} 946934301976 (881.90 GB)
telemt_user_unique_ips_current{user="hello"} 1421
telemt_user_unique_ips_recent_window{user="hello"} 495
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 56118.7 (15h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 954151
telemt_connections_bad_total 106237
telemt_connections_current 694
telemt_connections_me_current 694
telemt_handshake_timeouts_total 337867
telemt_upstream_connect_attempt_total 26629
telemt_upstream_connect_success_total 26626
telemt_upstream_connect_attempts_per_request{bucket="1"} 26626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1120
telemt_me_reconnect_success_total 435
telemt_me_reader_eof_total 434
telemt_me_idle_close_by_peer_total 434
telemt_me_route_drop_no_conn_total 197411
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 444896
telemt_me_endpoint_quarantine_total 516
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 477
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
telemt_desync_total 3080
telemt_desync_full_logged_total 1152
telemt_desync_suppressed_total 1928
telemt_desync_frames_bucket_total{bucket="1_2"} 540
telemt_desync_frames_bucket_total{bucket="3_10"} 1098
telemt_desync_frames_bucket_total{bucket="gt_10"} 1442
telemt_pool_swap_total 62
telemt_pool_force_close_total 1393
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 99
telemt_me_draining_writers_reap_progress_total 23876
telemt_me_writer_removed_unexpected_total 411
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1745
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22550
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1390
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22483
telemt_me_writer_teardown_success_total{mode="normal"} 24295
telemt_me_writer_teardown_noop_total 23876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48171
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.005512
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48171
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 99
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 354
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 444717
telemt_user_connections_current{user="hello"} 694
telemt_user_octets_from_client{user="hello"} 7200834495 (6.71 GB)
telemt_user_octets_to_client{user="hello"} 169647870997 (158.00 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 274
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 58137.3 (16h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3177811
telemt_connections_bad_total 310992
telemt_connections_current 4362
telemt_connections_me_current 4362
telemt_handshake_timeouts_total 92037
telemt_upstream_connect_attempt_total 24057
telemt_upstream_connect_success_total 23957
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 24026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12017
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 973
telemt_me_reconnect_success_total 550
telemt_me_reader_eof_total 514
telemt_me_idle_close_by_peer_total 514
telemt_me_route_drop_no_conn_total 864369
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2496429
telemt_me_endpoint_quarantine_total 445
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 450
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
telemt_desync_total 10148
telemt_desync_full_logged_total 3341
telemt_desync_suppressed_total 6807
telemt_desync_frames_bucket_total{bucket="1_2"} 2418
telemt_desync_frames_bucket_total{bucket="3_10"} 3799
telemt_desync_frames_bucket_total{bucket="gt_10"} 3931
telemt_pool_swap_total 64
telemt_pool_force_close_total 1626
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 174
telemt_me_draining_writers_reap_progress_total 21588
telemt_me_writer_removed_unexpected_total 505
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1673
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20437
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1596
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19962
telemt_me_writer_teardown_success_total{mode="normal"} 22110
telemt_me_writer_teardown_noop_total 21588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43698
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.466928
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43698
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 174
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 490
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 2489390
telemt_user_connections_current{user="hello"} 4362
telemt_user_octets_from_client{user="hello"} 52678182932 (49.06 GB)
telemt_user_octets_to_client{user="hello"} 1170382391684 (1.06 TB)
telemt_user_unique_ips_current{user="hello"} 1533
telemt_user_unique_ips_recent_window{user="hello"} 571
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 58134.0 (16h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2862015
telemt_connections_bad_total 238043
telemt_connections_current 3430
telemt_connections_me_current 3430
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 80844
telemt_upstream_connect_attempt_total 40232
telemt_upstream_connect_success_total 39973
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 40188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13652
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 586
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_reconnect_attempts_total 3413
telemt_me_reconnect_success_total 726
telemt_me_reader_eof_total 627
telemt_me_idle_close_by_peer_total 627
telemt_me_seq_mismatch_total 29
telemt_me_route_drop_no_conn_total 925167
telemt_me_route_drop_channel_closed_total 65
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2301787
telemt_me_endpoint_quarantine_total 503
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 449
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
telemt_me_writers_active_current 50
telemt_desync_total 8832
telemt_desync_full_logged_total 3018
telemt_desync_suppressed_total 5814
telemt_desync_frames_bucket_total{bucket="1_2"} 2275
telemt_desync_frames_bucket_total{bucket="3_10"} 3259
telemt_desync_frames_bucket_total{bucket="gt_10"} 3298
telemt_pool_swap_total 63
telemt_pool_force_close_total 1587
telemt_me_writer_close_signal_drop_total 152
telemt_me_draining_writers_reap_progress_total 20762
telemt_me_writer_removed_unexpected_total 640
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1960
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19470
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1483
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 104
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19175
telemt_me_writer_teardown_success_total{mode="normal"} 21430
telemt_me_writer_teardown_noop_total 20763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42193
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.550241
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42193
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 152
telemt_me_refill_failed_total 152
telemt_me_writer_restored_same_endpoint_total 551
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 2311978
telemt_user_connections_current{user="hello"} 3430
telemt_user_octets_from_client{user="hello"} 43071005589 (40.11 GB)
telemt_user_octets_to_client{user="hello"} 1013680780612 (944.06 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1369
telemt_user_unique_ips_recent_window{user="hello"} 473
```
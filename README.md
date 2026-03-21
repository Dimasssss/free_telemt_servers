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

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
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
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
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

# Server Metrics 2026-03-21 22:26:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 4801.5 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89092
telemt_connections_bad_total 6462
telemt_connections_current 634
telemt_connections_me_current 634
telemt_handshake_timeouts_total 4181
telemt_upstream_connect_attempt_total 1923
telemt_upstream_connect_success_total 1922
telemt_upstream_connect_attempts_per_request{bucket="1"} 1922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1220
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 43
telemt_me_reconnect_success_total 25
telemt_me_reader_eof_total 26
telemt_me_idle_close_by_peer_total 26
telemt_me_route_drop_no_conn_total 18632
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72258
telemt_me_endpoint_quarantine_total 31
telemt_me_single_endpoint_shadow_rotate_total 44
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_me_writers_active_current 43
telemt_desync_total 512
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 354
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 162
telemt_desync_frames_bucket_total{bucket="gt_10"} 253
telemt_pool_swap_total 5
telemt_pool_force_close_total 134
telemt_me_writer_close_signal_drop_total 10
telemt_me_draining_writers_reap_progress_total 1673
telemt_me_writer_removed_unexpected_total 24
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 123
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1576
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 130
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1539
telemt_me_writer_teardown_success_total{mode="normal"} 1699
telemt_me_writer_teardown_noop_total 1673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3372
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.127564
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3372
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 10
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 23
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 72188
telemt_user_connections_current{user="hello"} 634
telemt_user_octets_from_client{user="hello"} 981910680 (936.42 MB)
telemt_user_octets_to_client{user="hello"} 27234085720 (25.36 GB)
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 18168.3 (5h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 601712
telemt_connections_bad_total 27889
telemt_connections_current 1083
telemt_connections_me_current 1083
telemt_handshake_timeouts_total 21799
telemt_upstream_connect_attempt_total 7406
telemt_upstream_connect_success_total 7268
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 7391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3993
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_reconnect_attempts_total 622
telemt_me_reconnect_success_total 224
telemt_me_reader_eof_total 192
telemt_me_idle_close_by_peer_total 192
telemt_me_route_drop_no_conn_total 312053
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 489435
telemt_me_endpoint_quarantine_total 151
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 145
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_me_writers_active_current 43
telemt_desync_total 2184
telemt_desync_full_logged_total 1240
telemt_desync_suppressed_total 944
telemt_desync_frames_bucket_total{bucket="1_2"} 458
telemt_desync_frames_bucket_total{bucket="3_10"} 833
telemt_desync_frames_bucket_total{bucket="gt_10"} 893
telemt_pool_swap_total 20
telemt_pool_force_close_total 554
telemt_me_writer_close_signal_drop_total 43
telemt_me_draining_writers_reap_progress_total 6472
telemt_me_writer_removed_unexpected_total 181
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 573
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6078
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 547
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5918
telemt_me_writer_teardown_success_total{mode="normal"} 6651
telemt_me_writer_teardown_noop_total 6472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13123
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.097662
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13123
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 43
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 155
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 488794
telemt_user_connections_current{user="hello"} 1083
telemt_user_octets_from_client{user="hello"} 8434282144 (7.86 GB)
telemt_user_octets_to_client{user="hello"} 166879417784 (155.42 GB)
telemt_user_unique_ips_current{user="hello"} 691
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 93028.4 (25h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7242947
telemt_connections_bad_total 554618
telemt_connections_current 1915
telemt_connections_me_current 1915
telemt_handshake_timeouts_total 227516
telemt_upstream_connect_attempt_total 33475
telemt_upstream_connect_success_total 33407
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 33414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18168
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1456
telemt_me_reconnect_success_total 708
telemt_me_reader_eof_total 719
telemt_me_idle_close_by_peer_total 719
telemt_me_route_drop_no_conn_total 4461780
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5929180
telemt_me_endpoint_quarantine_total 587
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 687
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
telemt_desync_total 25044
telemt_desync_full_logged_total 8240
telemt_desync_suppressed_total 16804
telemt_desync_frames_bucket_total{bucket="1_2"} 5382
telemt_desync_frames_bucket_total{bucket="3_10"} 9809
telemt_desync_frames_bucket_total{bucket="gt_10"} 9853
telemt_pool_swap_total 100
telemt_pool_force_close_total 3390
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 554
telemt_me_draining_writers_reap_progress_total 30504
telemt_me_writer_removed_unexpected_total 691
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2609
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28163
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3151
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27114
telemt_me_writer_teardown_success_total{mode="normal"} 30772
telemt_me_writer_teardown_noop_total 30548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61320
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 150.486612
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61320
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 554
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 633
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 5921930
telemt_user_connections_current{user="hello"} 1915
telemt_user_octets_from_client{user="hello"} 101696727484 (94.71 GB)
telemt_user_octets_to_client{user="hello"} 1918364232800 (1.74 TB)
telemt_user_unique_ips_current{user="hello"} 807
telemt_user_unique_ips_recent_window{user="hello"} 261
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 93029.6 (25h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5944020
telemt_connections_bad_total 573452
telemt_connections_current 1875
telemt_connections_me_current 1875
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 194619
telemt_upstream_connect_attempt_total 37462
telemt_upstream_connect_success_total 37128
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 37302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17845
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1734
telemt_me_reconnect_success_total 738
telemt_me_reader_eof_total 713
telemt_me_idle_close_by_peer_total 713
telemt_me_route_drop_no_conn_total 2086567
telemt_me_route_drop_channel_closed_total 241
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4442444
telemt_me_endpoint_quarantine_total 566
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 711
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
telemt_desync_total 21401
telemt_desync_full_logged_total 7160
telemt_desync_suppressed_total 14241
telemt_desync_frames_bucket_total{bucket="1_2"} 5179
telemt_desync_frames_bucket_total{bucket="3_10"} 8269
telemt_desync_frames_bucket_total{bucket="gt_10"} 7953
telemt_pool_swap_total 102
telemt_pool_force_close_total 3092
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 341
telemt_me_draining_writers_reap_progress_total 29121
telemt_me_writer_removed_unexpected_total 690
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2506
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27237
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2893
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26029
telemt_me_writer_teardown_success_total{mode="normal"} 29743
telemt_me_writer_teardown_noop_total 29127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58870
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.131921
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58870
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 341
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 636
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 4407938
telemt_user_connections_current{user="hello"} 1875
telemt_user_octets_from_client{user="hello"} 136395688633 (127.03 GB)
telemt_user_octets_to_client{user="hello"} 2052728962335 (1.87 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 828
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 92992.9 (25h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5866024
telemt_connections_bad_total 532461
telemt_connections_current 1749
telemt_connections_me_current 1749
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 183896
telemt_upstream_connect_attempt_total 43842
telemt_upstream_connect_success_total 43546
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 43681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19288
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1044
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1778
telemt_me_reconnect_success_total 795
telemt_me_reader_eof_total 741
telemt_me_idle_close_by_peer_total 741
telemt_me_route_drop_no_conn_total 2070790
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4391898
telemt_me_endpoint_quarantine_total 624
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 693
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 21209
telemt_desync_full_logged_total 6970
telemt_desync_suppressed_total 14239
telemt_desync_frames_bucket_total{bucket="1_2"} 5245
telemt_desync_frames_bucket_total{bucket="3_10"} 8045
telemt_desync_frames_bucket_total{bucket="gt_10"} 7919
telemt_pool_swap_total 100
telemt_pool_force_close_total 2969
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 356
telemt_me_draining_writers_reap_progress_total 30525
telemt_me_writer_removed_unexpected_total 710
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2586
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28654
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2754
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27556
telemt_me_writer_teardown_success_total{mode="normal"} 31240
telemt_me_writer_teardown_noop_total 30536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61776
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.992879
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61776
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 356
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 688
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 4393553
telemt_user_connections_current{user="hello"} 1749
telemt_user_octets_from_client{user="hello"} 129408198579 (120.52 GB)
telemt_user_octets_to_client{user="hello"} 2008890462039 (1.83 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 831
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 93032.7 (25h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19659878
telemt_connections_bad_total 1375098
telemt_connections_current 2601
telemt_connections_me_current 2601
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 559384
telemt_upstream_connect_attempt_total 183534
telemt_upstream_connect_success_total 166210
telemt_upstream_connect_fail_total 15823
telemt_upstream_connect_attempts_per_request{bucket="1"} 182033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38083
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8858
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15823
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 60239
telemt_me_reconnect_success_total 1986
telemt_me_reader_eof_total 1288
telemt_me_idle_close_by_peer_total 1287
telemt_me_route_drop_no_conn_total 39402037
telemt_me_route_drop_channel_closed_total 120
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16081792
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 690
telemt_me_single_endpoint_outage_enter_total 112
telemt_me_single_endpoint_outage_exit_total 112
telemt_me_single_endpoint_outage_reconnect_attempt_total 240
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 240
telemt_me_single_endpoint_shadow_rotate_total 721
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_me_writers_active_current 47
telemt_desync_total 30784
telemt_desync_full_logged_total 9110
telemt_desync_suppressed_total 21674
telemt_desync_frames_bucket_total{bucket="1_2"} 6740
telemt_desync_frames_bucket_total{bucket="3_10"} 13640
telemt_desync_frames_bucket_total{bucket="gt_10"} 10404
telemt_pool_swap_total 95
telemt_pool_force_close_total 3202
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 723
telemt_me_draining_writers_reap_progress_total 28765
telemt_me_writer_removed_unexpected_total 1861
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3913
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26440
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2694
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 508
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25563
telemt_me_writer_teardown_success_total{mode="normal"} 30353
telemt_me_writer_teardown_noop_total 28791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59144
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 208.549171
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59144
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 723
telemt_me_refill_failed_total 3549
telemt_me_writer_restored_same_endpoint_total 1396
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14284
telemt_me_writer_removed_unexpected_minus_restored_total 451
telemt_user_connections_total{user="hello"} 16206698
telemt_user_connections_current{user="hello"} 2601
telemt_user_octets_from_client{user="hello"} 170867158938 (159.13 GB)
telemt_user_octets_to_client{user="hello"} 1054061614950 (981.67 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1126
telemt_user_unique_ips_recent_window{user="hello"} 287
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 92999.8 (25h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5691032
telemt_connections_bad_total 534013
telemt_connections_current 1940
telemt_connections_me_current 1940
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 117812
telemt_upstream_connect_attempt_total 51292
telemt_upstream_connect_success_total 50742
telemt_upstream_connect_fail_total 464
telemt_upstream_connect_attempts_per_request{bucket="1"} 51206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19800
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 464
telemt_me_reconnect_attempts_total 11762
telemt_me_reconnect_success_total 1339
telemt_me_reader_eof_total 1243
telemt_me_idle_close_by_peer_total 1243
telemt_me_route_drop_no_conn_total 2330069
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4431630
telemt_me_endpoint_quarantine_total 583
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 696
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_me_writers_active_current 43
telemt_desync_total 22305
telemt_desync_full_logged_total 7754
telemt_desync_suppressed_total 14551
telemt_desync_frames_bucket_total{bucket="1_2"} 4251
telemt_desync_frames_bucket_total{bucket="3_10"} 8656
telemt_desync_frames_bucket_total{bucket="gt_10"} 9398
telemt_pool_swap_total 95
telemt_pool_force_close_total 2785
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 361
telemt_me_draining_writers_reap_progress_total 31490
telemt_me_writer_removed_unexpected_total 1244
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3216
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29532
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2417
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28705
telemt_me_writer_teardown_success_total{mode="normal"} 32748
telemt_me_writer_teardown_noop_total 31491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64239
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.640487
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64239
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 361
telemt_me_refill_failed_total 625
telemt_me_writer_restored_same_endpoint_total 1116
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 1544
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 4424760
telemt_user_connections_current{user="hello"} 1940
telemt_user_octets_from_client{user="hello"} 117413635060 (109.35 GB)
telemt_user_octets_to_client{user="hello"} 1799811286378 (1.64 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 848
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 29835.5 (8h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3523556
telemt_connections_bad_total 124751
telemt_connections_current 1707
telemt_connections_me_current 1707
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1486142
telemt_upstream_connect_attempt_total 15324
telemt_upstream_connect_success_total 15199
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 15318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_reconnect_attempts_total 22080
telemt_me_reconnect_success_total 540
telemt_me_reader_eof_total 374
telemt_me_idle_close_by_peer_total 374
telemt_me_route_drop_no_conn_total 972316
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1684417
telemt_me_endpoint_quarantine_total 182
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 222
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 13
telemt_me_floor_swap_idle_failed_total 13
telemt_desync_total 9301
telemt_desync_full_logged_total 3131
telemt_desync_suppressed_total 6170
telemt_desync_frames_bucket_total{bucket="1_2"} 1653
telemt_desync_frames_bucket_total{bucket="3_10"} 3563
telemt_desync_frames_bucket_total{bucket="gt_10"} 4085
telemt_pool_swap_total 32
telemt_pool_force_close_total 1027
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 99
telemt_me_draining_writers_reap_progress_total 9006
telemt_me_writer_removed_unexpected_total 409
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 939
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8490
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 878
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 149
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7979
telemt_me_writer_teardown_success_total{mode="normal"} 9429
telemt_me_writer_teardown_noop_total 9007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 18330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 18436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 18436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 18436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 18436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 18436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 18436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 18436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 18436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 18436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 18436
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.713237
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 18436
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 99
telemt_me_refill_failed_total 1212
telemt_me_writer_restored_same_endpoint_total 472
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 160
telemt_me_async_recovery_trigger_total 2130
telemt_user_connections_total{user="hello"} 1684562
telemt_user_connections_current{user="hello"} 1707
telemt_user_octets_from_client{user="hello"} 48696103116 (45.35 GB)
telemt_user_octets_to_client{user="hello"} 722570008942 (672.95 GB)
telemt_user_msgs_from_client{user="hello"} 43112
telemt_user_msgs_to_client{user="hello"} 113951
telemt_user_unique_ips_current{user="hello"} 729
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 10806.5 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128738
telemt_connections_bad_total 1319
telemt_connections_current 450
telemt_connections_me_current 450
telemt_handshake_timeouts_total 3303
telemt_upstream_connect_attempt_total 4665
telemt_upstream_connect_success_total 4652
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 4664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2656
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 98
telemt_me_reconnect_success_total 50
telemt_me_reader_eof_total 51
telemt_me_idle_close_by_peer_total 51
telemt_me_route_drop_no_conn_total 36682
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111501
telemt_me_endpoint_quarantine_total 81
telemt_me_single_endpoint_shadow_rotate_total 93
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 910
telemt_desync_full_logged_total 222
telemt_desync_suppressed_total 688
telemt_desync_frames_bucket_total{bucket="1_2"} 375
telemt_desync_frames_bucket_total{bucket="3_10"} 326
telemt_desync_frames_bucket_total{bucket="gt_10"} 209
telemt_pool_swap_total 11
telemt_pool_force_close_total 279
telemt_me_writer_close_signal_drop_total 13
telemt_me_draining_writers_reap_progress_total 4126
telemt_me_writer_removed_unexpected_total 51
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 255
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3922
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 277
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3847
telemt_me_writer_teardown_success_total{mode="normal"} 4177
telemt_me_writer_teardown_noop_total 4126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 8293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 8303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8303
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.548108
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8303
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 13
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 111341
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 2233531588 (2.08 GB)
telemt_user_octets_to_client{user="hello"} 67584429540 (62.94 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 93004.6 (25h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6797600
telemt_connections_bad_total 685976
telemt_connections_current 2234
telemt_connections_me_current 2234
telemt_handshake_timeouts_total 194564
telemt_upstream_connect_attempt_total 35225
telemt_upstream_connect_success_total 35084
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 35188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17665
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_reconnect_attempts_total 1433
telemt_me_reconnect_success_total 737
telemt_me_reader_eof_total 714
telemt_me_idle_close_by_peer_total 714
telemt_me_route_drop_no_conn_total 2066021
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5184963
telemt_me_endpoint_quarantine_total 621
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 712
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
telemt_me_writers_active_current 47
telemt_desync_total 19889
telemt_desync_full_logged_total 6636
telemt_desync_suppressed_total 13253
telemt_desync_frames_bucket_total{bucket="1_2"} 4849
telemt_desync_frames_bucket_total{bucket="3_10"} 7248
telemt_desync_frames_bucket_total{bucket="gt_10"} 7792
telemt_pool_swap_total 103
telemt_pool_force_close_total 2824
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 353
telemt_me_draining_writers_reap_progress_total 31656
telemt_me_writer_removed_unexpected_total 693
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2573
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29787
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2736
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28832
telemt_me_writer_teardown_success_total{mode="normal"} 32360
telemt_me_writer_teardown_noop_total 31658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64018
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.288587
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64018
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 353
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 659
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 5160379
telemt_user_connections_current{user="hello"} 2234
telemt_user_octets_from_client{user="hello"} 104108904820 (96.96 GB)
telemt_user_octets_to_client{user="hello"} 2424178710500 (2.20 TB)
telemt_user_unique_ips_current{user="hello"} 901
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 93001.0 (25h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5792171
telemt_connections_bad_total 549601
telemt_connections_current 2025
telemt_connections_me_current 2025
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 163188
telemt_upstream_connect_attempt_total 51361
telemt_upstream_connect_success_total 50971
telemt_upstream_connect_fail_total 331
telemt_upstream_connect_attempts_per_request{bucket="1"} 51302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19419
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 331
telemt_me_reconnect_attempts_total 5220
telemt_me_reconnect_success_total 1044
telemt_me_reader_eof_total 921
telemt_me_idle_close_by_peer_total 921
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2118755
telemt_me_route_drop_channel_closed_total 188
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4551838
telemt_me_endpoint_quarantine_total 726
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 706
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
telemt_me_writers_active_current 43
telemt_desync_total 18561
telemt_desync_full_logged_total 6266
telemt_desync_suppressed_total 12295
telemt_desync_frames_bucket_total{bucket="1_2"} 4620
telemt_desync_frames_bucket_total{bucket="3_10"} 6765
telemt_desync_frames_bucket_total{bucket="gt_10"} 7176
telemt_pool_swap_total 101
telemt_pool_force_close_total 2779
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 358
telemt_me_draining_writers_reap_progress_total 30610
telemt_me_writer_removed_unexpected_total 931
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3070
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28514
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2556
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27831
telemt_me_writer_teardown_success_total{mode="normal"} 31584
telemt_me_writer_teardown_noop_total 30614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62198
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.487198
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62198
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 358
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 807
telemt_me_writer_restored_fallback_total 49
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 4555381
telemt_user_connections_current{user="hello"} 2025
telemt_user_octets_from_client{user="hello"} 87402036105 (81.40 GB)
telemt_user_octets_to_client{user="hello"} 1951980209956 (1.78 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 862
telemt_user_unique_ips_recent_window{user="hello"} 207
```
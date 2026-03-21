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

# Server Metrics 2026-03-21 15:33:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 68252.9 (18h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2416532
telemt_connections_bad_total 126278
telemt_connections_current 1431
telemt_connections_me_current 1431
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 77920
telemt_upstream_connect_attempt_total 29080
telemt_upstream_connect_success_total 28953
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 29037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16855
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1653
telemt_me_reconnect_success_total 665
telemt_me_reader_eof_total 638
telemt_me_idle_close_by_peer_total 638
telemt_me_route_drop_no_conn_total 2110842
telemt_me_route_drop_channel_closed_total 643
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1935077
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 476
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 532
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 7579
telemt_desync_full_logged_total 2618
telemt_desync_suppressed_total 4961
telemt_desync_frames_bucket_total{bucket="1_2"} 1663
telemt_desync_frames_bucket_total{bucket="3_10"} 2883
telemt_desync_frames_bucket_total{bucket="gt_10"} 3033
telemt_pool_swap_total 73
telemt_pool_force_close_total 2212
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 502
telemt_me_draining_writers_reap_progress_total 23281
telemt_me_writer_removed_unexpected_total 616
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1994
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21687
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2096
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 116
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21069
telemt_me_writer_teardown_success_total{mode="normal"} 23681
telemt_me_writer_teardown_noop_total 23287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46968
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 220.888110
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46968
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 502
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 570
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1936566
telemt_user_connections_current{user="hello"} 1431
telemt_user_octets_from_client{user="hello"} 27218121749 (25.35 GB)
telemt_user_octets_to_client{user="hello"} 477556554902 (444.76 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 549
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 647.6 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24158
telemt_connections_bad_total 1037
telemt_connections_current 997
telemt_connections_me_current 997
telemt_handshake_timeouts_total 586
telemt_upstream_connect_attempt_total 314
telemt_upstream_connect_success_total 310
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 160
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 12491
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20548
telemt_me_endpoint_quarantine_total 6
telemt_me_single_endpoint_shadow_rotate_total 8
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
telemt_desync_total 46
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_me_draining_writers_reap_progress_total 204
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 204
telemt_me_writer_teardown_success_total{mode="normal"} 204
telemt_me_writer_teardown_noop_total 204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 408
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.013085
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 408
telemt_user_connections_total{user="hello"} 20508
telemt_user_connections_current{user="hello"} 997
telemt_user_octets_from_client{user="hello"} 205734068 (196.20 MB)
telemt_user_octets_to_client{user="hello"} 5600444712 (5.22 GB)
telemt_user_unique_ips_current{user="hello"} 638
telemt_user_unique_ips_recent_window{user="hello"} 431
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 68250.6 (18h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4840148
telemt_connections_bad_total 438129
telemt_connections_current 5491
telemt_connections_me_current 5491
telemt_handshake_timeouts_total 172376
telemt_upstream_connect_attempt_total 25271
telemt_upstream_connect_success_total 25218
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 25223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13761
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1154
telemt_me_reconnect_success_total 580
telemt_me_reader_eof_total 584
telemt_me_idle_close_by_peer_total 584
telemt_me_route_drop_no_conn_total 2685580
telemt_me_route_drop_channel_closed_total 45
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3951273
telemt_me_endpoint_quarantine_total 428
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 514
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
telemt_me_writers_active_current 46
telemt_desync_total 16198
telemt_desync_full_logged_total 5443
telemt_desync_suppressed_total 10755
telemt_desync_frames_bucket_total{bucket="1_2"} 3442
telemt_desync_frames_bucket_total{bucket="3_10"} 6389
telemt_desync_frames_bucket_total{bucket="gt_10"} 6367
telemt_pool_swap_total 72
telemt_pool_force_close_total 2342
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 366
telemt_me_draining_writers_reap_progress_total 22915
telemt_me_writer_removed_unexpected_total 565
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2008
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21241
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2144
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 198
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20573
telemt_me_writer_teardown_success_total{mode="normal"} 23249
telemt_me_writer_teardown_noop_total 22947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46196
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 80.969734
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46196
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 366
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 522
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 3946480
telemt_user_connections_current{user="hello"} 5491
telemt_user_octets_from_client{user="hello"} 63425252140 (59.07 GB)
telemt_user_octets_to_client{user="hello"} 1302677326024 (1.18 TB)
telemt_user_unique_ips_current{user="hello"} 2136
telemt_user_unique_ips_recent_window{user="hello"} 654
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 68252.2 (18h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3925612
telemt_connections_bad_total 422023
telemt_connections_current 3951
telemt_connections_me_current 3951
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 139659
telemt_upstream_connect_attempt_total 29673
telemt_upstream_connect_success_total 29392
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 29531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13782
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 485
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1383
telemt_me_reconnect_success_total 603
telemt_me_reader_eof_total 563
telemt_me_idle_close_by_peer_total 563
telemt_me_route_drop_no_conn_total 1234560
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2876314
telemt_me_endpoint_quarantine_total 441
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 518
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 13382
telemt_desync_full_logged_total 4493
telemt_desync_suppressed_total 8889
telemt_desync_frames_bucket_total{bucket="1_2"} 3374
telemt_desync_frames_bucket_total{bucket="3_10"} 5152
telemt_desync_frames_bucket_total{bucket="gt_10"} 4856
telemt_pool_swap_total 74
telemt_pool_force_close_total 2140
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 213
telemt_me_draining_writers_reap_progress_total 22119
telemt_me_writer_removed_unexpected_total 547
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1908
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20760
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1987
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 153
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19979
telemt_me_writer_teardown_success_total{mode="normal"} 22668
telemt_me_writer_teardown_noop_total 22120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44788
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 21.942211
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44788
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 213
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 507
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 2875995
telemt_user_connections_current{user="hello"} 3951
telemt_user_octets_from_client{user="hello"} 56163322365 (52.31 GB)
telemt_user_octets_to_client{user="hello"} 1339185541339 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1568
telemt_user_unique_ips_recent_window{user="hello"} 596
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 68215.8 (18h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3857568
telemt_connections_bad_total 398073
telemt_connections_current 3887
telemt_connections_me_current 3887
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 116342
telemt_upstream_connect_attempt_total 34953
telemt_upstream_connect_success_total 34717
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 34850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15115
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 854
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1389
telemt_me_reconnect_success_total 654
telemt_me_reader_eof_total 595
telemt_me_idle_close_by_peer_total 595
telemt_me_route_drop_no_conn_total 1341416
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2863563
telemt_me_endpoint_quarantine_total 483
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 509
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
telemt_desync_total 13195
telemt_desync_full_logged_total 4385
telemt_desync_suppressed_total 8810
telemt_desync_frames_bucket_total{bucket="1_2"} 3309
telemt_desync_frames_bucket_total{bucket="3_10"} 4933
telemt_desync_frames_bucket_total{bucket="gt_10"} 4953
telemt_pool_swap_total 72
telemt_pool_force_close_total 2067
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 235
telemt_me_draining_writers_reap_progress_total 23562
telemt_me_writer_removed_unexpected_total 566
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1987
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22178
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1887
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 180
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21495
telemt_me_writer_teardown_success_total{mode="normal"} 24165
telemt_me_writer_teardown_noop_total 23568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47733
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.701107
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47733
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 235
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 564
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2867415
telemt_user_connections_current{user="hello"} 3887
telemt_user_octets_from_client{user="hello"} 60691041613 (56.52 GB)
telemt_user_octets_to_client{user="hello"} 1326172539268 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1517
telemt_user_unique_ips_recent_window{user="hello"} 581
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 68255.0 (18h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13245080
telemt_connections_bad_total 860106
telemt_connections_current 6644
telemt_connections_me_current 6644
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 401077
telemt_upstream_connect_attempt_total 116097
telemt_upstream_connect_success_total 106201
telemt_upstream_connect_fail_total 8852
telemt_upstream_connect_attempts_per_request{bucket="1"} 115053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8852
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 3870
telemt_me_reconnect_success_total 1413
telemt_me_reader_eof_total 983
telemt_me_idle_close_by_peer_total 982
telemt_me_route_drop_no_conn_total 25775201
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10889440
telemt_me_endpoint_quarantine_total 523
telemt_me_single_endpoint_outage_enter_total 78
telemt_me_single_endpoint_outage_exit_total 78
telemt_me_single_endpoint_outage_reconnect_attempt_total 174
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 174
telemt_me_single_endpoint_shadow_rotate_total 533
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
telemt_me_writers_active_current 49
telemt_desync_total 19268
telemt_desync_full_logged_total 6027
telemt_desync_suppressed_total 13241
telemt_desync_frames_bucket_total{bucket="1_2"} 4186
telemt_desync_frames_bucket_total{bucket="3_10"} 8487
telemt_desync_frames_bucket_total{bucket="gt_10"} 6595
telemt_pool_swap_total 69
telemt_pool_force_close_total 2247
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 493
telemt_me_draining_writers_reap_progress_total 21858
telemt_me_writer_removed_unexpected_total 1344
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2885
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20109
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1881
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 366
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19611
telemt_me_writer_teardown_success_total{mode="normal"} 22994
telemt_me_writer_teardown_noop_total 21870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44864
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 172.087896
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44864
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 493
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 987
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 10964504
telemt_user_connections_current{user="hello"} 6644
telemt_user_octets_from_client{user="hello"} 77605722977 (72.28 GB)
telemt_user_octets_to_client{user="hello"} 804813176465 (749.54 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 2111
telemt_user_unique_ips_recent_window{user="hello"} 1126
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 68222.6 (18h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3868246
telemt_connections_bad_total 425392
telemt_connections_current 4216
telemt_connections_me_current 4216
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 83415
telemt_upstream_connect_attempt_total 28575
telemt_upstream_connect_success_total 28265
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 28531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14718
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_reconnect_attempts_total 2721
telemt_me_reconnect_success_total 983
telemt_me_reader_eof_total 980
telemt_me_idle_close_by_peer_total 980
telemt_me_route_drop_no_conn_total 1638608
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2986181
telemt_me_endpoint_quarantine_total 421
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 510
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
telemt_me_writers_active_current 42
telemt_desync_total 14113
telemt_desync_full_logged_total 4922
telemt_desync_suppressed_total 9191
telemt_desync_frames_bucket_total{bucket="1_2"} 2757
telemt_desync_frames_bucket_total{bucket="3_10"} 5589
telemt_desync_frames_bucket_total{bucket="gt_10"} 5767
telemt_pool_swap_total 68
telemt_pool_force_close_total 1980
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 200
telemt_me_draining_writers_reap_progress_total 24010
telemt_me_writer_removed_unexpected_total 950
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2370
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22623
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1722
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 258
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22030
telemt_me_writer_teardown_success_total{mode="normal"} 24993
telemt_me_writer_teardown_noop_total 24011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49004
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.414539
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49004
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 200
telemt_me_refill_failed_total 95
telemt_me_writer_restored_same_endpoint_total 844
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 2969670
telemt_user_connections_current{user="hello"} 4216
telemt_user_octets_from_client{user="hello"} 77726994952 (72.39 GB)
telemt_user_octets_to_client{user="hello"} 1231026623002 (1.12 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1672
telemt_user_unique_ips_recent_window{user="hello"} 603
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 5058.2 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 811951
telemt_connections_bad_total 22604
telemt_connections_current 3526
telemt_connections_me_current 3526
telemt_handshake_timeouts_total 395135
telemt_upstream_connect_attempt_total 1855
telemt_upstream_connect_success_total 1817
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 1849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 970
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 246
telemt_me_reconnect_success_total 81
telemt_me_reader_eof_total 72
telemt_me_idle_close_by_peer_total 72
telemt_me_route_drop_no_conn_total 364445
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366520
telemt_me_endpoint_quarantine_total 21
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 40
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
telemt_me_writers_active_current 43
telemt_desync_total 1700
telemt_desync_full_logged_total 567
telemt_desync_suppressed_total 1133
telemt_desync_frames_bucket_total{bucket="1_2"} 286
telemt_desync_frames_bucket_total{bucket="3_10"} 657
telemt_desync_frames_bucket_total{bucket="gt_10"} 757
telemt_pool_swap_total 4
telemt_pool_force_close_total 143
telemt_me_writer_close_signal_drop_total 11
telemt_me_draining_writers_reap_progress_total 1534
telemt_me_writer_removed_unexpected_total 73
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 160
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1447
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 105
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 38
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1391
telemt_me_writer_teardown_success_total{mode="normal"} 1607
telemt_me_writer_teardown_noop_total 1534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3141
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.751404
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3141
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 11
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 70
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 365995
telemt_user_connections_current{user="hello"} 3526
telemt_user_octets_from_client{user="hello"} 10485847328 (9.77 GB)
telemt_user_octets_to_client{user="hello"} 133058082840 (123.92 GB)
telemt_user_unique_ips_current{user="hello"} 1409
telemt_user_unique_ips_recent_window{user="hello"} 564
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 66208.5 (18h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1234588
telemt_connections_bad_total 138630
telemt_connections_current 770
telemt_connections_me_current 770
telemt_handshake_timeouts_total 441822
telemt_upstream_connect_attempt_total 30976
telemt_upstream_connect_success_total 30969
telemt_upstream_connect_attempts_per_request{bucket="1"} 30969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18189
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1315
telemt_me_reconnect_success_total 547
telemt_me_reader_eof_total 547
telemt_me_idle_close_by_peer_total 547
telemt_me_route_drop_no_conn_total 269417
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 578863
telemt_me_endpoint_quarantine_total 589
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 555
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
telemt_me_writers_active_current 44
telemt_desync_total 3578
telemt_desync_full_logged_total 1303
telemt_desync_suppressed_total 2275
telemt_desync_frames_bucket_total{bucket="1_2"} 659
telemt_desync_frames_bucket_total{bucket="3_10"} 1285
telemt_desync_frames_bucket_total{bucket="gt_10"} 1634
telemt_pool_swap_total 72
telemt_pool_force_close_total 1683
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 112
telemt_me_draining_writers_reap_progress_total 27768
telemt_me_writer_removed_unexpected_total 518
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2096
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26205
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1654
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26085
telemt_me_writer_teardown_success_total{mode="normal"} 28301
telemt_me_writer_teardown_noop_total 27768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56069
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.349177
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56069
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 112
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 456
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 578504
telemt_user_connections_current{user="hello"} 770
telemt_user_octets_from_client{user="hello"} 11859971939 (11.05 GB)
telemt_user_octets_to_client{user="hello"} 221295592649 (206.10 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 68227.0 (18h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4254543
telemt_connections_bad_total 385693
telemt_connections_current 5037
telemt_connections_me_current 5037
telemt_handshake_timeouts_total 139671
telemt_upstream_connect_attempt_total 27112
telemt_upstream_connect_success_total 26999
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 27077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13595
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_reconnect_attempts_total 1186
telemt_me_reconnect_success_total 616
telemt_me_reader_eof_total 583
telemt_me_idle_close_by_peer_total 583
telemt_me_route_drop_no_conn_total 1292093
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3384371
telemt_me_endpoint_quarantine_total 495
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 521
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
telemt_me_writers_active_current 44
telemt_desync_total 13226
telemt_desync_full_logged_total 4369
telemt_desync_suppressed_total 8857
telemt_desync_frames_bucket_total{bucket="1_2"} 3122
telemt_desync_frames_bucket_total{bucket="3_10"} 4933
telemt_desync_frames_bucket_total{bucket="gt_10"} 5171
telemt_pool_swap_total 75
telemt_pool_force_close_total 1970
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 223
telemt_me_draining_writers_reap_progress_total 24310
telemt_me_writer_removed_unexpected_total 571
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1940
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22943
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1924
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22340
telemt_me_writer_teardown_success_total{mode="normal"} 24883
telemt_me_writer_teardown_noop_total 24310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49193
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.894449
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49193
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 223
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 545
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 3375966
telemt_user_connections_current{user="hello"} 5037
telemt_user_octets_from_client{user="hello"} 68819260012 (64.09 GB)
telemt_user_octets_to_client{user="hello"} 1589692523572 (1.45 TB)
telemt_user_unique_ips_current{user="hello"} 1780
telemt_user_unique_ips_recent_window{user="hello"} 730
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 68223.8 (18h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3789289
telemt_connections_bad_total 341320
telemt_connections_current 3954
telemt_connections_me_current 3954
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 116117
telemt_upstream_connect_attempt_total 43632
telemt_upstream_connect_success_total 43337
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 43581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15470
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 601
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_reconnect_attempts_total 3841
telemt_me_reconnect_success_total 847
telemt_me_reader_eof_total 744
telemt_me_idle_close_by_peer_total 744
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 1372203
telemt_me_route_drop_channel_closed_total 102
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3034474
telemt_me_endpoint_quarantine_total 564
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 518
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
telemt_me_writers_active_current 46
telemt_desync_total 11892
telemt_desync_full_logged_total 4040
telemt_desync_suppressed_total 7852
telemt_desync_frames_bucket_total{bucket="1_2"} 2972
telemt_desync_frames_bucket_total{bucket="3_10"} 4421
telemt_desync_frames_bucket_total{bucket="gt_10"} 4499
telemt_pool_swap_total 73
telemt_pool_force_close_total 1907
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 214
telemt_me_draining_writers_reap_progress_total 23746
telemt_me_writer_removed_unexpected_total 756
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2314
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22220
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1750
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 157
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21839
telemt_me_writer_teardown_success_total{mode="normal"} 24534
telemt_me_writer_teardown_noop_total 23747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48281
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.061444
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48281
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 214
telemt_me_refill_failed_total 170
telemt_me_writer_restored_same_endpoint_total 659
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 57
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 3042917
telemt_user_connections_current{user="hello"} 3954
telemt_user_octets_from_client{user="hello"} 54794136721 (51.03 GB)
telemt_user_octets_to_client{user="hello"} 1302981095952 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1547
telemt_user_unique_ips_recent_window{user="hello"} 606
```
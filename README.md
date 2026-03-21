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

# Server Metrics 2026-03-21 11:49:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 54793.2 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1682195
telemt_connections_bad_total 85576
telemt_connections_current 1797
telemt_connections_me_current 1797
telemt_handshake_timeouts_total 67108
telemt_upstream_connect_attempt_total 21390
telemt_upstream_connect_success_total 21283
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 21352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13660
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 1092
telemt_me_reconnect_success_total 483
telemt_me_reader_eof_total 467
telemt_me_idle_close_by_peer_total 467
telemt_me_route_drop_no_conn_total 1014957
telemt_me_route_drop_channel_closed_total 399
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1297279
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 382
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 435
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
telemt_desync_total 5268
telemt_desync_full_logged_total 1859
telemt_desync_suppressed_total 3409
telemt_desync_frames_bucket_total{bucket="1_2"} 1116
telemt_desync_frames_bucket_total{bucket="3_10"} 2027
telemt_desync_frames_bucket_total{bucket="gt_10"} 2125
telemt_pool_swap_total 59
telemt_pool_force_close_total 1729
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 311
telemt_me_draining_writers_reap_progress_total 19104
telemt_me_writer_removed_unexpected_total 447
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1565
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17845
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1665
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 64
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17375
telemt_me_writer_teardown_success_total{mode="normal"} 19410
telemt_me_writer_teardown_noop_total 19108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38518
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 125.813773
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38518
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 311
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 421
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1296348
telemt_user_connections_current{user="hello"} 1797
telemt_user_octets_from_client{user="hello"} 18684398347 (17.40 GB)
telemt_user_octets_to_client{user="hello"} 355737007731 (331.31 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 611
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 438.6 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25425
telemt_connections_bad_total 2291
telemt_connections_current 2038
telemt_connections_me_current 2038
telemt_handshake_timeouts_total 749
telemt_upstream_connect_attempt_total 209
telemt_upstream_connect_success_total 202
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 10167
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20121
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
telemt_desync_total 83
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_me_draining_writers_reap_progress_total 125
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 123
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 125
telemt_me_writer_teardown_success_total{mode="normal"} 125
telemt_me_writer_teardown_noop_total 125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 250
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.007485
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 250
telemt_user_connections_total{user="hello"} 20119
telemt_user_connections_current{user="hello"} 2038
telemt_user_octets_from_client{user="hello"} 228499740 (217.91 MB)
telemt_user_octets_to_client{user="hello"} 5271006972 (4.91 GB)
telemt_user_unique_ips_current{user="hello"} 1057
telemt_user_unique_ips_recent_window{user="hello"} 507
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 54791.2 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3240731
telemt_connections_bad_total 347913
telemt_connections_current 4541
telemt_connections_me_current 4541
telemt_handshake_timeouts_total 118881
telemt_upstream_connect_attempt_total 20773
telemt_upstream_connect_success_total 20760
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 20761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 728
telemt_me_reconnect_success_total 389
telemt_me_reader_eof_total 402
telemt_me_idle_close_by_peer_total 402
telemt_me_route_drop_no_conn_total 1401649
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2583781
telemt_me_endpoint_quarantine_total 356
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 422
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
telemt_desync_total 11335
telemt_desync_full_logged_total 3814
telemt_desync_suppressed_total 7521
telemt_desync_frames_bucket_total{bucket="1_2"} 2390
telemt_desync_frames_bucket_total{bucket="3_10"} 4414
telemt_desync_frames_bucket_total{bucket="gt_10"} 4531
telemt_pool_swap_total 59
telemt_pool_force_close_total 1814
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 254
telemt_me_draining_writers_reap_progress_total 18909
telemt_me_writer_removed_unexpected_total 379
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1554
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17585
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 14
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1716
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 98
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17095
telemt_me_writer_teardown_success_total{mode="normal"} 19139
telemt_me_writer_teardown_noop_total 18923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38062
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.805527
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38062
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 254
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 345
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 2580204
telemt_user_connections_current{user="hello"} 4541
telemt_user_octets_from_client{user="hello"} 42692322432 (39.76 GB)
telemt_user_octets_to_client{user="hello"} 937413129648 (873.03 GB)
telemt_user_unique_ips_current{user="hello"} 1819
telemt_user_unique_ips_recent_window{user="hello"} 580
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 54795.7 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2691230
telemt_connections_bad_total 300645
telemt_connections_current 3418
telemt_connections_me_current 3418
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 110935
telemt_upstream_connect_attempt_total 25674
telemt_upstream_connect_success_total 25414
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 25545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11628
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 1073
telemt_me_reconnect_success_total 501
telemt_me_reader_eof_total 462
telemt_me_idle_close_by_peer_total 462
telemt_me_route_drop_no_conn_total 793239
telemt_me_route_drop_channel_closed_total 67
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1898324
telemt_me_endpoint_quarantine_total 367
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 421
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
telemt_desync_total 8654
telemt_desync_full_logged_total 2973
telemt_desync_suppressed_total 5681
telemt_desync_frames_bucket_total{bucket="1_2"} 2169
telemt_desync_frames_bucket_total{bucket="3_10"} 3379
telemt_desync_frames_bucket_total{bucket="gt_10"} 3106
telemt_pool_swap_total 59
telemt_pool_force_close_total 1640
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 136
telemt_me_draining_writers_reap_progress_total 18619
telemt_me_writer_removed_unexpected_total 452
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1561
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17528
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1530
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 110
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16979
telemt_me_writer_teardown_success_total{mode="normal"} 19089
telemt_me_writer_teardown_noop_total 18620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37709
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.808321
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37709
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 136
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 420
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 1899755
telemt_user_connections_current{user="hello"} 3418
telemt_user_octets_from_client{user="hello"} 36355847581 (33.86 GB)
telemt_user_octets_to_client{user="hello"} 912707357919 (850.02 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1377
telemt_user_unique_ips_recent_window{user="hello"} 469
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 54756.6 (15h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2623479
telemt_connections_bad_total 294753
telemt_connections_current 3287
telemt_connections_me_current 3287
telemt_handshake_timeouts_total 78345
telemt_upstream_connect_attempt_total 22118
telemt_upstream_connect_success_total 22047
telemt_upstream_connect_attempts_per_request{bucket="1"} 22047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12004
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 793
telemt_me_reconnect_success_total 539
telemt_me_reader_eof_total 481
telemt_me_idle_close_by_peer_total 481
telemt_me_route_drop_no_conn_total 773556
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1894360
telemt_me_endpoint_quarantine_total 415
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 414
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
telemt_desync_total 8922
telemt_desync_full_logged_total 2995
telemt_desync_suppressed_total 5927
telemt_desync_frames_bucket_total{bucket="1_2"} 2374
telemt_desync_frames_bucket_total{bucket="3_10"} 3389
telemt_desync_frames_bucket_total{bucket="gt_10"} 3159
telemt_pool_swap_total 58
telemt_pool_force_close_total 1617
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 174
telemt_me_draining_writers_reap_progress_total 19792
telemt_me_writer_removed_unexpected_total 456
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1586
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18695
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1496
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 121
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18175
telemt_me_writer_teardown_success_total{mode="normal"} 20281
telemt_me_writer_teardown_noop_total 19795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40076
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.986147
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40076
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 174
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 465
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1891469
telemt_user_connections_current{user="hello"} 3287
telemt_user_octets_from_client{user="hello"} 42962606284 (40.01 GB)
telemt_user_octets_to_client{user="hello"} 919728741912 (856.56 GB)
telemt_user_unique_ips_current{user="hello"} 1303
telemt_user_unique_ips_recent_window{user="hello"} 462
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 54795.9 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8452399
telemt_connections_bad_total 566445
telemt_connections_current 5248
telemt_connections_me_current 5248
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 294338
telemt_upstream_connect_attempt_total 64063
telemt_upstream_connect_success_total 60345
telemt_upstream_connect_fail_total 2946
telemt_upstream_connect_attempts_per_request{bucket="1"} 63291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2946
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3203
telemt_me_reconnect_success_total 1098
telemt_me_reader_eof_total 797
telemt_me_idle_close_by_peer_total 796
telemt_me_route_drop_no_conn_total 14974938
telemt_me_route_drop_channel_closed_total 56
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7036821
telemt_me_endpoint_quarantine_total 425
telemt_me_single_endpoint_outage_enter_total 58
telemt_me_single_endpoint_outage_exit_total 58
telemt_me_single_endpoint_outage_reconnect_attempt_total 121
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 121
telemt_me_single_endpoint_shadow_rotate_total 429
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
telemt_me_writers_active_current 42
telemt_desync_total 13324
telemt_desync_full_logged_total 4280
telemt_desync_suppressed_total 9044
telemt_desync_frames_bucket_total{bucket="1_2"} 2870
telemt_desync_frames_bucket_total{bucket="3_10"} 5889
telemt_desync_frames_bucket_total{bucket="gt_10"} 4565
telemt_pool_swap_total 55
telemt_pool_force_close_total 1724
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 356
telemt_me_draining_writers_reap_progress_total 18174
telemt_me_writer_removed_unexpected_total 1063
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2325
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16808
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1473
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 251
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16450
telemt_me_writer_teardown_success_total{mode="normal"} 19133
telemt_me_writer_teardown_noop_total 18183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37316
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.756903
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37316
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 356
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 774
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 7072441
telemt_user_connections_current{user="hello"} 5248
telemt_user_octets_from_client{user="hello"} 57501079052 (53.55 GB)
telemt_user_octets_to_client{user="hello"} 656574330259 (611.48 GB)
telemt_user_msgs_from_client{user="hello"} 129175
telemt_user_msgs_to_client{user="hello"} 449473
telemt_user_unique_ips_current{user="hello"} 1905
telemt_user_unique_ips_recent_window{user="hello"} 992
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 54763.6 (15h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2653796
telemt_connections_bad_total 327794
telemt_connections_current 3712
telemt_connections_me_current 3712
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 58788
telemt_upstream_connect_attempt_total 23601
telemt_upstream_connect_success_total 23340
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 23576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_reconnect_attempts_total 2310
telemt_me_reconnect_success_total 769
telemt_me_reader_eof_total 761
telemt_me_idle_close_by_peer_total 761
telemt_me_route_drop_no_conn_total 920717
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2005146
telemt_me_endpoint_quarantine_total 344
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 419
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
telemt_me_writers_active_current 48
telemt_desync_total 9132
telemt_desync_full_logged_total 3283
telemt_desync_suppressed_total 5849
telemt_desync_frames_bucket_total{bucket="1_2"} 1783
telemt_desync_frames_bucket_total{bucket="3_10"} 3680
telemt_desync_frames_bucket_total{bucket="gt_10"} 3669
telemt_pool_swap_total 56
telemt_pool_force_close_total 1546
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 135
telemt_me_draining_writers_reap_progress_total 19631
telemt_me_writer_removed_unexpected_total 736
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1841
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18551
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1391
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 155
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18085
telemt_me_writer_teardown_success_total{mode="normal"} 20392
telemt_me_writer_teardown_noop_total 19631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40023
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.198106
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40023
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 135
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 645
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 1990396
telemt_user_connections_current{user="hello"} 3712
telemt_user_octets_from_client{user="hello"} 36470752948 (33.97 GB)
telemt_user_octets_to_client{user="hello"} 888184976678 (827.19 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1446
telemt_user_unique_ips_recent_window{user="hello"} 508
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 54758.1 (15h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3920552
telemt_connections_bad_total 203128
telemt_connections_current 3230
telemt_connections_me_current 3230
telemt_handshake_timeouts_total 1697862
telemt_upstream_connect_attempt_total 22128
telemt_upstream_connect_success_total 22094
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 22097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11888
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 287
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 801
telemt_me_reconnect_success_total 398
telemt_me_reader_eof_total 397
telemt_me_idle_close_by_peer_total 397
telemt_me_route_drop_no_conn_total 765185
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1777791
telemt_me_endpoint_quarantine_total 416
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 430
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
telemt_me_writers_active_current 45
telemt_desync_total 8733
telemt_desync_full_logged_total 3101
telemt_desync_suppressed_total 5632
telemt_desync_frames_bucket_total{bucket="1_2"} 1599
telemt_desync_frames_bucket_total{bucket="3_10"} 3490
telemt_desync_frames_bucket_total{bucket="gt_10"} 3644
telemt_pool_swap_total 59
telemt_pool_force_close_total 1491
telemt_me_writer_close_signal_drop_total 124
telemt_me_draining_writers_reap_progress_total 19797
telemt_me_writer_removed_unexpected_total 385
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1333
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18870
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1442
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 49
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18306
telemt_me_writer_teardown_success_total{mode="normal"} 20203
telemt_me_writer_teardown_noop_total 19797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40000
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.095652
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40000
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 124
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 349
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 1771593
telemt_user_connections_current{user="hello"} 3230
telemt_user_octets_from_client{user="hello"} 32069110728 (29.87 GB)
telemt_user_octets_to_client{user="hello"} 856349375100 (797.54 GB)
telemt_user_unique_ips_current{user="hello"} 1341
telemt_user_unique_ips_recent_window{user="hello"} 492
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 52749.3 (14h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 823573
telemt_connections_bad_total 59132
telemt_connections_current 684
telemt_connections_me_current 684
telemt_handshake_timeouts_total 299272
telemt_upstream_connect_attempt_total 25327
telemt_upstream_connect_success_total 25324
telemt_upstream_connect_attempts_per_request{bucket="1"} 25324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14789
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1086
telemt_me_reconnect_success_total 419
telemt_me_reader_eof_total 414
telemt_me_idle_close_by_peer_total 414
telemt_me_route_drop_no_conn_total 175622
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 402398
telemt_me_endpoint_quarantine_total 488
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 450
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
telemt_desync_total 2782
telemt_desync_full_logged_total 1064
telemt_desync_suppressed_total 1718
telemt_desync_frames_bucket_total{bucket="1_2"} 438
telemt_desync_frames_bucket_total{bucket="3_10"} 1008
telemt_desync_frames_bucket_total{bucket="gt_10"} 1336
telemt_pool_swap_total 58
telemt_pool_force_close_total 1291
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 87
telemt_me_draining_writers_reap_progress_total 22673
telemt_me_writer_removed_unexpected_total 394
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1653
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21419
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1288
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21382
telemt_me_writer_teardown_success_total{mode="normal"} 23072
telemt_me_writer_teardown_noop_total 22673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45745
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.600526
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45745
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 87
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 339
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 402270
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 6474600047 (6.03 GB)
telemt_user_octets_to_client{user="hello"} 155089955453 (144.44 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 54767.9 (15h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2807295
telemt_connections_bad_total 262194
telemt_connections_current 3961
telemt_connections_me_current 3961
telemt_handshake_timeouts_total 75343
telemt_upstream_connect_attempt_total 22941
telemt_upstream_connect_success_total 22845
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 22910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11434
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_reconnect_attempts_total 936
telemt_me_reconnect_success_total 519
telemt_me_reader_eof_total 485
telemt_me_idle_close_by_peer_total 485
telemt_me_route_drop_no_conn_total 747075
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2222039
telemt_me_endpoint_quarantine_total 422
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 427
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
telemt_desync_total 8921
telemt_desync_full_logged_total 2950
telemt_desync_suppressed_total 5971
telemt_desync_frames_bucket_total{bucket="1_2"} 2123
telemt_desync_frames_bucket_total{bucket="3_10"} 3330
telemt_desync_frames_bucket_total{bucket="gt_10"} 3468
telemt_pool_swap_total 60
telemt_pool_force_close_total 1506
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 158
telemt_me_draining_writers_reap_progress_total 20605
telemt_me_writer_removed_unexpected_total 477
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1582
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19516
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1479
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19099
telemt_me_writer_teardown_success_total{mode="normal"} 21098
telemt_me_writer_teardown_noop_total 20605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41703
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.506482
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41703
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 158
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 464
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 2215445
telemt_user_connections_current{user="hello"} 3961
telemt_user_octets_from_client{user="hello"} 46257431652 (43.08 GB)
telemt_user_octets_to_client{user="hello"} 1035975524948 (964.83 GB)
telemt_user_unique_ips_current{user="hello"} 1480
telemt_user_unique_ips_recent_window{user="hello"} 572
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 54764.5 (15h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2569897
telemt_connections_bad_total 202061
telemt_connections_current 3687
telemt_connections_me_current 3687
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 69615
telemt_upstream_connect_attempt_total 39080
telemt_upstream_connect_success_total 38842
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 39037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 585
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_reconnect_attempts_total 3248
telemt_me_reconnect_success_total 670
telemt_me_reader_eof_total 587
telemt_me_idle_close_by_peer_total 587
telemt_me_seq_mismatch_total 28
telemt_me_route_drop_no_conn_total 753093
telemt_me_route_drop_channel_closed_total 53
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2067497
telemt_me_endpoint_quarantine_total 470
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 425
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
telemt_me_writers_active_current 46
telemt_desync_total 7790
telemt_desync_full_logged_total 2670
telemt_desync_suppressed_total 5120
telemt_desync_frames_bucket_total{bucket="1_2"} 2044
telemt_desync_frames_bucket_total{bucket="3_10"} 2892
telemt_desync_frames_bucket_total{bucket="gt_10"} 2854
telemt_pool_swap_total 59
telemt_pool_force_close_total 1461
telemt_me_writer_close_signal_drop_total 137
telemt_me_draining_writers_reap_progress_total 19766
telemt_me_writer_removed_unexpected_total 599
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1847
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18546
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1369
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 92
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18305
telemt_me_writer_teardown_success_total{mode="normal"} 20393
telemt_me_writer_teardown_noop_total 19767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40160
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.280418
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40160
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 137
telemt_me_refill_failed_total 146
telemt_me_writer_restored_same_endpoint_total 509
telemt_me_writer_restored_fallback_total 37
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 2078237
telemt_user_connections_current{user="hello"} 3687
telemt_user_octets_from_client{user="hello"} 37906137801 (35.30 GB)
telemt_user_octets_to_client{user="hello"} 914924388592 (852.09 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1448
telemt_user_unique_ips_recent_window{user="hello"} 518
```
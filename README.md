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

# Server Metrics 2026-03-21 17:10:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 74070.8 (20h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2668067
telemt_connections_bad_total 158318
telemt_connections_current 1529
telemt_connections_me_current 1529
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 82089
telemt_upstream_connect_attempt_total 31016
telemt_upstream_connect_success_total 30883
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 30972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1754
telemt_me_reconnect_success_total 697
telemt_me_reader_eof_total 670
telemt_me_idle_close_by_peer_total 670
telemt_me_route_drop_no_conn_total 2256458
telemt_me_route_drop_channel_closed_total 718
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2134829
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 512
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 579
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
telemt_me_writers_active_current 45
telemt_desync_total 8497
telemt_desync_full_logged_total 2956
telemt_desync_suppressed_total 5541
telemt_desync_frames_bucket_total{bucket="1_2"} 1845
telemt_desync_frames_bucket_total{bucket="3_10"} 3217
telemt_desync_frames_bucket_total{bucket="gt_10"} 3435
telemt_pool_swap_total 80
telemt_pool_force_close_total 2421
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 552
telemt_me_draining_writers_reap_progress_total 25033
telemt_me_writer_removed_unexpected_total 648
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2140
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23323
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2296
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 125
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22612
telemt_me_writer_teardown_success_total{mode="normal"} 25464
telemt_me_writer_teardown_noop_total 25040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50504
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 243.603668
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50504
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 552
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 598
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2135340
telemt_user_connections_current{user="hello"} 1529
telemt_user_octets_from_client{user="hello"} 30967198713 (28.84 GB)
telemt_user_octets_to_client{user="hello"} 527235939894 (491.03 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 544
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 573.9 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12875
telemt_connections_bad_total 514
telemt_connections_current 1048
telemt_connections_me_current 1048
telemt_handshake_timeouts_total 312
telemt_upstream_connect_attempt_total 279
telemt_upstream_connect_success_total 276
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 278
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 139
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 1
telemt_me_route_drop_no_conn_total 4855
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10926
telemt_me_endpoint_quarantine_total 5
telemt_me_single_endpoint_shadow_rotate_total 8
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
telemt_me_writers_active_current 46
telemt_desync_total 33
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_me_draining_writers_reap_progress_total 191
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 188
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 191
telemt_me_writer_teardown_success_total{mode="normal"} 191
telemt_me_writer_teardown_noop_total 191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 382
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.003550
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 382
telemt_user_connections_total{user="hello"} 10920
telemt_user_connections_current{user="hello"} 1048
telemt_user_octets_from_client{user="hello"} 101731948 (97.02 MB)
telemt_user_octets_to_client{user="hello"} 3710016632 (3.46 GB)
telemt_user_unique_ips_current{user="hello"} 731
telemt_user_unique_ips_recent_window{user="hello"} 359
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 74068.7 (20h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5558391
telemt_connections_bad_total 460198
telemt_connections_current 2769
telemt_connections_me_current 2769
telemt_handshake_timeouts_total 181641
telemt_upstream_connect_attempt_total 27141
telemt_upstream_connect_success_total 27082
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 27088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14784
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1208
telemt_me_reconnect_success_total 612
telemt_me_reader_eof_total 616
telemt_me_idle_close_by_peer_total 616
telemt_me_route_drop_no_conn_total 3472025
telemt_me_route_drop_channel_closed_total 48
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4582529
telemt_me_endpoint_quarantine_total 468
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 553
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
telemt_me_writers_active_current 44
telemt_desync_total 18614
telemt_desync_full_logged_total 6274
telemt_desync_suppressed_total 12340
telemt_desync_frames_bucket_total{bucket="1_2"} 3940
telemt_desync_frames_bucket_total{bucket="3_10"} 7378
telemt_desync_frames_bucket_total{bucket="gt_10"} 7296
telemt_pool_swap_total 79
telemt_pool_force_close_total 2632
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 413
telemt_me_draining_writers_reap_progress_total 24690
telemt_me_writer_removed_unexpected_total 596
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2158
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22809
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2421
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 211
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22058
telemt_me_writer_teardown_success_total{mode="normal"} 24967
telemt_me_writer_teardown_noop_total 24725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49692
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 105.483560
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49692
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 413
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 551
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 4576989
telemt_user_connections_current{user="hello"} 2769
telemt_user_octets_from_client{user="hello"} 72086086140 (67.14 GB)
telemt_user_octets_to_client{user="hello"} 1444147679588 (1.31 TB)
telemt_user_unique_ips_current{user="hello"} 1045
telemt_user_unique_ips_recent_window{user="hello"} 495
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 74069.8 (20h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4466899
telemt_connections_bad_total 453850
telemt_connections_current 4719
telemt_connections_me_current 4719
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 150328
telemt_upstream_connect_attempt_total 31441
telemt_upstream_connect_success_total 31150
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 31294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 497
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1429
telemt_me_reconnect_success_total 629
telemt_me_reader_eof_total 595
telemt_me_idle_close_by_peer_total 595
telemt_me_route_drop_no_conn_total 1497172
telemt_me_route_drop_channel_closed_total 139
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3323931
telemt_me_endpoint_quarantine_total 467
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 565
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
telemt_desync_total 15879
telemt_desync_full_logged_total 5223
telemt_desync_suppressed_total 10656
telemt_desync_frames_bucket_total{bucket="1_2"} 3914
telemt_desync_frames_bucket_total{bucket="3_10"} 6167
telemt_desync_frames_bucket_total{bucket="gt_10"} 5798
telemt_pool_swap_total 81
telemt_pool_force_close_total 2410
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 255
telemt_me_draining_writers_reap_progress_total 23740
telemt_me_writer_removed_unexpected_total 576
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2049
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22224
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2244
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 166
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21330
telemt_me_writer_teardown_success_total{mode="normal"} 24273
telemt_me_writer_teardown_noop_total 23743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48016
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 30.828471
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48016
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 255
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 533
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 3322712
telemt_user_connections_current{user="hello"} 4719
telemt_user_octets_from_client{user="hello"} 80012554853 (74.52 GB)
telemt_user_octets_to_client{user="hello"} 1516515720763 (1.38 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1661
telemt_user_unique_ips_recent_window{user="hello"} 667
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 74034.9 (20h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4400621
telemt_connections_bad_total 431604
telemt_connections_current 3810
telemt_connections_me_current 3810
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 131349
telemt_upstream_connect_attempt_total 36668
telemt_upstream_connect_success_total 36419
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 36552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16075
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 876
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 1541
telemt_me_reconnect_success_total 681
telemt_me_reader_eof_total 629
telemt_me_idle_close_by_peer_total 629
telemt_me_route_drop_no_conn_total 1604476
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3298605
telemt_me_endpoint_quarantine_total 512
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 557
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
telemt_desync_total 15293
telemt_desync_full_logged_total 5011
telemt_desync_suppressed_total 10282
telemt_desync_frames_bucket_total{bucket="1_2"} 3781
telemt_desync_frames_bucket_total{bucket="3_10"} 5786
telemt_desync_frames_bucket_total{bucket="gt_10"} 5726
telemt_pool_swap_total 79
telemt_pool_force_close_total 2308
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 274
telemt_me_draining_writers_reap_progress_total 25101
telemt_me_writer_removed_unexpected_total 597
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2131
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23591
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2113
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 195
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22793
telemt_me_writer_teardown_success_total{mode="normal"} 25722
telemt_me_writer_teardown_noop_total 25108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50830
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.932882
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50830
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 274
telemt_me_refill_failed_total 48
telemt_me_writer_restored_same_endpoint_total 588
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 3301592
telemt_user_connections_current{user="hello"} 3810
telemt_user_octets_from_client{user="hello"} 81792028741 (76.17 GB)
telemt_user_octets_to_client{user="hello"} 1512598512156 (1.38 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1371
telemt_user_unique_ips_recent_window{user="hello"} 570
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 74073.0 (20h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15316961
telemt_connections_bad_total 982117
telemt_connections_current 5515
telemt_connections_me_current 5515
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 442105
telemt_upstream_connect_attempt_total 148030
telemt_upstream_connect_success_total 132213
telemt_upstream_connect_fail_total 14631
telemt_upstream_connect_attempts_per_request{bucket="1"} 146844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30079
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14631
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 4152
telemt_me_reconnect_success_total 1556
telemt_me_reader_eof_total 1074
telemt_me_idle_close_by_peer_total 1073
telemt_me_route_drop_no_conn_total 30327634
telemt_me_route_drop_channel_closed_total 96
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12624637
telemt_me_endpoint_quarantine_total 555
telemt_me_single_endpoint_outage_enter_total 86
telemt_me_single_endpoint_outage_exit_total 86
telemt_me_single_endpoint_outage_reconnect_attempt_total 195
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 195
telemt_me_single_endpoint_shadow_rotate_total 579
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 22204
telemt_desync_full_logged_total 6816
telemt_desync_suppressed_total 15388
telemt_desync_frames_bucket_total{bucket="1_2"} 4874
telemt_desync_frames_bucket_total{bucket="3_10"} 9697
telemt_desync_frames_bucket_total{bucket="gt_10"} 7633
telemt_pool_swap_total 75
telemt_pool_force_close_total 2503
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 574
telemt_me_draining_writers_reap_progress_total 23513
telemt_me_writer_removed_unexpected_total 1483
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3147
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21611
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 13
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2087
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 416
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21010
telemt_me_writer_teardown_success_total{mode="normal"} 24758
telemt_me_writer_teardown_noop_total 23527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48285
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 182.459962
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48285
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 574
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 1093
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 148
telemt_me_writer_removed_unexpected_minus_restored_total 380
telemt_user_connections_total{user="hello"} 12723026
telemt_user_connections_current{user="hello"} 5515
telemt_user_octets_from_client{user="hello"} 102376576078 (95.35 GB)
telemt_user_octets_to_client{user="hello"} 854131736115 (795.47 GB)
telemt_user_msgs_from_client{user="hello"} 290173
telemt_user_msgs_to_client{user="hello"} 585212
telemt_user_unique_ips_current{user="hello"} 2043
telemt_user_unique_ips_recent_window{user="hello"} 1176
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 74040.6 (20h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4406790
telemt_connections_bad_total 464776
telemt_connections_current 3434
telemt_connections_me_current 3434
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 93512
telemt_upstream_connect_attempt_total 30695
telemt_upstream_connect_success_total 30298
telemt_upstream_connect_fail_total 328
telemt_upstream_connect_attempts_per_request{bucket="1"} 30626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15880
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 328
telemt_me_reconnect_attempts_total 3134
telemt_me_reconnect_success_total 1109
telemt_me_reader_eof_total 1092
telemt_me_idle_close_by_peer_total 1092
telemt_me_route_drop_no_conn_total 1897558
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3410915
telemt_me_endpoint_quarantine_total 450
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 550
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
telemt_me_writers_active_current 46
telemt_desync_total 16639
telemt_desync_full_logged_total 5780
telemt_desync_suppressed_total 10859
telemt_desync_frames_bucket_total{bucket="1_2"} 3232
telemt_desync_frames_bucket_total{bucket="3_10"} 6560
telemt_desync_frames_bucket_total{bucket="gt_10"} 6847
telemt_pool_swap_total 74
telemt_pool_force_close_total 2210
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 235
telemt_me_draining_writers_reap_progress_total 25744
telemt_me_writer_removed_unexpected_total 1061
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2596
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24245
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1893
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 317
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23534
telemt_me_writer_teardown_success_total{mode="normal"} 26841
telemt_me_writer_teardown_noop_total 25745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52586
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.115305
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52586
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 235
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 951
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 3393382
telemt_user_connections_current{user="hello"} 3434
telemt_user_octets_from_client{user="hello"} 88911344308 (82.81 GB)
telemt_user_octets_to_client{user="hello"} 1384398607562 (1.26 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1305
telemt_user_unique_ips_recent_window{user="hello"} 973
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 10876.4 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1645306
telemt_connections_bad_total 61536
telemt_connections_current 5003
telemt_connections_me_current 5003
telemt_handshake_timeouts_total 747487
telemt_upstream_connect_attempt_total 3576
telemt_upstream_connect_success_total 3515
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 3570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 461
telemt_me_reconnect_success_total 118
telemt_me_reader_eof_total 111
telemt_me_idle_close_by_peer_total 111
telemt_me_route_drop_no_conn_total 566004
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 762814
telemt_me_endpoint_quarantine_total 42
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 81
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
telemt_me_writers_warm_current 31
telemt_desync_total 4169
telemt_desync_full_logged_total 1333
telemt_desync_suppressed_total 2836
telemt_desync_frames_bucket_total{bucket="1_2"} 774
telemt_desync_frames_bucket_total{bucket="3_10"} 1572
telemt_desync_frames_bucket_total{bucket="gt_10"} 1823
telemt_pool_swap_total 10
telemt_pool_force_close_total 329
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 28
telemt_me_draining_writers_reap_progress_total 3032
telemt_me_writer_removed_unexpected_total 113
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 275
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2870
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 274
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2703
telemt_me_writer_teardown_success_total{mode="normal"} 3145
telemt_me_writer_teardown_noop_total 3032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6177
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.249647
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6177
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 28
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 99
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 761658
telemt_user_connections_current{user="hello"} 5003
telemt_user_octets_from_client{user="hello"} 17895718240 (16.67 GB)
telemt_user_octets_to_client{user="hello"} 290044205680 (270.12 GB)
telemt_user_unique_ips_current{user="hello"} 1851
telemt_user_unique_ips_recent_window{user="hello"} 844
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 72027.0 (20h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1492660
telemt_connections_bad_total 159959
telemt_connections_current 3619
telemt_connections_me_current 3619
telemt_handshake_timeouts_total 524687
telemt_upstream_connect_attempt_total 32969
telemt_upstream_connect_success_total 32958
telemt_upstream_connect_attempts_per_request{bucket="1"} 32958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19400
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1375
telemt_me_reconnect_success_total 582
telemt_me_reader_eof_total 583
telemt_me_idle_close_by_peer_total 583
telemt_me_route_drop_no_conn_total 357632
telemt_me_route_drop_channel_closed_total 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 716822
telemt_me_endpoint_quarantine_total 627
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 596
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
telemt_me_writers_warm_current 1
telemt_desync_total 4185
telemt_desync_full_logged_total 1492
telemt_desync_suppressed_total 2693
telemt_desync_frames_bucket_total{bucket="1_2"} 802
telemt_desync_frames_bucket_total{bucket="3_10"} 1507
telemt_desync_frames_bucket_total{bucket="gt_10"} 1876
telemt_pool_swap_total 78
telemt_pool_force_close_total 1860
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 29540
telemt_me_writer_removed_unexpected_total 550
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2246
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27863
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1828
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27680
telemt_me_writer_teardown_success_total{mode="normal"} 30109
telemt_me_writer_teardown_noop_total 29540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59649
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.488963
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59649
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 486
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 716309
telemt_user_connections_current{user="hello"} 3620
telemt_user_octets_from_client{user="hello"} 15183694715 (14.14 GB)
telemt_user_octets_to_client{user="hello"} 268887352689 (250.42 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 1554
telemt_user_unique_ips_recent_window{user="hello"} 486
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 74045.2 (20h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4959260
telemt_connections_bad_total 456551
telemt_connections_current 4808
telemt_connections_me_current 4808
telemt_handshake_timeouts_total 159903
telemt_upstream_connect_attempt_total 28977
telemt_upstream_connect_success_total 28858
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 28941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14563
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_reconnect_attempts_total 1236
telemt_me_reconnect_success_total 646
telemt_me_reader_eof_total 616
telemt_me_idle_close_by_peer_total 616
telemt_me_route_drop_no_conn_total 1506572
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3906873
telemt_me_endpoint_quarantine_total 520
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 568
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
telemt_me_writers_active_current 44
telemt_desync_total 15164
telemt_desync_full_logged_total 5025
telemt_desync_suppressed_total 10139
telemt_desync_frames_bucket_total{bucket="1_2"} 3619
telemt_desync_frames_bucket_total{bucket="3_10"} 5608
telemt_desync_frames_bucket_total{bucket="gt_10"} 5937
telemt_pool_swap_total 82
telemt_pool_force_close_total 2183
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 263
telemt_me_draining_writers_reap_progress_total 25977
telemt_me_writer_removed_unexpected_total 602
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2106
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24477
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2130
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23794
telemt_me_writer_teardown_success_total{mode="normal"} 26583
telemt_me_writer_teardown_noop_total 25978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52561
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.556422
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52561
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 263
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 575
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 3896876
telemt_user_connections_current{user="hello"} 4808
telemt_user_octets_from_client{user="hello"} 76995417204 (71.71 GB)
telemt_user_octets_to_client{user="hello"} 1816990951828 (1.65 TB)
telemt_user_unique_ips_current{user="hello"} 1583
telemt_user_unique_ips_recent_window{user="hello"} 697
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 74041.7 (20h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4350387
telemt_connections_bad_total 394814
telemt_connections_current 4057
telemt_connections_me_current 4057
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 133140
telemt_upstream_connect_attempt_total 45457
telemt_upstream_connect_success_total 45134
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 45401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16390
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 606
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_reconnect_attempts_total 4168
telemt_me_reconnect_success_total 918
telemt_me_reader_eof_total 799
telemt_me_idle_close_by_peer_total 799
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 1598693
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3461442
telemt_me_endpoint_quarantine_total 615
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 564
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
telemt_desync_total 13495
telemt_desync_full_logged_total 4592
telemt_desync_suppressed_total 8903
telemt_desync_frames_bucket_total{bucket="1_2"} 3361
telemt_desync_frames_bucket_total{bucket="3_10"} 5006
telemt_desync_frames_bucket_total{bucket="gt_10"} 5128
telemt_pool_swap_total 80
telemt_pool_force_close_total 2125
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 250
telemt_me_draining_writers_reap_progress_total 25345
telemt_me_writer_removed_unexpected_total 812
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2515
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23675
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1949
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 176
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23220
telemt_me_writer_teardown_success_total{mode="normal"} 26190
telemt_me_writer_teardown_noop_total 25347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51537
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.350090
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51537
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 250
telemt_me_refill_failed_total 185
telemt_me_writer_restored_same_endpoint_total 706
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 3469025
telemt_user_connections_current{user="hello"} 4057
telemt_user_octets_from_client{user="hello"} 63298192669 (58.95 GB)
telemt_user_octets_to_client{user="hello"} 1459564360696 (1.33 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1490
telemt_user_unique_ips_recent_window{user="hello"} 618
```
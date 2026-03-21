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

# Server Metrics 2026-03-21 19:52:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 83824.0 (23h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3019786
telemt_connections_bad_total 176300
telemt_connections_current 1045
telemt_connections_me_current 1045
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 92478
telemt_upstream_connect_attempt_total 34349
telemt_upstream_connect_success_total 34206
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 34306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20249
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 53
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1858
telemt_me_reconnect_success_total 748
telemt_me_reader_eof_total 716
telemt_me_idle_close_by_peer_total 716
telemt_me_route_drop_no_conn_total 2607363
telemt_me_route_drop_channel_closed_total 837
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2441188
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 569
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 652
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 9705
telemt_desync_full_logged_total 3394
telemt_desync_suppressed_total 6311
telemt_desync_frames_bucket_total{bucket="1_2"} 2119
telemt_desync_frames_bucket_total{bucket="3_10"} 3678
telemt_desync_frames_bucket_total{bucket="gt_10"} 3908
telemt_pool_swap_total 91
telemt_pool_force_close_total 2737
telemt_pool_stale_pick_total 31
telemt_me_writer_close_signal_drop_total 629
telemt_me_draining_writers_reap_progress_total 28066
telemt_me_writer_removed_unexpected_total 698
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2368
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26138
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2598
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 139
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25329
telemt_me_writer_teardown_success_total{mode="normal"} 28506
telemt_me_writer_teardown_noop_total 28074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56580
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 292.714767
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56580
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 629
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 642
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 2440895
telemt_user_connections_current{user="hello"} 1045
telemt_user_octets_from_client{user="hello"} 36156353141 (33.67 GB)
telemt_user_octets_to_client{user="hello"} 611547268486 (569.55 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 438
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 8962.0 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376492
telemt_connections_bad_total 17155
telemt_connections_current 1576
telemt_connections_me_current 1576
telemt_handshake_timeouts_total 12847
telemt_upstream_connect_attempt_total 3550
telemt_upstream_connect_success_total 3472
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 3539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1958
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_reconnect_attempts_total 164
telemt_me_reconnect_success_total 119
telemt_me_reader_eof_total 94
telemt_me_idle_close_by_peer_total 94
telemt_me_route_drop_no_conn_total 244448
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 310263
telemt_me_endpoint_quarantine_total 75
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 1334
telemt_desync_full_logged_total 745
telemt_desync_suppressed_total 589
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 495
telemt_desync_frames_bucket_total{bucket="gt_10"} 567
telemt_pool_swap_total 9
telemt_pool_force_close_total 280
telemt_me_writer_close_signal_drop_total 30
telemt_me_draining_writers_reap_progress_total 3065
telemt_me_writer_removed_unexpected_total 89
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 267
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2879
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 273
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2785
telemt_me_writer_teardown_success_total{mode="normal"} 3146
telemt_me_writer_teardown_noop_total 3065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6211
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.396157
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6211
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 30
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 79
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 309920
telemt_user_connections_current{user="hello"} 1576
telemt_user_octets_from_client{user="hello"} 5025120468 (4.68 GB)
telemt_user_octets_to_client{user="hello"} 86423642204 (80.49 GB)
telemt_user_unique_ips_current{user="hello"} 923
telemt_user_unique_ips_recent_window{user="hello"} 363
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 83822.0 (23h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6647702
telemt_connections_bad_total 512302
telemt_connections_current 4153
telemt_connections_me_current 4153
telemt_handshake_timeouts_total 209359
telemt_upstream_connect_attempt_total 30178
telemt_upstream_connect_success_total 30116
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 30122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16436
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1277
telemt_me_reconnect_success_total 654
telemt_me_reader_eof_total 664
telemt_me_idle_close_by_peer_total 664
telemt_me_route_drop_no_conn_total 4284523
telemt_me_route_drop_channel_closed_total 61
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5471739
telemt_me_endpoint_quarantine_total 521
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 621
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
telemt_desync_total 22334
telemt_desync_full_logged_total 7437
telemt_desync_suppressed_total 14897
telemt_desync_frames_bucket_total{bucket="1_2"} 4681
telemt_desync_frames_bucket_total{bucket="3_10"} 8913
telemt_desync_frames_bucket_total{bucket="gt_10"} 8740
telemt_pool_swap_total 90
telemt_pool_force_close_total 2987
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 487
telemt_me_draining_writers_reap_progress_total 27433
telemt_me_writer_removed_unexpected_total 639
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2372
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25350
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2757
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 230
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24446
telemt_me_writer_teardown_success_total{mode="normal"} 27722
telemt_me_writer_teardown_noop_total 27470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55192
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 129.165774
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55192
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 487
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 590
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 5465189
telemt_user_connections_current{user="hello"} 4153
telemt_user_octets_from_client{user="hello"} 91404321456 (85.13 GB)
telemt_user_octets_to_client{user="hello"} 1700039348968 (1.55 TB)
telemt_user_unique_ips_current{user="hello"} 1774
telemt_user_unique_ips_recent_window{user="hello"} 507
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 83823.5 (23h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5364905
telemt_connections_bad_total 507622
telemt_connections_current 3491
telemt_connections_me_current 3491
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 177748
telemt_upstream_connect_attempt_total 34389
telemt_upstream_connect_success_total 34074
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 34235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16251
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 540
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1644
telemt_me_reconnect_success_total 687
telemt_me_reader_eof_total 659
telemt_me_idle_close_by_peer_total 659
telemt_me_route_drop_no_conn_total 1862337
telemt_me_route_drop_channel_closed_total 212
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4020978
telemt_me_endpoint_quarantine_total 516
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 637
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
telemt_me_writers_active_current 42
telemt_desync_total 18860
telemt_desync_full_logged_total 6262
telemt_desync_suppressed_total 12598
telemt_desync_frames_bucket_total{bucket="1_2"} 4569
telemt_desync_frames_bucket_total{bucket="3_10"} 7316
telemt_desync_frames_bucket_total{bucket="gt_10"} 6975
telemt_pool_swap_total 92
telemt_pool_force_close_total 2759
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 309
telemt_me_draining_writers_reap_progress_total 26315
telemt_me_writer_removed_unexpected_total 639
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2293
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24589
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2568
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 191
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23556
telemt_me_writer_teardown_success_total{mode="normal"} 26882
telemt_me_writer_teardown_noop_total 26320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53202
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 38.964844
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53202
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 309
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 587
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 4018143
telemt_user_connections_current{user="hello"} 3491
telemt_user_octets_from_client{user="hello"} 119192314257 (111.01 GB)
telemt_user_octets_to_client{user="hello"} 1823221032895 (1.66 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1419
telemt_user_unique_ips_recent_window{user="hello"} 452
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 83787.7 (23h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5295508
telemt_connections_bad_total 477833
telemt_connections_current 3394
telemt_connections_me_current 3394
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 160092
telemt_upstream_connect_attempt_total 40735
telemt_upstream_connect_success_total 40471
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 40605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17672
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1704
telemt_me_reconnect_success_total 740
telemt_me_reader_eof_total 684
telemt_me_idle_close_by_peer_total 684
telemt_me_route_drop_no_conn_total 1922875
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4000049
telemt_me_endpoint_quarantine_total 564
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 624
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 41
telemt_desync_total 18656
telemt_desync_full_logged_total 6078
telemt_desync_suppressed_total 12578
telemt_desync_frames_bucket_total{bucket="1_2"} 4620
telemt_desync_frames_bucket_total{bucket="3_10"} 7079
telemt_desync_frames_bucket_total{bucket="gt_10"} 6957
telemt_pool_swap_total 90
telemt_pool_force_close_total 2622
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 321
telemt_me_draining_writers_reap_progress_total 27690
telemt_me_writer_removed_unexpected_total 653
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2362
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26002
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2414
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 208
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25068
telemt_me_writer_teardown_success_total{mode="normal"} 28364
telemt_me_writer_teardown_noop_total 27700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56064
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.934106
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56064
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 321
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 636
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 4002597
telemt_user_connections_current{user="hello"} 3394
telemt_user_octets_from_client{user="hello"} 116014055191 (108.05 GB)
telemt_user_octets_to_client{user="hello"} 1823472148467 (1.66 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1385
telemt_user_unique_ips_recent_window{user="hello"} 421
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 83826.8 (23h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18438964
telemt_connections_bad_total 1163236
telemt_connections_current 4777
telemt_connections_me_current 4777
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 517738
telemt_upstream_connect_attempt_total 173820
telemt_upstream_connect_success_total 156963
telemt_upstream_connect_fail_total 15493
telemt_upstream_connect_attempts_per_request{bucket="1"} 172456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35160
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8819
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15493
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 4595
telemt_me_reconnect_success_total 1721
telemt_me_reader_eof_total 1178
telemt_me_idle_close_by_peer_total 1177
telemt_me_route_drop_no_conn_total 37699534
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15191175
telemt_me_endpoint_quarantine_total 617
telemt_me_single_endpoint_outage_enter_total 98
telemt_me_single_endpoint_outage_exit_total 98
telemt_me_single_endpoint_outage_reconnect_attempt_total 216
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 216
telemt_me_single_endpoint_shadow_rotate_total 650
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 28039
telemt_desync_full_logged_total 8307
telemt_desync_suppressed_total 19732
telemt_desync_frames_bucket_total{bucket="1_2"} 5984
telemt_desync_frames_bucket_total{bucket="3_10"} 12535
telemt_desync_frames_bucket_total{bucket="gt_10"} 9520
telemt_pool_swap_total 86
telemt_pool_force_close_total 2827
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 637
telemt_me_draining_writers_reap_progress_total 25860
telemt_me_writer_removed_unexpected_total 1630
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3458
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23790
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2383
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23033
telemt_me_writer_teardown_success_total{mode="normal"} 27248
telemt_me_writer_teardown_noop_total 25876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53124
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 196.837792
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53124
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 637
telemt_me_refill_failed_total 98
telemt_me_writer_restored_same_endpoint_total 1192
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 160
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 15310160
telemt_user_connections_current{user="hello"} 4777
telemt_user_octets_from_client{user="hello"} 137935481851 (128.46 GB)
telemt_user_octets_to_client{user="hello"} 942170149679 (877.46 GB)
telemt_user_msgs_from_client{user="hello"} 352315
telemt_user_msgs_to_client{user="hello"} 633668
telemt_user_unique_ips_current{user="hello"} 1740
telemt_user_unique_ips_recent_window{user="hello"} 833
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 83794.2 (23h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5239171
telemt_connections_bad_total 509601
telemt_connections_current 3512
telemt_connections_me_current 3512
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 107794
telemt_upstream_connect_attempt_total 43784
telemt_upstream_connect_success_total 43325
telemt_upstream_connect_fail_total 378
telemt_upstream_connect_attempts_per_request{bucket="1"} 43703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17863
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 324
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 378
telemt_me_reconnect_attempts_total 3417
telemt_me_reconnect_success_total 1204
telemt_me_reader_eof_total 1178
telemt_me_idle_close_by_peer_total 1178
telemt_me_route_drop_no_conn_total 2209662
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4056399
telemt_me_endpoint_quarantine_total 501
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 619
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
telemt_me_writers_warm_current 33
telemt_desync_total 19994
telemt_desync_full_logged_total 6935
telemt_desync_suppressed_total 13059
telemt_desync_frames_bucket_total{bucket="1_2"} 3840
telemt_desync_frames_bucket_total{bucket="3_10"} 7849
telemt_desync_frames_bucket_total{bucket="gt_10"} 8305
telemt_pool_swap_total 84
telemt_pool_force_close_total 2468
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 305
telemt_me_draining_writers_reap_progress_total 28463
telemt_me_writer_removed_unexpected_total 1141
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2887
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26729
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2127
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 341
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25995
telemt_me_writer_teardown_success_total{mode="normal"} 29616
telemt_me_writer_teardown_noop_total 28464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58080
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.662727
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58080
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 305
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 1024
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 4046924
telemt_user_connections_current{user="hello"} 3512
telemt_user_octets_from_client{user="hello"} 108153972321 (100.73 GB)
telemt_user_octets_to_client{user="hello"} 1630499721787 (1.48 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 1498
telemt_user_unique_ips_recent_window{user="hello"} 461
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 20630.1 (5h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2835196
telemt_connections_bad_total 107474
telemt_connections_current 3017
telemt_connections_me_current 3017
telemt_handshake_timeouts_total 1220498
telemt_upstream_connect_attempt_total 6595
telemt_upstream_connect_success_total 6499
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 6589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_reconnect_attempts_total 647
telemt_me_reconnect_success_total 198
telemt_me_reader_eof_total 183
telemt_me_idle_close_by_peer_total 183
telemt_me_route_drop_no_conn_total 854788
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1338837
telemt_me_endpoint_quarantine_total 98
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 149
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
telemt_desync_total 7331
telemt_desync_full_logged_total 2408
telemt_desync_suppressed_total 4923
telemt_desync_frames_bucket_total{bucket="1_2"} 1320
telemt_desync_frames_bucket_total{bucket="3_10"} 2754
telemt_desync_frames_bucket_total{bucket="gt_10"} 3257
telemt_pool_swap_total 21
telemt_pool_force_close_total 676
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 67
telemt_me_draining_writers_reap_progress_total 5722
telemt_me_writer_removed_unexpected_total 180
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 547
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5360
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 590
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 86
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5046
telemt_me_writer_teardown_success_total{mode="normal"} 5907
telemt_me_writer_teardown_noop_total 5722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11629
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.900080
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11629
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 67
telemt_me_refill_failed_total 26
telemt_me_writer_restored_same_endpoint_total 164
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 1335296
telemt_user_connections_current{user="hello"} 3017
telemt_user_octets_from_client{user="hello"} 41587916792 (38.73 GB)
telemt_user_octets_to_client{user="hello"} 538755988320 (501.76 GB)
telemt_user_unique_ips_current{user="hello"} 1284
telemt_user_unique_ips_recent_window{user="hello"} 419
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 1601.0 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15203
telemt_connections_bad_total 20
telemt_connections_current 763
telemt_connections_me_current 763
telemt_handshake_timeouts_total 385
telemt_upstream_connect_attempt_total 703
telemt_upstream_connect_success_total 702
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 6
telemt_me_idle_close_by_peer_total 6
telemt_me_route_drop_no_conn_total 4008
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14065
telemt_me_endpoint_quarantine_total 9
telemt_me_single_endpoint_shadow_rotate_total 15
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
telemt_desync_total 56
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_draining_writers_reap_progress_total 559
telemt_me_writer_removed_unexpected_total 6
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 534
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 530
telemt_me_writer_teardown_success_total{mode="normal"} 565
telemt_me_writer_teardown_noop_total 559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1124
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.017047
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1124
telemt_me_writer_restored_same_endpoint_total 6
telemt_user_connections_total{user="hello"} 14056
telemt_user_connections_current{user="hello"} 763
telemt_user_octets_from_client{user="hello"} 674064136 (642.84 MB)
telemt_user_octets_to_client{user="hello"} 12013543612 (11.19 GB)
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 83798.4 (23h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6116072
telemt_connections_bad_total 578306
telemt_connections_current 4324
telemt_connections_me_current 4324
telemt_handshake_timeouts_total 181743
telemt_upstream_connect_attempt_total 31958
telemt_upstream_connect_success_total 31829
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 31921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16034
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_reconnect_attempts_total 1354
telemt_me_reconnect_success_total 693
telemt_me_reader_eof_total 665
telemt_me_idle_close_by_peer_total 665
telemt_me_route_drop_no_conn_total 1920718
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 21
telemt_me_route_drop_queue_full_profile_total{profile="high"} 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4746999
telemt_me_endpoint_quarantine_total 557
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 637
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
telemt_me_writers_warm_current 38
telemt_desync_total 17949
telemt_desync_full_logged_total 5934
telemt_desync_suppressed_total 12015
telemt_desync_frames_bucket_total{bucket="1_2"} 4388
telemt_desync_frames_bucket_total{bucket="3_10"} 6566
telemt_desync_frames_bucket_total{bucket="gt_10"} 6995
telemt_pool_swap_total 92
telemt_pool_force_close_total 2498
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 314
telemt_me_draining_writers_reap_progress_total 28642
telemt_me_writer_removed_unexpected_total 650
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2327
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26970
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2428
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26144
telemt_me_writer_teardown_success_total{mode="normal"} 29297
telemt_me_writer_teardown_noop_total 28643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57940
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.294964
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57940
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 314
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 619
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 4723433
telemt_user_connections_current{user="hello"} 4324
telemt_user_octets_from_client{user="hello"} 92974924060 (86.59 GB)
telemt_user_octets_to_client{user="hello"} 2187919054352 (1.99 TB)
telemt_user_unique_ips_current{user="hello"} 1587
telemt_user_unique_ips_recent_window{user="hello"} 503
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 83795.1 (23h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5215604
telemt_connections_bad_total 481162
telemt_connections_current 3637
telemt_connections_me_current 3637
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 151979
telemt_upstream_connect_attempt_total 48336
telemt_upstream_connect_success_total 47979
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 48277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17882
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 613
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_reconnect_attempts_total 4433
telemt_me_reconnect_success_total 975
telemt_me_reader_eof_total 863
telemt_me_idle_close_by_peer_total 863
telemt_me_seq_mismatch_total 36
telemt_me_route_drop_no_conn_total 1976836
telemt_me_route_drop_channel_closed_total 180
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4132462
telemt_me_endpoint_quarantine_total 667
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 636
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
telemt_me_writers_warm_current 32
telemt_desync_total 16455
telemt_desync_full_logged_total 5571
telemt_desync_suppressed_total 10884
telemt_desync_frames_bucket_total{bucket="1_2"} 4062
telemt_desync_frames_bucket_total{bucket="3_10"} 6073
telemt_desync_frames_bucket_total{bucket="gt_10"} 6320
telemt_pool_swap_total 90
telemt_pool_force_close_total 2433
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 308
telemt_me_draining_writers_reap_progress_total 27869
telemt_me_writer_removed_unexpected_total 875
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2782
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26000
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2242
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 191
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25436
telemt_me_writer_teardown_success_total{mode="normal"} 28782
telemt_me_writer_teardown_noop_total 27871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56653
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.136804
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56653
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 308
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 753
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 4137451
telemt_user_connections_current{user="hello"} 3637
telemt_user_octets_from_client{user="hello"} 76924802721 (71.64 GB)
telemt_user_octets_to_client{user="hello"} 1725343802320 (1.57 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1489
telemt_user_unique_ips_recent_window{user="hello"} 424
```
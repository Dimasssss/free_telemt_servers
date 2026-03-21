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

# Server Metrics 2026-03-21 15:43:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 68862.3 (19h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2446667
telemt_connections_bad_total 136220
telemt_connections_current 1440
telemt_connections_me_current 1440
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 78151
telemt_upstream_connect_attempt_total 29305
telemt_upstream_connect_success_total 29175
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 29262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16989
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1698
telemt_me_reconnect_success_total 673
telemt_me_reader_eof_total 646
telemt_me_idle_close_by_peer_total 646
telemt_me_route_drop_no_conn_total 2117757
telemt_me_route_drop_channel_closed_total 651
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1954160
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 482
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 537
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
telemt_me_writers_active_current 47
telemt_desync_total 7721
telemt_desync_full_logged_total 2661
telemt_desync_suppressed_total 5060
telemt_desync_frames_bucket_total{bucket="1_2"} 1694
telemt_desync_frames_bucket_total{bucket="3_10"} 2939
telemt_desync_frames_bucket_total{bucket="gt_10"} 3088
telemt_pool_swap_total 74
telemt_pool_force_close_total 2243
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 505
telemt_me_draining_writers_reap_progress_total 23474
telemt_me_writer_removed_unexpected_total 624
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2029
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21853
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2124
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 119
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21231
telemt_me_writer_teardown_success_total{mode="normal"} 23882
telemt_me_writer_teardown_noop_total 23480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47362
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 221.267653
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47362
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 505
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 576
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 1955583
telemt_user_connections_current{user="hello"} 1440
telemt_user_octets_from_client{user="hello"} 27616598721 (25.72 GB)
telemt_user_octets_to_client{user="hello"} 482743635678 (449.59 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 554
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 1256.2 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45458
telemt_connections_bad_total 1720
telemt_connections_current 1491
telemt_connections_me_current 1491
telemt_handshake_timeouts_total 1098
telemt_upstream_connect_attempt_total 607
telemt_upstream_connect_success_total 601
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 309
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 20
telemt_me_reconnect_success_total 23
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 34380
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40507
telemt_me_endpoint_quarantine_total 10
telemt_me_single_endpoint_shadow_rotate_total 14
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
telemt_me_writers_active_current 50
telemt_desync_total 115
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 1
telemt_pool_force_close_total 28
telemt_me_writer_close_signal_drop_total 2
telemt_me_draining_writers_reap_progress_total 469
telemt_me_writer_removed_unexpected_total 11
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 34
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 446
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 441
telemt_me_writer_teardown_success_total{mode="normal"} 480
telemt_me_writer_teardown_noop_total 469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 949
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.044014
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 949
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 2
telemt_me_writer_restored_same_endpoint_total 18
telemt_me_async_recovery_trigger_total 2
telemt_user_connections_total{user="hello"} 39353
telemt_user_connections_current{user="hello"} 1491
telemt_user_octets_from_client{user="hello"} 508029584 (484.49 MB)
telemt_user_octets_to_client{user="hello"} 9649493944 (8.99 GB)
telemt_user_unique_ips_current{user="hello"} 961
telemt_user_unique_ips_recent_window{user="hello"} 431
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 68859.8 (19h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4918010
telemt_connections_bad_total 442716
telemt_connections_current 4506
telemt_connections_me_current 4506
telemt_handshake_timeouts_total 174218
telemt_upstream_connect_attempt_total 25495
telemt_upstream_connect_success_total 25440
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 25446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13882
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1157
telemt_me_reconnect_success_total 582
telemt_me_reader_eof_total 587
telemt_me_idle_close_by_peer_total 587
telemt_me_route_drop_no_conn_total 2769811
telemt_me_route_drop_channel_closed_total 45
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4018363
telemt_me_endpoint_quarantine_total 435
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 520
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
telemt_desync_total 16495
telemt_desync_full_logged_total 5546
telemt_desync_suppressed_total 10949
telemt_desync_frames_bucket_total{bucket="1_2"} 3478
telemt_desync_frames_bucket_total{bucket="3_10"} 6515
telemt_desync_frames_bucket_total{bucket="gt_10"} 6502
telemt_pool_swap_total 73
telemt_pool_force_close_total 2378
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 370
telemt_me_draining_writers_reap_progress_total 23125
telemt_me_writer_removed_unexpected_total 567
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2029
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21428
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2180
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 198
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20747
telemt_me_writer_teardown_success_total{mode="normal"} 23457
telemt_me_writer_teardown_noop_total 23157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46614
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 87.813535
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46614
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 370
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 524
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 4013490
telemt_user_connections_current{user="hello"} 4506
telemt_user_octets_from_client{user="hello"} 64632511020 (60.19 GB)
telemt_user_octets_to_client{user="hello"} 1319376642748 (1.20 TB)
telemt_user_unique_ips_current{user="hello"} 1795
telemt_user_unique_ips_recent_window{user="hello"} 661
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 68861.1 (19h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3983234
telemt_connections_bad_total 424784
telemt_connections_current 3899
telemt_connections_me_current 3899
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 140521
telemt_upstream_connect_attempt_total 29865
telemt_upstream_connect_success_total 29583
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 29723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13882
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 487
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1387
telemt_me_reconnect_success_total 607
telemt_me_reader_eof_total 569
telemt_me_idle_close_by_peer_total 569
telemt_me_route_drop_no_conn_total 1252875
telemt_me_route_drop_channel_closed_total 102
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2921740
telemt_me_endpoint_quarantine_total 444
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 526
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
telemt_desync_total 13652
telemt_desync_full_logged_total 4569
telemt_desync_suppressed_total 9083
telemt_desync_frames_bucket_total{bucket="1_2"} 3437
telemt_desync_frames_bucket_total{bucket="3_10"} 5265
telemt_desync_frames_bucket_total{bucket="gt_10"} 4950
telemt_pool_swap_total 75
telemt_pool_force_close_total 2174
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 219
telemt_me_draining_writers_reap_progress_total 22293
telemt_me_writer_removed_unexpected_total 552
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1927
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20918
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2020
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 154
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20119
telemt_me_writer_teardown_success_total{mode="normal"} 22845
telemt_me_writer_teardown_noop_total 22294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45139
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.576693
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45139
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 219
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 511
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 2921333
telemt_user_connections_current{user="hello"} 3899
telemt_user_octets_from_client{user="hello"} 60112203909 (55.98 GB)
telemt_user_octets_to_client{user="hello"} 1358239160339 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1476
telemt_user_unique_ips_recent_window{user="hello"} 504
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 68825.0 (19h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3917544
telemt_connections_bad_total 406673
telemt_connections_current 3667
telemt_connections_me_current 3667
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 118727
telemt_upstream_connect_attempt_total 35150
telemt_upstream_connect_success_total 34914
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 35047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15215
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 855
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1434
telemt_me_reconnect_success_total 660
telemt_me_reader_eof_total 602
telemt_me_idle_close_by_peer_total 602
telemt_me_route_drop_no_conn_total 1360024
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2908798
telemt_me_endpoint_quarantine_total 489
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 517
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
telemt_me_writers_active_current 45
telemt_desync_total 13440
telemt_desync_full_logged_total 4457
telemt_desync_suppressed_total 8983
telemt_desync_frames_bucket_total{bucket="1_2"} 3356
telemt_desync_frames_bucket_total{bucket="3_10"} 5052
telemt_desync_frames_bucket_total{bucket="gt_10"} 5032
telemt_pool_swap_total 73
telemt_pool_force_close_total 2099
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 238
telemt_me_draining_writers_reap_progress_total 23730
telemt_me_writer_removed_unexpected_total 572
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2009
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22331
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1918
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 181
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21631
telemt_me_writer_teardown_success_total{mode="normal"} 24340
telemt_me_writer_teardown_noop_total 23736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48076
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.723527
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48076
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 238
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 568
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 2912556
telemt_user_connections_current{user="hello"} 3667
telemt_user_octets_from_client{user="hello"} 62416655677 (58.13 GB)
telemt_user_octets_to_client{user="hello"} 1344772339176 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1466
telemt_user_unique_ips_recent_window{user="hello"} 522
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 68864.2 (19h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13476493
telemt_connections_bad_total 874770
telemt_connections_current 5524
telemt_connections_me_current 5524
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 405229
telemt_upstream_connect_attempt_total 116276
telemt_upstream_connect_success_total 106366
telemt_upstream_connect_fail_total 8852
telemt_upstream_connect_attempts_per_request{bucket="1"} 115218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25732
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8852
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 3871
telemt_me_reconnect_success_total 1414
telemt_me_reader_eof_total 984
telemt_me_idle_close_by_peer_total 983
telemt_me_route_drop_no_conn_total 26306383
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11087194
telemt_me_endpoint_quarantine_total 529
telemt_me_single_endpoint_outage_enter_total 78
telemt_me_single_endpoint_outage_exit_total 78
telemt_me_single_endpoint_outage_reconnect_attempt_total 174
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 174
telemt_me_single_endpoint_shadow_rotate_total 537
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
telemt_me_writers_active_current 43
telemt_desync_total 19475
telemt_desync_full_logged_total 6092
telemt_desync_suppressed_total 13383
telemt_desync_frames_bucket_total{bucket="1_2"} 4246
telemt_desync_frames_bucket_total{bucket="3_10"} 8587
telemt_desync_frames_bucket_total{bucket="gt_10"} 6642
telemt_pool_swap_total 70
telemt_pool_force_close_total 2280
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 500
telemt_me_draining_writers_reap_progress_total 22018
telemt_me_writer_removed_unexpected_total 1345
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2899
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20257
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1909
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 371
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19738
telemt_me_writer_teardown_success_total{mode="normal"} 23156
telemt_me_writer_teardown_noop_total 22030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45186
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 172.852767
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45186
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 500
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 988
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 11162203
telemt_user_connections_current{user="hello"} 5524
telemt_user_octets_from_client{user="hello"} 78447102833 (73.06 GB)
telemt_user_octets_to_client{user="hello"} 811146549857 (755.44 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 2051
telemt_user_unique_ips_recent_window{user="hello"} 1029
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 68831.9 (19h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3923005
telemt_connections_bad_total 428408
telemt_connections_current 4561
telemt_connections_me_current 4561
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 84527
telemt_upstream_connect_attempt_total 28850
telemt_upstream_connect_success_total 28536
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 28806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14875
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_reconnect_attempts_total 2770
telemt_me_reconnect_success_total 1031
telemt_me_reader_eof_total 1032
telemt_me_idle_close_by_peer_total 1032
telemt_me_route_drop_no_conn_total 1674559
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3032779
telemt_me_endpoint_quarantine_total 421
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 515
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
telemt_me_writers_active_current 86
telemt_desync_total 14491
telemt_desync_full_logged_total 5038
telemt_desync_suppressed_total 9453
telemt_desync_frames_bucket_total{bucket="1_2"} 2813
telemt_desync_frames_bucket_total{bucket="3_10"} 5767
telemt_desync_frames_bucket_total{bucket="gt_10"} 5911
telemt_pool_swap_total 68
telemt_pool_force_close_total 1981
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 201
telemt_me_draining_writers_reap_progress_total 24158
telemt_me_writer_removed_unexpected_total 1001
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2427
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22766
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1723
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 258
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22177
telemt_me_writer_teardown_success_total{mode="normal"} 25193
telemt_me_writer_teardown_noop_total 24159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49352
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.418027
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49352
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 201
telemt_me_refill_failed_total 95
telemt_me_writer_restored_same_endpoint_total 892
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 3016263
telemt_user_connections_current{user="hello"} 4561
telemt_user_octets_from_client{user="hello"} 79144410036 (73.71 GB)
telemt_user_octets_to_client{user="hello"} 1246809982686 (1.13 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1880
telemt_user_unique_ips_recent_window{user="hello"} 540
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 5667.4 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 899412
telemt_connections_bad_total 25332
telemt_connections_current 2900
telemt_connections_me_current 2900
telemt_handshake_timeouts_total 431328
telemt_upstream_connect_attempt_total 2064
telemt_upstream_connect_success_total 2025
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 2058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 249
telemt_me_reconnect_success_total 84
telemt_me_reader_eof_total 75
telemt_me_idle_close_by_peer_total 75
telemt_me_route_drop_no_conn_total 384272
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 406612
telemt_me_endpoint_quarantine_total 24
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 46
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
telemt_desync_total 1983
telemt_desync_full_logged_total 650
telemt_desync_suppressed_total 1333
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 773
telemt_desync_frames_bucket_total{bucket="gt_10"} 877
telemt_pool_swap_total 5
telemt_pool_force_close_total 172
telemt_me_writer_close_signal_drop_total 13
telemt_me_draining_writers_reap_progress_total 1724
telemt_me_writer_removed_unexpected_total 76
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 169
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1631
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 133
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 39
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1552
telemt_me_writer_teardown_success_total{mode="normal"} 1800
telemt_me_writer_teardown_noop_total 1724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3524
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.789231
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3524
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 13
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 73
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 406004
telemt_user_connections_current{user="hello"} 2900
telemt_user_octets_from_client{user="hello"} 11205078984 (10.44 GB)
telemt_user_octets_to_client{user="hello"} 149641263152 (139.36 GB)
telemt_user_unique_ips_current{user="hello"} 1131
telemt_user_unique_ips_recent_window{user="hello"} 592
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 66817.9 (18h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1252802
telemt_connections_bad_total 139569
telemt_connections_current 777
telemt_connections_me_current 777
telemt_handshake_timeouts_total 449091
telemt_upstream_connect_attempt_total 31232
telemt_upstream_connect_success_total 31225
telemt_upstream_connect_attempts_per_request{bucket="1"} 31225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1337
telemt_me_reconnect_success_total 563
telemt_me_reader_eof_total 560
telemt_me_idle_close_by_peer_total 560
telemt_me_route_drop_no_conn_total 273880
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 588364
telemt_me_endpoint_quarantine_total 600
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 559
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
telemt_me_writers_active_current 43
telemt_desync_total 3620
telemt_desync_full_logged_total 1312
telemt_desync_suppressed_total 2308
telemt_desync_frames_bucket_total{bucket="1_2"} 666
telemt_desync_frames_bucket_total{bucket="3_10"} 1302
telemt_desync_frames_bucket_total{bucket="gt_10"} 1652
telemt_pool_swap_total 73
telemt_pool_force_close_total 1711
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 114
telemt_me_draining_writers_reap_progress_total 27995
telemt_me_writer_removed_unexpected_total 530
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2125
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26416
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1682
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26284
telemt_me_writer_teardown_success_total{mode="normal"} 28541
telemt_me_writer_teardown_noop_total 27995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56536
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.524793
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56536
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 114
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 468
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 587980
telemt_user_connections_current{user="hello"} 777
telemt_user_octets_from_client{user="hello"} 12033649171 (11.21 GB)
telemt_user_octets_to_client{user="hello"} 225526094229 (210.04 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 264
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 68836.2 (19h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4341249
telemt_connections_bad_total 400610
telemt_connections_current 4781
telemt_connections_me_current 4781
telemt_handshake_timeouts_total 141731
telemt_upstream_connect_attempt_total 27310
telemt_upstream_connect_success_total 27197
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 27275
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13686
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_reconnect_attempts_total 1187
telemt_me_reconnect_success_total 617
telemt_me_reader_eof_total 584
telemt_me_idle_close_by_peer_total 584
telemt_me_route_drop_no_conn_total 1316676
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3440738
telemt_me_endpoint_quarantine_total 498
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 526
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
telemt_me_writers_active_current 43
telemt_desync_total 13442
telemt_desync_full_logged_total 4444
telemt_desync_suppressed_total 8998
telemt_desync_frames_bucket_total{bucket="1_2"} 3187
telemt_desync_frames_bucket_total{bucket="3_10"} 4999
telemt_desync_frames_bucket_total{bucket="gt_10"} 5256
telemt_pool_swap_total 76
telemt_pool_force_close_total 2002
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 224
telemt_me_draining_writers_reap_progress_total 24496
telemt_me_writer_removed_unexpected_total 572
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1959
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23111
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1955
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22494
telemt_me_writer_teardown_success_total{mode="normal"} 25070
telemt_me_writer_teardown_noop_total 24496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49566
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.910184
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49566
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 224
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 546
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 3432261
telemt_user_connections_current{user="hello"} 4781
telemt_user_octets_from_client{user="hello"} 69647460152 (64.86 GB)
telemt_user_octets_to_client{user="hello"} 1612966137624 (1.47 TB)
telemt_user_unique_ips_current{user="hello"} 1683
telemt_user_unique_ips_recent_window{user="hello"} 628
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 68832.8 (19h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3859321
telemt_connections_bad_total 352195
telemt_connections_current 4016
telemt_connections_me_current 4016
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 118213
telemt_upstream_connect_attempt_total 43833
telemt_upstream_connect_success_total 43537
telemt_upstream_connect_fail_total 245
telemt_upstream_connect_attempts_per_request{bucket="1"} 43782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15577
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 602
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 245
telemt_me_reconnect_attempts_total 3862
telemt_me_reconnect_success_total 861
telemt_me_reader_eof_total 753
telemt_me_idle_close_by_peer_total 753
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 1402471
telemt_me_route_drop_channel_closed_total 104
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3080165
telemt_me_endpoint_quarantine_total 574
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 524
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
telemt_me_writers_active_current 44
telemt_desync_total 12031
telemt_desync_full_logged_total 4084
telemt_desync_suppressed_total 7947
telemt_desync_frames_bucket_total{bucket="1_2"} 3011
telemt_desync_frames_bucket_total{bucket="3_10"} 4472
telemt_desync_frames_bucket_total{bucket="gt_10"} 4548
telemt_pool_swap_total 74
telemt_pool_force_close_total 1935
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 214
telemt_me_draining_writers_reap_progress_total 23920
telemt_me_writer_removed_unexpected_total 766
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2345
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22374
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1778
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 157
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21985
telemt_me_writer_teardown_success_total{mode="normal"} 24719
telemt_me_writer_teardown_noop_total 23921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48640
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.147687
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48640
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 214
telemt_me_refill_failed_total 170
telemt_me_writer_restored_same_endpoint_total 667
telemt_me_writer_restored_fallback_total 42
telemt_me_async_recovery_trigger_total 57
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 3088526
telemt_user_connections_current{user="hello"} 4016
telemt_user_octets_from_client{user="hello"} 55991743145 (52.15 GB)
telemt_user_octets_to_client{user="hello"} 1318500528592 (1.20 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1495
telemt_user_unique_ips_recent_window{user="hello"} 520
```
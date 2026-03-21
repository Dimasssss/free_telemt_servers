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

# Server Metrics 2026-03-21 13:46:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 61835.8 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2052527
telemt_connections_bad_total 102188
telemt_connections_current 1605
telemt_connections_me_current 1605
telemt_handshake_timeouts_total 73675
telemt_upstream_connect_attempt_total 23705
telemt_upstream_connect_success_total 23585
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 23662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15175
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1341
telemt_me_reconnect_success_total 559
telemt_me_reader_eof_total 530
telemt_me_idle_close_by_peer_total 530
telemt_me_route_drop_no_conn_total 1530662
telemt_me_route_drop_channel_closed_total 512
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1622264
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 436
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 487
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
telemt_me_writers_active_current 50
telemt_desync_total 6416
telemt_desync_full_logged_total 2216
telemt_desync_suppressed_total 4200
telemt_desync_frames_bucket_total{bucket="1_2"} 1435
telemt_desync_frames_bucket_total{bucket="3_10"} 2430
telemt_desync_frames_bucket_total{bucket="gt_10"} 2551
telemt_pool_swap_total 67
telemt_pool_force_close_total 2004
telemt_pool_stale_pick_total 14
telemt_me_writer_close_signal_drop_total 385
telemt_me_draining_writers_reap_progress_total 21184
telemt_me_writer_removed_unexpected_total 513
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1753
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19766
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1929
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 75
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19180
telemt_me_writer_teardown_success_total{mode="normal"} 21519
telemt_me_writer_teardown_noop_total 21189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42708
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 169.888284
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42708
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 385
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 483
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 1621031
telemt_user_connections_current{user="hello"} 1605
telemt_user_octets_from_client{user="hello"} 24101567427 (22.45 GB)
telemt_user_octets_to_client{user="hello"} 421679438887 (392.72 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 604
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 1390.2 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149425
telemt_connections_bad_total 5185
telemt_connections_current 2699
telemt_connections_me_current 2699
telemt_handshake_timeouts_total 4292
telemt_upstream_connect_attempt_total 498
telemt_upstream_connect_success_total 497
telemt_upstream_connect_attempts_per_request{bucket="1"} 497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 271
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 44
telemt_me_reconnect_success_total 12
telemt_me_reader_eof_total 9
telemt_me_idle_close_by_peer_total 9
telemt_me_route_drop_no_conn_total 74256
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130534
telemt_me_endpoint_quarantine_total 14
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
telemt_me_writers_active_current 43
telemt_desync_total 483
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 309
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 185
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 1
telemt_pool_force_close_total 21
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 372
telemt_me_writer_removed_unexpected_total 8
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 357
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 351
telemt_me_writer_teardown_success_total{mode="normal"} 381
telemt_me_writer_teardown_noop_total 372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 753
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.047854
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 753
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 129514
telemt_user_connections_current{user="hello"} 2699
telemt_user_octets_from_client{user="hello"} 2880483784 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 29885439372 (27.83 GB)
telemt_user_unique_ips_current{user="hello"} 1311
telemt_user_unique_ips_recent_window{user="hello"} 475
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 61834.4 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4081019
telemt_connections_bad_total 395120
telemt_connections_current 4457
telemt_connections_me_current 4457
telemt_handshake_timeouts_total 157348
telemt_upstream_connect_attempt_total 23450
telemt_upstream_connect_success_total 23410
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 23415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12737
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 903
telemt_me_reconnect_success_total 530
telemt_me_reader_eof_total 528
telemt_me_idle_close_by_peer_total 528
telemt_me_route_drop_no_conn_total 2064721
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3295904
telemt_me_endpoint_quarantine_total 392
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 470
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_desync_total 13843
telemt_desync_full_logged_total 4691
telemt_desync_suppressed_total 9152
telemt_desync_frames_bucket_total{bucket="1_2"} 2923
telemt_desync_frames_bucket_total{bucket="3_10"} 5456
telemt_desync_frames_bucket_total{bucket="gt_10"} 5464
telemt_pool_swap_total 65
telemt_pool_force_close_total 2078
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 319
telemt_me_draining_writers_reap_progress_total 21280
telemt_me_writer_removed_unexpected_total 510
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1848
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19752
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1895
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 183
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19202
telemt_me_writer_teardown_success_total{mode="normal"} 21600
telemt_me_writer_teardown_noop_total 21298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42898
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 65.972394
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42898
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 319
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 482
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 3291784
telemt_user_connections_current{user="hello"} 4457
telemt_user_octets_from_client{user="hello"} 54502864880 (50.76 GB)
telemt_user_octets_to_client{user="hello"} 1130652133236 (1.03 TB)
telemt_user_unique_ips_current{user="hello"} 1787
telemt_user_unique_ips_recent_window{user="hello"} 581
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 61835.0 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3336587
telemt_connections_bad_total 370579
telemt_connections_current 3790
telemt_connections_me_current 3790
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 125174
telemt_upstream_connect_attempt_total 27818
telemt_upstream_connect_success_total 27543
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 27678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12732
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 477
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1165
telemt_me_reconnect_success_total 549
telemt_me_reader_eof_total 514
telemt_me_idle_close_by_peer_total 514
telemt_me_route_drop_no_conn_total 1042382
telemt_me_route_drop_channel_closed_total 83
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2411748
telemt_me_endpoint_quarantine_total 401
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 473
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
telemt_desync_total 10996
telemt_desync_full_logged_total 3727
telemt_desync_suppressed_total 7269
telemt_desync_frames_bucket_total{bucket="1_2"} 2756
telemt_desync_frames_bucket_total{bucket="3_10"} 4224
telemt_desync_frames_bucket_total{bucket="gt_10"} 4016
telemt_pool_swap_total 67
telemt_pool_force_close_total 1906
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 173
telemt_me_draining_writers_reap_progress_total 20484
telemt_me_writer_removed_unexpected_total 499
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1738
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19251
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1780
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 126
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18578
telemt_me_writer_teardown_success_total{mode="normal"} 20989
telemt_me_writer_teardown_noop_total 20485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41474
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.989262
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41474
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 173
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 463
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 2412272
telemt_user_connections_current{user="hello"} 3790
telemt_user_octets_from_client{user="hello"} 45187890457 (42.08 GB)
telemt_user_octets_to_client{user="hello"} 1135056686823 (1.03 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1474
telemt_user_unique_ips_recent_window{user="hello"} 535
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 61799.9 (17h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3247661
telemt_connections_bad_total 346443
telemt_connections_current 3379
telemt_connections_me_current 3379
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 93985
telemt_upstream_connect_attempt_total 32995
telemt_upstream_connect_success_total 32768
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 32901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14085
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 845
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1281
telemt_me_reconnect_success_total 621
telemt_me_reader_eof_total 565
telemt_me_idle_close_by_peer_total 565
telemt_me_route_drop_no_conn_total 997799
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2377014
telemt_me_endpoint_quarantine_total 449
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 462
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
telemt_desync_total 11113
telemt_desync_full_logged_total 3688
telemt_desync_suppressed_total 7425
telemt_desync_frames_bucket_total{bucket="1_2"} 2815
telemt_desync_frames_bucket_total{bucket="3_10"} 4188
telemt_desync_frames_bucket_total{bucket="gt_10"} 4110
telemt_pool_swap_total 65
telemt_pool_force_close_total 1845
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 214
telemt_me_draining_writers_reap_progress_total 21811
telemt_me_writer_removed_unexpected_total 538
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1839
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20545
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1678
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 167
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19966
telemt_me_writer_teardown_success_total{mode="normal"} 22384
telemt_me_writer_teardown_noop_total 21816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44200
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.325772
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44200
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 214
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 542
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2381739
telemt_user_connections_current{user="hello"} 3379
telemt_user_octets_from_client{user="hello"} 52412871293 (48.81 GB)
telemt_user_octets_to_client{user="hello"} 1132360967372 (1.03 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1326
telemt_user_unique_ips_recent_window{user="hello"} 490
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 61838.1 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11055802
telemt_connections_bad_total 757174
telemt_connections_current 5595
telemt_connections_me_current 5595
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 349036
telemt_upstream_connect_attempt_total 111008
telemt_upstream_connect_success_total 101858
telemt_upstream_connect_fail_total 8199
telemt_upstream_connect_attempts_per_request{bucket="1"} 110057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24025
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5007
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8199
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 3621
telemt_me_reconnect_success_total 1262
telemt_me_reader_eof_total 918
telemt_me_idle_close_by_peer_total 917
telemt_me_route_drop_no_conn_total 20454920
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9055557
telemt_me_endpoint_quarantine_total 465
telemt_me_single_endpoint_outage_enter_total 68
telemt_me_single_endpoint_outage_exit_total 68
telemt_me_single_endpoint_outage_reconnect_attempt_total 153
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 153
telemt_me_single_endpoint_shadow_rotate_total 486
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 16752
telemt_desync_full_logged_total 5352
telemt_desync_suppressed_total 11400
telemt_desync_frames_bucket_total{bucket="1_2"} 3612
telemt_desync_frames_bucket_total{bucket="3_10"} 7324
telemt_desync_frames_bucket_total{bucket="gt_10"} 5816
telemt_pool_swap_total 62
telemt_pool_force_close_total 2020
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 420
telemt_me_draining_writers_reap_progress_total 20136
telemt_me_writer_removed_unexpected_total 1228
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2625
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18567
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1686
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 334
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18116
telemt_me_writer_teardown_success_total{mode="normal"} 21192
telemt_me_writer_teardown_noop_total 20146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41338
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 161.521912
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41338
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 420
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 896
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 323
telemt_user_connections_total{user="hello"} 9129681
telemt_user_connections_current{user="hello"} 5595
telemt_user_octets_from_client{user="hello"} 68794536177 (64.07 GB)
telemt_user_octets_to_client{user="hello"} 732723180022 (682.40 GB)
telemt_user_msgs_from_client{user="hello"} 227549
telemt_user_msgs_to_client{user="hello"} 539047
telemt_user_unique_ips_current{user="hello"} 1931
telemt_user_unique_ips_recent_window{user="hello"} 1139
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 61806.0 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3267639
telemt_connections_bad_total 372399
telemt_connections_current 3935
telemt_connections_me_current 3935
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 72323
telemt_upstream_connect_attempt_total 26581
telemt_upstream_connect_success_total 26295
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 26550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_reconnect_attempts_total 2579
telemt_me_reconnect_success_total 949
telemt_me_reader_eof_total 942
telemt_me_idle_close_by_peer_total 942
telemt_me_route_drop_no_conn_total 1284113
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2497340
telemt_me_endpoint_quarantine_total 385
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 467
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
telemt_me_writers_active_current 89
telemt_desync_total 11666
telemt_desync_full_logged_total 4054
telemt_desync_suppressed_total 7612
telemt_desync_frames_bucket_total{bucket="1_2"} 2269
telemt_desync_frames_bucket_total{bucket="3_10"} 4636
telemt_desync_frames_bucket_total{bucket="gt_10"} 4761
telemt_pool_swap_total 61
telemt_pool_force_close_total 1741
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 165
telemt_me_draining_writers_reap_progress_total 22170
telemt_me_writer_removed_unexpected_total 913
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2188
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20925
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1527
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 214
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20429
telemt_me_writer_teardown_success_total{mode="normal"} 23113
telemt_me_writer_teardown_noop_total 22171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45284
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.832992
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45284
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 165
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 814
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 2481993
telemt_user_connections_current{user="hello"} 3935
telemt_user_octets_from_client{user="hello"} 52200871108 (48.62 GB)
telemt_user_octets_to_client{user="hello"} 1074241734078 (1000.47 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1606
telemt_user_unique_ips_recent_window{user="hello"} 519
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 61800.5 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5007430
telemt_connections_bad_total 244781
telemt_connections_current 3080
telemt_connections_me_current 3080
telemt_handshake_timeouts_total 2210532
telemt_upstream_connect_attempt_total 24405
telemt_upstream_connect_success_total 24371
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 24374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13177
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 290
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1055
telemt_me_reconnect_success_total 453
telemt_me_reader_eof_total 454
telemt_me_idle_close_by_peer_total 454
telemt_me_route_drop_no_conn_total 1167286
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2253389
telemt_me_endpoint_quarantine_total 457
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 480
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
telemt_me_writers_active_current 46
telemt_desync_total 10730
telemt_desync_full_logged_total 3782
telemt_desync_suppressed_total 6948
telemt_desync_frames_bucket_total{bucket="1_2"} 1989
telemt_desync_frames_bucket_total{bucket="3_10"} 4240
telemt_desync_frames_bucket_total{bucket="gt_10"} 4501
telemt_pool_swap_total 67
telemt_pool_force_close_total 1717
telemt_me_writer_close_signal_drop_total 150
telemt_me_draining_writers_reap_progress_total 21840
telemt_me_writer_removed_unexpected_total 436
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1511
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20792
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1653
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 64
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20123
telemt_me_writer_teardown_success_total{mode="normal"} 22303
telemt_me_writer_teardown_noop_total 21840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44143
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.709208
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44143
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 150
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 393
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 2246425
telemt_user_connections_current{user="hello"} 3080
telemt_user_octets_from_client{user="hello"} 47417955148 (44.16 GB)
telemt_user_octets_to_client{user="hello"} 1042298204192 (970.72 GB)
telemt_user_unique_ips_current{user="hello"} 1321
telemt_user_unique_ips_recent_window{user="hello"} 575
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 59791.6 (16h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1074167
telemt_connections_bad_total 135004
telemt_connections_current 741
telemt_connections_me_current 741
telemt_handshake_timeouts_total 375983
telemt_upstream_connect_attempt_total 28055
telemt_upstream_connect_success_total 28052
telemt_upstream_connect_attempts_per_request{bucket="1"} 28052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16437
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1191
telemt_me_reconnect_success_total 462
telemt_me_reader_eof_total 460
telemt_me_idle_close_by_peer_total 460
telemt_me_route_drop_no_conn_total 224071
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 493121
telemt_me_endpoint_quarantine_total 553
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 506
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 3236
telemt_desync_full_logged_total 1200
telemt_desync_suppressed_total 2036
telemt_desync_frames_bucket_total{bucket="1_2"} 566
telemt_desync_frames_bucket_total{bucket="3_10"} 1156
telemt_desync_frames_bucket_total{bucket="gt_10"} 1514
telemt_pool_swap_total 66
telemt_pool_force_close_total 1499
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 103
telemt_me_draining_writers_reap_progress_total 25163
telemt_me_writer_removed_unexpected_total 434
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1849
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23759
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1496
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23664
telemt_me_writer_teardown_success_total{mode="normal"} 25608
telemt_me_writer_teardown_noop_total 25163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50771
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.348410
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50771
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 103
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 375
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 492899
telemt_user_connections_current{user="hello"} 741
telemt_user_octets_from_client{user="hello"} 9180937827 (8.55 GB)
telemt_user_octets_to_client{user="hello"} 187418774853 (174.55 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 61810.8 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3547577
telemt_connections_bad_total 330229
telemt_connections_current 4493
telemt_connections_me_current 4493
telemt_handshake_timeouts_total 107643
telemt_upstream_connect_attempt_total 25209
telemt_upstream_connect_success_total 25106
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 25178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12577
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 1029
telemt_me_reconnect_success_total 581
telemt_me_reader_eof_total 541
telemt_me_idle_close_by_peer_total 541
telemt_me_route_drop_no_conn_total 1033542
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2807355
telemt_me_endpoint_quarantine_total 464
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 477
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
telemt_me_writers_active_current 46
telemt_desync_total 11256
telemt_desync_full_logged_total 3696
telemt_desync_suppressed_total 7560
telemt_desync_frames_bucket_total{bucket="1_2"} 2689
telemt_desync_frames_bucket_total{bucket="3_10"} 4179
telemt_desync_frames_bucket_total{bucket="gt_10"} 4388
telemt_pool_swap_total 68
telemt_pool_force_close_total 1759
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 189
telemt_me_draining_writers_reap_progress_total 22633
telemt_me_writer_removed_unexpected_total 531
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1770
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21393
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1727
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20874
telemt_me_writer_teardown_success_total{mode="normal"} 23163
telemt_me_writer_teardown_noop_total 22633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45796
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.649492
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45796
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 189
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 513
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 2799859
telemt_user_connections_current{user="hello"} 4493
telemt_user_octets_from_client{user="hello"} 59139924244 (55.08 GB)
telemt_user_octets_to_client{user="hello"} 1319316449308 (1.20 TB)
telemt_user_unique_ips_current{user="hello"} 1563
telemt_user_unique_ips_recent_window{user="hello"} 601
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 61807.4 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3193640
telemt_connections_bad_total 274547
telemt_connections_current 3866
telemt_connections_me_current 3866
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 93987
telemt_upstream_connect_attempt_total 41385
telemt_upstream_connect_success_total 41118
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 41340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14267
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 588
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_reconnect_attempts_total 3532
telemt_me_reconnect_success_total 746
telemt_me_reader_eof_total 654
telemt_me_idle_close_by_peer_total 654
telemt_me_seq_mismatch_total 30
telemt_me_route_drop_no_conn_total 1076840
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2565925
telemt_me_endpoint_quarantine_total 524
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 476
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
telemt_me_writers_active_current 45
telemt_desync_total 9936
telemt_desync_full_logged_total 3386
telemt_desync_suppressed_total 6550
telemt_desync_frames_bucket_total{bucket="1_2"} 2529
telemt_desync_frames_bucket_total{bucket="3_10"} 3668
telemt_desync_frames_bucket_total{bucket="gt_10"} 3739
telemt_pool_swap_total 67
telemt_pool_force_close_total 1706
telemt_me_writer_close_signal_drop_total 176
telemt_me_draining_writers_reap_progress_total 21783
telemt_me_writer_removed_unexpected_total 666
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2071
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20408
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1594
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 112
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20077
telemt_me_writer_teardown_success_total{mode="normal"} 22479
telemt_me_writer_teardown_noop_total 21784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44263
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.182783
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44263
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 176
telemt_me_refill_failed_total 158
telemt_me_writer_restored_same_endpoint_total 570
telemt_me_writer_restored_fallback_total 39
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2575156
telemt_user_connections_current{user="hello"} 3866
telemt_user_octets_from_client{user="hello"} 46982847361 (43.76 GB)
telemt_user_octets_to_client{user="hello"} 1119821577860 (1.02 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1516
telemt_user_unique_ips_recent_window{user="hello"} 555
```
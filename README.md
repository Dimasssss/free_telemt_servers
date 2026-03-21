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

# Server Metrics 2026-03-21 14:22:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 63968.0 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2198740
telemt_connections_bad_total 108307
telemt_connections_current 1666
telemt_connections_me_current 1666
telemt_handshake_timeouts_total 74915
telemt_upstream_connect_attempt_total 24621
telemt_upstream_connect_success_total 24496
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 24578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15751
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1443
telemt_me_reconnect_success_total 612
telemt_me_reader_eof_total 587
telemt_me_idle_close_by_peer_total 587
telemt_me_route_drop_no_conn_total 1876818
telemt_me_route_drop_channel_closed_total 592
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1754722
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 444
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 500
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
telemt_me_writers_active_current 89
telemt_me_writers_warm_current 19
telemt_desync_total 6923
telemt_desync_full_logged_total 2368
telemt_desync_suppressed_total 4555
telemt_desync_frames_bucket_total{bucket="1_2"} 1540
telemt_desync_frames_bucket_total{bucket="3_10"} 2647
telemt_desync_frames_bucket_total{bucket="gt_10"} 2736
telemt_pool_swap_total 68
telemt_pool_force_close_total 2060
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 433
telemt_me_draining_writers_reap_progress_total 21964
telemt_me_writer_removed_unexpected_total 569
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1840
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20483
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1983
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19904
telemt_me_writer_teardown_success_total{mode="normal"} 22323
telemt_me_writer_teardown_noop_total 21970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44293
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 198.074135
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44293
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 433
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 536
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1753395
telemt_user_connections_current{user="hello"} 1666
telemt_user_octets_from_client{user="hello"} 25368006791 (23.63 GB)
telemt_user_octets_to_client{user="hello"} 438480196547 (408.37 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 601
telemt_user_unique_ips_recent_window{user="hello"} 288
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 3521.4 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288587
telemt_connections_bad_total 10265
telemt_connections_current 2950
telemt_connections_me_current 2950
telemt_handshake_timeouts_total 8858
telemt_upstream_connect_attempt_total 1321
telemt_upstream_connect_success_total 1317
telemt_upstream_connect_attempts_per_request{bucket="1"} 1317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 615
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 108
telemt_me_reconnect_success_total 24
telemt_me_reader_eof_total 22
telemt_me_idle_close_by_peer_total 22
telemt_me_route_drop_no_conn_total 187059
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 256162
telemt_me_endpoint_quarantine_total 24
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 31
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
telemt_me_writers_active_current 43
telemt_desync_total 1045
telemt_desync_full_logged_total 419
telemt_desync_suppressed_total 626
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 406
telemt_desync_frames_bucket_total{bucket="gt_10"} 425
telemt_pool_swap_total 3
telemt_pool_force_close_total 80
telemt_me_writer_close_signal_drop_total 19
telemt_me_draining_writers_reap_progress_total 919
telemt_me_writer_removed_unexpected_total 20
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 68
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 873
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 839
telemt_me_writer_teardown_success_total{mode="normal"} 941
telemt_me_writer_teardown_noop_total 919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1860
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.308569
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1860
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 19
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 251504
telemt_user_connections_current{user="hello"} 2950
telemt_user_octets_from_client{user="hello"} 4493320075 (4.18 GB)
telemt_user_octets_to_client{user="hello"} 62785366723 (58.47 GB)
telemt_user_msgs_from_client{user="hello"} 423
telemt_user_msgs_to_client{user="hello"} 734
telemt_user_unique_ips_current{user="hello"} 1470
telemt_user_unique_ips_recent_window{user="hello"} 577
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 63965.8 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4336442
telemt_connections_bad_total 404777
telemt_connections_current 4440
telemt_connections_me_current 4440
telemt_handshake_timeouts_total 163299
telemt_upstream_connect_attempt_total 24088
telemt_upstream_connect_success_total 24045
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 24050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13084
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 953
telemt_me_reconnect_success_total 549
telemt_me_reader_eof_total 548
telemt_me_idle_close_by_peer_total 548
telemt_me_route_drop_no_conn_total 2357710
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3521990
telemt_me_endpoint_quarantine_total 402
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 485
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
telemt_me_writers_warm_current 28
telemt_desync_total 14646
telemt_desync_full_logged_total 4943
telemt_desync_suppressed_total 9703
telemt_desync_frames_bucket_total{bucket="1_2"} 3111
telemt_desync_frames_bucket_total{bucket="3_10"} 5765
telemt_desync_frames_bucket_total{bucket="gt_10"} 5770
telemt_pool_swap_total 67
telemt_pool_force_close_total 2162
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 337
telemt_me_draining_writers_reap_progress_total 21837
telemt_me_writer_removed_unexpected_total 529
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1901
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20256
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1974
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 188
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19675
telemt_me_writer_teardown_success_total{mode="normal"} 22157
telemt_me_writer_teardown_noop_total 21866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44023
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 70.252512
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44023
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 337
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 499
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 3517662
telemt_user_connections_current{user="hello"} 4439
telemt_user_octets_from_client{user="hello"} 57172639840 (53.25 GB)
telemt_user_octets_to_client{user="hello"} 1187023514420 (1.08 TB)
telemt_user_unique_ips_current{user="hello"} 1733
telemt_user_unique_ips_recent_window{user="hello"} 655
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 63967.0 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3534194
telemt_connections_bad_total 393089
telemt_connections_current 3654
telemt_connections_me_current 3654
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 130636
telemt_upstream_connect_attempt_total 28398
telemt_upstream_connect_success_total 28120
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 28256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13055
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 481
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1187
telemt_me_reconnect_success_total 554
telemt_me_reader_eof_total 521
telemt_me_idle_close_by_peer_total 521
telemt_me_route_drop_no_conn_total 1101366
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2564987
telemt_me_endpoint_quarantine_total 411
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 486
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
telemt_me_writers_warm_current 17
telemt_desync_total 11800
telemt_desync_full_logged_total 4001
telemt_desync_suppressed_total 7799
telemt_desync_frames_bucket_total{bucket="1_2"} 2964
telemt_desync_frames_bucket_total{bucket="3_10"} 4549
telemt_desync_frames_bucket_total{bucket="gt_10"} 4287
telemt_pool_swap_total 69
telemt_pool_force_close_total 1975
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 182
telemt_me_draining_writers_reap_progress_total 20989
telemt_me_writer_removed_unexpected_total 505
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1772
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19729
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1842
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 133
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19014
telemt_me_writer_teardown_success_total{mode="normal"} 21501
telemt_me_writer_teardown_noop_total 20990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42491
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.138813
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42491
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 182
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 468
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 2565233
telemt_user_connections_current{user="hello"} 3654
telemt_user_octets_from_client{user="hello"} 47898952437 (44.61 GB)
telemt_user_octets_to_client{user="hello"} 1199202921619 (1.09 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1488
telemt_user_unique_ips_recent_window{user="hello"} 500
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 63931.0 (17h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3435980
telemt_connections_bad_total 365389
telemt_connections_current 3453
telemt_connections_me_current 3453
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 101554
telemt_upstream_connect_attempt_total 33594
telemt_upstream_connect_success_total 33363
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 33496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14416
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 283
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 847
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1288
telemt_me_reconnect_success_total 627
telemt_me_reader_eof_total 571
telemt_me_idle_close_by_peer_total 571
telemt_me_route_drop_no_conn_total 1056154
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2523192
telemt_me_endpoint_quarantine_total 463
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 477
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 6
telemt_desync_total 11832
telemt_desync_full_logged_total 3940
telemt_desync_suppressed_total 7892
telemt_desync_frames_bucket_total{bucket="1_2"} 2990
telemt_desync_frames_bucket_total{bucket="3_10"} 4449
telemt_desync_frames_bucket_total{bucket="gt_10"} 4393
telemt_pool_swap_total 67
telemt_pool_force_close_total 1908
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 218
telemt_me_draining_writers_reap_progress_total 22356
telemt_me_writer_removed_unexpected_total 544
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1879
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21056
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1736
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 172
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20448
telemt_me_writer_teardown_success_total{mode="normal"} 22935
telemt_me_writer_teardown_noop_total 22361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45296
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.606950
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45296
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 218
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 546
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2527473
telemt_user_connections_current{user="hello"} 3453
telemt_user_octets_from_client{user="hello"} 54872143665 (51.10 GB)
telemt_user_octets_to_client{user="hello"} 1191360760000 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1402
telemt_user_unique_ips_recent_window{user="hello"} 513
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 63970.2 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11769016
telemt_connections_bad_total 779625
telemt_connections_current 5136
telemt_connections_me_current 5136
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 366602
telemt_upstream_connect_attempt_total 114786
telemt_upstream_connect_success_total 104932
telemt_upstream_connect_fail_total 8843
telemt_upstream_connect_attempts_per_request{bucket="1"} 113775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24932
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8843
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 3822
telemt_me_reconnect_success_total 1361
telemt_me_reader_eof_total 948
telemt_me_idle_close_by_peer_total 947
telemt_me_route_drop_no_conn_total 21871025
telemt_me_route_drop_channel_closed_total 73
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9646463
telemt_me_endpoint_quarantine_total 494
telemt_me_single_endpoint_outage_enter_total 77
telemt_me_single_endpoint_outage_exit_total 77
telemt_me_single_endpoint_outage_reconnect_attempt_total 173
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 173
telemt_me_single_endpoint_shadow_rotate_total 502
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_me_writers_warm_current 26
telemt_desync_total 17674
telemt_desync_full_logged_total 5591
telemt_desync_suppressed_total 12083
telemt_desync_frames_bucket_total{bucket="1_2"} 3871
telemt_desync_frames_bucket_total{bucket="3_10"} 7705
telemt_desync_frames_bucket_total{bucket="gt_10"} 6098
telemt_pool_swap_total 64
telemt_pool_force_close_total 2067
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 447
telemt_me_draining_writers_reap_progress_total 20675
telemt_me_writer_removed_unexpected_total 1310
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2759
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19047
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1723
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 344
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18608
telemt_me_writer_teardown_success_total{mode="normal"} 21806
telemt_me_writer_teardown_noop_total 20685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42491
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 163.458909
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42491
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 447
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 945
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 97
telemt_me_writer_removed_unexpected_minus_restored_total 356
telemt_user_connections_total{user="hello"} 9722822
telemt_user_connections_current{user="hello"} 5136
telemt_user_octets_from_client{user="hello"} 71127441329 (66.24 GB)
telemt_user_octets_to_client{user="hello"} 758054881741 (705.99 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 1905
telemt_user_unique_ips_recent_window{user="hello"} 967
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 63937.8 (17h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3459931
telemt_connections_bad_total 386486
telemt_connections_current 4249
telemt_connections_me_current 4249
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 76144
telemt_upstream_connect_attempt_total 27292
telemt_upstream_connect_success_total 26993
telemt_upstream_connect_fail_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 27251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 258
telemt_me_reconnect_attempts_total 2645
telemt_me_reconnect_success_total 960
telemt_me_reader_eof_total 953
telemt_me_idle_close_by_peer_total 953
telemt_me_route_drop_no_conn_total 1414773
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2655808
telemt_me_endpoint_quarantine_total 401
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 479
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
telemt_me_writers_warm_current 6
telemt_desync_total 12578
telemt_desync_full_logged_total 4380
telemt_desync_suppressed_total 8198
telemt_desync_frames_bucket_total{bucket="1_2"} 2433
telemt_desync_frames_bucket_total{bucket="3_10"} 5017
telemt_desync_frames_bucket_total{bucket="gt_10"} 5128
telemt_pool_swap_total 63
telemt_pool_force_close_total 1827
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 177
telemt_me_draining_writers_reap_progress_total 22857
telemt_me_writer_removed_unexpected_total 924
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2242
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21569
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1583
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 244
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21030
telemt_me_writer_teardown_success_total{mode="normal"} 23811
telemt_me_writer_teardown_noop_total 22858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46669
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.128728
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46669
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 177
telemt_me_refill_failed_total 92
telemt_me_writer_restored_same_endpoint_total 821
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 2639792
telemt_user_connections_current{user="hello"} 4249
telemt_user_octets_from_client{user="hello"} 59817505704 (55.71 GB)
telemt_user_octets_to_client{user="hello"} 1127280051210 (1.03 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1711
telemt_user_unique_ips_recent_window{user="hello"} 586
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 773.3 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131444
telemt_connections_bad_total 2755
telemt_connections_current 3198
telemt_connections_me_current 3198
telemt_handshake_timeouts_total 67614
telemt_upstream_connect_attempt_total 288
telemt_upstream_connect_success_total 280
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 136
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 38333
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53972
telemt_me_endpoint_quarantine_total 1
telemt_me_single_endpoint_shadow_rotate_total 7
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
telemt_me_writers_active_current 46
telemt_desync_total 235
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 159
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 172
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 166
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 172
telemt_me_writer_teardown_success_total{mode="normal"} 174
telemt_me_writer_teardown_noop_total 172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 346
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.001111
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 346
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 53975
telemt_user_connections_current{user="hello"} 3198
telemt_user_octets_from_client{user="hello"} 638073564 (608.51 MB)
telemt_user_octets_to_client{user="hello"} 20726829060 (19.30 GB)
telemt_user_unique_ips_current{user="hello"} 1329
telemt_user_unique_ips_recent_window{user="hello"} 617
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 61923.7 (17h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1128161
telemt_connections_bad_total 135794
telemt_connections_current 795
telemt_connections_me_current 795
telemt_handshake_timeouts_total 399595
telemt_upstream_connect_attempt_total 28936
telemt_upstream_connect_success_total 28933
telemt_upstream_connect_attempts_per_request{bucket="1"} 28933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1227
telemt_me_reconnect_success_total 478
telemt_me_reader_eof_total 476
telemt_me_idle_close_by_peer_total 476
telemt_me_route_drop_no_conn_total 240168
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 521691
telemt_me_endpoint_quarantine_total 562
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 521
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
telemt_me_writers_active_current 44
telemt_desync_total 3353
telemt_desync_full_logged_total 1238
telemt_desync_suppressed_total 2115
telemt_desync_frames_bucket_total{bucket="1_2"} 604
telemt_desync_frames_bucket_total{bucket="3_10"} 1203
telemt_desync_frames_bucket_total{bucket="gt_10"} 1546
telemt_pool_swap_total 68
telemt_pool_force_close_total 1553
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 108
telemt_me_draining_writers_reap_progress_total 25934
telemt_me_writer_removed_unexpected_total 449
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1900
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24495
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1550
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24381
telemt_me_writer_teardown_success_total{mode="normal"} 26395
telemt_me_writer_teardown_noop_total 25934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52329
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.542527
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52329
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 108
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 389
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 521437
telemt_user_connections_current{user="hello"} 795
telemt_user_octets_from_client{user="hello"} 10668313571 (9.94 GB)
telemt_user_octets_to_client{user="hello"} 197263812353 (183.72 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 63942.2 (17h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3788258
telemt_connections_bad_total 349377
telemt_connections_current 4755
telemt_connections_me_current 4755
telemt_handshake_timeouts_total 119433
telemt_upstream_connect_attempt_total 25806
telemt_upstream_connect_success_total 25702
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 25774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12881
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 1050
telemt_me_reconnect_success_total 586
telemt_me_reader_eof_total 547
telemt_me_idle_close_by_peer_total 547
telemt_me_route_drop_no_conn_total 1142531
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3005406
telemt_me_endpoint_quarantine_total 471
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 489
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
telemt_me_writers_warm_current 5
telemt_desync_total 11905
telemt_desync_full_logged_total 3933
telemt_desync_suppressed_total 7972
telemt_desync_frames_bucket_total{bucket="1_2"} 2821
telemt_desync_frames_bucket_total{bucket="3_10"} 4446
telemt_desync_frames_bucket_total{bucket="gt_10"} 4638
telemt_pool_swap_total 70
telemt_pool_force_close_total 1820
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 198
telemt_me_draining_writers_reap_progress_total 23170
telemt_me_writer_removed_unexpected_total 537
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1819
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21888
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1784
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21350
telemt_me_writer_teardown_success_total{mode="normal"} 23707
telemt_me_writer_teardown_noop_total 23170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46877
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.278625
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46877
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 198
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 518
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 2997546
telemt_user_connections_current{user="hello"} 4755
telemt_user_octets_from_client{user="hello"} 62398324148 (58.11 GB)
telemt_user_octets_to_client{user="hello"} 1411681739756 (1.28 TB)
telemt_user_unique_ips_current{user="hello"} 1753
telemt_user_unique_ips_recent_window{user="hello"} 612
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 63939.0 (17h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3398093
telemt_connections_bad_total 299098
telemt_connections_current 3874
telemt_connections_me_current 3874
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 98493
telemt_upstream_connect_attempt_total 42026
telemt_upstream_connect_success_total 41748
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 41977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14599
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 593
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_reconnect_attempts_total 3581
telemt_me_reconnect_success_total 760
telemt_me_reader_eof_total 667
telemt_me_idle_close_by_peer_total 667
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 1212846
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2732252
telemt_me_endpoint_quarantine_total 535
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 487
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
telemt_me_writers_warm_current 6
telemt_desync_total 10510
telemt_desync_full_logged_total 3587
telemt_desync_suppressed_total 6923
telemt_desync_frames_bucket_total{bucket="1_2"} 2642
telemt_desync_frames_bucket_total{bucket="3_10"} 3887
telemt_desync_frames_bucket_total{bucket="gt_10"} 3981
telemt_pool_swap_total 69
telemt_pool_force_close_total 1769
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 193
telemt_me_draining_writers_reap_progress_total 22348
telemt_me_writer_removed_unexpected_total 679
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2131
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20927
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1648
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 121
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20579
telemt_me_writer_teardown_success_total{mode="normal"} 23058
telemt_me_writer_teardown_noop_total 22349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45407
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.459621
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45407
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 193
telemt_me_refill_failed_total 160
telemt_me_writer_restored_same_endpoint_total 580
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 2741170
telemt_user_connections_current{user="hello"} 3874
telemt_user_octets_from_client{user="hello"} 49479114501 (46.08 GB)
telemt_user_octets_to_client{user="hello"} 1179918667016 (1.07 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1465
telemt_user_unique_ips_recent_window{user="hello"} 536
```
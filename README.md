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

# Server Metrics 2026-03-21 16:19:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 70995.7 (19h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2538604
telemt_connections_bad_total 151777
telemt_connections_current 1460
telemt_connections_me_current 1460
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 80159
telemt_upstream_connect_attempt_total 29959
telemt_upstream_connect_success_total 29828
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 29916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17386
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1737
telemt_me_reconnect_success_total 681
telemt_me_reader_eof_total 654
telemt_me_idle_close_by_peer_total 654
telemt_me_route_drop_no_conn_total 2144926
telemt_me_route_drop_channel_closed_total 671
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2021482
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 490
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 551
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
telemt_me_writers_active_current 43
telemt_desync_total 8066
telemt_desync_full_logged_total 2788
telemt_desync_suppressed_total 5278
telemt_desync_frames_bucket_total{bucket="1_2"} 1763
telemt_desync_frames_bucket_total{bucket="3_10"} 3066
telemt_desync_frames_bucket_total{bucket="gt_10"} 3237
telemt_pool_swap_total 76
telemt_pool_force_close_total 2302
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 520
telemt_me_draining_writers_reap_progress_total 24072
telemt_me_writer_removed_unexpected_total 632
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2068
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22420
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2181
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 121
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21770
telemt_me_writer_teardown_success_total{mode="normal"} 24488
telemt_me_writer_teardown_noop_total 24079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48567
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 227.184248
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48567
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 520
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 582
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2022822
telemt_user_connections_current{user="hello"} 1460
telemt_user_octets_from_client{user="hello"} 28595904129 (26.63 GB)
telemt_user_octets_to_client{user="hello"} 502209285178 (467.72 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 542
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 2120.6 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82538
telemt_connections_bad_total 3537
telemt_connections_current 1460
telemt_connections_me_current 1460
telemt_handshake_timeouts_total 1784
telemt_upstream_connect_attempt_total 903
telemt_upstream_connect_success_total 902
telemt_upstream_connect_attempts_per_request{bucket="1"} 902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 6
telemt_me_idle_close_by_peer_total 6
telemt_me_route_drop_no_conn_total 50347
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71026
telemt_me_endpoint_quarantine_total 19
telemt_me_single_endpoint_shadow_rotate_total 24
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
telemt_me_writers_active_current 43
telemt_desync_total 234
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_pool_swap_total 2
telemt_pool_force_close_total 27
telemt_me_writer_close_signal_drop_total 18
telemt_me_draining_writers_reap_progress_total 767
telemt_me_writer_removed_unexpected_total 6
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 712
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 740
telemt_me_writer_teardown_success_total{mode="normal"} 773
telemt_me_writer_teardown_noop_total 767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1540
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.060234
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1540
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 18
telemt_me_writer_restored_same_endpoint_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 70593
telemt_user_connections_current{user="hello"} 1460
telemt_user_octets_from_client{user="hello"} 620849952 (592.09 MB)
telemt_user_octets_to_client{user="hello"} 15933490480 (14.84 GB)
telemt_user_unique_ips_current{user="hello"} 511
telemt_user_unique_ips_recent_window{user="hello"} 268
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 70993.1 (19h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5214230
telemt_connections_bad_total 448163
telemt_connections_current 5368
telemt_connections_me_current 5368
telemt_handshake_timeouts_total 177174
telemt_upstream_connect_attempt_total 26135
telemt_upstream_connect_success_total 26079
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 26085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14255
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1173
telemt_me_reconnect_success_total 595
telemt_me_reader_eof_total 599
telemt_me_idle_close_by_peer_total 599
telemt_me_route_drop_no_conn_total 3170199
telemt_me_route_drop_channel_closed_total 47
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4283755
telemt_me_endpoint_quarantine_total 441
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 533
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
telemt_desync_total 17606
telemt_desync_full_logged_total 5907
telemt_desync_suppressed_total 11699
telemt_desync_frames_bucket_total{bucket="1_2"} 3708
telemt_desync_frames_bucket_total{bucket="3_10"} 7005
telemt_desync_frames_bucket_total{bucket="gt_10"} 6893
telemt_pool_swap_total 75
telemt_pool_force_close_total 2463
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 388
telemt_me_draining_writers_reap_progress_total 23730
telemt_me_writer_removed_unexpected_total 579
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2078
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21965
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 34
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2262
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 201
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21267
telemt_me_writer_teardown_success_total{mode="normal"} 24043
telemt_me_writer_teardown_noop_total 23764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47807
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 93.384643
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47807
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 388
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 536
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 4278645
telemt_user_connections_current{user="hello"} 5368
telemt_user_octets_from_client{user="hello"} 67510999672 (62.87 GB)
telemt_user_octets_to_client{user="hello"} 1370281978796 (1.25 TB)
telemt_user_unique_ips_current{user="hello"} 2069
telemt_user_unique_ips_recent_window{user="hello"} 661
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 70994.9 (19h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4180021
telemt_connections_bad_total 435152
telemt_connections_current 4153
telemt_connections_me_current 4153
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 145977
telemt_upstream_connect_attempt_total 30523
telemt_upstream_connect_success_total 30235
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 30376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14227
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 496
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1401
telemt_me_reconnect_success_total 620
telemt_me_reader_eof_total 584
telemt_me_idle_close_by_peer_total 584
telemt_me_route_drop_no_conn_total 1337491
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3085381
telemt_me_endpoint_quarantine_total 448
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 540
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
telemt_desync_total 14720
telemt_desync_full_logged_total 4859
telemt_desync_suppressed_total 9861
telemt_desync_frames_bucket_total{bucket="1_2"} 3657
telemt_desync_frames_bucket_total{bucket="3_10"} 5698
telemt_desync_frames_bucket_total{bucket="gt_10"} 5365
telemt_pool_swap_total 77
telemt_pool_force_close_total 2260
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 232
telemt_me_draining_writers_reap_progress_total 22881
telemt_me_writer_removed_unexpected_total 565
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1974
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21452
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2101
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 159
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20621
telemt_me_writer_teardown_success_total{mode="normal"} 23426
telemt_me_writer_teardown_noop_total 22884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46310
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.834620
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46310
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 232
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 524
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 3084769
telemt_user_connections_current{user="hello"} 4153
telemt_user_octets_from_client{user="hello"} 69625635065 (64.84 GB)
telemt_user_octets_to_client{user="hello"} 1422542959431 (1.29 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1621
telemt_user_unique_ips_recent_window{user="hello"} 543
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 70958.8 (19h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4124360
telemt_connections_bad_total 419997
telemt_connections_current 3548
telemt_connections_me_current 3548
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 124954
telemt_upstream_connect_attempt_total 35768
telemt_upstream_connect_success_total 35524
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 35657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15567
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 295
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 865
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 1460
telemt_me_reconnect_success_total 667
telemt_me_reader_eof_total 609
telemt_me_idle_close_by_peer_total 609
telemt_me_route_drop_no_conn_total 1429263
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3068230
telemt_me_endpoint_quarantine_total 500
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 532
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
telemt_desync_total 14173
telemt_desync_full_logged_total 4670
telemt_desync_suppressed_total 9503
telemt_desync_frames_bucket_total{bucket="1_2"} 3528
telemt_desync_frames_bucket_total{bucket="3_10"} 5330
telemt_desync_frames_bucket_total{bucket="gt_10"} 5315
telemt_pool_swap_total 75
telemt_pool_force_close_total 2177
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 253
telemt_me_draining_writers_reap_progress_total 24303
telemt_me_writer_removed_unexpected_total 579
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2051
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22853
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1993
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 184
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22126
telemt_me_writer_teardown_success_total{mode="normal"} 24904
telemt_me_writer_teardown_noop_total 24309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49213
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.593535
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49213
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 253
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 574
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 3071707
telemt_user_connections_current{user="hello"} 3548
telemt_user_octets_from_client{user="hello"} 73263303209 (68.23 GB)
telemt_user_octets_to_client{user="hello"} 1419523950640 (1.29 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1422
telemt_user_unique_ips_recent_window{user="hello"} 496
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 70997.9 (19h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14214467
telemt_connections_bad_total 917070
telemt_connections_current 5437
telemt_connections_me_current 5437
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 420082
telemt_upstream_connect_attempt_total 116901
telemt_upstream_connect_success_total 106972
telemt_upstream_connect_fail_total 8856
telemt_upstream_connect_attempts_per_request{bucket="1"} 115828
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26074
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8856
telemt_me_keepalive_timeout_total 171
telemt_me_reconnect_attempts_total 3902
telemt_me_reconnect_success_total 1426
telemt_me_reader_eof_total 997
telemt_me_idle_close_by_peer_total 996
telemt_me_route_drop_no_conn_total 28088438
telemt_me_route_drop_channel_closed_total 92
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11726650
telemt_me_endpoint_quarantine_total 538
telemt_me_single_endpoint_outage_enter_total 78
telemt_me_single_endpoint_outage_exit_total 78
telemt_me_single_endpoint_outage_reconnect_attempt_total 174
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 174
telemt_me_single_endpoint_shadow_rotate_total 555
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
telemt_desync_total 20732
telemt_desync_full_logged_total 6416
telemt_desync_suppressed_total 14316
telemt_desync_frames_bucket_total{bucket="1_2"} 4517
telemt_desync_frames_bucket_total{bucket="3_10"} 9086
telemt_desync_frames_bucket_total{bucket="gt_10"} 7129
telemt_pool_swap_total 72
telemt_pool_force_close_total 2361
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 513
telemt_me_draining_writers_reap_progress_total 22575
telemt_me_writer_removed_unexpected_total 1357
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2945
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20765
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1984
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 377
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20214
telemt_me_writer_teardown_success_total{mode="normal"} 23710
telemt_me_writer_teardown_noop_total 22587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46297
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 175.985797
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46297
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 513
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 999
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 348
telemt_user_connections_total{user="hello"} 11801242
telemt_user_connections_current{user="hello"} 5437
telemt_user_octets_from_client{user="hello"} 86307817681 (80.38 GB)
telemt_user_octets_to_client{user="hello"} 829995912505 (772.99 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 2011
telemt_user_unique_ips_recent_window{user="hello"} 1137
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 70965.5 (19h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4119405
telemt_connections_bad_total 444275
telemt_connections_current 4088
telemt_connections_me_current 4088
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 87452
telemt_upstream_connect_attempt_total 29644
telemt_upstream_connect_success_total 29308
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 29597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15336
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_reconnect_attempts_total 3011
telemt_me_reconnect_success_total 1059
telemt_me_reader_eof_total 1053
telemt_me_idle_close_by_peer_total 1053
telemt_me_route_drop_no_conn_total 1751907
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3184279
telemt_me_endpoint_quarantine_total 434
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 528
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
telemt_me_writers_active_current 48
telemt_desync_total 15408
telemt_desync_full_logged_total 5350
telemt_desync_suppressed_total 10058
telemt_desync_frames_bucket_total{bucket="1_2"} 3019
telemt_desync_frames_bucket_total{bucket="3_10"} 6097
telemt_desync_frames_bucket_total{bucket="gt_10"} 6292
telemt_pool_swap_total 70
telemt_pool_force_close_total 2070
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 210
telemt_me_draining_writers_reap_progress_total 24890
telemt_me_writer_removed_unexpected_total 1020
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2499
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23447
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1775
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 295
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22820
telemt_me_writer_teardown_success_total{mode="normal"} 25946
telemt_me_writer_teardown_noop_total 24891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50837
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.543143
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50837
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 210
telemt_me_refill_failed_total 107
telemt_me_writer_restored_same_endpoint_total 915
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 3167422
telemt_user_connections_current{user="hello"} 4088
telemt_user_octets_from_client{user="hello"} 82845562408 (77.16 GB)
telemt_user_octets_to_client{user="hello"} 1303661415698 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1682
telemt_user_unique_ips_recent_window{user="hello"} 575
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 7801.1 (2h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1213095
telemt_connections_bad_total 44375
telemt_connections_current 3396
telemt_connections_me_current 3396
telemt_handshake_timeouts_total 563486
telemt_upstream_connect_attempt_total 2715
telemt_upstream_connect_success_total 2666
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 2709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1448
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_reconnect_attempts_total 380
telemt_me_reconnect_success_total 106
telemt_me_reader_eof_total 97
telemt_me_idle_close_by_peer_total 97
telemt_me_route_drop_no_conn_total 469745
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 556899
telemt_me_endpoint_quarantine_total 32
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 59
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
telemt_me_writers_active_current 41
telemt_desync_total 3019
telemt_desync_full_logged_total 943
telemt_desync_suppressed_total 2076
telemt_desync_frames_bucket_total{bucket="1_2"} 578
telemt_desync_frames_bucket_total{bucket="3_10"} 1102
telemt_desync_frames_bucket_total{bucket="gt_10"} 1339
telemt_pool_swap_total 7
telemt_pool_force_close_total 231
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 20
telemt_me_draining_writers_reap_progress_total 2293
telemt_me_writer_removed_unexpected_total 98
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2173
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 188
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2062
telemt_me_writer_teardown_success_total{mode="normal"} 2391
telemt_me_writer_teardown_noop_total 2293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4684
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.824064
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4684
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 20
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 88
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 556095
telemt_user_connections_current{user="hello"} 3396
telemt_user_octets_from_client{user="hello"} 13733420332 (12.79 GB)
telemt_user_octets_to_client{user="hello"} 207870993388 (193.59 GB)
telemt_user_unique_ips_current{user="hello"} 1352
telemt_user_unique_ips_recent_window{user="hello"} 505
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 68951.2 (19h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1309546
telemt_connections_bad_total 146249
telemt_connections_current 859
telemt_connections_me_current 859
telemt_handshake_timeouts_total 466234
telemt_upstream_connect_attempt_total 31957
telemt_upstream_connect_success_total 31949
telemt_upstream_connect_attempts_per_request{bucket="1"} 31949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18770
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1365
telemt_me_reconnect_success_total 572
telemt_me_reader_eof_total 571
telemt_me_idle_close_by_peer_total 571
telemt_me_route_drop_no_conn_total 287990
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 618472
telemt_me_endpoint_quarantine_total 610
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 576
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 3730
telemt_desync_full_logged_total 1335
telemt_desync_suppressed_total 2395
telemt_desync_frames_bucket_total{bucket="1_2"} 707
telemt_desync_frames_bucket_total{bucket="3_10"} 1332
telemt_desync_frames_bucket_total{bucket="gt_10"} 1691
telemt_pool_swap_total 75
telemt_pool_force_close_total 1772
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 114
telemt_me_draining_writers_reap_progress_total 28627
telemt_me_writer_removed_unexpected_total 540
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2173
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27011
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1742
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26855
telemt_me_writer_teardown_success_total{mode="normal"} 29184
telemt_me_writer_teardown_noop_total 28627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57811
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.681870
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57811
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 114
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 477
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 618041
telemt_user_connections_current{user="hello"} 859
telemt_user_octets_from_client{user="hello"} 12771951415 (11.89 GB)
telemt_user_octets_to_client{user="hello"} 239629988509 (223.17 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 70969.8 (19h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4586357
telemt_connections_bad_total 423788
telemt_connections_current 4631
telemt_connections_me_current 4631
telemt_handshake_timeouts_total 150447
telemt_upstream_connect_attempt_total 27976
telemt_upstream_connect_success_total 27862
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 27941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14050
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_reconnect_attempts_total 1197
telemt_me_reconnect_success_total 626
telemt_me_reader_eof_total 593
telemt_me_idle_close_by_peer_total 593
telemt_me_route_drop_no_conn_total 1409941
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3629098
telemt_me_endpoint_quarantine_total 507
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 542
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
telemt_me_writers_active_current 43
telemt_desync_total 14156
telemt_desync_full_logged_total 4680
telemt_desync_suppressed_total 9476
telemt_desync_frames_bucket_total{bucket="1_2"} 3341
telemt_desync_frames_bucket_total{bucket="3_10"} 5268
telemt_desync_frames_bucket_total{bucket="gt_10"} 5547
telemt_pool_swap_total 78
telemt_pool_force_close_total 2059
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 241
telemt_me_draining_writers_reap_progress_total 25091
telemt_me_writer_removed_unexpected_total 581
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2009
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23665
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2011
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 48
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23032
telemt_me_writer_teardown_success_total{mode="normal"} 25674
telemt_me_writer_teardown_noop_total 25092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50766
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.259071
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50766
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 241
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 555
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 3619649
telemt_user_connections_current{user="hello"} 4631
telemt_user_octets_from_client{user="hello"} 72673364860 (67.68 GB)
telemt_user_octets_to_client{user="hello"} 1696369263008 (1.54 TB)
telemt_user_unique_ips_current{user="hello"} 1712
telemt_user_unique_ips_recent_window{user="hello"} 597
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 70966.6 (19h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4059184
telemt_connections_bad_total 367625
telemt_connections_current 4125
telemt_connections_me_current 4125
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 126089
telemt_upstream_connect_attempt_total 44443
telemt_upstream_connect_success_total 44131
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 44388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15891
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 602
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_reconnect_attempts_total 4040
telemt_me_reconnect_success_total 895
telemt_me_reader_eof_total 774
telemt_me_idle_close_by_peer_total 774
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 1470565
telemt_me_route_drop_channel_closed_total 116
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3234543
telemt_me_endpoint_quarantine_total 588
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 536
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
telemt_me_writers_active_current 43
telemt_desync_total 12645
telemt_desync_full_logged_total 4284
telemt_desync_suppressed_total 8361
telemt_desync_frames_bucket_total{bucket="1_2"} 3160
telemt_desync_frames_bucket_total{bucket="3_10"} 4705
telemt_desync_frames_bucket_total{bucket="gt_10"} 4780
telemt_pool_swap_total 76
telemt_pool_force_close_total 2002
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 223
telemt_me_draining_writers_reap_progress_total 24449
telemt_me_writer_removed_unexpected_total 787
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2407
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22862
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1831
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 171
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22447
telemt_me_writer_teardown_success_total{mode="normal"} 25269
telemt_me_writer_teardown_noop_total 24450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49719
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.396571
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49719
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 223
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 687
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 3242673
telemt_user_connections_current{user="hello"} 4125
telemt_user_octets_from_client{user="hello"} 58678976385 (54.65 GB)
telemt_user_octets_to_client{user="hello"} 1378684142744 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1570
telemt_user_unique_ips_recent_window{user="hello"} 563
```
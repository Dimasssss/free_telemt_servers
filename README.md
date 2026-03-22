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

# Server Metrics 2026-03-22 15:59:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 67956.9 (18h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2385426
telemt_connections_bad_total 128129
telemt_connections_current 1718
telemt_connections_me_current 1718
telemt_handshake_timeouts_total 86593
telemt_upstream_connect_attempt_total 25157
telemt_upstream_connect_success_total 25156
telemt_upstream_connect_attempts_per_request{bucket="1"} 25156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16326
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1022
telemt_me_reconnect_success_total 430
telemt_me_reader_eof_total 432
telemt_me_idle_close_by_peer_total 432
telemt_me_route_drop_no_conn_total 1914169
telemt_me_route_drop_channel_closed_total 775
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2028204
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 462
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 533
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
telemt_desync_total 9959
telemt_desync_full_logged_total 3088
telemt_desync_suppressed_total 6871
telemt_desync_frames_bucket_total{bucket="1_2"} 2663
telemt_desync_frames_bucket_total{bucket="3_10"} 3736
telemt_desync_frames_bucket_total{bucket="gt_10"} 3560
telemt_pool_swap_total 75
telemt_pool_force_close_total 2318
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 435
telemt_me_draining_writers_reap_progress_total 22988
telemt_me_writer_removed_unexpected_total 419
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1671
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21522
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2271
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20670
telemt_me_writer_teardown_success_total{mode="normal"} 23193
telemt_me_writer_teardown_noop_total 22994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46187
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 207.242321
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46187
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 435
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 380
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2024854
telemt_user_connections_current{user="hello"} 1718
telemt_user_octets_from_client{user="hello"} 30847307392 (28.73 GB)
telemt_user_octets_to_client{user="hello"} 542880614884 (505.60 GB)
telemt_user_unique_ips_current{user="hello"} 659
telemt_user_unique_ips_recent_window{user="hello"} 270
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 81324.5 (22h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3564471
telemt_connections_bad_total 325602
telemt_connections_current 740
telemt_connections_me_current 740
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 86372
telemt_upstream_connect_attempt_total 51510
telemt_upstream_connect_success_total 50882
telemt_upstream_connect_fail_total 555
telemt_upstream_connect_attempts_per_request{bucket="1"} 51437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21032
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 555
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6049
telemt_me_reconnect_success_total 2187
telemt_me_reader_eof_total 2130
telemt_me_idle_close_by_peer_total 2130
telemt_me_route_drop_no_conn_total 3521476
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2823551
telemt_me_endpoint_quarantine_total 659
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 627
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 10942
telemt_desync_full_logged_total 6095
telemt_desync_suppressed_total 4847
telemt_desync_frames_bucket_total{bucket="1_2"} 2559
telemt_desync_frames_bucket_total{bucket="3_10"} 4306
telemt_desync_frames_bucket_total{bucket="gt_10"} 4077
telemt_pool_swap_total 76
telemt_pool_force_close_total 2291
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 195
telemt_me_draining_writers_reap_progress_total 32495
telemt_me_writer_removed_unexpected_total 2085
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3942
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30644
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1935
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 356
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30204
telemt_me_writer_teardown_success_total{mode="normal"} 34586
telemt_me_writer_teardown_noop_total 32495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67081
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.172118
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67081
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 195
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 1897
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 2834848
telemt_user_connections_current{user="hello"} 740
telemt_user_octets_from_client{user="hello"} 34858329439 (32.46 GB)
telemt_user_octets_to_client{user="hello"} 624067703582 (581.21 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 465
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 156183.9 (43h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15231768
telemt_connections_bad_total 1410535
telemt_connections_current 2257
telemt_connections_me_current 2257
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 370488
telemt_upstream_connect_attempt_total 70718
telemt_upstream_connect_success_total 70623
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 70640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33359
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1672
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2610
telemt_me_reconnect_success_total 1341
telemt_me_reader_eof_total 1280
telemt_me_idle_close_by_peer_total 1278
telemt_me_route_drop_no_conn_total 13780702
telemt_me_route_drop_channel_closed_total 138
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12178117
telemt_me_endpoint_quarantine_total 987
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1163
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 49499
telemt_desync_full_logged_total 15523
telemt_desync_suppressed_total 33976
telemt_desync_frames_bucket_total{bucket="1_2"} 11101
telemt_desync_frames_bucket_total{bucket="3_10"} 19362
telemt_desync_frames_bucket_total{bucket="gt_10"} 19036
telemt_pool_swap_total 168
telemt_pool_force_close_total 5735
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 932
telemt_me_draining_writers_reap_progress_total 51398
telemt_me_writer_removed_unexpected_total 1235
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4469
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47455
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5275
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45663
telemt_me_writer_teardown_success_total{mode="normal"} 51924
telemt_me_writer_teardown_noop_total 51448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103372
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 294.768481
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103372
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 932
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 1151
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 12179394
telemt_user_connections_current{user="hello"} 2257
telemt_user_octets_from_client{user="hello"} 171405171177 (159.63 GB)
telemt_user_octets_to_client{user="hello"} 3138346802363 (2.85 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 895
telemt_user_unique_ips_recent_window{user="hello"} 264
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 156185.9 (43h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10987554
telemt_connections_bad_total 1063664
telemt_connections_current 1608
telemt_connections_me_current 1608
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 325227
telemt_upstream_connect_attempt_total 82918
telemt_upstream_connect_success_total 81764
telemt_upstream_connect_fail_total 830
telemt_upstream_connect_attempts_per_request{bucket="1"} 82594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33249
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3692
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 830
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3909
telemt_me_reconnect_success_total 1590
telemt_me_reader_eof_total 1458
telemt_me_idle_close_by_peer_total 1458
telemt_me_route_drop_no_conn_total 4343689
telemt_me_route_drop_channel_closed_total 478
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8197552
telemt_me_endpoint_quarantine_total 983
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1182
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 36410
telemt_desync_full_logged_total 12238
telemt_desync_suppressed_total 24172
telemt_desync_frames_bucket_total{bucket="1_2"} 8919
telemt_desync_frames_bucket_total{bucket="3_10"} 14030
telemt_desync_frames_bucket_total{bucket="gt_10"} 13461
telemt_pool_swap_total 166
telemt_pool_force_close_total 5158
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 665
telemt_me_draining_writers_reap_progress_total 49684
telemt_me_writer_removed_unexpected_total 1489
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4589
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46442
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4682
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 476
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44526
telemt_me_writer_teardown_success_total{mode="normal"} 51031
telemt_me_writer_teardown_noop_total 49702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100733
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.224477
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100733
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 665
telemt_me_refill_failed_total 125
telemt_me_writer_restored_same_endpoint_total 1352
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 8136314
telemt_user_connections_current{user="hello"} 1608
telemt_user_octets_from_client{user="hello"} 203866036009 (189.87 GB)
telemt_user_octets_to_client{user="hello"} 3667952764874 (3.34 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 588
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 156148.4 (43h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10400939
telemt_connections_bad_total 894543
telemt_connections_current 1249
telemt_connections_me_current 1249
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 331965
telemt_upstream_connect_attempt_total 68115
telemt_upstream_connect_success_total 67183
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 67365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31764
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2062
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4643
telemt_me_reconnect_success_total 1868
telemt_me_reader_eof_total 1626
telemt_me_idle_close_by_peer_total 1625
telemt_me_route_drop_no_conn_total 5114612
telemt_me_route_drop_channel_closed_total 356
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7852404
telemt_me_endpoint_quarantine_total 1067
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 1149
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 35973
telemt_desync_full_logged_total 11918
telemt_desync_suppressed_total 24055
telemt_desync_frames_bucket_total{bucket="1_2"} 9112
telemt_desync_frames_bucket_total{bucket="3_10"} 13746
telemt_desync_frames_bucket_total{bucket="gt_10"} 13115
telemt_pool_swap_total 163
telemt_pool_force_close_total 5106
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 683
telemt_me_draining_writers_reap_progress_total 50103
telemt_me_writer_removed_unexpected_total 1766
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5012
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46769
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4567
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 539
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44997
telemt_me_writer_teardown_success_total{mode="normal"} 51781
telemt_me_writer_teardown_noop_total 50174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101955
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3170.180997
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101955
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 683
telemt_me_refill_failed_total 147
telemt_me_writer_restored_same_endpoint_total 1619
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 7845385
telemt_user_connections_current{user="hello"} 1249
telemt_user_octets_from_client{user="hello"} 181125247045 (168.69 GB)
telemt_user_octets_to_client{user="hello"} 3260183938537 (2.97 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 508
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 26428.8 (7h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10053884
telemt_connections_bad_total 614800
telemt_connections_current 2116
telemt_connections_me_current 2116
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 178908
telemt_upstream_connect_attempt_total 35165
telemt_upstream_connect_success_total 33396
telemt_upstream_connect_fail_total 1250
telemt_upstream_connect_attempts_per_request{bucket="1"} 34646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8984
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5294
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1250
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5869
telemt_me_reconnect_success_total 693
telemt_me_reader_eof_total 435
telemt_me_idle_close_by_peer_total 435
telemt_me_route_drop_no_conn_total 24869778
telemt_me_route_drop_channel_closed_total 44
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8373636
telemt_me_endpoint_quarantine_total 168
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 210
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
telemt_desync_total 12883
telemt_desync_full_logged_total 3298
telemt_desync_suppressed_total 9585
telemt_desync_frames_bucket_total{bucket="1_2"} 2246
telemt_desync_frames_bucket_total{bucket="3_10"} 5244
telemt_desync_frames_bucket_total{bucket="gt_10"} 5393
telemt_pool_swap_total 25
telemt_pool_force_close_total 1013
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 360
telemt_me_draining_writers_reap_progress_total 7172
telemt_me_writer_removed_unexpected_total 596
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1223
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6509
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 735
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 278
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6159
telemt_me_writer_teardown_success_total{mode="normal"} 7732
telemt_me_writer_teardown_noop_total 7177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 14538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 14789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 14882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 14909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 14909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 14909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 14909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 14909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 14909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 14909
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 35.572333
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 14909
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 360
telemt_me_refill_failed_total 293
telemt_me_writer_restored_same_endpoint_total 469
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 8391851
telemt_user_connections_current{user="hello"} 2116
telemt_user_octets_from_client{user="hello"} 57606559430 (53.65 GB)
telemt_user_octets_to_client{user="hello"} 279789505408 (260.57 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 770
telemt_user_unique_ips_recent_window{user="hello"} 306
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 156155.2 (43h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10172255
telemt_connections_bad_total 848270
telemt_connections_current 1900
telemt_connections_me_current 1900
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 225327
telemt_upstream_connect_attempt_total 96859
telemt_upstream_connect_success_total 95874
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 96712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34962
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1301
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71739
telemt_me_reconnect_success_total 2594
telemt_me_reader_eof_total 2299
telemt_me_idle_close_by_peer_total 2298
telemt_me_route_drop_no_conn_total 5041991
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8023824
telemt_me_endpoint_quarantine_total 1053
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1166
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
telemt_me_writers_active_current 46
telemt_desync_total 41749
telemt_desync_full_logged_total 14242
telemt_desync_suppressed_total 27507
telemt_desync_frames_bucket_total{bucket="1_2"} 8495
telemt_desync_frames_bucket_total{bucket="3_10"} 16155
telemt_desync_frames_bucket_total{bucket="gt_10"} 17099
telemt_pool_swap_total 159
telemt_pool_force_close_total 4734
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 596
telemt_me_draining_writers_reap_progress_total 53184
telemt_me_writer_removed_unexpected_total 2343
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5696
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49851
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4050
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 684
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48450
telemt_me_writer_teardown_success_total{mode="normal"} 55547
telemt_me_writer_teardown_noop_total 53185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108732
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.406705
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108732
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 596
telemt_me_refill_failed_total 4264
telemt_me_writer_restored_same_endpoint_total 2181
telemt_me_writer_restored_fallback_total 44
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7360
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 8027828
telemt_user_connections_current{user="hello"} 1900
telemt_user_octets_from_client{user="hello"} 181634023461 (169.16 GB)
telemt_user_octets_to_client{user="hello"} 3021947374928 (2.75 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 715
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 92991.0 (25h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10579817
telemt_connections_bad_total 392058
telemt_connections_current 1308
telemt_connections_me_current 1308
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4460745
telemt_upstream_connect_attempt_total 44903
telemt_upstream_connect_success_total 44575
telemt_upstream_connect_fail_total 319
telemt_upstream_connect_attempts_per_request{bucket="1"} 44894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 319
telemt_me_reconnect_attempts_total 48037
telemt_me_reconnect_success_total 1500
telemt_me_reader_eof_total 1163
telemt_me_idle_close_by_peer_total 1162
telemt_me_route_drop_no_conn_total 3899215
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5065698
telemt_me_endpoint_quarantine_total 609
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 701
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 27695
telemt_desync_full_logged_total 9358
telemt_desync_suppressed_total 18337
telemt_desync_frames_bucket_total{bucket="1_2"} 5574
telemt_desync_frames_bucket_total{bucket="3_10"} 10930
telemt_desync_frames_bucket_total{bucket="gt_10"} 11191
telemt_pool_swap_total 98
telemt_pool_force_close_total 3029
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 311
telemt_me_draining_writers_reap_progress_total 31985
telemt_me_writer_removed_unexpected_total 1226
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2886
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30355
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2610
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28956
telemt_me_writer_teardown_success_total{mode="normal"} 33241
telemt_me_writer_teardown_noop_total 31992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65233
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.762403
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65233
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 311
telemt_me_refill_failed_total 2705
telemt_me_writer_restored_same_endpoint_total 1334
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5059308
telemt_user_connections_current{user="hello"} 1308
telemt_user_octets_from_client{user="hello"} 109102773464 (101.61 GB)
telemt_user_octets_to_client{user="hello"} 1907714654898 (1.74 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 511
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 73961.9 (20h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 974237
telemt_connections_bad_total 13998
telemt_connections_current 1042
telemt_connections_me_current 1042
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 18758
telemt_upstream_connect_attempt_total 36535
telemt_upstream_connect_success_total 36443
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 36519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 510
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_reconnect_attempts_total 1643
telemt_me_reconnect_success_total 694
telemt_me_reader_eof_total 670
telemt_me_idle_close_by_peer_total 670
telemt_me_route_drop_no_conn_total 334278
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 863795
telemt_me_endpoint_quarantine_total 639
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 612
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
telemt_me_writers_active_current 43
telemt_desync_total 4814
telemt_desync_full_logged_total 1472
telemt_desync_suppressed_total 3342
telemt_desync_frames_bucket_total{bucket="1_2"} 1124
telemt_desync_frames_bucket_total{bucket="3_10"} 1919
telemt_desync_frames_bucket_total{bucket="gt_10"} 1771
telemt_pool_swap_total 79
telemt_pool_force_close_total 1968
telemt_me_writer_close_signal_drop_total 115
telemt_me_draining_writers_reap_progress_total 30198
telemt_me_writer_removed_unexpected_total 647
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2331
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28539
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1888
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 80
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28230
telemt_me_writer_teardown_success_total{mode="normal"} 30870
telemt_me_writer_teardown_noop_total 30201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61071
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.533202
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61071
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 115
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 592
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 864824
telemt_user_connections_current{user="hello"} 1042
telemt_user_octets_from_client{user="hello"} 15645386409 (14.57 GB)
telemt_user_octets_to_client{user="hello"} 387271771491 (360.67 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 422
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 156160.1 (43h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12444291
telemt_connections_bad_total 1443841
telemt_connections_current 1888
telemt_connections_me_current 1888
telemt_handshake_timeouts_total 341817
telemt_upstream_connect_attempt_total 58591
telemt_upstream_connect_success_total 58364
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 58541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29492
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_reconnect_attempts_total 2268
telemt_me_reconnect_success_total 1212
telemt_me_reader_eof_total 1176
telemt_me_idle_close_by_peer_total 1176
telemt_me_route_drop_no_conn_total 4150786
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9406100
telemt_me_endpoint_quarantine_total 1055
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1167
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 38563
telemt_desync_full_logged_total 12593
telemt_desync_suppressed_total 25970
telemt_desync_frames_bucket_total{bucket="1_2"} 9179
telemt_desync_frames_bucket_total{bucket="3_10"} 14281
telemt_desync_frames_bucket_total{bucket="gt_10"} 15103
telemt_pool_swap_total 173
telemt_pool_force_close_total 4780
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 617
telemt_me_draining_writers_reap_progress_total 52791
telemt_me_writer_removed_unexpected_total 1130
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4322
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49631
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4607
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48011
telemt_me_writer_teardown_success_total{mode="normal"} 53953
telemt_me_writer_teardown_noop_total 52793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106746
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.999983
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106746
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 617
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 1061
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 9375426
telemt_user_connections_current{user="hello"} 1888
telemt_user_octets_from_client{user="hello"} 183027194924 (170.46 GB)
telemt_user_octets_to_client{user="hello"} 4142149160660 (3.77 TB)
telemt_user_unique_ips_current{user="hello"} 658
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 156156.5 (43h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10788709
telemt_connections_bad_total 1205545
telemt_connections_current 1518
telemt_connections_me_current 1518
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 278352
telemt_upstream_connect_attempt_total 84351
telemt_upstream_connect_success_total 83719
telemt_upstream_connect_fail_total 547
telemt_upstream_connect_attempts_per_request{bucket="1"} 84266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34720
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2028
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 547
telemt_me_reconnect_attempts_total 8877
telemt_me_reconnect_success_total 2040
telemt_me_reader_eof_total 1905
telemt_me_idle_close_by_peer_total 1905
telemt_me_seq_mismatch_total 74
telemt_me_route_drop_no_conn_total 5400207
telemt_me_route_drop_channel_closed_total 347
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8339107
telemt_me_endpoint_quarantine_total 1183
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1170
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_desync_total 38072
telemt_desync_full_logged_total 12304
telemt_desync_suppressed_total 25768
telemt_desync_frames_bucket_total{bucket="1_2"} 9465
telemt_desync_frames_bucket_total{bucket="3_10"} 14193
telemt_desync_frames_bucket_total{bucket="gt_10"} 14414
telemt_pool_swap_total 165
telemt_pool_force_close_total 4628
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 603
telemt_me_draining_writers_reap_progress_total 52200
telemt_me_writer_removed_unexpected_total 1931
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5420
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48779
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4189
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47572
telemt_me_writer_teardown_success_total{mode="normal"} 54199
telemt_me_writer_teardown_noop_total 52205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106404
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.477724
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106404
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 603
telemt_me_refill_failed_total 351
telemt_me_writer_restored_same_endpoint_total 1659
telemt_me_writer_restored_fallback_total 99
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 8345126
telemt_user_connections_current{user="hello"} 1518
telemt_user_octets_from_client{user="hello"} 146947124993 (136.86 GB)
telemt_user_octets_to_client{user="hello"} 3184075994807 (2.90 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 566
telemt_user_unique_ips_recent_window{user="hello"} 174
```
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

# Server Metrics 2026-03-21 14:52:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 65795.5 (18h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2293093
telemt_connections_bad_total 113442
telemt_connections_current 1539
telemt_connections_me_current 1539
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 75945
telemt_upstream_connect_attempt_total 28247
telemt_upstream_connect_success_total 28122
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 28204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16293
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1638
telemt_me_reconnect_success_total 650
telemt_me_reader_eof_total 622
telemt_me_idle_close_by_peer_total 622
telemt_me_route_drop_no_conn_total 1956875
telemt_me_route_drop_channel_closed_total 609
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1832515
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 462
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 512
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 40
telemt_desync_total 7165
telemt_desync_full_logged_total 2466
telemt_desync_suppressed_total 4699
telemt_desync_frames_bucket_total{bucket="1_2"} 1585
telemt_desync_frames_bucket_total{bucket="3_10"} 2728
telemt_desync_frames_bucket_total{bucket="gt_10"} 2852
telemt_pool_swap_total 70
telemt_pool_force_close_total 2123
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 476
telemt_me_draining_writers_reap_progress_total 22487
telemt_me_writer_removed_unexpected_total 602
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1923
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20953
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2010
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 113
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20364
telemt_me_writer_teardown_success_total{mode="normal"} 22876
telemt_me_writer_teardown_noop_total 22493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45369
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 209.966353
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45369
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 476
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 558
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1834162
telemt_user_connections_current{user="hello"} 1539
telemt_user_octets_from_client{user="hello"} 26084990229 (24.29 GB)
telemt_user_octets_to_client{user="hello"} 454243843710 (423.05 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 583
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 5348.8 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 384010
telemt_connections_bad_total 13202
telemt_connections_current 1114
telemt_connections_me_current 1114
telemt_handshake_timeouts_total 13256
telemt_upstream_connect_attempt_total 2027
telemt_upstream_connect_success_total 2014
telemt_upstream_connect_attempts_per_request{bucket="1"} 2014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1001
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 133
telemt_me_reconnect_success_total 47
telemt_me_reader_eof_total 39
telemt_me_idle_close_by_peer_total 39
telemt_me_route_drop_no_conn_total 249871
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 340323
telemt_me_endpoint_quarantine_total 36
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1410
telemt_desync_full_logged_total 601
telemt_desync_suppressed_total 809
telemt_desync_frames_bucket_total{bucket="1_2"} 293
telemt_desync_frames_bucket_total{bucket="3_10"} 547
telemt_desync_frames_bucket_total{bucket="gt_10"} 570
telemt_pool_swap_total 5
telemt_pool_force_close_total 142
telemt_me_writer_close_signal_drop_total 25
telemt_me_draining_writers_reap_progress_total 1520
telemt_me_writer_removed_unexpected_total 36
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 117
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1442
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 137
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1378
telemt_me_writer_teardown_success_total{mode="normal"} 1559
telemt_me_writer_teardown_noop_total 1520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3079
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.765222
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3079
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 25
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 333091
telemt_user_connections_current{user="hello"} 1114
telemt_user_octets_from_client{user="hello"} 5672166323 (5.28 GB)
telemt_user_octets_to_client{user="hello"} 87160764563 (81.17 GB)
telemt_user_msgs_from_client{user="hello"} 423
telemt_user_msgs_to_client{user="hello"} 734
telemt_user_unique_ips_current{user="hello"} 749
telemt_user_unique_ips_recent_window{user="hello"} 407
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 65793.4 (18h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4528949
telemt_connections_bad_total 409085
telemt_connections_current 5146
telemt_connections_me_current 5146
telemt_handshake_timeouts_total 167521
telemt_upstream_connect_attempt_total 24567
telemt_upstream_connect_success_total 24516
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 24521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13339
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1076
telemt_me_reconnect_success_total 567
telemt_me_reader_eof_total 567
telemt_me_idle_close_by_peer_total 567
telemt_me_route_drop_no_conn_total 2493171
telemt_me_route_drop_channel_closed_total 43
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3695631
telemt_me_endpoint_quarantine_total 419
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 496
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
telemt_me_writers_active_current 40
telemt_me_writers_warm_current 36
telemt_desync_total 15225
telemt_desync_full_logged_total 5137
telemt_desync_suppressed_total 10088
telemt_desync_frames_bucket_total{bucket="1_2"} 3253
telemt_desync_frames_bucket_total{bucket="3_10"} 6000
telemt_desync_frames_bucket_total{bucket="gt_10"} 5972
telemt_pool_swap_total 69
telemt_pool_force_close_total 2235
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 349
telemt_me_draining_writers_reap_progress_total 22251
telemt_me_writer_removed_unexpected_total 548
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1946
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20635
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2042
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 193
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20016
telemt_me_writer_teardown_success_total{mode="normal"} 22581
telemt_me_writer_teardown_noop_total 22282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44863
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 73.360079
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44863
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 349
telemt_me_refill_failed_total 26
telemt_me_writer_restored_same_endpoint_total 509
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 3691095
telemt_user_connections_current{user="hello"} 5146
telemt_user_octets_from_client{user="hello"} 60140861616 (56.01 GB)
telemt_user_octets_to_client{user="hello"} 1233511864988 (1.12 TB)
telemt_user_unique_ips_current{user="hello"} 2083
telemt_user_unique_ips_recent_window{user="hello"} 636
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 65794.6 (18h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3696276
telemt_connections_bad_total 406588
telemt_connections_current 3865
telemt_connections_me_current 3865
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 135070
telemt_upstream_connect_attempt_total 28961
telemt_upstream_connect_success_total 28682
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 28819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13365
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 483
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1200
telemt_me_reconnect_success_total 565
telemt_me_reader_eof_total 533
telemt_me_idle_close_by_peer_total 533
telemt_me_route_drop_no_conn_total 1151272
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2692179
telemt_me_endpoint_quarantine_total 423
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 499
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
telemt_me_writers_warm_current 34
telemt_desync_total 12489
telemt_desync_full_logged_total 4206
telemt_desync_suppressed_total 8283
telemt_desync_frames_bucket_total{bucket="1_2"} 3131
telemt_desync_frames_bucket_total{bucket="3_10"} 4817
telemt_desync_frames_bucket_total{bucket="gt_10"} 4541
telemt_pool_swap_total 71
telemt_pool_force_close_total 2042
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 194
telemt_me_draining_writers_reap_progress_total 21460
telemt_me_writer_removed_unexpected_total 517
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1811
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20168
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1907
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 135
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19418
telemt_me_writer_teardown_success_total{mode="normal"} 21979
telemt_me_writer_teardown_noop_total 21461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43440
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.250240
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43440
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 194
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 478
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 2692238
telemt_user_connections_current{user="hello"} 3865
telemt_user_octets_from_client{user="hello"} 50624754317 (47.15 GB)
telemt_user_octets_to_client{user="hello"} 1257253236999 (1.14 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1495
telemt_user_unique_ips_recent_window{user="hello"} 498
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 65758.5 (18h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3602824
telemt_connections_bad_total 385055
telemt_connections_current 3778
telemt_connections_me_current 3778
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 107845
telemt_upstream_connect_attempt_total 34182
telemt_upstream_connect_success_total 33949
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 34082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14728
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 849
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1308
telemt_me_reconnect_success_total 636
telemt_me_reader_eof_total 579
telemt_me_idle_close_by_peer_total 579
telemt_me_route_drop_no_conn_total 1114801
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2651218
telemt_me_endpoint_quarantine_total 472
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 491
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
telemt_me_writers_warm_current 22
telemt_desync_total 12350
telemt_desync_full_logged_total 4134
telemt_desync_suppressed_total 8216
telemt_desync_frames_bucket_total{bucket="1_2"} 3098
telemt_desync_frames_bucket_total{bucket="3_10"} 4642
telemt_desync_frames_bucket_total{bucket="gt_10"} 4610
telemt_pool_swap_total 69
telemt_pool_force_close_total 1972
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 221
telemt_me_draining_writers_reap_progress_total 22870
telemt_me_writer_removed_unexpected_total 551
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1926
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21531
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1796
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 176
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20898
telemt_me_writer_teardown_success_total{mode="normal"} 23457
telemt_me_writer_teardown_noop_total 22875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46332
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.785042
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46332
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 221
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 553
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2655318
telemt_user_connections_current{user="hello"} 3778
telemt_user_octets_from_client{user="hello"} 57397425025 (53.46 GB)
telemt_user_octets_to_client{user="hello"} 1247212980436 (1.13 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1469
telemt_user_unique_ips_recent_window{user="hello"} 547
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 65797.7 (18h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12362253
telemt_connections_bad_total 813540
telemt_connections_current 5641
telemt_connections_me_current 5641
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 382425
telemt_upstream_connect_attempt_total 115376
telemt_upstream_connect_success_total 105505
telemt_upstream_connect_fail_total 8847
telemt_upstream_connect_attempts_per_request{bucket="1"} 114352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25269
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8847
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 3836
telemt_me_reconnect_success_total 1374
telemt_me_reader_eof_total 961
telemt_me_idle_close_by_peer_total 960
telemt_me_route_drop_no_conn_total 23351087
telemt_me_route_drop_channel_closed_total 77
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10140487
telemt_me_endpoint_quarantine_total 507
telemt_me_single_endpoint_outage_enter_total 77
telemt_me_single_endpoint_outage_exit_total 77
telemt_me_single_endpoint_outage_reconnect_attempt_total 173
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 173
telemt_me_single_endpoint_shadow_rotate_total 513
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
telemt_me_writers_warm_current 37
telemt_desync_total 18149
telemt_desync_full_logged_total 5738
telemt_desync_suppressed_total 12411
telemt_desync_frames_bucket_total{bucket="1_2"} 3972
telemt_desync_frames_bucket_total{bucket="3_10"} 7942
telemt_desync_frames_bucket_total{bucket="gt_10"} 6235
telemt_pool_swap_total 66
telemt_pool_force_close_total 2145
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 461
telemt_me_draining_writers_reap_progress_total 21196
telemt_me_writer_removed_unexpected_total 1322
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2805
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19510
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1796
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 349
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19051
telemt_me_writer_teardown_success_total{mode="normal"} 22315
telemt_me_writer_teardown_noop_total 21206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43521
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 167.144277
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43521
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 461
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 957
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 97
telemt_me_writer_removed_unexpected_minus_restored_total 356
telemt_user_connections_total{user="hello"} 10216625
telemt_user_connections_current{user="hello"} 5641
telemt_user_octets_from_client{user="hello"} 74112396689 (69.02 GB)
telemt_user_octets_to_client{user="hello"} 777759727893 (724.35 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 2000
telemt_user_unique_ips_recent_window{user="hello"} 1134
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 65765.3 (18h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3631422
telemt_connections_bad_total 410042
telemt_connections_current 3881
telemt_connections_me_current 3881
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 79937
telemt_upstream_connect_attempt_total 27860
telemt_upstream_connect_success_total 27552
telemt_upstream_connect_fail_total 264
telemt_upstream_connect_attempts_per_request{bucket="1"} 27816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14322
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 264
telemt_me_reconnect_attempts_total 2669
telemt_me_reconnect_success_total 966
telemt_me_reader_eof_total 959
telemt_me_idle_close_by_peer_total 959
telemt_me_route_drop_no_conn_total 1511633
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2787781
telemt_me_endpoint_quarantine_total 409
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 492
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 18
telemt_desync_total 13321
telemt_desync_full_logged_total 4634
telemt_desync_suppressed_total 8687
telemt_desync_frames_bucket_total{bucket="1_2"} 2568
telemt_desync_frames_bucket_total{bucket="3_10"} 5289
telemt_desync_frames_bucket_total{bucket="gt_10"} 5464
telemt_pool_swap_total 65
telemt_pool_force_close_total 1890
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 187
telemt_me_draining_writers_reap_progress_total 23346
telemt_me_writer_removed_unexpected_total 931
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2288
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22019
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1637
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 253
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21456
telemt_me_writer_teardown_success_total{mode="normal"} 24307
telemt_me_writer_teardown_noop_total 23347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47654
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.254761
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47654
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 187
telemt_me_refill_failed_total 93
telemt_me_writer_restored_same_endpoint_total 827
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 2771546
telemt_user_connections_current{user="hello"} 3881
telemt_user_octets_from_client{user="hello"} 70760893096 (65.90 GB)
telemt_user_octets_to_client{user="hello"} 1168896445662 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1600
telemt_user_unique_ips_recent_window{user="hello"} 504
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 2601.0 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 423590
telemt_connections_bad_total 9393
telemt_connections_current 3739
telemt_connections_me_current 3739
telemt_handshake_timeouts_total 219250
telemt_upstream_connect_attempt_total 1054
telemt_upstream_connect_success_total 1027
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 1048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 557
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 98
telemt_me_reconnect_success_total 53
telemt_me_reader_eof_total 52
telemt_me_idle_close_by_peer_total 52
telemt_me_route_drop_no_conn_total 163554
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182717
telemt_me_endpoint_quarantine_total 9
telemt_me_single_endpoint_shadow_rotate_total 19
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
telemt_desync_total 788
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 518
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 317
telemt_desync_frames_bucket_total{bucket="gt_10"} 335
telemt_pool_swap_total 1
telemt_pool_force_close_total 54
telemt_me_writer_close_signal_drop_total 5
telemt_me_draining_writers_reap_progress_total 825
telemt_me_writer_removed_unexpected_total 53
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 93
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 785
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 771
telemt_me_writer_teardown_success_total{mode="normal"} 878
telemt_me_writer_teardown_noop_total 825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1703
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.241494
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1703
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 5
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 182530
telemt_user_connections_current{user="hello"} 3739
telemt_user_octets_from_client{user="hello"} 4220511084 (3.93 GB)
telemt_user_octets_to_client{user="hello"} 69518074756 (64.74 GB)
telemt_user_unique_ips_current{user="hello"} 1495
telemt_user_unique_ips_recent_window{user="hello"} 555
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 63751.2 (17h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1163296
telemt_connections_bad_total 136612
telemt_connections_current 780
telemt_connections_me_current 780
telemt_handshake_timeouts_total 409691
telemt_upstream_connect_attempt_total 29692
telemt_upstream_connect_success_total 29687
telemt_upstream_connect_attempts_per_request{bucket="1"} 29687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1252
telemt_me_reconnect_success_total 485
telemt_me_reader_eof_total 484
telemt_me_idle_close_by_peer_total 484
telemt_me_route_drop_no_conn_total 251281
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 544986
telemt_me_endpoint_quarantine_total 575
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 535
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
telemt_desync_total 3476
telemt_desync_full_logged_total 1277
telemt_desync_suppressed_total 2199
telemt_desync_frames_bucket_total{bucket="1_2"} 634
telemt_desync_frames_bucket_total{bucket="3_10"} 1240
telemt_desync_frames_bucket_total{bucket="gt_10"} 1602
telemt_pool_swap_total 70
telemt_pool_force_close_total 1603
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 109
telemt_me_draining_writers_reap_progress_total 26624
telemt_me_writer_removed_unexpected_total 457
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1951
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25142
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1600
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25021
telemt_me_writer_teardown_success_total{mode="normal"} 27093
telemt_me_writer_teardown_noop_total 26624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53717
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.934366
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53717
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 109
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 396
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 544679
telemt_user_connections_current{user="hello"} 780
telemt_user_octets_from_client{user="hello"} 11261384723 (10.49 GB)
telemt_user_octets_to_client{user="hello"} 207065477453 (192.84 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 65769.7 (18h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3979717
telemt_connections_bad_total 365111
telemt_connections_current 4292
telemt_connections_me_current 4292
telemt_handshake_timeouts_total 126170
telemt_upstream_connect_attempt_total 26448
telemt_upstream_connect_success_total 26338
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 26414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_reconnect_attempts_total 1065
telemt_me_reconnect_success_total 599
telemt_me_reader_eof_total 560
telemt_me_idle_close_by_peer_total 560
telemt_me_route_drop_no_conn_total 1207308
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3163787
telemt_me_endpoint_quarantine_total 483
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 500
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 24
telemt_desync_total 12507
telemt_desync_full_logged_total 4132
telemt_desync_suppressed_total 8375
telemt_desync_frames_bucket_total{bucket="1_2"} 2946
telemt_desync_frames_bucket_total{bucket="3_10"} 4675
telemt_desync_frames_bucket_total{bucket="gt_10"} 4886
telemt_pool_swap_total 72
telemt_pool_force_close_total 1878
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 209
telemt_me_draining_writers_reap_progress_total 23704
telemt_me_writer_removed_unexpected_total 550
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1872
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22382
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1841
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21826
telemt_me_writer_teardown_success_total{mode="normal"} 24254
telemt_me_writer_teardown_noop_total 23704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47958
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.530122
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47958
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 209
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 530
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 3155691
telemt_user_connections_current{user="hello"} 4292
telemt_user_octets_from_client{user="hello"} 64684786784 (60.24 GB)
telemt_user_octets_to_client{user="hello"} 1488677290140 (1.35 TB)
telemt_user_unique_ips_current{user="hello"} 1594
telemt_user_unique_ips_recent_window{user="hello"} 551
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 65766.3 (18h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3550242
telemt_connections_bad_total 308617
telemt_connections_current 4088
telemt_connections_me_current 4088
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 106138
telemt_upstream_connect_attempt_total 42825
telemt_upstream_connect_success_total 42536
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 42774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15032
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 600
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_reconnect_attempts_total 3628
telemt_me_reconnect_success_total 806
telemt_me_reader_eof_total 712
telemt_me_idle_close_by_peer_total 712
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 1285026
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2857365
telemt_me_endpoint_quarantine_total 548
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 498
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
telemt_me_writers_warm_current 21
telemt_desync_total 11099
telemt_desync_full_logged_total 3773
telemt_desync_suppressed_total 7326
telemt_desync_frames_bucket_total{bucket="1_2"} 2765
telemt_desync_frames_bucket_total{bucket="3_10"} 4118
telemt_desync_frames_bucket_total{bucket="gt_10"} 4216
telemt_pool_swap_total 70
telemt_pool_force_close_total 1815
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 202
telemt_me_draining_writers_reap_progress_total 23039
telemt_me_writer_removed_unexpected_total 725
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2220
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21575
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1670
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 145
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21224
telemt_me_writer_teardown_success_total{mode="normal"} 23795
telemt_me_writer_teardown_noop_total 23040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46835
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.831143
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46835
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 202
telemt_me_refill_failed_total 160
telemt_me_writer_restored_same_endpoint_total 626
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 2866171
telemt_user_connections_current{user="hello"} 4088
telemt_user_octets_from_client{user="hello"} 51427644633 (47.90 GB)
telemt_user_octets_to_client{user="hello"} 1234169302724 (1.12 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1606
telemt_user_unique_ips_recent_window{user="hello"} 532
```
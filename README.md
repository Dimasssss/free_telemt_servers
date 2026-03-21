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

# Server Metrics 2026-03-21 14:37:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 64881.7 (18h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2241609
telemt_connections_bad_total 110949
telemt_connections_current 1500
telemt_connections_me_current 1500
telemt_handshake_timeouts_total 75294
telemt_upstream_connect_attempt_total 24930
telemt_upstream_connect_success_total 24805
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 24887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15957
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1454
telemt_me_reconnect_success_total 623
telemt_me_reader_eof_total 597
telemt_me_idle_close_by_peer_total 597
telemt_me_route_drop_no_conn_total 1894744
telemt_me_route_drop_channel_closed_total 599
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1790807
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 450
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 506
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
telemt_me_writers_warm_current 30
telemt_desync_total 7059
telemt_desync_full_logged_total 2419
telemt_desync_suppressed_total 4640
telemt_desync_frames_bucket_total{bucket="1_2"} 1559
telemt_desync_frames_bucket_total{bucket="3_10"} 2691
telemt_desync_frames_bucket_total{bucket="gt_10"} 2809
telemt_pool_swap_total 69
telemt_pool_force_close_total 2119
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 453
telemt_me_draining_writers_reap_progress_total 22272
telemt_me_writer_removed_unexpected_total 578
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1870
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20770
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2010
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 109
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20153
telemt_me_writer_teardown_success_total{mode="normal"} 22640
telemt_me_writer_teardown_noop_total 22278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44918
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 203.982662
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44918
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 453
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 545
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1789418
telemt_user_connections_current{user="hello"} 1500
telemt_user_octets_from_client{user="hello"} 25811958907 (24.04 GB)
telemt_user_octets_to_client{user="hello"} 446135104319 (415.50 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 580
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 4435.1 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344129
telemt_connections_bad_total 11573
telemt_connections_current 1866
telemt_connections_me_current 1866
telemt_handshake_timeouts_total 11243
telemt_upstream_connect_attempt_total 1628
telemt_upstream_connect_success_total 1619
telemt_upstream_connect_attempts_per_request{bucket="1"} 1619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 789
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 113
telemt_me_reconnect_success_total 29
telemt_me_reader_eof_total 27
telemt_me_idle_close_by_peer_total 27
telemt_me_route_drop_no_conn_total 226373
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 305886
telemt_me_endpoint_quarantine_total 28
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 39
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_desync_total 1256
telemt_desync_full_logged_total 519
telemt_desync_suppressed_total 737
telemt_desync_frames_bucket_total{bucket="1_2"} 255
telemt_desync_frames_bucket_total{bucket="3_10"} 490
telemt_desync_frames_bucket_total{bucket="gt_10"} 511
telemt_pool_swap_total 4
telemt_pool_force_close_total 112
telemt_me_writer_close_signal_drop_total 24
telemt_me_draining_writers_reap_progress_total 1180
telemt_me_writer_removed_unexpected_total 25
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1120
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 107
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1068
telemt_me_writer_teardown_success_total{mode="normal"} 1207
telemt_me_writer_teardown_noop_total 1180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2387
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.736082
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2387
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 24
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 299387
telemt_user_connections_current{user="hello"} 1866
telemt_user_octets_from_client{user="hello"} 5035187955 (4.69 GB)
telemt_user_octets_to_client{user="hello"} 77820705843 (72.48 GB)
telemt_user_msgs_from_client{user="hello"} 423
telemt_user_msgs_to_client{user="hello"} 734
telemt_user_unique_ips_current{user="hello"} 980
telemt_user_unique_ips_recent_window{user="hello"} 561
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 64880.3 (18h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4430677
telemt_connections_bad_total 407416
telemt_connections_current 4697
telemt_connections_me_current 4697
telemt_handshake_timeouts_total 165579
telemt_upstream_connect_attempt_total 24341
telemt_upstream_connect_success_total 24295
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 24300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13233
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 987
telemt_me_reconnect_success_total 551
telemt_me_reader_eof_total 552
telemt_me_idle_close_by_peer_total 552
telemt_me_route_drop_no_conn_total 2415991
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3605727
telemt_me_endpoint_quarantine_total 408
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 492
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
telemt_me_writers_active_current 42
telemt_me_writers_warm_current 22
telemt_desync_total 14956
telemt_desync_full_logged_total 5047
telemt_desync_suppressed_total 9909
telemt_desync_frames_bucket_total{bucket="1_2"} 3171
telemt_desync_frames_bucket_total{bucket="3_10"} 5883
telemt_desync_frames_bucket_total{bucket="gt_10"} 5902
telemt_pool_swap_total 68
telemt_pool_force_close_total 2195
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 22068
telemt_me_writer_removed_unexpected_total 533
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1920
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20472
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2003
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19873
telemt_me_writer_teardown_success_total{mode="normal"} 22392
telemt_me_writer_teardown_noop_total 22097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44489
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 70.966123
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44489
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 501
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 3601337
telemt_user_connections_current{user="hello"} 4697
telemt_user_octets_from_client{user="hello"} 58784414760 (54.75 GB)
telemt_user_octets_to_client{user="hello"} 1211977374292 (1.10 TB)
telemt_user_unique_ips_current{user="hello"} 1896
telemt_user_unique_ips_recent_window{user="hello"} 581
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 64880.6 (18h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3620633
telemt_connections_bad_total 401086
telemt_connections_current 4003
telemt_connections_me_current 4003
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 132899
telemt_upstream_connect_attempt_total 28692
telemt_upstream_connect_success_total 28413
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 28550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13211
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 483
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1193
telemt_me_reconnect_success_total 559
telemt_me_reader_eof_total 526
telemt_me_idle_close_by_peer_total 526
telemt_me_route_drop_no_conn_total 1126526
telemt_me_route_drop_channel_closed_total 87
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2629499
telemt_me_endpoint_quarantine_total 416
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 493
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
telemt_me_writers_warm_current 34
telemt_desync_total 12180
telemt_desync_full_logged_total 4104
telemt_desync_suppressed_total 8076
telemt_desync_frames_bucket_total{bucket="1_2"} 3070
telemt_desync_frames_bucket_total{bucket="3_10"} 4699
telemt_desync_frames_bucket_total{bucket="gt_10"} 4411
telemt_pool_swap_total 70
telemt_pool_force_close_total 2006
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 183
telemt_me_draining_writers_reap_progress_total 21228
telemt_me_writer_removed_unexpected_total 510
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1792
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19953
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1872
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 134
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19222
telemt_me_writer_teardown_success_total{mode="normal"} 21745
telemt_me_writer_teardown_noop_total 21229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42974
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.803513
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42974
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 183
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 472
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 2629658
telemt_user_connections_current{user="hello"} 4003
telemt_user_octets_from_client{user="hello"} 49278960337 (45.89 GB)
telemt_user_octets_to_client{user="hello"} 1228325518055 (1.12 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1579
telemt_user_unique_ips_recent_window{user="hello"} 520
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 64845.2 (18h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3521228
telemt_connections_bad_total 377504
telemt_connections_current 3351
telemt_connections_me_current 3351
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 104526
telemt_upstream_connect_attempt_total 33897
telemt_upstream_connect_success_total 33665
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 33798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14593
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 848
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1292
telemt_me_reconnect_success_total 630
telemt_me_reader_eof_total 574
telemt_me_idle_close_by_peer_total 574
telemt_me_route_drop_no_conn_total 1088229
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2586366
telemt_me_endpoint_quarantine_total 467
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 485
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
telemt_me_writers_warm_current 10
telemt_desync_total 12080
telemt_desync_full_logged_total 4040
telemt_desync_suppressed_total 8040
telemt_desync_frames_bucket_total{bucket="1_2"} 3031
telemt_desync_frames_bucket_total{bucket="3_10"} 4545
telemt_desync_frames_bucket_total{bucket="gt_10"} 4504
telemt_pool_swap_total 68
telemt_pool_force_close_total 1941
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 220
telemt_me_draining_writers_reap_progress_total 22618
telemt_me_writer_removed_unexpected_total 547
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1903
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21297
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1767
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20677
telemt_me_writer_teardown_success_total{mode="normal"} 23200
telemt_me_writer_teardown_noop_total 22623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45823
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.760982
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45823
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 220
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 549
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2590572
telemt_user_connections_current{user="hello"} 3351
telemt_user_octets_from_client{user="hello"} 55886289445 (52.05 GB)
telemt_user_octets_to_client{user="hello"} 1216726100504 (1.11 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1364
telemt_user_unique_ips_recent_window{user="hello"} 446
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 64884.3 (18h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12062214
telemt_connections_bad_total 799137
telemt_connections_current 5520
telemt_connections_me_current 5520
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 374038
telemt_upstream_connect_attempt_total 115083
telemt_upstream_connect_success_total 105220
telemt_upstream_connect_fail_total 8845
telemt_upstream_connect_attempts_per_request{bucket="1"} 114065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25097
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8845
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 3826
telemt_me_reconnect_success_total 1364
telemt_me_reader_eof_total 951
telemt_me_idle_close_by_peer_total 950
telemt_me_route_drop_no_conn_total 22524957
telemt_me_route_drop_channel_closed_total 75
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9889963
telemt_me_endpoint_quarantine_total 502
telemt_me_single_endpoint_outage_enter_total 77
telemt_me_single_endpoint_outage_exit_total 77
telemt_me_single_endpoint_outage_reconnect_attempt_total 173
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 173
telemt_me_single_endpoint_shadow_rotate_total 507
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 35
telemt_desync_total 17873
telemt_desync_full_logged_total 5656
telemt_desync_suppressed_total 12217
telemt_desync_frames_bucket_total{bucket="1_2"} 3911
telemt_desync_frames_bucket_total{bucket="3_10"} 7809
telemt_desync_frames_bucket_total{bucket="gt_10"} 6153
telemt_pool_swap_total 65
telemt_pool_force_close_total 2102
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 453
telemt_me_draining_writers_reap_progress_total 20945
telemt_me_writer_removed_unexpected_total 1313
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2782
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19286
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1753
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 349
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18843
telemt_me_writer_teardown_success_total{mode="normal"} 22068
telemt_me_writer_teardown_noop_total 20955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43023
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 165.685808
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43023
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 453
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 948
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 97
telemt_me_writer_removed_unexpected_minus_restored_total 356
telemt_user_connections_total{user="hello"} 9966236
telemt_user_connections_current{user="hello"} 5520
telemt_user_octets_from_client{user="hello"} 72470795553 (67.49 GB)
telemt_user_octets_to_client{user="hello"} 768517314529 (715.74 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 1916
telemt_user_unique_ips_recent_window{user="hello"} 1075
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 64851.7 (18h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3552300
telemt_connections_bad_total 403966
telemt_connections_current 3707
telemt_connections_me_current 3707
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 78187
telemt_upstream_connect_attempt_total 27576
telemt_upstream_connect_success_total 27273
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 27533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14175
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_reconnect_attempts_total 2664
telemt_me_reconnect_success_total 962
telemt_me_reader_eof_total 955
telemt_me_idle_close_by_peer_total 955
telemt_me_route_drop_no_conn_total 1458848
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2721496
telemt_me_endpoint_quarantine_total 407
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 486
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 10
telemt_desync_total 13010
telemt_desync_full_logged_total 4524
telemt_desync_suppressed_total 8486
telemt_desync_frames_bucket_total{bucket="1_2"} 2511
telemt_desync_frames_bucket_total{bucket="3_10"} 5176
telemt_desync_frames_bucket_total{bucket="gt_10"} 5323
telemt_pool_swap_total 64
telemt_pool_force_close_total 1860
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 183
telemt_me_draining_writers_reap_progress_total 23095
telemt_me_writer_removed_unexpected_total 927
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2264
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21788
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1612
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 248
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21235
telemt_me_writer_teardown_success_total{mode="normal"} 24052
telemt_me_writer_teardown_noop_total 23096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47148
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.198709
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47148
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 183
telemt_me_refill_failed_total 93
telemt_me_writer_restored_same_endpoint_total 823
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 2705390
telemt_user_connections_current{user="hello"} 3707
telemt_user_octets_from_client{user="hello"} 65044133808 (60.58 GB)
telemt_user_octets_to_client{user="hello"} 1148332732670 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1476
telemt_user_unique_ips_recent_window{user="hello"} 506
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 1687.3 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278137
telemt_connections_bad_total 5635
telemt_connections_current 3963
telemt_connections_me_current 3963
telemt_handshake_timeouts_total 143090
telemt_upstream_connect_attempt_total 732
telemt_upstream_connect_success_total 711
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 374
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 63
telemt_me_reconnect_success_total 50
telemt_me_reader_eof_total 47
telemt_me_idle_close_by_peer_total 47
telemt_me_route_drop_no_conn_total 109953
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118581
telemt_me_endpoint_quarantine_total 4
telemt_me_single_endpoint_shadow_rotate_total 13
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
telemt_me_writers_active_current 87
telemt_desync_total 493
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 319
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 203
telemt_desync_frames_bucket_total{bucket="gt_10"} 197
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 492
telemt_me_writer_removed_unexpected_total 48
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 63
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 477
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 492
telemt_me_writer_teardown_success_total{mode="normal"} 540
telemt_me_writer_teardown_noop_total 492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1032
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.004898
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1032
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 118603
telemt_user_connections_current{user="hello"} 3963
telemt_user_octets_from_client{user="hello"} 1646047144 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 45857422692 (42.71 GB)
telemt_user_unique_ips_current{user="hello"} 1542
telemt_user_unique_ips_recent_window{user="hello"} 541
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 62837.4 (17h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1143648
telemt_connections_bad_total 136233
telemt_connections_current 769
telemt_connections_me_current 769
telemt_handshake_timeouts_total 402570
telemt_upstream_connect_attempt_total 29317
telemt_upstream_connect_success_total 29311
telemt_upstream_connect_attempts_per_request{bucket="1"} 29311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1231
telemt_me_reconnect_success_total 481
telemt_me_reader_eof_total 479
telemt_me_idle_close_by_peer_total 479
telemt_me_route_drop_no_conn_total 245611
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 533270
telemt_me_endpoint_quarantine_total 570
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 527
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
telemt_desync_total 3412
telemt_desync_full_logged_total 1259
telemt_desync_suppressed_total 2153
telemt_desync_frames_bucket_total{bucket="1_2"} 619
telemt_desync_frames_bucket_total{bucket="3_10"} 1222
telemt_desync_frames_bucket_total{bucket="gt_10"} 1571
telemt_pool_swap_total 69
telemt_pool_force_close_total 1578
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 108
telemt_me_draining_writers_reap_progress_total 26281
telemt_me_writer_removed_unexpected_total 452
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1928
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24817
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1575
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24703
telemt_me_writer_teardown_success_total{mode="normal"} 26745
telemt_me_writer_teardown_noop_total 26281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53026
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.631423
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53026
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 108
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 392
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 532996
telemt_user_connections_current{user="hello"} 769
telemt_user_octets_from_client{user="hello"} 10943446107 (10.19 GB)
telemt_user_octets_to_client{user="hello"} 203176171057 (189.22 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 64856.4 (18h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3886870
telemt_connections_bad_total 356062
telemt_connections_current 4464
telemt_connections_me_current 4464
telemt_handshake_timeouts_total 122107
telemt_upstream_connect_attempt_total 26121
telemt_upstream_connect_success_total 26012
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 26087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13032
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_reconnect_attempts_total 1057
telemt_me_reconnect_success_total 591
telemt_me_reader_eof_total 552
telemt_me_idle_close_by_peer_total 552
telemt_me_route_drop_no_conn_total 1175427
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3087494
telemt_me_endpoint_quarantine_total 478
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 495
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 13
telemt_desync_total 12120
telemt_desync_full_logged_total 4017
telemt_desync_suppressed_total 8103
telemt_desync_frames_bucket_total{bucket="1_2"} 2864
telemt_desync_frames_bucket_total{bucket="3_10"} 4521
telemt_desync_frames_bucket_total{bucket="gt_10"} 4735
telemt_pool_swap_total 71
telemt_pool_force_close_total 1848
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 203
telemt_me_draining_writers_reap_progress_total 23439
telemt_me_writer_removed_unexpected_total 542
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1840
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22141
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1812
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21591
telemt_me_writer_teardown_success_total{mode="normal"} 23981
telemt_me_writer_teardown_noop_total 23439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47420
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.412115
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47420
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 203
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 523
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 3079557
telemt_user_connections_current{user="hello"} 4464
telemt_user_octets_from_client{user="hello"} 63579688472 (59.21 GB)
telemt_user_octets_to_client{user="hello"} 1454345800836 (1.32 TB)
telemt_user_unique_ips_current{user="hello"} 1569
telemt_user_unique_ips_recent_window{user="hello"} 618
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 64853.1 (18h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3473686
telemt_connections_bad_total 305270
telemt_connections_current 4198
telemt_connections_me_current 4198
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 102443
telemt_upstream_connect_attempt_total 42555
telemt_upstream_connect_success_total 42269
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 42504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14887
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 599
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_reconnect_attempts_total 3625
telemt_me_reconnect_success_total 804
telemt_me_reader_eof_total 710
telemt_me_idle_close_by_peer_total 710
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 1251953
telemt_me_route_drop_channel_closed_total 96
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2791447
telemt_me_endpoint_quarantine_total 536
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 493
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
telemt_me_writers_warm_current 13
telemt_desync_total 10841
telemt_desync_full_logged_total 3685
telemt_desync_suppressed_total 7156
telemt_desync_frames_bucket_total{bucket="1_2"} 2702
telemt_desync_frames_bucket_total{bucket="3_10"} 4018
telemt_desync_frames_bucket_total{bucket="gt_10"} 4121
telemt_pool_swap_total 69
telemt_pool_force_close_total 1769
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 194
telemt_me_draining_writers_reap_progress_total 22756
telemt_me_writer_removed_unexpected_total 723
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2188
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21322
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1648
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 121
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20987
telemt_me_writer_teardown_success_total{mode="normal"} 23510
telemt_me_writer_teardown_noop_total 22757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46267
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.508345
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46267
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 194
telemt_me_refill_failed_total 160
telemt_me_writer_restored_same_endpoint_total 624
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 2800366
telemt_user_connections_current{user="hello"} 4198
telemt_user_octets_from_client{user="hello"} 50580495061 (47.11 GB)
telemt_user_octets_to_client{user="hello"} 1205418584328 (1.10 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1702
telemt_user_unique_ips_recent_window{user="hello"} 484
```
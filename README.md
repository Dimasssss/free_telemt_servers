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

# Server Metrics 2026-03-21 13:15:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 59998.3 (16h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1975984
telemt_connections_bad_total 98862
telemt_connections_current 1596
telemt_connections_me_current 1596
telemt_handshake_timeouts_total 72212
telemt_upstream_connect_attempt_total 23105
telemt_upstream_connect_success_total 22990
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 23067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14766
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1296
telemt_me_reconnect_success_total 530
telemt_me_reader_eof_total 512
telemt_me_idle_close_by_peer_total 512
telemt_me_route_drop_no_conn_total 1484906
telemt_me_route_drop_channel_closed_total 493
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1555864
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 422
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 474
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
telemt_desync_total 6116
telemt_desync_full_logged_total 2109
telemt_desync_suppressed_total 4007
telemt_desync_frames_bucket_total{bucket="1_2"} 1353
telemt_desync_frames_bucket_total{bucket="3_10"} 2326
telemt_desync_frames_bucket_total{bucket="gt_10"} 2437
telemt_pool_swap_total 65
telemt_pool_force_close_total 1927
telemt_pool_stale_pick_total 14
telemt_me_writer_close_signal_drop_total 371
telemt_me_draining_writers_reap_progress_total 20665
telemt_me_writer_removed_unexpected_total 493
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1705
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19281
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1857
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18738
telemt_me_writer_teardown_success_total{mode="normal"} 20986
telemt_me_writer_teardown_noop_total 20670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41656
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 164.128737
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41656
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 371
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 458
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 1554720
telemt_user_connections_current{user="hello"} 1596
telemt_user_octets_from_client{user="hello"} 23334517787 (21.73 GB)
telemt_user_octets_to_client{user="hello"} 404689346455 (376.90 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 582
telemt_user_unique_ips_recent_window{user="hello"} 268
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 5643.6 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 398688
telemt_connections_bad_total 20372
telemt_connections_current 2017
telemt_connections_me_current 2017
telemt_handshake_timeouts_total 19519
telemt_upstream_connect_attempt_total 2424
telemt_upstream_connect_success_total 2346
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 2403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1340
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 203
telemt_me_reconnect_success_total 142
telemt_me_reader_eof_total 127
telemt_me_idle_close_by_peer_total 127
telemt_me_route_drop_no_conn_total 344539
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334070
telemt_me_endpoint_quarantine_total 46
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 43
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
telemt_me_writers_active_current 45
telemt_desync_total 1185
telemt_desync_full_logged_total 552
telemt_desync_suppressed_total 633
telemt_desync_frames_bucket_total{bucket="1_2"} 251
telemt_desync_frames_bucket_total{bucket="3_10"} 484
telemt_desync_frames_bucket_total{bucket="gt_10"} 450
telemt_pool_swap_total 4
telemt_pool_force_close_total 167
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 11
telemt_me_draining_writers_reap_progress_total 2002
telemt_me_writer_removed_unexpected_total 135
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 254
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1883
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 112
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1835
telemt_me_writer_teardown_success_total{mode="normal"} 2137
telemt_me_writer_teardown_noop_total 2002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4139
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.161182
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4139
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 11
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 128
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 333824
telemt_user_connections_current{user="hello"} 2017
telemt_user_octets_from_client{user="hello"} 4773575392 (4.45 GB)
telemt_user_octets_to_client{user="hello"} 85565746696 (79.69 GB)
telemt_user_unique_ips_current{user="hello"} 988
telemt_user_unique_ips_recent_window{user="hello"} 760
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 59996.2 (16h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3881478
telemt_connections_bad_total 388531
telemt_connections_current 5178
telemt_connections_me_current 5178
telemt_handshake_timeouts_total 150095
telemt_upstream_connect_attempt_total 22617
telemt_upstream_connect_success_total 22582
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 22587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12268
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 848
telemt_me_reconnect_success_total 479
telemt_me_reader_eof_total 475
telemt_me_idle_close_by_peer_total 475
telemt_me_route_drop_no_conn_total 1917950
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3118981
telemt_me_endpoint_quarantine_total 383
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 459
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
telemt_me_writers_active_current 52
telemt_desync_total 13221
telemt_desync_full_logged_total 4480
telemt_desync_suppressed_total 8741
telemt_desync_frames_bucket_total{bucket="1_2"} 2814
telemt_desync_frames_bucket_total{bucket="3_10"} 5184
telemt_desync_frames_bucket_total{bucket="gt_10"} 5223
telemt_pool_swap_total 64
telemt_pool_force_close_total 2022
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 308
telemt_me_draining_writers_reap_progress_total 20545
telemt_me_writer_removed_unexpected_total 458
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1757
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19055
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1871
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 151
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18523
telemt_me_writer_teardown_success_total{mode="normal"} 20812
telemt_me_writer_teardown_noop_total 20563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41375
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 62.477669
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41375
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 308
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 431
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 3114968
telemt_user_connections_current{user="hello"} 5178
telemt_user_octets_from_client{user="hello"} 51080776488 (47.57 GB)
telemt_user_octets_to_client{user="hello"} 1077444592292 (1003.45 GB)
telemt_user_unique_ips_current{user="hello"} 1909
telemt_user_unique_ips_recent_window{user="hello"} 925
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 59997.5 (16h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3163574
telemt_connections_bad_total 342642
telemt_connections_current 3704
telemt_connections_me_current 3704
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 122062
telemt_upstream_connect_attempt_total 27258
telemt_upstream_connect_success_total 26984
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 27118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12432
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 476
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1154
telemt_me_reconnect_success_total 538
telemt_me_reader_eof_total 501
telemt_me_idle_close_by_peer_total 501
telemt_me_route_drop_no_conn_total 990517
telemt_me_route_drop_channel_closed_total 81
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2280918
telemt_me_endpoint_quarantine_total 393
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 459
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
telemt_desync_total 10522
telemt_desync_full_logged_total 3561
telemt_desync_suppressed_total 6961
telemt_desync_frames_bucket_total{bucket="1_2"} 2623
telemt_desync_frames_bucket_total{bucket="3_10"} 4055
telemt_desync_frames_bucket_total{bucket="gt_10"} 3844
telemt_pool_swap_total 65
telemt_pool_force_close_total 1825
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 154
telemt_me_draining_writers_reap_progress_total 19966
telemt_me_writer_removed_unexpected_total 488
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1689
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18786
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1704
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 121
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18141
telemt_me_writer_teardown_success_total{mode="normal"} 20475
telemt_me_writer_teardown_noop_total 19967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40442
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.438226
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40442
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 154
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 453
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 2281749
telemt_user_connections_current{user="hello"} 3704
telemt_user_octets_from_client{user="hello"} 42857493145 (39.91 GB)
telemt_user_octets_to_client{user="hello"} 1080464958695 (1006.26 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1422
telemt_user_unique_ips_recent_window{user="hello"} 557
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 59961.4 (16h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3090168
telemt_connections_bad_total 332948
telemt_connections_current 3718
telemt_connections_me_current 3718
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 89991
telemt_upstream_connect_attempt_total 32459
telemt_upstream_connect_success_total 32234
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 32367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13774
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 842
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1276
telemt_me_reconnect_success_total 616
telemt_me_reader_eof_total 559
telemt_me_idle_close_by_peer_total 559
telemt_me_route_drop_no_conn_total 942125
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2253582
telemt_me_endpoint_quarantine_total 437
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 451
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
telemt_desync_total 10431
telemt_desync_full_logged_total 3484
telemt_desync_suppressed_total 6947
telemt_desync_frames_bucket_total{bucket="1_2"} 2666
telemt_desync_frames_bucket_total{bucket="3_10"} 3962
telemt_desync_frames_bucket_total{bucket="gt_10"} 3803
telemt_pool_swap_total 63
telemt_pool_force_close_total 1779
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 207
telemt_me_draining_writers_reap_progress_total 21323
telemt_me_writer_removed_unexpected_total 533
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1804
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20086
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1619
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 160
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19544
telemt_me_writer_teardown_success_total{mode="normal"} 21890
telemt_me_writer_teardown_noop_total 21327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43217
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.387076
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43217
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 207
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 537
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2258492
telemt_user_connections_current{user="hello"} 3718
telemt_user_octets_from_client{user="hello"} 50238566193 (46.79 GB)
telemt_user_octets_to_client{user="hello"} 1074673533896 (1000.87 GB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1445
telemt_user_unique_ips_recent_window{user="hello"} 521
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 60000.8 (16h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10402638
telemt_connections_bad_total 706280
telemt_connections_current 5633
telemt_connections_me_current 5633
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 334737
telemt_upstream_connect_attempt_total 89722
telemt_upstream_connect_success_total 84504
telemt_upstream_connect_fail_total 4331
telemt_upstream_connect_attempts_per_request{bucket="1"} 88835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4331
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 3535
telemt_me_reconnect_success_total 1228
telemt_me_reader_eof_total 882
telemt_me_idle_close_by_peer_total 881
telemt_me_route_drop_no_conn_total 19221138
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8553788
telemt_me_endpoint_quarantine_total 450
telemt_me_single_endpoint_outage_enter_total 67
telemt_me_single_endpoint_outage_exit_total 67
telemt_me_single_endpoint_outage_reconnect_attempt_total 152
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 152
telemt_me_single_endpoint_shadow_rotate_total 472
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 16096
telemt_desync_full_logged_total 5139
telemt_desync_suppressed_total 10957
telemt_desync_frames_bucket_total{bucket="1_2"} 3422
telemt_desync_frames_bucket_total{bucket="3_10"} 7064
telemt_desync_frames_bucket_total{bucket="gt_10"} 5610
telemt_pool_swap_total 60
telemt_pool_force_close_total 1906
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 395
telemt_me_draining_writers_reap_progress_total 19503
telemt_me_writer_removed_unexpected_total 1192
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2551
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18027
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1632
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 274
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17597
telemt_me_writer_teardown_success_total{mode="normal"} 20578
telemt_me_writer_teardown_noop_total 19512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40090
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.420851
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40090
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 395
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 868
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 8611427
telemt_user_connections_current{user="hello"} 5633
telemt_user_octets_from_client{user="hello"} 66087234533 (61.55 GB)
telemt_user_octets_to_client{user="hello"} 711492158112 (662.63 GB)
telemt_user_msgs_from_client{user="hello"} 173886
telemt_user_msgs_to_client{user="hello"} 472410
telemt_user_unique_ips_current{user="hello"} 2036
telemt_user_unique_ips_recent_window{user="hello"} 1096
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 59968.3 (16h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3117454
telemt_connections_bad_total 365611
telemt_connections_current 4136
telemt_connections_me_current 4136
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 68285
telemt_upstream_connect_attempt_total 25728
telemt_upstream_connect_success_total 25443
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 25698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13177
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_reconnect_attempts_total 2525
telemt_me_reconnect_success_total 896
telemt_me_reader_eof_total 888
telemt_me_idle_close_by_peer_total 888
telemt_me_route_drop_no_conn_total 1177518
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2369542
telemt_me_endpoint_quarantine_total 374
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 457
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
telemt_me_writers_active_current 89
telemt_desync_total 11087
telemt_desync_full_logged_total 3845
telemt_desync_suppressed_total 7242
telemt_desync_frames_bucket_total{bucket="1_2"} 2161
telemt_desync_frames_bucket_total{bucket="3_10"} 4423
telemt_desync_frames_bucket_total{bucket="gt_10"} 4503
telemt_pool_swap_total 60
telemt_pool_force_close_total 1687
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 158
telemt_me_draining_writers_reap_progress_total 21415
telemt_me_writer_removed_unexpected_total 859
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2089
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20214
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1497
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 190
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19728
telemt_me_writer_teardown_success_total{mode="normal"} 22303
telemt_me_writer_teardown_noop_total 21416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43719
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.481927
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43719
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 158
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 761
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 2354316
telemt_user_connections_current{user="hello"} 4136
telemt_user_octets_from_client{user="hello"} 46674513348 (43.47 GB)
telemt_user_octets_to_client{user="hello"} 1027111058242 (956.57 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1689
telemt_user_unique_ips_recent_window{user="hello"} 548
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 59962.8 (16h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4751609
telemt_connections_bad_total 235619
telemt_connections_current 3395
telemt_connections_me_current 3395
telemt_handshake_timeouts_total 2097368
telemt_upstream_connect_attempt_total 23812
telemt_upstream_connect_success_total 23778
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 23781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12859
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 991
telemt_me_reconnect_success_total 427
telemt_me_reader_eof_total 435
telemt_me_idle_close_by_peer_total 435
telemt_me_route_drop_no_conn_total 1067312
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2128007
telemt_me_endpoint_quarantine_total 446
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 467
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
telemt_desync_total 10166
telemt_desync_full_logged_total 3609
telemt_desync_suppressed_total 6557
telemt_desync_frames_bucket_total{bucket="1_2"} 1878
telemt_desync_frames_bucket_total{bucket="3_10"} 4034
telemt_desync_frames_bucket_total{bucket="gt_10"} 4254
telemt_pool_swap_total 65
telemt_pool_force_close_total 1658
telemt_me_writer_close_signal_drop_total 146
telemt_me_draining_writers_reap_progress_total 21310
telemt_me_writer_removed_unexpected_total 417
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1457
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20297
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1601
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 57
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19652
telemt_me_writer_teardown_success_total{mode="normal"} 21754
telemt_me_writer_teardown_noop_total 21310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43064
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.471341
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43064
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 146
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 372
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2121245
telemt_user_connections_current{user="hello"} 3395
telemt_user_octets_from_client{user="hello"} 39903595720 (37.16 GB)
telemt_user_octets_to_client{user="hello"} 996827070992 (928.37 GB)
telemt_user_unique_ips_current{user="hello"} 1327
telemt_user_unique_ips_recent_window{user="hello"} 554
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 57954.5 (16h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1017709
telemt_connections_bad_total 123729
telemt_connections_current 726
telemt_connections_me_current 726
telemt_handshake_timeouts_total 356375
telemt_upstream_connect_attempt_total 27359
telemt_upstream_connect_success_total 27357
telemt_upstream_connect_attempts_per_request{bucket="1"} 27357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15998
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1185
telemt_me_reconnect_success_total 457
telemt_me_reader_eof_total 454
telemt_me_idle_close_by_peer_total 454
telemt_me_route_drop_no_conn_total 210732
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 468601
telemt_me_endpoint_quarantine_total 535
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 491
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
telemt_me_writers_active_current 46
telemt_desync_total 3150
telemt_desync_full_logged_total 1172
telemt_desync_suppressed_total 1978
telemt_desync_frames_bucket_total{bucket="1_2"} 550
telemt_desync_frames_bucket_total{bucket="3_10"} 1118
telemt_desync_frames_bucket_total{bucket="gt_10"} 1482
telemt_pool_swap_total 64
telemt_pool_force_close_total 1441
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 102
telemt_me_draining_writers_reap_progress_total 24517
telemt_me_writer_removed_unexpected_total 429
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1811
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23145
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1438
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23076
telemt_me_writer_teardown_success_total{mode="normal"} 24956
telemt_me_writer_teardown_noop_total 24517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49473
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.262857
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49473
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 102
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 370
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 468404
telemt_user_connections_current{user="hello"} 726
telemt_user_octets_from_client{user="hello"} 8092042987 (7.54 GB)
telemt_user_octets_to_client{user="hello"} 179114888733 (166.81 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 59972.7 (16h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3365743
telemt_connections_bad_total 319814
telemt_connections_current 4542
telemt_connections_me_current 4542
telemt_handshake_timeouts_total 99374
telemt_upstream_connect_attempt_total 24610
telemt_upstream_connect_success_total 24510
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 24579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12295
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 998
telemt_me_reconnect_success_total 555
telemt_me_reader_eof_total 519
telemt_me_idle_close_by_peer_total 519
telemt_me_route_drop_no_conn_total 965492
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2655842
telemt_me_endpoint_quarantine_total 457
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 463
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
telemt_desync_total 10742
telemt_desync_full_logged_total 3530
telemt_desync_suppressed_total 7212
telemt_desync_frames_bucket_total{bucket="1_2"} 2560
telemt_desync_frames_bucket_total{bucket="3_10"} 3995
telemt_desync_frames_bucket_total{bucket="gt_10"} 4187
telemt_pool_swap_total 66
telemt_pool_force_close_total 1703
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 183
telemt_me_draining_writers_reap_progress_total 22110
telemt_me_writer_removed_unexpected_total 510
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1712
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20906
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1672
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20407
telemt_me_writer_teardown_success_total{mode="normal"} 22618
telemt_me_writer_teardown_noop_total 22110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44728
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.612330
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44728
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 183
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 494
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 2648569
telemt_user_connections_current{user="hello"} 4542
telemt_user_octets_from_client{user="hello"} 55782860528 (51.95 GB)
telemt_user_octets_to_client{user="hello"} 1245151772576 (1.13 TB)
telemt_user_unique_ips_current{user="hello"} 1636
telemt_user_unique_ips_recent_window{user="hello"} 591
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 59969.3 (16h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3022421
telemt_connections_bad_total 252986
telemt_connections_current 3631
telemt_connections_me_current 3631
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 88615
telemt_upstream_connect_attempt_total 40856
telemt_upstream_connect_success_total 40592
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 40811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13989
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 587
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_reconnect_attempts_total 3428
telemt_me_reconnect_success_total 739
telemt_me_reader_eof_total 641
telemt_me_idle_close_by_peer_total 641
telemt_me_seq_mismatch_total 30
telemt_me_route_drop_no_conn_total 1001459
telemt_me_route_drop_channel_closed_total 75
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2428967
telemt_me_endpoint_quarantine_total 513
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 463
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
telemt_desync_total 9342
telemt_desync_full_logged_total 3186
telemt_desync_suppressed_total 6156
telemt_desync_frames_bucket_total{bucket="1_2"} 2395
telemt_desync_frames_bucket_total{bucket="3_10"} 3444
telemt_desync_frames_bucket_total{bucket="gt_10"} 3503
telemt_pool_swap_total 65
telemt_pool_force_close_total 1647
telemt_me_writer_close_signal_drop_total 169
telemt_me_draining_writers_reap_progress_total 21312
telemt_me_writer_removed_unexpected_total 653
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2020
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19975
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1539
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19665
telemt_me_writer_teardown_success_total{mode="normal"} 21995
telemt_me_writer_teardown_noop_total 21313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43308
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.782281
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43308
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 169
telemt_me_refill_failed_total 152
telemt_me_writer_restored_same_endpoint_total 563
telemt_me_writer_restored_fallback_total 39
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 2438495
telemt_user_connections_current{user="hello"} 3631
telemt_user_octets_from_client{user="hello"} 44927030477 (41.84 GB)
telemt_user_octets_to_client{user="hello"} 1066332381504 (993.10 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1339
telemt_user_unique_ips_recent_window{user="hello"} 474
```
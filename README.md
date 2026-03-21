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

# Server Metrics 2026-03-21 16:34:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 71923.8 (19h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2579297
telemt_connections_bad_total 153752
telemt_connections_current 1519
telemt_connections_me_current 1519
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 80975
telemt_upstream_connect_attempt_total 30265
telemt_upstream_connect_success_total 30134
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 30222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17579
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1744
telemt_me_reconnect_success_total 687
telemt_me_reader_eof_total 660
telemt_me_idle_close_by_peer_total 660
telemt_me_route_drop_no_conn_total 2188780
telemt_me_route_drop_channel_closed_total 686
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2057254
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 492
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 558
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
telemt_desync_total 8215
telemt_desync_full_logged_total 2837
telemt_desync_suppressed_total 5378
telemt_desync_frames_bucket_total{bucket="1_2"} 1797
telemt_desync_frames_bucket_total{bucket="3_10"} 3128
telemt_desync_frames_bucket_total{bucket="gt_10"} 3290
telemt_pool_swap_total 77
telemt_pool_force_close_total 2334
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 528
telemt_me_draining_writers_reap_progress_total 24347
telemt_me_writer_removed_unexpected_total 638
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2092
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22677
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2210
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22013
telemt_me_writer_teardown_success_total{mode="normal"} 24769
telemt_me_writer_teardown_noop_total 24354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49123
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 231.024606
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49123
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 528
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 588
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2058476
telemt_user_connections_current{user="hello"} 1519
telemt_user_octets_from_client{user="hello"} 29354065665 (27.34 GB)
telemt_user_octets_to_client{user="hello"} 509009168422 (474.05 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 3049.0 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169395
telemt_connections_bad_total 6746
telemt_connections_current 4384
telemt_connections_me_current 4384
telemt_handshake_timeouts_total 3610
telemt_upstream_connect_attempt_total 1258
telemt_upstream_connect_success_total 1257
telemt_upstream_connect_attempts_per_request{bucket="1"} 1257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 632
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 10
telemt_me_reconnect_success_total 9
telemt_me_reader_eof_total 9
telemt_me_idle_close_by_peer_total 9
telemt_me_route_drop_no_conn_total 140340
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149706
telemt_me_endpoint_quarantine_total 23
telemt_me_single_endpoint_shadow_rotate_total 32
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
telemt_me_writers_active_current 44
telemt_desync_total 498
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 258
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 187
telemt_pool_swap_total 3
telemt_pool_force_close_total 56
telemt_me_writer_close_signal_drop_total 25
telemt_me_draining_writers_reap_progress_total 1099
telemt_me_writer_removed_unexpected_total 9
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 86
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1022
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1043
telemt_me_writer_teardown_success_total{mode="normal"} 1108
telemt_me_writer_teardown_noop_total 1099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2207
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.284441
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2207
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 25
telemt_me_writer_restored_same_endpoint_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 147207
telemt_user_connections_current{user="hello"} 4384
telemt_user_octets_from_client{user="hello"} 1333027164 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 29794595744 (27.75 GB)
telemt_user_unique_ips_current{user="hello"} 1556
telemt_user_unique_ips_recent_window{user="hello"} 777
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 71921.5 (19h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5350562
telemt_connections_bad_total 452830
telemt_connections_current 5333
telemt_connections_me_current 5333
telemt_handshake_timeouts_total 178639
telemt_upstream_connect_attempt_total 26406
telemt_upstream_connect_success_total 26348
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 26354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1175
telemt_me_reconnect_success_total 596
telemt_me_reader_eof_total 600
telemt_me_idle_close_by_peer_total 600
telemt_me_route_drop_no_conn_total 3322976
telemt_me_route_drop_channel_closed_total 47
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4402498
telemt_me_endpoint_quarantine_total 446
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 537
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
telemt_me_writers_active_current 45
telemt_desync_total 17934
telemt_desync_full_logged_total 6026
telemt_desync_suppressed_total 11908
telemt_desync_frames_bucket_total{bucket="1_2"} 3788
telemt_desync_frames_bucket_total{bucket="3_10"} 7131
telemt_desync_frames_bucket_total{bucket="gt_10"} 7015
telemt_pool_swap_total 76
telemt_pool_force_close_total 2498
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 396
telemt_me_draining_writers_reap_progress_total 23987
telemt_me_writer_removed_unexpected_total 580
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2098
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22194
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 34
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2294
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 204
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21489
telemt_me_writer_teardown_success_total{mode="normal"} 24292
telemt_me_writer_teardown_noop_total 24021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48313
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 97.331429
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48313
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 396
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 537
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 4397262
telemt_user_connections_current{user="hello"} 5333
telemt_user_octets_from_client{user="hello"} 68752826480 (64.03 GB)
telemt_user_octets_to_client{user="hello"} 1392028803212 (1.27 TB)
telemt_user_unique_ips_current{user="hello"} 2068
telemt_user_unique_ips_recent_window{user="hello"} 640
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 71922.9 (19h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4264778
telemt_connections_bad_total 441115
telemt_connections_current 3945
telemt_connections_me_current 3945
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 147290
telemt_upstream_connect_attempt_total 30786
telemt_upstream_connect_success_total 30498
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 30639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14374
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 497
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1402
telemt_me_reconnect_success_total 621
telemt_me_reader_eof_total 585
telemt_me_idle_close_by_peer_total 585
telemt_me_route_drop_no_conn_total 1363808
telemt_me_route_drop_channel_closed_total 110
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3154945
telemt_me_endpoint_quarantine_total 452
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 547
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
telemt_desync_total 15091
telemt_desync_full_logged_total 4976
telemt_desync_suppressed_total 10115
telemt_desync_frames_bucket_total{bucket="1_2"} 3741
telemt_desync_frames_bucket_total{bucket="3_10"} 5843
telemt_desync_frames_bucket_total{bucket="gt_10"} 5507
telemt_pool_swap_total 78
telemt_pool_force_close_total 2292
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 235
telemt_me_draining_writers_reap_progress_total 23125
telemt_me_writer_removed_unexpected_total 566
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1992
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21679
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2131
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 161
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20833
telemt_me_writer_teardown_success_total{mode="normal"} 23671
telemt_me_writer_teardown_noop_total 23128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46799
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 26.270536
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46799
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 235
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 525
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 3154196
telemt_user_connections_current{user="hello"} 3945
telemt_user_octets_from_client{user="hello"} 70824742021 (65.96 GB)
telemt_user_octets_to_client{user="hello"} 1449283041087 (1.32 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1587
telemt_user_unique_ips_recent_window{user="hello"} 560
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 71886.9 (19h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4208950
telemt_connections_bad_total 423570
telemt_connections_current 3782
telemt_connections_me_current 3782
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 127282
telemt_upstream_connect_attempt_total 36041
telemt_upstream_connect_success_total 35797
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 35930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15719
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 296
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 866
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 1466
telemt_me_reconnect_success_total 672
telemt_me_reader_eof_total 615
telemt_me_idle_close_by_peer_total 615
telemt_me_route_drop_no_conn_total 1471297
telemt_me_route_drop_channel_closed_total 46
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3135532
telemt_me_endpoint_quarantine_total 504
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 538
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
telemt_desync_total 14577
telemt_desync_full_logged_total 4781
telemt_desync_suppressed_total 9796
telemt_desync_frames_bucket_total{bucket="1_2"} 3615
telemt_desync_frames_bucket_total{bucket="3_10"} 5493
telemt_desync_frames_bucket_total{bucket="gt_10"} 5469
telemt_pool_swap_total 76
telemt_pool_force_close_total 2209
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 259
telemt_me_draining_writers_reap_progress_total 24542
telemt_me_writer_removed_unexpected_total 584
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2073
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23076
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2024
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 185
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22333
telemt_me_writer_teardown_success_total{mode="normal"} 25149
telemt_me_writer_teardown_noop_total 24549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49698
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.698016
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49698
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 259
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 579
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 3138903
telemt_user_connections_current{user="hello"} 3782
telemt_user_octets_from_client{user="hello"} 77246615949 (71.94 GB)
telemt_user_octets_to_client{user="hello"} 1446402038940 (1.32 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1460
telemt_user_unique_ips_recent_window{user="hello"} 545
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 71926.0 (19h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14552295
telemt_connections_bad_total 937203
telemt_connections_current 5855
telemt_connections_me_current 5855
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 425845
telemt_upstream_connect_attempt_total 117153
telemt_upstream_connect_success_total 107218
telemt_upstream_connect_fail_total 8859
telemt_upstream_connect_attempts_per_request{bucket="1"} 116077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26214
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8859
telemt_me_keepalive_timeout_total 242
telemt_me_reconnect_attempts_total 3905
telemt_me_reconnect_success_total 1429
telemt_me_reader_eof_total 999
telemt_me_idle_close_by_peer_total 998
telemt_me_route_drop_no_conn_total 28893927
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12016740
telemt_me_endpoint_quarantine_total 541
telemt_me_single_endpoint_outage_enter_total 78
telemt_me_single_endpoint_outage_exit_total 78
telemt_me_single_endpoint_outage_reconnect_attempt_total 174
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 174
telemt_me_single_endpoint_shadow_rotate_total 560
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
telemt_desync_total 21227
telemt_desync_full_logged_total 6547
telemt_desync_suppressed_total 14680
telemt_desync_frames_bucket_total{bucket="1_2"} 4663
telemt_desync_frames_bucket_total{bucket="3_10"} 9266
telemt_desync_frames_bucket_total{bucket="gt_10"} 7298
telemt_pool_swap_total 73
telemt_pool_force_close_total 2391
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 523
telemt_me_draining_writers_reap_progress_total 22805
telemt_me_writer_removed_unexpected_total 1360
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2965
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20978
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2011
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 380
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20414
telemt_me_writer_teardown_success_total{mode="normal"} 23943
telemt_me_writer_teardown_noop_total 22817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46760
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 177.624777
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46760
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 523
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 1002
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 348
telemt_user_connections_total{user="hello"} 12091239
telemt_user_connections_current{user="hello"} 5855
telemt_user_octets_from_client{user="hello"} 95269571985 (88.73 GB)
telemt_user_octets_to_client{user="hello"} 834017558453 (776.74 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 2125
telemt_user_unique_ips_recent_window{user="hello"} 1249
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 71893.6 (19h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4209721
telemt_connections_bad_total 448353
telemt_connections_current 4048
telemt_connections_me_current 4048
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 88933
telemt_upstream_connect_attempt_total 29923
telemt_upstream_connect_success_total 29583
telemt_upstream_connect_fail_total 292
telemt_upstream_connect_attempts_per_request{bucket="1"} 29875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15495
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 292
telemt_me_reconnect_attempts_total 3021
telemt_me_reconnect_success_total 1067
telemt_me_reader_eof_total 1061
telemt_me_idle_close_by_peer_total 1061
telemt_me_route_drop_no_conn_total 1805712
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3252655
telemt_me_endpoint_quarantine_total 437
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 534
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
telemt_me_writers_active_current 44
telemt_desync_total 15758
telemt_desync_full_logged_total 5460
telemt_desync_suppressed_total 10298
telemt_desync_frames_bucket_total{bucket="1_2"} 3075
telemt_desync_frames_bucket_total{bucket="3_10"} 6243
telemt_desync_frames_bucket_total{bucket="gt_10"} 6440
telemt_pool_swap_total 71
telemt_pool_force_close_total 2104
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 213
telemt_me_draining_writers_reap_progress_total 25138
telemt_me_writer_removed_unexpected_total 1028
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2523
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23679
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1803
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 301
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23034
telemt_me_writer_teardown_success_total{mode="normal"} 26202
telemt_me_writer_teardown_noop_total 25139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51341
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.639901
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51341
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 213
telemt_me_refill_failed_total 107
telemt_me_writer_restored_same_endpoint_total 922
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 3235636
telemt_user_connections_current{user="hello"} 4048
telemt_user_octets_from_client{user="hello"} 84329057600 (78.54 GB)
telemt_user_octets_to_client{user="hello"} 1327914508146 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1666
telemt_user_unique_ips_recent_window{user="hello"} 522
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 8729.3 (2h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1345370
telemt_connections_bad_total 48004
telemt_connections_current 3471
telemt_connections_me_current 3471
telemt_handshake_timeouts_total 624163
telemt_upstream_connect_attempt_total 2955
telemt_upstream_connect_success_total 2902
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 2949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_reconnect_attempts_total 414
telemt_me_reconnect_success_total 107
telemt_me_reader_eof_total 100
telemt_me_idle_close_by_peer_total 100
telemt_me_route_drop_no_conn_total 498012
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 619576
telemt_me_endpoint_quarantine_total 36
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 65
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
telemt_me_writers_active_current 42
telemt_desync_total 3374
telemt_desync_full_logged_total 1048
telemt_desync_suppressed_total 2326
telemt_desync_frames_bucket_total{bucket="1_2"} 650
telemt_desync_frames_bucket_total{bucket="3_10"} 1230
telemt_desync_frames_bucket_total{bucket="gt_10"} 1494
telemt_pool_swap_total 8
telemt_pool_force_close_total 264
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 24
telemt_me_draining_writers_reap_progress_total 2510
telemt_me_writer_removed_unexpected_total 101
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 229
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2382
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2246
telemt_me_writer_teardown_success_total{mode="normal"} 2611
telemt_me_writer_teardown_noop_total 2510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5121
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.828870
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5121
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 24
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 89
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 618673
telemt_user_connections_current{user="hello"} 3471
telemt_user_octets_from_client{user="hello"} 14969209808 (13.94 GB)
telemt_user_octets_to_client{user="hello"} 232893468124 (216.90 GB)
telemt_user_unique_ips_current{user="hello"} 1371
telemt_user_unique_ips_recent_window{user="hello"} 535
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 69879.5 (19h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1332757
telemt_connections_bad_total 148428
telemt_connections_current 875
telemt_connections_me_current 875
telemt_handshake_timeouts_total 472309
telemt_upstream_connect_attempt_total 32283
telemt_upstream_connect_success_total 32274
telemt_upstream_connect_attempts_per_request{bucket="1"} 32274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18962
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1366
telemt_me_reconnect_success_total 573
telemt_me_reader_eof_total 574
telemt_me_idle_close_by_peer_total 574
telemt_me_route_drop_no_conn_total 294869
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 631922
telemt_me_endpoint_quarantine_total 616
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 583
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
telemt_me_writers_active_current 42
telemt_desync_total 3793
telemt_desync_full_logged_total 1357
telemt_desync_suppressed_total 2436
telemt_desync_frames_bucket_total{bucket="1_2"} 723
telemt_desync_frames_bucket_total{bucket="3_10"} 1352
telemt_desync_frames_bucket_total{bucket="gt_10"} 1718
telemt_pool_swap_total 76
telemt_pool_force_close_total 1799
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 115
telemt_me_draining_writers_reap_progress_total 28930
telemt_me_writer_removed_unexpected_total 542
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2192
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27298
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1769
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27131
telemt_me_writer_teardown_success_total{mode="normal"} 29490
telemt_me_writer_teardown_noop_total 28930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58420
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.764354
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58420
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 115
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 478
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 631480
telemt_user_connections_current{user="hello"} 875
telemt_user_octets_from_client{user="hello"} 13009384439 (12.12 GB)
telemt_user_octets_to_client{user="hello"} 244676344013 (227.87 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 71898.0 (19h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4697946
telemt_connections_bad_total 437499
telemt_connections_current 4917
telemt_connections_me_current 4917
telemt_handshake_timeouts_total 154875
telemt_upstream_connect_attempt_total 28273
telemt_upstream_connect_success_total 28155
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 28237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14191
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_reconnect_attempts_total 1204
telemt_me_reconnect_success_total 632
telemt_me_reader_eof_total 600
telemt_me_idle_close_by_peer_total 600
telemt_me_route_drop_no_conn_total 1440600
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3712931
telemt_me_endpoint_quarantine_total 511
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 549
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
telemt_me_writers_active_current 47
telemt_desync_total 14468
telemt_desync_full_logged_total 4782
telemt_desync_suppressed_total 9686
telemt_desync_frames_bucket_total{bucket="1_2"} 3409
telemt_desync_frames_bucket_total{bucket="3_10"} 5381
telemt_desync_frames_bucket_total{bucket="gt_10"} 5678
telemt_pool_swap_total 79
telemt_pool_force_close_total 2089
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 246
telemt_me_draining_writers_reap_progress_total 25352
telemt_me_writer_removed_unexpected_total 587
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2034
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23908
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2041
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 48
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23263
telemt_me_writer_teardown_success_total{mode="normal"} 25942
telemt_me_writer_teardown_noop_total 25353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51295
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.375100
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51295
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 246
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 561
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 3703353
telemt_user_connections_current{user="hello"} 4917
telemt_user_octets_from_client{user="hello"} 73809926620 (68.74 GB)
telemt_user_octets_to_client{user="hello"} 1734632875136 (1.58 TB)
telemt_user_unique_ips_current{user="hello"} 1705
telemt_user_unique_ips_recent_window{user="hello"} 645
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 71895.0 (19h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4139007
telemt_connections_bad_total 372750
telemt_connections_current 3874
telemt_connections_me_current 3874
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 128386
telemt_upstream_connect_attempt_total 44747
telemt_upstream_connect_success_total 44433
telemt_upstream_connect_fail_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 44691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16047
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 602
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 258
telemt_me_reconnect_attempts_total 4048
telemt_me_reconnect_success_total 901
telemt_me_reader_eof_total 780
telemt_me_idle_close_by_peer_total 780
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 1515666
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3303148
telemt_me_endpoint_quarantine_total 592
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 543
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
telemt_desync_total 12909
telemt_desync_full_logged_total 4373
telemt_desync_suppressed_total 8536
telemt_desync_frames_bucket_total{bucket="1_2"} 3217
telemt_desync_frames_bucket_total{bucket="3_10"} 4793
telemt_desync_frames_bucket_total{bucket="gt_10"} 4899
telemt_pool_swap_total 77
telemt_pool_force_close_total 2034
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 228
telemt_me_draining_writers_reap_progress_total 24715
telemt_me_writer_removed_unexpected_total 793
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2434
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23107
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1861
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22681
telemt_me_writer_teardown_success_total{mode="normal"} 25541
telemt_me_writer_teardown_noop_total 24716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50257
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.672698
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50257
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 228
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 693
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 3311010
telemt_user_connections_current{user="hello"} 3874
telemt_user_octets_from_client{user="hello"} 59902004501 (55.79 GB)
telemt_user_octets_to_client{user="hello"} 1403845944500 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1571
telemt_user_unique_ips_recent_window{user="hello"} 553
```
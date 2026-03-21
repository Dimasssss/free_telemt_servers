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

# Server Metrics 2026-03-21 21:40:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 2054.6 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44114
telemt_connections_bad_total 2379
telemt_connections_current 889
telemt_connections_me_current 889
telemt_handshake_timeouts_total 1558
telemt_upstream_connect_attempt_total 875
telemt_upstream_connect_success_total 875
telemt_upstream_connect_attempts_per_request{bucket="1"} 875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 551
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_me_reconnect_attempts_total 26
telemt_me_reconnect_success_total 8
telemt_me_reader_eof_total 10
telemt_me_idle_close_by_peer_total 10
telemt_me_route_drop_no_conn_total 9769
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35827
telemt_me_endpoint_quarantine_total 15
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 202
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 2
telemt_pool_force_close_total 54
telemt_me_writer_close_signal_drop_total 5
telemt_me_draining_writers_reap_progress_total 734
telemt_me_writer_removed_unexpected_total 9
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 699
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 54
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 680
telemt_me_writer_teardown_success_total{mode="normal"} 744
telemt_me_writer_teardown_noop_total 734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1478
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.661458
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1478
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 5
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 35793
telemt_user_connections_current{user="hello"} 889
telemt_user_octets_from_client{user="hello"} 511364516 (487.68 MB)
telemt_user_octets_to_client{user="hello"} 10735478652 (10.00 GB)
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 15421.6 (4h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 556898
telemt_connections_bad_total 26246
telemt_connections_current 1358
telemt_connections_me_current 1358
telemt_handshake_timeouts_total 19588
telemt_upstream_connect_attempt_total 6164
telemt_upstream_connect_success_total 6043
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 6150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_reconnect_attempts_total 500
telemt_me_reconnect_success_total 189
telemt_me_reader_eof_total 166
telemt_me_idle_close_by_peer_total 166
telemt_me_route_drop_no_conn_total 299410
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 450107
telemt_me_endpoint_quarantine_total 122
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 121
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_desync_total 2026
telemt_desync_full_logged_total 1145
telemt_desync_suppressed_total 881
telemt_desync_frames_bucket_total{bucket="1_2"} 423
telemt_desync_frames_bucket_total{bucket="3_10"} 770
telemt_desync_frames_bucket_total{bucket="gt_10"} 833
telemt_pool_swap_total 17
telemt_pool_force_close_total 476
telemt_me_writer_close_signal_drop_total 38
telemt_me_draining_writers_reap_progress_total 5356
telemt_me_writer_removed_unexpected_total 155
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 465
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5044
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 469
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4880
telemt_me_writer_teardown_success_total{mode="normal"} 5509
telemt_me_writer_teardown_noop_total 5356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 10851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 10863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 10865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 10865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 10865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 10865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 10865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 10865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 10865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 10865
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.895873
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 10865
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 38
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 129
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 449554
telemt_user_connections_current{user="hello"} 1358
telemt_user_octets_from_client{user="hello"} 7296725624 (6.80 GB)
telemt_user_octets_to_client{user="hello"} 146276527688 (136.23 GB)
telemt_user_unique_ips_current{user="hello"} 827
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 90280.8 (25h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7125202
telemt_connections_bad_total 549134
telemt_connections_current 2286
telemt_connections_me_current 2286
telemt_handshake_timeouts_total 222897
telemt_upstream_connect_attempt_total 32452
telemt_upstream_connect_success_total 32388
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 32395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17649
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1434
telemt_me_reconnect_success_total 688
telemt_me_reader_eof_total 699
telemt_me_idle_close_by_peer_total 699
telemt_me_route_drop_no_conn_total 4425839
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5825679
telemt_me_endpoint_quarantine_total 568
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 669
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
telemt_desync_total 24270
telemt_desync_full_logged_total 8046
telemt_desync_suppressed_total 16224
telemt_desync_frames_bucket_total{bucket="1_2"} 5139
telemt_desync_frames_bucket_total{bucket="3_10"} 9570
telemt_desync_frames_bucket_total{bucket="gt_10"} 9561
telemt_pool_swap_total 97
telemt_pool_force_close_total 3281
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 537
telemt_me_draining_writers_reap_progress_total 29575
telemt_me_writer_removed_unexpected_total 672
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2527
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27312
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3046
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 235
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26294
telemt_me_writer_teardown_success_total{mode="normal"} 29839
telemt_me_writer_teardown_noop_total 29615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59454
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 145.447147
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59454
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 537
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 614
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 5818618
telemt_user_connections_current{user="hello"} 2286
telemt_user_octets_from_client{user="hello"} 99972027888 (93.11 GB)
telemt_user_octets_to_client{user="hello"} 1865155940336 (1.70 TB)
telemt_user_unique_ips_current{user="hello"} 948
telemt_user_unique_ips_recent_window{user="hello"} 351
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 90282.2 (25h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5817725
telemt_connections_bad_total 569687
telemt_connections_current 2408
telemt_connections_me_current 2408
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 189718
telemt_upstream_connect_attempt_total 36450
telemt_upstream_connect_success_total 36127
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 36296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17328
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 542
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1713
telemt_me_reconnect_success_total 718
telemt_me_reader_eof_total 694
telemt_me_idle_close_by_peer_total 694
telemt_me_route_drop_no_conn_total 2022120
telemt_me_route_drop_channel_closed_total 228
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4340063
telemt_me_endpoint_quarantine_total 548
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 690
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
telemt_me_writers_active_current 45
telemt_desync_total 20885
telemt_desync_full_logged_total 6951
telemt_desync_suppressed_total 13934
telemt_desync_frames_bucket_total{bucket="1_2"} 5077
telemt_desync_frames_bucket_total{bucket="3_10"} 8074
telemt_desync_frames_bucket_total{bucket="gt_10"} 7734
telemt_pool_swap_total 99
telemt_pool_force_close_total 3008
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 335
telemt_me_draining_writers_reap_progress_total 28217
telemt_me_writer_removed_unexpected_total 671
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2440
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26379
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2809
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25209
telemt_me_writer_teardown_success_total{mode="normal"} 28819
telemt_me_writer_teardown_noop_total 28222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57041
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.807327
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57041
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 335
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 617
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 4320132
telemt_user_connections_current{user="hello"} 2408
telemt_user_octets_from_client{user="hello"} 133195864933 (124.05 GB)
telemt_user_octets_to_client{user="hello"} 2002154075479 (1.82 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 974
telemt_user_unique_ips_recent_window{user="hello"} 295
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 90246.5 (25h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5740404
telemt_connections_bad_total 526263
telemt_connections_current 2152
telemt_connections_me_current 2152
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 177118
telemt_upstream_connect_attempt_total 42866
telemt_upstream_connect_success_total 42587
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 42722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22444
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18761
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1044
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1749
telemt_me_reconnect_success_total 783
telemt_me_reader_eof_total 728
telemt_me_idle_close_by_peer_total 728
telemt_me_route_drop_no_conn_total 2046234
telemt_me_route_drop_channel_closed_total 107
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4312451
telemt_me_endpoint_quarantine_total 605
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 674
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 20636
telemt_desync_full_logged_total 6782
telemt_desync_suppressed_total 13854
telemt_desync_frames_bucket_total{bucket="1_2"} 5128
telemt_desync_frames_bucket_total{bucket="3_10"} 7837
telemt_desync_frames_bucket_total{bucket="gt_10"} 7671
telemt_pool_swap_total 97
telemt_pool_force_close_total 2883
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 347
telemt_me_draining_writers_reap_progress_total 29643
telemt_me_writer_removed_unexpected_total 697
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2530
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27814
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2668
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26760
telemt_me_writer_teardown_success_total{mode="normal"} 30344
telemt_me_writer_teardown_noop_total 29653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59997
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.693386
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59997
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 347
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 677
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 4314288
telemt_user_connections_current{user="hello"} 2152
telemt_user_octets_from_client{user="hello"} 127058634487 (118.33 GB)
telemt_user_octets_to_client{user="hello"} 1969263039651 (1.79 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 883
telemt_user_unique_ips_recent_window{user="hello"} 253
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 90285.5 (25h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19478110
telemt_connections_bad_total 1319797
telemt_connections_current 2973
telemt_connections_me_current 2973
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 548084
telemt_upstream_connect_attempt_total 182472
telemt_upstream_connect_success_total 165186
telemt_upstream_connect_fail_total 15816
telemt_upstream_connect_attempts_per_request{bucket="1"} 181002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37534
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8853
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15816
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59681
telemt_me_reconnect_success_total 1936
telemt_me_reader_eof_total 1279
telemt_me_idle_close_by_peer_total 1278
telemt_me_route_drop_no_conn_total 39360834
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15971886
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 658
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 239
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 239
telemt_me_single_endpoint_shadow_rotate_total 701
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 30282
telemt_desync_full_logged_total 8943
telemt_desync_suppressed_total 21339
telemt_desync_frames_bucket_total{bucket="1_2"} 6637
telemt_desync_frames_bucket_total{bucket="3_10"} 13433
telemt_desync_frames_bucket_total{bucket="gt_10"} 10212
telemt_pool_swap_total 92
telemt_pool_force_close_total 3105
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 703
telemt_me_draining_writers_reap_progress_total 27843
telemt_me_writer_removed_unexpected_total 1817
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3796
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25608
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2598
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 507
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24738
telemt_me_writer_teardown_success_total{mode="normal"} 29404
telemt_me_writer_teardown_noop_total 27869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57273
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 205.867052
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57273
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 703
telemt_me_refill_failed_total 3519
telemt_me_writer_restored_same_endpoint_total 1357
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14245
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 16096870
telemt_user_connections_current{user="hello"} 2973
telemt_user_octets_from_client{user="hello"} 163879495002 (152.62 GB)
telemt_user_octets_to_client{user="hello"} 1014175878326 (944.52 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1258
telemt_user_unique_ips_recent_window{user="hello"} 385
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 90253.0 (25h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5591200
telemt_connections_bad_total 528599
telemt_connections_current 1713
telemt_connections_me_current 1713
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 115250
telemt_upstream_connect_attempt_total 46027
telemt_upstream_connect_success_total 45522
telemt_upstream_connect_fail_total 420
telemt_upstream_connect_attempts_per_request{bucket="1"} 45942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19061
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 330
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 420
telemt_me_reconnect_attempts_total 11176
telemt_me_reconnect_success_total 1292
telemt_me_reader_eof_total 1223
telemt_me_idle_close_by_peer_total 1223
telemt_me_route_drop_no_conn_total 2308731
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4349020
telemt_me_endpoint_quarantine_total 554
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 673
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 21772
telemt_desync_full_logged_total 7559
telemt_desync_suppressed_total 14213
telemt_desync_frames_bucket_total{bucket="1_2"} 4149
telemt_desync_frames_bucket_total{bucket="3_10"} 8454
telemt_desync_frames_bucket_total{bucket="gt_10"} 9169
telemt_pool_swap_total 92
telemt_pool_force_close_total 2729
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 341
telemt_me_draining_writers_reap_progress_total 30487
telemt_me_writer_removed_unexpected_total 1202
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3095
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28608
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2361
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27758
telemt_me_writer_teardown_success_total{mode="normal"} 31703
telemt_me_writer_teardown_noop_total 30488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62191
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.595413
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62191
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 341
telemt_me_refill_failed_total 596
telemt_me_writer_restored_same_endpoint_total 1091
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 1512
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 4338455
telemt_user_connections_current{user="hello"} 1713
telemt_user_octets_from_client{user="hello"} 115628359681 (107.69 GB)
telemt_user_octets_to_client{user="hello"} 1764552091895 (1.60 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 724
telemt_user_unique_ips_recent_window{user="hello"} 288
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 27088.9 (7h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3364023
telemt_connections_bad_total 122287
telemt_connections_current 2578
telemt_connections_me_current 2578
telemt_handshake_timeouts_total 1417566
telemt_upstream_connect_attempt_total 8936
telemt_upstream_connect_success_total 8821
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 8930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_reconnect_attempts_total 2260
telemt_me_reconnect_success_total 284
telemt_me_reader_eof_total 226
telemt_me_idle_close_by_peer_total 226
telemt_me_route_drop_no_conn_total 952992
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1610060
telemt_me_endpoint_quarantine_total 129
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 200
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
telemt_me_writers_active_current 42
telemt_me_writers_warm_current 31
telemt_desync_total 8939
telemt_desync_full_logged_total 2989
telemt_desync_suppressed_total 5950
telemt_desync_frames_bucket_total{bucket="1_2"} 1608
telemt_desync_frames_bucket_total{bucket="3_10"} 3419
telemt_desync_frames_bucket_total{bucket="gt_10"} 3912
telemt_pool_swap_total 28
telemt_pool_force_close_total 905
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 84
telemt_me_draining_writers_reap_progress_total 7763
telemt_me_writer_removed_unexpected_total 243
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 707
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7307
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 793
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 112
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6858
telemt_me_writer_teardown_success_total{mode="normal"} 8014
telemt_me_writer_teardown_noop_total 7764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 15637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 15686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 15778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 15778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 15778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 15778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 15778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 15778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 15778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 15778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 15778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 15778
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.358948
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 15778
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 84
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 231
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 192
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1605525
telemt_user_connections_current{user="hello"} 2578
telemt_user_octets_from_client{user="hello"} 46728167332 (43.52 GB)
telemt_user_octets_to_client{user="hello"} 684078972048 (637.10 GB)
telemt_user_unique_ips_current{user="hello"} 1163
telemt_user_unique_ips_recent_window{user="hello"} 269
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 8059.9 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107156
telemt_connections_bad_total 1208
telemt_connections_current 573
telemt_connections_me_current 573
telemt_handshake_timeouts_total 3087
telemt_upstream_connect_attempt_total 3416
telemt_upstream_connect_success_total 3407
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 3415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1967
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 73
telemt_me_reconnect_success_total 42
telemt_me_reader_eof_total 42
telemt_me_idle_close_by_peer_total 42
telemt_me_route_drop_no_conn_total 30079
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91966
telemt_me_endpoint_quarantine_total 55
telemt_me_single_endpoint_shadow_rotate_total 69
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
telemt_me_writers_active_current 45
telemt_desync_total 859
telemt_desync_full_logged_total 203
telemt_desync_suppressed_total 656
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 292
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 8
telemt_pool_force_close_total 217
telemt_me_writer_close_signal_drop_total 11
telemt_me_draining_writers_reap_progress_total 2976
telemt_me_writer_removed_unexpected_total 42
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 198
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2820
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2759
telemt_me_writer_teardown_success_total{mode="normal"} 3018
telemt_me_writer_teardown_noop_total 2976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5994
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.505961
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5994
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 11
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 91828
telemt_user_connections_current{user="hello"} 573
telemt_user_octets_from_client{user="hello"} 2101376176 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 60118658412 (55.99 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 90257.3 (25h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6656605
telemt_connections_bad_total 671724
telemt_connections_current 2429
telemt_connections_me_current 2429
telemt_handshake_timeouts_total 192190
telemt_upstream_connect_attempt_total 34163
telemt_upstream_connect_success_total 34027
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 34126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17123
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_reconnect_attempts_total 1415
telemt_me_reconnect_success_total 719
telemt_me_reader_eof_total 695
telemt_me_idle_close_by_peer_total 695
telemt_me_route_drop_no_conn_total 2040070
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5093085
telemt_me_endpoint_quarantine_total 601
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 688
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
telemt_me_writers_active_current 43
telemt_desync_total 19554
telemt_desync_full_logged_total 6516
telemt_desync_suppressed_total 13038
telemt_desync_frames_bucket_total{bucket="1_2"} 4760
telemt_desync_frames_bucket_total{bucket="3_10"} 7150
telemt_desync_frames_bucket_total{bucket="gt_10"} 7644
telemt_pool_swap_total 100
telemt_pool_force_close_total 2740
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 30695
telemt_me_writer_removed_unexpected_total 676
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2491
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28889
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2655
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27955
telemt_me_writer_teardown_success_total{mode="normal"} 31380
telemt_me_writer_teardown_noop_total 30697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62077
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.134183
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62077
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 643
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 5068715
telemt_user_connections_current{user="hello"} 2429
telemt_user_octets_from_client{user="hello"} 101927601636 (94.93 GB)
telemt_user_octets_to_client{user="hello"} 2375465595440 (2.16 TB)
telemt_user_unique_ips_current{user="hello"} 978
telemt_user_unique_ips_recent_window{user="hello"} 282
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 90254.0 (25h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5670275
telemt_connections_bad_total 536803
telemt_connections_current 2789
telemt_connections_me_current 2789
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 161440
telemt_upstream_connect_attempt_total 50389
telemt_upstream_connect_success_total 50015
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 50330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18943
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_reconnect_attempts_total 4586
telemt_me_reconnect_success_total 1007
telemt_me_reader_eof_total 896
telemt_me_idle_close_by_peer_total 896
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2096520
telemt_me_route_drop_channel_closed_total 188
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4462117
telemt_me_endpoint_quarantine_total 709
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 686
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
telemt_desync_total 18125
telemt_desync_full_logged_total 6125
telemt_desync_suppressed_total 12000
telemt_desync_frames_bucket_total{bucket="1_2"} 4471
telemt_desync_frames_bucket_total{bucket="3_10"} 6646
telemt_desync_frames_bucket_total{bucket="gt_10"} 7008
telemt_pool_swap_total 98
telemt_pool_force_close_total 2682
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 346
telemt_me_draining_writers_reap_progress_total 29745
telemt_me_writer_removed_unexpected_total 907
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2977
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27717
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2474
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 208
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27063
telemt_me_writer_teardown_success_total{mode="normal"} 30694
telemt_me_writer_teardown_noop_total 29749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60443
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.155848
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60443
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 346
telemt_me_refill_failed_total 204
telemt_me_writer_restored_same_endpoint_total 776
telemt_me_writer_restored_fallback_total 48
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 4465833
telemt_user_connections_current{user="hello"} 2789
telemt_user_octets_from_client{user="hello"} 85132909101 (79.29 GB)
telemt_user_octets_to_client{user="hello"} 1898001810112 (1.73 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1038
telemt_user_unique_ips_recent_window{user="hello"} 331
```
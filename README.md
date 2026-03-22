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

# Server Metrics 2026-03-22 01:54:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 17314.9 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249815
telemt_connections_bad_total 17975
telemt_connections_current 633
telemt_connections_me_current 633
telemt_handshake_timeouts_total 14413
telemt_upstream_connect_attempt_total 7262
telemt_upstream_connect_success_total 7261
telemt_upstream_connect_attempts_per_request{bucket="1"} 7261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4600
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 239
telemt_me_reconnect_success_total 114
telemt_me_reader_eof_total 113
telemt_me_idle_close_by_peer_total 113
telemt_me_route_drop_no_conn_total 46280
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 203735
telemt_me_endpoint_quarantine_total 144
telemt_me_single_endpoint_shadow_rotate_total 150
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
telemt_me_writers_active_current 45
telemt_desync_total 1818
telemt_desync_full_logged_total 496
telemt_desync_suppressed_total 1322
telemt_desync_frames_bucket_total{bucket="1_2"} 581
telemt_desync_frames_bucket_total{bucket="3_10"} 662
telemt_desync_frames_bucket_total{bucket="gt_10"} 575
telemt_pool_swap_total 19
telemt_pool_force_close_total 494
telemt_me_writer_close_signal_drop_total 33
telemt_me_draining_writers_reap_progress_total 6535
telemt_me_writer_removed_unexpected_total 113
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 457
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6181
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 489
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6041
telemt_me_writer_teardown_success_total{mode="normal"} 6638
telemt_me_writer_teardown_noop_total 6536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13174
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.173714
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13174
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 33
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 104
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 203371
telemt_user_connections_current{user="hello"} 633
telemt_user_octets_from_client{user="hello"} 2173180268 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 69867313152 (65.07 GB)
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 30681.1 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 752301
telemt_connections_bad_total 43323
telemt_connections_current 835
telemt_connections_me_current 835
telemt_handshake_timeouts_total 27931
telemt_upstream_connect_attempt_total 14048
telemt_upstream_connect_success_total 13819
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 14026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7684
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_reconnect_attempts_total 1162
telemt_me_reconnect_success_total 431
telemt_me_reader_eof_total 382
telemt_me_idle_close_by_peer_total 382
telemt_me_route_drop_no_conn_total 336647
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 601225
telemt_me_endpoint_quarantine_total 283
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 247
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 21
telemt_desync_total 2637
telemt_desync_full_logged_total 1506
telemt_desync_suppressed_total 1131
telemt_desync_frames_bucket_total{bucket="1_2"} 561
telemt_desync_frames_bucket_total{bucket="3_10"} 999
telemt_desync_frames_bucket_total{bucket="gt_10"} 1077
telemt_pool_swap_total 32
telemt_pool_force_close_total 884
telemt_me_writer_close_signal_drop_total 61
telemt_me_draining_writers_reap_progress_total 12421
telemt_me_writer_removed_unexpected_total 363
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1045
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11745
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 862
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11537
telemt_me_writer_teardown_success_total{mode="normal"} 12790
telemt_me_writer_teardown_noop_total 12421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25211
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.506838
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25211
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 61
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 317
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 600345
telemt_user_connections_current{user="hello"} 835
telemt_user_octets_from_client{user="hello"} 9947824184 (9.26 GB)
telemt_user_octets_to_client{user="hello"} 215302871608 (200.52 GB)
telemt_user_unique_ips_current{user="hello"} 557
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 105541.0 (29h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7656165
telemt_connections_bad_total 621070
telemt_connections_current 1133
telemt_connections_me_current 1133
telemt_handshake_timeouts_total 251224
telemt_upstream_connect_attempt_total 38936
telemt_upstream_connect_success_total 38863
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 38870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21071
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1555
telemt_me_reconnect_success_total 793
telemt_me_reader_eof_total 804
telemt_me_idle_close_by_peer_total 804
telemt_me_route_drop_no_conn_total 4525334
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6208483
telemt_me_endpoint_quarantine_total 681
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 788
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 26249
telemt_desync_full_logged_total 8677
telemt_desync_suppressed_total 17572
telemt_desync_frames_bucket_total{bucket="1_2"} 5649
telemt_desync_frames_bucket_total{bucket="3_10"} 10240
telemt_desync_frames_bucket_total{bucket="gt_10"} 10360
telemt_pool_swap_total 114
telemt_pool_force_close_total 3810
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 598
telemt_me_draining_writers_reap_progress_total 35528
telemt_me_writer_removed_unexpected_total 773
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2976
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32869
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3571
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31718
telemt_me_writer_teardown_success_total{mode="normal"} 35845
telemt_me_writer_teardown_noop_total 35572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71417
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 157.440275
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71417
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 598
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 706
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 6200683
telemt_user_connections_current{user="hello"} 1133
telemt_user_octets_from_client{user="hello"} 105742121092 (98.48 GB)
telemt_user_octets_to_client{user="hello"} 2057232363656 (1.87 TB)
telemt_user_unique_ips_current{user="hello"} 586
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 105542.4 (29h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6312953
telemt_connections_bad_total 584574
telemt_connections_current 1409
telemt_connections_me_current 1409
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 209191
telemt_upstream_connect_attempt_total 42956
telemt_upstream_connect_success_total 42570
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 42759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20808
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1916
telemt_me_reconnect_success_total 863
telemt_me_reader_eof_total 833
telemt_me_idle_close_by_peer_total 833
telemt_me_route_drop_no_conn_total 2247082
telemt_me_route_drop_channel_closed_total 257
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4727377
telemt_me_endpoint_quarantine_total 658
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 810
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22442
telemt_desync_full_logged_total 7623
telemt_desync_suppressed_total 14819
telemt_desync_frames_bucket_total{bucket="1_2"} 5408
telemt_desync_frames_bucket_total{bucket="3_10"} 8711
telemt_desync_frames_bucket_total{bucket="gt_10"} 8323
telemt_pool_swap_total 115
telemt_pool_force_close_total 3444
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 358
telemt_me_draining_writers_reap_progress_total 34040
telemt_me_writer_removed_unexpected_total 818
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2886
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31909
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3231
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30596
telemt_me_writer_teardown_success_total{mode="normal"} 34795
telemt_me_writer_teardown_noop_total 34046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68841
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.255038
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68841
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 358
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 754
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 4649624
telemt_user_connections_current{user="hello"} 1409
telemt_user_octets_from_client{user="hello"} 139689166661 (130.10 GB)
telemt_user_octets_to_client{user="hello"} 2187764561407 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 660
telemt_user_unique_ips_recent_window{user="hello"} 325
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 105506.5 (29h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6196753
telemt_connections_bad_total 545647
telemt_connections_current 1180
telemt_connections_me_current 1180
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 199682
telemt_upstream_connect_attempt_total 49255
telemt_upstream_connect_success_total 48902
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 49038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22190
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 434
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1062
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1957
telemt_me_reconnect_success_total 882
telemt_me_reader_eof_total 826
telemt_me_idle_close_by_peer_total 826
telemt_me_route_drop_no_conn_total 2139933
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4620241
telemt_me_endpoint_quarantine_total 736
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 789
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 22267
telemt_desync_full_logged_total 7468
telemt_desync_suppressed_total 14799
telemt_desync_frames_bucket_total{bucket="1_2"} 5445
telemt_desync_frames_bucket_total{bucket="3_10"} 8532
telemt_desync_frames_bucket_total{bucket="gt_10"} 8290
telemt_pool_swap_total 114
telemt_pool_force_close_total 3314
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 379
telemt_me_draining_writers_reap_progress_total 35404
telemt_me_writer_removed_unexpected_total 799
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2931
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33285
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3099
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32090
telemt_me_writer_teardown_success_total{mode="normal"} 36216
telemt_me_writer_teardown_noop_total 35415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71631
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.756179
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71631
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 379
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 766
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4615921
telemt_user_connections_current{user="hello"} 1180
telemt_user_octets_from_client{user="hello"} 133049321883 (123.91 GB)
telemt_user_octets_to_client{user="hello"} 2108249096763 (1.92 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 569
telemt_user_unique_ips_recent_window{user="hello"} 374
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 105545.8 (29h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20285757
telemt_connections_bad_total 1579065
telemt_connections_current 1805
telemt_connections_me_current 1805
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 597054
telemt_upstream_connect_attempt_total 194292
telemt_upstream_connect_success_total 176357
telemt_upstream_connect_fail_total 16222
telemt_upstream_connect_attempts_per_request{bucket="1"} 192579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41816
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8911
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16222
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64817
telemt_me_reconnect_success_total 2284
telemt_me_reader_eof_total 1423
telemt_me_idle_close_by_peer_total 1422
telemt_me_route_drop_no_conn_total 39491226
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16431182
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 828
telemt_me_single_endpoint_outage_enter_total 133
telemt_me_single_endpoint_outage_exit_total 133
telemt_me_single_endpoint_outage_reconnect_attempt_total 283
telemt_me_single_endpoint_outage_reconnect_success_total 68
telemt_me_single_endpoint_quarantine_bypass_total 283
telemt_me_single_endpoint_shadow_rotate_total 825
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 62
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
telemt_desync_total 31843
telemt_desync_full_logged_total 9522
telemt_desync_suppressed_total 22321
telemt_desync_frames_bucket_total{bucket="1_2"} 6899
telemt_desync_frames_bucket_total{bucket="3_10"} 14131
telemt_desync_frames_bucket_total{bucket="gt_10"} 10813
telemt_pool_swap_total 109
telemt_pool_force_close_total 3574
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 790
telemt_me_draining_writers_reap_progress_total 32953
telemt_me_writer_removed_unexpected_total 2124
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4475
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30340
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3051
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 523
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29379
telemt_me_writer_teardown_success_total{mode="normal"} 34815
telemt_me_writer_teardown_noop_total 32979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67794
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 214.625287
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67794
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 790
telemt_me_refill_failed_total 3801
telemt_me_writer_restored_same_endpoint_total 1565
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 538
telemt_user_connections_total{user="hello"} 16560730
telemt_user_connections_current{user="hello"} 1805
telemt_user_octets_from_client{user="hello"} 209361333154 (194.98 GB)
telemt_user_octets_to_client{user="hello"} 1175728041987 (1.07 TB)
telemt_user_msgs_from_client{user="hello"} 373576
telemt_user_msgs_to_client{user="hello"} 663916
telemt_user_unique_ips_current{user="hello"} 865
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 105513.3 (29h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5960083
telemt_connections_bad_total 558589
telemt_connections_current 968
telemt_connections_me_current 968
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 124421
telemt_upstream_connect_attempt_total 57653
telemt_upstream_connect_success_total 56978
telemt_upstream_connect_fail_total 578
telemt_upstream_connect_attempts_per_request{bucket="1"} 57556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23173
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 578
telemt_me_reconnect_attempts_total 69628
telemt_me_reconnect_success_total 1768
telemt_me_reader_eof_total 1546
telemt_me_idle_close_by_peer_total 1545
telemt_me_route_drop_no_conn_total 2379843
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4651369
telemt_me_endpoint_quarantine_total 714
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 795
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 23258
telemt_desync_full_logged_total 8176
telemt_desync_suppressed_total 15082
telemt_desync_frames_bucket_total{bucket="1_2"} 4422
telemt_desync_frames_bucket_total{bucket="3_10"} 9001
telemt_desync_frames_bucket_total{bucket="gt_10"} 9835
telemt_pool_swap_total 109
telemt_pool_force_close_total 3157
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 390
telemt_me_draining_writers_reap_progress_total 36978
telemt_me_writer_removed_unexpected_total 1585
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3842
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34751
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2756
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33821
telemt_me_writer_teardown_success_total{mode="normal"} 38593
telemt_me_writer_teardown_noop_total 36979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75572
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.103633
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75572
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 390
telemt_me_refill_failed_total 4206
telemt_me_writer_restored_same_endpoint_total 1480
telemt_me_writer_restored_fallback_total 33
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 4644287
telemt_user_connections_current{user="hello"} 968
telemt_user_octets_from_client{user="hello"} 123660377888 (115.17 GB)
telemt_user_octets_to_client{user="hello"} 1897677990818 (1.73 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 429
telemt_user_unique_ips_recent_window{user="hello"} 386
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 42349.1 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3851070
telemt_connections_bad_total 139564
telemt_connections_current 1483
telemt_connections_me_current 1483
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1578462
telemt_upstream_connect_attempt_total 26026
telemt_upstream_connect_success_total 25857
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 26019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_reconnect_attempts_total 45780
telemt_me_reconnect_success_total 944
telemt_me_reader_eof_total 622
telemt_me_idle_close_by_peer_total 622
telemt_me_route_drop_no_conn_total 1014024
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1882969
telemt_me_endpoint_quarantine_total 312
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 321
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 33
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 8
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10308
telemt_desync_full_logged_total 3555
telemt_desync_suppressed_total 6753
telemt_desync_frames_bucket_total{bucket="1_2"} 1836
telemt_desync_frames_bucket_total{bucket="3_10"} 3959
telemt_desync_frames_bucket_total{bucket="gt_10"} 4513
telemt_pool_swap_total 45
telemt_pool_force_close_total 1408
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 131
telemt_me_draining_writers_reap_progress_total 15189
telemt_me_writer_removed_unexpected_total 699
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1454
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14457
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1202
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13781
telemt_me_writer_teardown_success_total{mode="normal"} 15911
telemt_me_writer_teardown_noop_total 15191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31102
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.338678
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31102
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 131
telemt_me_refill_failed_total 2605
telemt_me_writer_restored_same_endpoint_total 845
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1886649
telemt_user_connections_current{user="hello"} 1483
telemt_user_octets_from_client{user="hello"} 53588043724 (49.91 GB)
telemt_user_octets_to_client{user="hello"} 804490801978 (749.24 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 780
telemt_user_unique_ips_recent_window{user="hello"} 288
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 23320.1 (6h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185432
telemt_connections_bad_total 1622
telemt_connections_current 317
telemt_connections_me_current 317
telemt_handshake_timeouts_total 5137
telemt_upstream_connect_attempt_total 11116
telemt_upstream_connect_success_total 11091
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 11114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6319
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 231
telemt_me_reconnect_success_total 145
telemt_me_reader_eof_total 148
telemt_me_idle_close_by_peer_total 148
telemt_me_route_drop_no_conn_total 50663
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163193
telemt_me_endpoint_quarantine_total 231
telemt_me_single_endpoint_shadow_rotate_total 204
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 1008
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 754
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 250
telemt_pool_swap_total 25
telemt_pool_force_close_total 559
telemt_me_writer_close_signal_drop_total 22
telemt_me_draining_writers_reap_progress_total 10010
telemt_me_writer_removed_unexpected_total 143
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 654
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9504
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 557
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9451
telemt_me_writer_teardown_success_total{mode="normal"} 10158
telemt_me_writer_teardown_noop_total 10010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 20158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 20168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 20168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 20168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 20168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 20168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 20168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 20168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 20168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 20168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 20168
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.949135
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 20168
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 22
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 134
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 162892
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 2974237460 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 95559445156 (89.00 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 105517.6 (29h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7242745
telemt_connections_bad_total 737347
telemt_connections_current 1547
telemt_connections_me_current 1547
telemt_handshake_timeouts_total 206157
telemt_upstream_connect_attempt_total 41179
telemt_upstream_connect_success_total 41025
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 41142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20658
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_reconnect_attempts_total 1551
telemt_me_reconnect_success_total 834
telemt_me_reader_eof_total 816
telemt_me_idle_close_by_peer_total 816
telemt_me_route_drop_no_conn_total 2117203
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5430862
telemt_me_endpoint_quarantine_total 733
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 811
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_me_writers_active_current 46
telemt_desync_total 21332
telemt_desync_full_logged_total 6998
telemt_desync_suppressed_total 14334
telemt_desync_frames_bucket_total{bucket="1_2"} 5361
telemt_desync_frames_bucket_total{bucket="3_10"} 7722
telemt_desync_frames_bucket_total{bucket="gt_10"} 8249
telemt_pool_swap_total 117
telemt_pool_force_close_total 3149
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 382
telemt_me_draining_writers_reap_progress_total 37115
telemt_me_writer_removed_unexpected_total 787
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2936
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34985
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3061
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33966
telemt_me_writer_teardown_success_total{mode="normal"} 37921
telemt_me_writer_teardown_noop_total 37117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75038
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.619552
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75038
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 382
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 744
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 5405890
telemt_user_connections_current{user="hello"} 1547
telemt_user_octets_from_client{user="hello"} 108700382424 (101.24 GB)
telemt_user_octets_to_client{user="hello"} 2522727205776 (2.29 TB)
telemt_user_unique_ips_current{user="hello"} 671
telemt_user_unique_ips_recent_window{user="hello"} 495
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 105514.3 (29h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6239242
telemt_connections_bad_total 615502
telemt_connections_current 1216
telemt_connections_me_current 1216
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 171417
telemt_upstream_connect_attempt_total 56943
telemt_upstream_connect_success_total 56517
telemt_upstream_connect_fail_total 367
telemt_upstream_connect_attempts_per_request{bucket="1"} 56884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22305
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 367
telemt_me_reconnect_attempts_total 5541
telemt_me_reconnect_success_total 1144
telemt_me_reader_eof_total 1027
telemt_me_idle_close_by_peer_total 1027
telemt_me_seq_mismatch_total 46
telemt_me_route_drop_no_conn_total 2170790
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4798278
telemt_me_endpoint_quarantine_total 841
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 808
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 19983
telemt_desync_full_logged_total 6640
telemt_desync_suppressed_total 13343
telemt_desync_frames_bucket_total{bucket="1_2"} 5102
telemt_desync_frames_bucket_total{bucket="3_10"} 7278
telemt_desync_frames_bucket_total{bucket="gt_10"} 7603
telemt_pool_swap_total 115
telemt_pool_force_close_total 3105
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 376
telemt_me_draining_writers_reap_progress_total 35666
telemt_me_writer_removed_unexpected_total 1040
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3450
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33304
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32561
telemt_me_writer_teardown_success_total{mode="normal"} 36754
telemt_me_writer_teardown_noop_total 35670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72424
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.997562
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72424
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 376
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 891
telemt_me_writer_restored_fallback_total 59
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4801381
telemt_user_connections_current{user="hello"} 1216
telemt_user_octets_from_client{user="hello"} 90202837501 (84.01 GB)
telemt_user_octets_to_client{user="hello"} 2052768587152 (1.87 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 563
telemt_user_unique_ips_recent_window{user="hello"} 457
```
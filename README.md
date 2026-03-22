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

# Server Metrics 2026-03-22 05:55:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 31734.0 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 565595
telemt_connections_bad_total 36691
telemt_connections_current 1103
telemt_connections_me_current 1103
telemt_handshake_timeouts_total 29050
telemt_upstream_connect_attempt_total 13035
telemt_upstream_connect_success_total 13034
telemt_upstream_connect_attempts_per_request{bucket="1"} 13034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8441
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 354
telemt_me_reconnect_success_total 204
telemt_me_reader_eof_total 200
telemt_me_idle_close_by_peer_total 200
telemt_me_route_drop_no_conn_total 127206
telemt_me_route_drop_channel_closed_total 43
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 467338
telemt_me_endpoint_quarantine_total 239
telemt_me_single_endpoint_shadow_rotate_total 265
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_desync_total 4087
telemt_desync_full_logged_total 1139
telemt_desync_suppressed_total 2948
telemt_desync_frames_bucket_total{bucket="1_2"} 1365
telemt_desync_frames_bucket_total{bucket="3_10"} 1550
telemt_desync_frames_bucket_total{bucket="gt_10"} 1172
telemt_pool_swap_total 35
telemt_pool_force_close_total 935
telemt_me_writer_close_signal_drop_total 85
telemt_me_draining_writers_reap_progress_total 11797
telemt_me_writer_removed_unexpected_total 197
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 812
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11170
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 925
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10862
telemt_me_writer_teardown_success_total{mode="normal"} 11982
telemt_me_writer_teardown_noop_total 11798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 23352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 23575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 23713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 23776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 23780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 23780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 23780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 23780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 23780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 23780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 23780
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.447149
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 23780
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 85
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 185
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 466308
telemt_user_connections_current{user="hello"} 1103
telemt_user_octets_from_client{user="hello"} 6246549704 (5.82 GB)
telemt_user_octets_to_client{user="hello"} 168440826320 (156.87 GB)
telemt_user_unique_ips_current{user="hello"} 457
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 45100.1 (12h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1030644
telemt_connections_bad_total 89114
telemt_connections_current 1380
telemt_connections_me_current 1380
telemt_handshake_timeouts_total 34489
telemt_upstream_connect_attempt_total 23893
telemt_upstream_connect_success_total 23563
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 23861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_reconnect_attempts_total 1799
telemt_me_reconnect_success_total 645
telemt_me_reader_eof_total 569
telemt_me_idle_close_by_peer_total 569
telemt_me_route_drop_no_conn_total 386160
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 791398
telemt_me_endpoint_quarantine_total 417
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 364
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
telemt_me_writers_warm_current 34
telemt_desync_total 3370
telemt_desync_full_logged_total 1958
telemt_desync_suppressed_total 1412
telemt_desync_frames_bucket_total{bucket="1_2"} 706
telemt_desync_frames_bucket_total{bucket="3_10"} 1298
telemt_desync_frames_bucket_total{bucket="gt_10"} 1366
telemt_pool_swap_total 48
telemt_pool_force_close_total 1259
telemt_me_writer_close_signal_drop_total 96
telemt_me_draining_writers_reap_progress_total 18545
telemt_me_writer_removed_unexpected_total 543
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1577
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17524
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1237
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17286
telemt_me_writer_teardown_success_total{mode="normal"} 19101
telemt_me_writer_teardown_noop_total 18545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37646
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.184917
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37646
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 96
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 484
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 793085
telemt_user_connections_current{user="hello"} 1380
telemt_user_octets_from_client{user="hello"} 13100599923 (12.20 GB)
telemt_user_octets_to_client{user="hello"} 292724209286 (272.62 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 869
telemt_user_unique_ips_recent_window{user="hello"} 282
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 119960.0 (33h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8389326
telemt_connections_bad_total 734732
telemt_connections_current 2631
telemt_connections_me_current 2631
telemt_handshake_timeouts_total 272068
telemt_upstream_connect_attempt_total 44649
telemt_upstream_connect_success_total 44571
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 44579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24194
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1705
telemt_me_reconnect_success_total 871
telemt_me_reader_eof_total 882
telemt_me_idle_close_by_peer_total 882
telemt_me_route_drop_no_conn_total 4666673
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6712543
telemt_me_endpoint_quarantine_total 764
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 902
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
telemt_desync_total 28402
telemt_desync_full_logged_total 9462
telemt_desync_suppressed_total 18940
telemt_desync_frames_bucket_total{bucket="1_2"} 6155
telemt_desync_frames_bucket_total{bucket="3_10"} 11091
telemt_desync_frames_bucket_total{bucket="gt_10"} 11156
telemt_pool_swap_total 130
telemt_pool_force_close_total 4293
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 648
telemt_me_draining_writers_reap_progress_total 40781
telemt_me_writer_removed_unexpected_total 850
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3372
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37763
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4044
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 249
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36488
telemt_me_writer_teardown_success_total{mode="normal"} 41135
telemt_me_writer_teardown_noop_total 40825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81960
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 169.514488
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81960
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 648
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 778
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 6703792
telemt_user_connections_current{user="hello"} 2631
telemt_user_octets_from_client{user="hello"} 114450073984 (106.59 GB)
telemt_user_octets_to_client{user="hello"} 2285716860556 (2.08 TB)
telemt_user_unique_ips_current{user="hello"} 1094
telemt_user_unique_ips_recent_window{user="hello"} 464
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 119961.4 (33h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6902853
telemt_connections_bad_total 616600
telemt_connections_current 2931
telemt_connections_me_current 2931
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 231649
telemt_upstream_connect_attempt_total 48592
telemt_upstream_connect_success_total 48190
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 48395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23807
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 558
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2057
telemt_me_reconnect_success_total 933
telemt_me_reader_eof_total 912
telemt_me_idle_close_by_peer_total 912
telemt_me_route_drop_no_conn_total 2361234
telemt_me_route_drop_channel_closed_total 289
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5160562
telemt_me_endpoint_quarantine_total 761
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 924
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 23879
telemt_desync_full_logged_total 8210
telemt_desync_suppressed_total 15669
telemt_desync_frames_bucket_total{bucket="1_2"} 5719
telemt_desync_frames_bucket_total{bucket="3_10"} 9282
telemt_desync_frames_bucket_total{bucket="gt_10"} 8878
telemt_pool_swap_total 131
telemt_pool_force_close_total 3898
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 396
telemt_me_draining_writers_reap_progress_total 39193
telemt_me_writer_removed_unexpected_total 890
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3236
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36775
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3680
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35295
telemt_me_writer_teardown_success_total{mode="normal"} 40011
telemt_me_writer_teardown_noop_total 39199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79210
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 50.275018
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79210
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 396
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 814
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 5081915
telemt_user_connections_current{user="hello"} 2931
telemt_user_octets_from_client{user="hello"} 147553735509 (137.42 GB)
telemt_user_octets_to_client{user="hello"} 2435157149871 (2.21 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1146
telemt_user_unique_ips_recent_window{user="hello"} 389
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 119926.9 (33h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6737603
telemt_connections_bad_total 566608
telemt_connections_current 2681
telemt_connections_me_current 2681
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 225470
telemt_upstream_connect_attempt_total 55015
telemt_upstream_connect_success_total 54439
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 54583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25340
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 778
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 2527
telemt_me_reconnect_success_total 1091
telemt_me_reader_eof_total 1022
telemt_me_idle_close_by_peer_total 1022
telemt_me_route_drop_no_conn_total 2381709
telemt_me_route_drop_channel_closed_total 149
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5009918
telemt_me_endpoint_quarantine_total 856
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 893
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 23731
telemt_desync_full_logged_total 8066
telemt_desync_suppressed_total 15665
telemt_desync_frames_bucket_total{bucket="1_2"} 5770
telemt_desync_frames_bucket_total{bucket="3_10"} 9103
telemt_desync_frames_bucket_total{bucket="gt_10"} 8858
telemt_pool_swap_total 129
telemt_pool_force_close_total 3735
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 418
telemt_me_draining_writers_reap_progress_total 40132
telemt_me_writer_removed_unexpected_total 1012
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3478
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37682
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3488
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 247
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36397
telemt_me_writer_teardown_success_total{mode="normal"} 41160
telemt_me_writer_teardown_noop_total 40144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81304
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 37.025212
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81304
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 418
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 947
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 5004208
telemt_user_connections_current{user="hello"} 2681
telemt_user_octets_from_client{user="hello"} 138404362091 (128.90 GB)
telemt_user_octets_to_client{user="hello"} 2287217133963 (2.08 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1172
telemt_user_unique_ips_recent_window{user="hello"} 338
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 119964.5 (33h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21529755
telemt_connections_bad_total 1825096
telemt_connections_current 3835
telemt_connections_me_current 3835
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 655529
telemt_upstream_connect_attempt_total 210870
telemt_upstream_connect_success_total 192190
telemt_upstream_connect_fail_total 16763
telemt_upstream_connect_attempts_per_request{bucket="1"} 208953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47094
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1954
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9878
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16763
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65504
telemt_me_reconnect_success_total 2553
telemt_me_reader_eof_total 1597
telemt_me_idle_close_by_peer_total 1596
telemt_me_route_drop_no_conn_total 40657624
telemt_me_route_drop_channel_closed_total 130
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17303743
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 936
telemt_me_single_endpoint_outage_enter_total 153
telemt_me_single_endpoint_outage_exit_total 153
telemt_me_single_endpoint_outage_reconnect_attempt_total 322
telemt_me_single_endpoint_outage_reconnect_success_total 80
telemt_me_single_endpoint_quarantine_bypass_total 322
telemt_me_single_endpoint_shadow_rotate_total 943
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 70
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
telemt_desync_total 33397
telemt_desync_full_logged_total 10060
telemt_desync_suppressed_total 23337
telemt_desync_frames_bucket_total{bucket="1_2"} 7320
telemt_desync_frames_bucket_total{bucket="3_10"} 14829
telemt_desync_frames_bucket_total{bucket="gt_10"} 11248
telemt_pool_swap_total 124
telemt_pool_force_close_total 3977
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 878
telemt_me_draining_writers_reap_progress_total 37755
telemt_me_writer_removed_unexpected_total 2375
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5108
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34771
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3416
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 561
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33778
telemt_me_writer_teardown_success_total{mode="normal"} 39879
telemt_me_writer_teardown_noop_total 37782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77661
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 219.256153
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77661
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 878
telemt_me_refill_failed_total 3814
telemt_me_writer_restored_same_endpoint_total 1735
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 618
telemt_user_connections_total{user="hello"} 17443050
telemt_user_connections_current{user="hello"} 3835
telemt_user_octets_from_client{user="hello"} 257026909721 (239.37 GB)
telemt_user_octets_to_client{user="hello"} 1347414343811 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 409002
telemt_user_msgs_to_client{user="hello"} 794272
telemt_user_unique_ips_current{user="hello"} 1573
telemt_user_unique_ips_recent_window{user="hello"} 704
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 119931.9 (33h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6499975
telemt_connections_bad_total 615870
telemt_connections_current 2224
telemt_connections_me_current 2224
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 136459
telemt_upstream_connect_attempt_total 63616
telemt_upstream_connect_success_total 62879
telemt_upstream_connect_fail_total 631
telemt_upstream_connect_attempts_per_request{bucket="1"} 63510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26320
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 631
telemt_me_reconnect_attempts_total 69946
telemt_me_reconnect_success_total 1899
telemt_me_reader_eof_total 1675
telemt_me_idle_close_by_peer_total 1674
telemt_me_route_drop_no_conn_total 2497480
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5062053
telemt_me_endpoint_quarantine_total 811
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 910
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
telemt_me_writers_active_current 43
telemt_desync_total 25157
telemt_desync_full_logged_total 8814
telemt_desync_suppressed_total 16343
telemt_desync_frames_bucket_total{bucket="1_2"} 4982
telemt_desync_frames_bucket_total{bucket="3_10"} 9707
telemt_desync_frames_bucket_total{bucket="gt_10"} 10468
telemt_pool_swap_total 125
telemt_pool_force_close_total 3580
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 422
telemt_me_draining_writers_reap_progress_total 42310
telemt_me_writer_removed_unexpected_total 1708
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4264
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39789
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3174
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 406
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38730
telemt_me_writer_teardown_success_total{mode="normal"} 44053
telemt_me_writer_teardown_noop_total 42311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86364
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.638793
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86364
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 422
telemt_me_refill_failed_total 4215
telemt_me_writer_restored_same_endpoint_total 1586
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 5053966
telemt_user_connections_current{user="hello"} 2224
telemt_user_octets_from_client{user="hello"} 130460409664 (121.50 GB)
telemt_user_octets_to_client{user="hello"} 2107122055854 (1.92 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 923
telemt_user_unique_ips_recent_window{user="hello"} 407
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 56767.8 (15h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4550713
telemt_connections_bad_total 187320
telemt_connections_current 3199
telemt_connections_me_current 3199
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1802253
telemt_upstream_connect_attempt_total 32413
telemt_upstream_connect_success_total 32196
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 32405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12608
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_reconnect_attempts_total 46106
telemt_me_reconnect_success_total 1040
telemt_me_reader_eof_total 731
telemt_me_idle_close_by_peer_total 731
telemt_me_route_drop_no_conn_total 1132572
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2252894
telemt_me_endpoint_quarantine_total 402
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 437
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
telemt_me_writers_warm_current 23
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 12054
telemt_desync_full_logged_total 4143
telemt_desync_suppressed_total 7911
telemt_desync_frames_bucket_total{bucket="1_2"} 2322
telemt_desync_frames_bucket_total{bucket="3_10"} 4612
telemt_desync_frames_bucket_total{bucket="gt_10"} 5120
telemt_pool_swap_total 61
telemt_pool_force_close_total 1788
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 159
telemt_me_draining_writers_reap_progress_total 20958
telemt_me_writer_removed_unexpected_total 801
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1783
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20006
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1578
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19170
telemt_me_writer_teardown_success_total{mode="normal"} 21789
telemt_me_writer_teardown_noop_total 20960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42749
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.703983
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42749
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 159
telemt_me_refill_failed_total 2618
telemt_me_writer_restored_same_endpoint_total 928
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2255165
telemt_user_connections_current{user="hello"} 3199
telemt_user_octets_from_client{user="hello"} 59868167192 (55.76 GB)
telemt_user_octets_to_client{user="hello"} 996711831166 (928.26 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1377
telemt_user_unique_ips_recent_window{user="hello"} 372
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 37738.8 (10h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271734
telemt_connections_bad_total 2000
telemt_connections_current 539
telemt_connections_me_current 539
telemt_handshake_timeouts_total 6809
telemt_upstream_connect_attempt_total 18164
telemt_upstream_connect_success_total 18119
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 18159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10420
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 427
telemt_me_reconnect_success_total 248
telemt_me_reader_eof_total 248
telemt_me_idle_close_by_peer_total 248
telemt_me_route_drop_no_conn_total 76952
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 243297
telemt_me_endpoint_quarantine_total 357
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 326
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1266
telemt_desync_full_logged_total 347
telemt_desync_suppressed_total 919
telemt_desync_frames_bucket_total{bucket="1_2"} 434
telemt_desync_frames_bucket_total{bucket="3_10"} 487
telemt_desync_frames_bucket_total{bucket="gt_10"} 345
telemt_pool_swap_total 41
telemt_pool_force_close_total 913
telemt_me_writer_close_signal_drop_total 35
telemt_me_draining_writers_reap_progress_total 16449
telemt_me_writer_removed_unexpected_total 237
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1050
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15647
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 911
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15536
telemt_me_writer_teardown_success_total{mode="normal"} 16697
telemt_me_writer_teardown_noop_total 16449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33146
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.274890
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33146
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 35
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 216
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 242896
telemt_user_connections_current{user="hello"} 539
telemt_user_octets_from_client{user="hello"} 4079857036 (3.80 GB)
telemt_user_octets_to_client{user="hello"} 147557501904 (137.42 GB)
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 119936.4 (33h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7883280
telemt_connections_bad_total 791963
telemt_connections_current 3097
telemt_connections_me_current 3097
telemt_handshake_timeouts_total 224055
telemt_upstream_connect_attempt_total 47240
telemt_upstream_connect_success_total 47069
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 47203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23754
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_reconnect_attempts_total 1700
telemt_me_reconnect_success_total 917
telemt_me_reader_eof_total 910
telemt_me_idle_close_by_peer_total 910
telemt_me_route_drop_no_conn_total 2231501
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5876695
telemt_me_endpoint_quarantine_total 858
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 920
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
telemt_me_writers_active_current 45
telemt_desync_total 23001
telemt_desync_full_logged_total 7582
telemt_desync_suppressed_total 15419
telemt_desync_frames_bucket_total{bucket="1_2"} 5750
telemt_desync_frames_bucket_total{bucket="3_10"} 8368
telemt_desync_frames_bucket_total{bucket="gt_10"} 8883
telemt_pool_swap_total 133
telemt_pool_force_close_total 3543
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 416
telemt_me_draining_writers_reap_progress_total 42651
telemt_me_writer_removed_unexpected_total 873
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3338
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40213
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3455
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39108
telemt_me_writer_teardown_success_total{mode="normal"} 43551
telemt_me_writer_teardown_noop_total 42653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86204
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.031964
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86204
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 416
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 820
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 5851139
telemt_user_connections_current{user="hello"} 3097
telemt_user_octets_from_client{user="hello"} 115113132204 (107.21 GB)
telemt_user_octets_to_client{user="hello"} 2741592773988 (2.49 TB)
telemt_user_unique_ips_current{user="hello"} 1199
telemt_user_unique_ips_recent_window{user="hello"} 467
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 119932.9 (33h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6848953
telemt_connections_bad_total 666192
telemt_connections_current 3292
telemt_connections_me_current 3292
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 184847
telemt_upstream_connect_attempt_total 63078
telemt_upstream_connect_success_total 62595
telemt_upstream_connect_fail_total 420
telemt_upstream_connect_attempts_per_request{bucket="1"} 63015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25354
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 420
telemt_me_reconnect_attempts_total 5850
telemt_me_reconnect_success_total 1298
telemt_me_reader_eof_total 1166
telemt_me_idle_close_by_peer_total 1166
telemt_me_seq_mismatch_total 57
telemt_me_route_drop_no_conn_total 2287280
telemt_me_route_drop_channel_closed_total 192
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5244201
telemt_me_endpoint_quarantine_total 950
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 920
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_desync_total 21944
telemt_desync_full_logged_total 7299
telemt_desync_suppressed_total 14645
telemt_desync_frames_bucket_total{bucket="1_2"} 5504
telemt_desync_frames_bucket_total{bucket="3_10"} 8013
telemt_desync_frames_bucket_total{bucket="gt_10"} 8427
telemt_pool_swap_total 131
telemt_pool_force_close_total 3491
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 420
telemt_me_draining_writers_reap_progress_total 41201
telemt_me_writer_removed_unexpected_total 1179
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3896
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38543
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3267
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 224
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37710
telemt_me_writer_teardown_success_total{mode="normal"} 42439
telemt_me_writer_teardown_noop_total 41205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83644
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.889605
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83644
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 420
telemt_me_refill_failed_total 262
telemt_me_writer_restored_same_endpoint_total 1010
telemt_me_writer_restored_fallback_total 76
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 5246666
telemt_user_connections_current{user="hello"} 3292
telemt_user_octets_from_client{user="hello"} 98258590333 (91.51 GB)
telemt_user_octets_to_client{user="hello"} 2275571863912 (2.07 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1262
telemt_user_unique_ips_recent_window{user="hello"} 538
```
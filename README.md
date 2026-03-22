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

# Server Metrics 2026-03-22 09:55:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 46123.9 (12h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1184929
telemt_connections_bad_total 64002
telemt_connections_current 1731
telemt_connections_me_current 1731
telemt_handshake_timeouts_total 54492
telemt_upstream_connect_attempt_total 17980
telemt_upstream_connect_success_total 17979
telemt_upstream_connect_attempts_per_request{bucket="1"} 17979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 543
telemt_me_reconnect_success_total 276
telemt_me_reader_eof_total 275
telemt_me_idle_close_by_peer_total 275
telemt_me_route_drop_no_conn_total 630027
telemt_me_route_drop_channel_closed_total 264
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 986746
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 326
telemt_me_single_endpoint_shadow_rotate_total 373
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 6888
telemt_desync_full_logged_total 1997
telemt_desync_suppressed_total 4891
telemt_desync_frames_bucket_total{bucket="1_2"} 2017
telemt_desync_frames_bucket_total{bucket="3_10"} 2606
telemt_desync_frames_bucket_total{bucket="gt_10"} 2265
telemt_pool_swap_total 51
telemt_pool_force_close_total 1485
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 177
telemt_me_draining_writers_reap_progress_total 16381
telemt_me_writer_removed_unexpected_total 272
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1133
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15442
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1454
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14896
telemt_me_writer_teardown_success_total{mode="normal"} 16575
telemt_me_writer_teardown_noop_total 16383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32958
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 72.701688
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32958
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 177
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 252
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 984960
telemt_user_connections_current{user="hello"} 1731
telemt_user_octets_from_client{user="hello"} 15471940436 (14.41 GB)
telemt_user_octets_to_client{user="hello"} 315722262332 (294.04 GB)
telemt_user_unique_ips_current{user="hello"} 621
telemt_user_unique_ips_recent_window{user="hello"} 588
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 59490.2 (16h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1796613
telemt_connections_bad_total 163729
telemt_connections_current 3208
telemt_connections_me_current 3208
telemt_handshake_timeouts_total 47344
telemt_upstream_connect_attempt_total 35499
telemt_upstream_connect_success_total 35029
telemt_upstream_connect_fail_total 415
telemt_upstream_connect_attempts_per_request{bucket="1"} 35444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 415
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2883
telemt_me_reconnect_success_total 1354
telemt_me_reader_eof_total 1253
telemt_me_idle_close_by_peer_total 1253
telemt_me_route_drop_no_conn_total 1011393
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1378974
telemt_me_endpoint_quarantine_total 506
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 469
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
telemt_me_writers_active_current 127
telemt_me_writers_warm_current 17
telemt_desync_total 6094
telemt_desync_full_logged_total 3497
telemt_desync_suppressed_total 2597
telemt_desync_frames_bucket_total{bucket="1_2"} 1358
telemt_desync_frames_bucket_total{bucket="3_10"} 2384
telemt_desync_frames_bucket_total{bucket="gt_10"} 2352
telemt_pool_swap_total 59
telemt_pool_force_close_total 1610
telemt_me_writer_close_signal_drop_total 135
telemt_me_draining_writers_reap_progress_total 24067
telemt_me_writer_removed_unexpected_total 1221
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2591
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22689
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1486
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22457
telemt_me_writer_teardown_success_total{mode="normal"} 25280
telemt_me_writer_teardown_noop_total 24067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49347
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.430347
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49347
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 135
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 1135
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 1385120
telemt_user_connections_current{user="hello"} 3208
telemt_user_octets_from_client{user="hello"} 20204689886 (18.82 GB)
telemt_user_octets_to_client{user="hello"} 436709115060 (406.72 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 1745
telemt_user_unique_ips_recent_window{user="hello"} 637
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 134350.1 (37h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10587311
telemt_connections_bad_total 937637
telemt_connections_current 4401
telemt_connections_me_current 4401
telemt_handshake_timeouts_total 303774
telemt_upstream_connect_attempt_total 49309
telemt_upstream_connect_success_total 49229
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 49237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26758
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2082
telemt_me_reconnect_success_total 1067
telemt_me_reader_eof_total 1058
telemt_me_idle_close_by_peer_total 1057
telemt_me_route_drop_no_conn_total 6612199
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8355575
telemt_me_endpoint_quarantine_total 857
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 1003
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
telemt_me_writers_active_current 42
telemt_desync_total 35868
telemt_desync_full_logged_total 11702
telemt_desync_suppressed_total 24166
telemt_desync_frames_bucket_total{bucket="1_2"} 7998
telemt_desync_frames_bucket_total{bucket="3_10"} 13928
telemt_desync_frames_bucket_total{bucket="gt_10"} 13942
telemt_pool_swap_total 145
telemt_pool_force_close_total 4851
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 749
telemt_me_draining_writers_reap_progress_total 44981
telemt_me_writer_removed_unexpected_total 1016
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3826
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41621
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4524
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 327
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40130
telemt_me_writer_teardown_success_total{mode="normal"} 45447
telemt_me_writer_teardown_noop_total 45025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90472
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 202.732149
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90472
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 749
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 936
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 8345162
telemt_user_connections_current{user="hello"} 4401
telemt_user_octets_from_client{user="hello"} 133673854848 (124.49 GB)
telemt_user_octets_to_client{user="hello"} 2660054532024 (2.42 TB)
telemt_user_unique_ips_current{user="hello"} 1584
telemt_user_unique_ips_recent_window{user="hello"} 842
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 134352.0 (37h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8498493
telemt_connections_bad_total 771297
telemt_connections_current 3857
telemt_connections_me_current 3857
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 266961
telemt_upstream_connect_attempt_total 55484
telemt_upstream_connect_success_total 54988
telemt_upstream_connect_fail_total 252
telemt_upstream_connect_attempts_per_request{bucket="1"} 55240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26935
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 252
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 3019
telemt_me_reconnect_success_total 1179
telemt_me_reader_eof_total 1084
telemt_me_idle_close_by_peer_total 1084
telemt_me_route_drop_no_conn_total 2939639
telemt_me_route_drop_channel_closed_total 349
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6285874
telemt_me_endpoint_quarantine_total 856
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 1036
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 28767
telemt_desync_full_logged_total 9774
telemt_desync_suppressed_total 18993
telemt_desync_frames_bucket_total{bucket="1_2"} 6955
telemt_desync_frames_bucket_total{bucket="3_10"} 11143
telemt_desync_frames_bucket_total{bucket="gt_10"} 10669
telemt_pool_swap_total 146
telemt_pool_force_close_total 4430
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 490
telemt_me_draining_writers_reap_progress_total 43330
telemt_me_writer_removed_unexpected_total 1100
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3751
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40574
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4128
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 302
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38900
telemt_me_writer_teardown_success_total{mode="normal"} 44325
telemt_me_writer_teardown_noop_total 43336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87661
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 63.336273
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87661
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 490
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 999
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 6207845
telemt_user_connections_current{user="hello"} 3857
telemt_user_octets_from_client{user="hello"} 167863471579 (156.34 GB)
telemt_user_octets_to_client{user="hello"} 2947505509906 (2.68 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1536
telemt_user_unique_ips_recent_window{user="hello"} 950
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 134315.4 (37h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8148760
telemt_connections_bad_total 687036
telemt_connections_current 4100
telemt_connections_me_current 4100
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 265651
telemt_upstream_connect_attempt_total 60043
telemt_upstream_connect_success_total 59348
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 59495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27971
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3420
telemt_me_reconnect_success_total 1461
telemt_me_reader_eof_total 1349
telemt_me_idle_close_by_peer_total 1349
telemt_me_route_drop_no_conn_total 3378997
telemt_me_route_drop_channel_closed_total 219
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6083856
telemt_me_endpoint_quarantine_total 925
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 985
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 50
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
telemt_desync_total 28414
telemt_desync_full_logged_total 9651
telemt_desync_suppressed_total 18763
telemt_desync_frames_bucket_total{bucket="1_2"} 6855
telemt_desync_frames_bucket_total{bucket="3_10"} 10915
telemt_desync_frames_bucket_total{bucket="gt_10"} 10644
telemt_pool_swap_total 142
telemt_pool_force_close_total 4324
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 510
telemt_me_draining_writers_reap_progress_total 44262
telemt_me_writer_removed_unexpected_total 1376
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4146
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41438
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3941
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 383
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39938
telemt_me_writer_teardown_success_total{mode="normal"} 45584
telemt_me_writer_teardown_noop_total 44279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89863
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.199236
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89863
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 510
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 1287
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 6076304
telemt_user_connections_current{user="hello"} 4100
telemt_user_octets_from_client{user="hello"} 153262711055 (142.74 GB)
telemt_user_octets_to_client{user="hello"} 2660154222095 (2.42 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1549
telemt_user_unique_ips_recent_window{user="hello"} 1225
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 4594.9 (1h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1924955
telemt_connections_bad_total 156104
telemt_connections_current 6597
telemt_connections_me_current 6597
telemt_handshake_timeouts_total 24137
telemt_upstream_connect_attempt_total 8249
telemt_upstream_connect_success_total 7818
telemt_upstream_connect_fail_total 339
telemt_upstream_connect_attempts_per_request{bucket="1"} 8157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1400
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2676
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 339
telemt_me_keepalive_timeout_total 188
telemt_me_reconnect_attempts_total 318
telemt_me_reconnect_success_total 116
telemt_me_reader_eof_total 65
telemt_me_idle_close_by_peer_total 65
telemt_me_route_drop_no_conn_total 4327935
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1588078
telemt_me_endpoint_quarantine_total 23
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 39
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 38
telemt_desync_total 2504
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 1876
telemt_desync_frames_bucket_total{bucket="1_2"} 480
telemt_desync_frames_bucket_total{bucket="3_10"} 940
telemt_desync_frames_bucket_total{bucket="gt_10"} 1084
telemt_pool_swap_total 3
telemt_pool_force_close_total 125
telemt_me_writer_close_signal_drop_total 59
telemt_me_draining_writers_reap_progress_total 1131
telemt_me_writer_removed_unexpected_total 109
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 187
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1053
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 80
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1006
telemt_me_writer_teardown_success_total{mode="normal"} 1240
telemt_me_writer_teardown_noop_total 1131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2371
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.580570
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2371
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 59
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 71
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1594030
telemt_user_connections_current{user="hello"} 6597
telemt_user_octets_from_client{user="hello"} 9018851002 (8.40 GB)
telemt_user_octets_to_client{user="hello"} 46944968543 (43.72 GB)
telemt_user_msgs_from_client{user="hello"} 6014
telemt_user_msgs_to_client{user="hello"} 4995
telemt_user_unique_ips_current{user="hello"} 2356
telemt_user_unique_ips_recent_window{user="hello"} 1307
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 134322.3 (37h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7754776
telemt_connections_bad_total 686684
telemt_connections_current 4703
telemt_connections_me_current 4703
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 160018
telemt_upstream_connect_attempt_total 76186
telemt_upstream_connect_success_total 75353
telemt_upstream_connect_fail_total 713
telemt_upstream_connect_attempts_per_request{bucket="1"} 76066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29058
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 444
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 713
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70504
telemt_me_reconnect_success_total 2122
telemt_me_reader_eof_total 1867
telemt_me_idle_close_by_peer_total 1866
telemt_me_route_drop_no_conn_total 3153476
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6109246
telemt_me_endpoint_quarantine_total 896
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1011
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
telemt_me_writers_active_current 81
telemt_me_writers_warm_current 6
telemt_desync_total 30897
telemt_desync_full_logged_total 10703
telemt_desync_suppressed_total 20194
telemt_desync_frames_bucket_total{bucket="1_2"} 6244
telemt_desync_frames_bucket_total{bucket="3_10"} 11852
telemt_desync_frames_bucket_total{bucket="gt_10"} 12801
telemt_pool_swap_total 139
telemt_pool_force_close_total 4031
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 483
telemt_me_draining_writers_reap_progress_total 46410
telemt_me_writer_removed_unexpected_total 1896
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4765
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43568
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3544
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 487
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42379
telemt_me_writer_teardown_success_total{mode="normal"} 48333
telemt_me_writer_teardown_noop_total 46411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94744
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.701941
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94744
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 483
telemt_me_refill_failed_total 4230
telemt_me_writer_restored_same_endpoint_total 1768
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 6106993
telemt_user_connections_current{user="hello"} 4703
telemt_user_octets_from_client{user="hello"} 151865888399 (141.44 GB)
telemt_user_octets_to_client{user="hello"} 2486599944395 (2.26 TB)
telemt_user_msgs_from_client{user="hello"} 115484
telemt_user_msgs_to_client{user="hello"} 517108
telemt_user_unique_ips_current{user="hello"} 1934
telemt_user_unique_ips_recent_window{user="hello"} 672
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 71157.8 (19h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6512462
telemt_connections_bad_total 250479
telemt_connections_current 4160
telemt_connections_me_current 4160
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2639589
telemt_upstream_connect_attempt_total 37516
telemt_upstream_connect_success_total 37252
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 37509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_reconnect_attempts_total 47489
telemt_me_reconnect_success_total 1260
telemt_me_reader_eof_total 923
telemt_me_idle_close_by_peer_total 923
telemt_me_route_drop_no_conn_total 1734774
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3238769
telemt_me_endpoint_quarantine_total 489
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 541
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_me_writers_warm_current 19
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 17796
telemt_desync_full_logged_total 5986
telemt_desync_suppressed_total 11810
telemt_desync_frames_bucket_total{bucket="1_2"} 3567
telemt_desync_frames_bucket_total{bucket="3_10"} 6811
telemt_desync_frames_bucket_total{bucket="gt_10"} 7418
telemt_pool_swap_total 75
telemt_pool_force_close_total 2279
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 218
telemt_me_draining_writers_reap_progress_total 25455
telemt_me_writer_removed_unexpected_total 993
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2220
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24251
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1960
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 319
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23176
telemt_me_writer_teardown_success_total{mode="normal"} 26471
telemt_me_writer_teardown_noop_total 25461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51932
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.845641
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51932
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 218
telemt_me_refill_failed_total 2688
telemt_me_writer_restored_same_endpoint_total 1124
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3239119
telemt_user_connections_current{user="hello"} 4160
telemt_user_octets_from_client{user="hello"} 80111190564 (74.61 GB)
telemt_user_octets_to_client{user="hello"} 1377235357270 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1663
telemt_user_unique_ips_recent_window{user="hello"} 601
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 52129.1 (14h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 504652
telemt_connections_bad_total 3720
telemt_connections_current 998
telemt_connections_me_current 998
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 9306
telemt_upstream_connect_attempt_total 27486
telemt_upstream_connect_success_total 27423
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 27481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 274
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1130
telemt_me_reconnect_success_total 455
telemt_me_reader_eof_total 453
telemt_me_idle_close_by_peer_total 453
telemt_me_route_drop_no_conn_total 164488
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 455984
telemt_me_endpoint_quarantine_total 480
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 445
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 2179
telemt_desync_full_logged_total 640
telemt_desync_suppressed_total 1539
telemt_desync_frames_bucket_total{bucket="1_2"} 646
telemt_desync_frames_bucket_total{bucket="3_10"} 838
telemt_desync_frames_bucket_total{bucket="gt_10"} 695
telemt_pool_swap_total 55
telemt_pool_force_close_total 1299
telemt_me_writer_close_signal_drop_total 62
telemt_me_draining_writers_reap_progress_total 22237
telemt_me_writer_removed_unexpected_total 436
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1625
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21065
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1248
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20938
telemt_me_writer_teardown_success_total{mode="normal"} 22690
telemt_me_writer_teardown_noop_total 22237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44927
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.155744
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44927
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 62
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 402
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 458050
telemt_user_connections_current{user="hello"} 998
telemt_user_octets_from_client{user="hello"} 9175764785 (8.55 GB)
telemt_user_octets_to_client{user="hello"} 224593734787 (209.17 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 134326.9 (37h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9541819
telemt_connections_bad_total 1115343
telemt_connections_current 4955
telemt_connections_me_current 4955
telemt_handshake_timeouts_total 258631
telemt_upstream_connect_attempt_total 51828
telemt_upstream_connect_success_total 51630
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 51782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26049
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 1927
telemt_me_reconnect_success_total 1055
telemt_me_reader_eof_total 1027
telemt_me_idle_close_by_peer_total 1027
telemt_me_route_drop_no_conn_total 2704534
telemt_me_route_drop_channel_closed_total 70
telemt_me_route_drop_queue_full_total 28
telemt_me_route_drop_queue_full_profile_total{profile="high"} 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7085272
telemt_me_endpoint_quarantine_total 950
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1019
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
telemt_me_writers_active_current 45
telemt_desync_total 28608
telemt_desync_full_logged_total 9379
telemt_desync_suppressed_total 19229
telemt_desync_frames_bucket_total{bucket="1_2"} 7069
telemt_desync_frames_bucket_total{bucket="3_10"} 10419
telemt_desync_frames_bucket_total{bucket="gt_10"} 11120
telemt_pool_swap_total 149
telemt_pool_force_close_total 4021
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 487
telemt_me_draining_writers_reap_progress_total 46754
telemt_me_writer_removed_unexpected_total 987
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3758
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44014
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3913
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42733
telemt_me_writer_teardown_success_total{mode="normal"} 47772
telemt_me_writer_teardown_noop_total 46756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94528
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.937218
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94528
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 487
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 926
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 7057742
telemt_user_connections_current{user="hello"} 4955
telemt_user_octets_from_client{user="hello"} 136705439476 (127.32 GB)
telemt_user_octets_to_client{user="hello"} 3298453157404 (3.00 TB)
telemt_user_unique_ips_current{user="hello"} 1722
telemt_user_unique_ips_recent_window{user="hello"} 1442
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 134323.3 (37h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8280948
telemt_connections_bad_total 924882
telemt_connections_current 4356
telemt_connections_me_current 4356
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 216045
telemt_upstream_connect_attempt_total 76299
telemt_upstream_connect_success_total 75758
telemt_upstream_connect_fail_total 472
telemt_upstream_connect_attempts_per_request{bucket="1"} 76230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30553
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1967
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 472
telemt_me_reconnect_attempts_total 6559
telemt_me_reconnect_success_total 1522
telemt_me_reader_eof_total 1352
telemt_me_idle_close_by_peer_total 1352
telemt_me_seq_mismatch_total 64
telemt_me_route_drop_no_conn_total 2908561
telemt_me_route_drop_channel_closed_total 256
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6317278
telemt_me_endpoint_quarantine_total 1050
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1019
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 27702
telemt_desync_full_logged_total 9173
telemt_desync_suppressed_total 18529
telemt_desync_frames_bucket_total{bucket="1_2"} 6802
telemt_desync_frames_bucket_total{bucket="3_10"} 10193
telemt_desync_frames_bucket_total{bucket="gt_10"} 10707
telemt_pool_swap_total 146
telemt_pool_force_close_total 3953
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 489
telemt_me_draining_writers_reap_progress_total 45415
telemt_me_writer_removed_unexpected_total 1370
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4411
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42436
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3662
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 291
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41462
telemt_me_writer_teardown_success_total{mode="normal"} 46847
telemt_me_writer_teardown_noop_total 45419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92266
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.492196
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92266
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 489
telemt_me_refill_failed_total 290
telemt_me_writer_restored_same_endpoint_total 1186
telemt_me_writer_restored_fallback_total 88
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 6325610
telemt_user_connections_current{user="hello"} 4356
telemt_user_octets_from_client{user="hello"} 115358832817 (107.44 GB)
telemt_user_octets_to_client{user="hello"} 2689977285435 (2.45 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1598
telemt_user_unique_ips_recent_window{user="hello"} 1325
```
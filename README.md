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

# Server Metrics 2026-03-22 14:21:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 62129.7 (17h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1993780
telemt_connections_bad_total 85611
telemt_connections_current 1638
telemt_connections_me_current 1638
telemt_handshake_timeouts_total 81971
telemt_upstream_connect_attempt_total 23166
telemt_upstream_connect_success_total 23165
telemt_upstream_connect_attempts_per_request{bucket="1"} 23165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15069
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 925
telemt_me_reconnect_success_total 378
telemt_me_reader_eof_total 383
telemt_me_idle_close_by_peer_total 383
telemt_me_route_drop_no_conn_total 1449885
telemt_me_route_drop_channel_closed_total 645
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1700107
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 422
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 486
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 6
telemt_desync_total 9124
telemt_desync_full_logged_total 2819
telemt_desync_suppressed_total 6305
telemt_desync_frames_bucket_total{bucket="1_2"} 2521
telemt_desync_frames_bucket_total{bucket="3_10"} 3426
telemt_desync_frames_bucket_total{bucket="gt_10"} 3177
telemt_pool_swap_total 68
telemt_pool_force_close_total 2056
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 349
telemt_me_draining_writers_reap_progress_total 21127
telemt_me_writer_removed_unexpected_total 373
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1504
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19835
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2018
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 38
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19071
telemt_me_writer_teardown_success_total{mode="normal"} 21339
telemt_me_writer_teardown_noop_total 21131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42470
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 165.189045
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42470
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 349
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 336
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1697100
telemt_user_connections_current{user="hello"} 1638
telemt_user_octets_from_client{user="hello"} 26477325028 (24.66 GB)
telemt_user_octets_to_client{user="hello"} 491939850520 (458.15 GB)
telemt_user_unique_ips_current{user="hello"} 663
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 75495.9 (20h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3203352
telemt_connections_bad_total 293738
telemt_connections_current 3262
telemt_connections_me_current 3262
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 76480
telemt_upstream_connect_attempt_total 48452
telemt_upstream_connect_success_total 47871
telemt_upstream_connect_fail_total 514
telemt_upstream_connect_attempts_per_request{bucket="1"} 48385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 514
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 5329
telemt_me_reconnect_success_total 1832
telemt_me_reader_eof_total 1758
telemt_me_idle_close_by_peer_total 1758
telemt_me_route_drop_no_conn_total 3001021
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2528200
telemt_me_endpoint_quarantine_total 614
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 587
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
telemt_me_writers_active_current 127
telemt_desync_total 10001
telemt_desync_full_logged_total 5566
telemt_desync_suppressed_total 4435
telemt_desync_frames_bucket_total{bucket="1_2"} 2359
telemt_desync_frames_bucket_total{bucket="3_10"} 3934
telemt_desync_frames_bucket_total{bucket="gt_10"} 3708
telemt_pool_swap_total 72
telemt_pool_force_close_total 2070
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 175
telemt_me_draining_writers_reap_progress_total 29945
telemt_me_writer_removed_unexpected_total 1716
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3436
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28226
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1824
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 246
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27875
telemt_me_writer_teardown_success_total{mode="normal"} 31662
telemt_me_writer_teardown_noop_total 29945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61607
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.025170
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61607
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 175
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1553
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 2539757
telemt_user_connections_current{user="hello"} 3262
telemt_user_octets_from_client{user="hello"} 30544649435 (28.45 GB)
telemt_user_octets_to_client{user="hello"} 583848775110 (543.75 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1812
telemt_user_unique_ips_recent_window{user="hello"} 637
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 150355.7 (41h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14308528
telemt_connections_bad_total 1264163
telemt_connections_current 5477
telemt_connections_me_current 5477
telemt_handshake_timeouts_total 358047
telemt_upstream_connect_attempt_total 54398
telemt_upstream_connect_success_total 54316
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 54324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29476
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2466
telemt_me_reconnect_success_total 1290
telemt_me_reader_eof_total 1234
telemt_me_idle_close_by_peer_total 1233
telemt_me_route_drop_no_conn_total 12637267
telemt_me_route_drop_channel_closed_total 127
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11478483
telemt_me_endpoint_quarantine_total 952
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1117
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 20
telemt_desync_total 46804
telemt_desync_full_logged_total 14778
telemt_desync_suppressed_total 32026
telemt_desync_frames_bucket_total{bucket="1_2"} 10597
telemt_desync_frames_bucket_total{bucket="3_10"} 18322
telemt_desync_frames_bucket_total{bucket="gt_10"} 17885
telemt_pool_swap_total 161
telemt_pool_force_close_total 5506
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 886
telemt_me_draining_writers_reap_progress_total 49596
telemt_me_writer_removed_unexpected_total 1189
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4306
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45806
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5066
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 440
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44090
telemt_me_writer_teardown_success_total{mode="normal"} 50112
telemt_me_writer_teardown_noop_total 49645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99757
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 257.617506
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99757
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 886
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1112
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 11465966
telemt_user_connections_current{user="hello"} 5477
telemt_user_octets_from_client{user="hello"} 163439645900 (152.22 GB)
telemt_user_octets_to_client{user="hello"} 3026848693304 (2.75 TB)
telemt_user_unique_ips_current{user="hello"} 2160
telemt_user_unique_ips_recent_window{user="hello"} 836
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 150357.0 (41h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10553384
telemt_connections_bad_total 1007340
telemt_connections_current 4643
telemt_connections_me_current 4643
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 314320
telemt_upstream_connect_attempt_total 80792
telemt_upstream_connect_success_total 79648
telemt_upstream_connect_fail_total 822
telemt_upstream_connect_attempts_per_request{bucket="1"} 80470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32026
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3683
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 822
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3705
telemt_me_reconnect_success_total 1476
telemt_me_reader_eof_total 1351
telemt_me_idle_close_by_peer_total 1351
telemt_me_route_drop_no_conn_total 4193133
telemt_me_route_drop_channel_closed_total 460
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7879276
telemt_me_endpoint_quarantine_total 940
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1138
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_me_writers_warm_current 21
telemt_desync_total 35100
telemt_desync_full_logged_total 11812
telemt_desync_suppressed_total 23288
telemt_desync_frames_bucket_total{bucket="1_2"} 8659
telemt_desync_frames_bucket_total{bucket="3_10"} 13500
telemt_desync_frames_bucket_total{bucket="gt_10"} 12941
telemt_pool_swap_total 160
telemt_pool_force_close_total 4942
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 620
telemt_me_draining_writers_reap_progress_total 47807
telemt_me_writer_removed_unexpected_total 1383
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4343
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44704
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4514
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 428
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42865
telemt_me_writer_teardown_success_total{mode="normal"} 49047
telemt_me_writer_teardown_noop_total 47822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96869
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 95.206422
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96869
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 620
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1253
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 7818580
telemt_user_connections_current{user="hello"} 4643
telemt_user_octets_from_client{user="hello"} 197628086325 (184.06 GB)
telemt_user_octets_to_client{user="hello"} 3523322867802 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1953
telemt_user_unique_ips_recent_window{user="hello"} 638
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 150321.2 (41h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10003422
telemt_connections_bad_total 848337
telemt_connections_current 4187
telemt_connections_me_current 4187
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 322496
telemt_upstream_connect_attempt_total 66193
telemt_upstream_connect_success_total 65282
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 65464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30722
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1189
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2018
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4532
telemt_me_reconnect_success_total 1841
telemt_me_reader_eof_total 1594
telemt_me_idle_close_by_peer_total 1593
telemt_me_route_drop_no_conn_total 4920384
telemt_me_route_drop_channel_closed_total 336
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7552901
telemt_me_endpoint_quarantine_total 1036
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1100
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
telemt_me_writers_active_current 46
telemt_desync_total 35004
telemt_desync_full_logged_total 11591
telemt_desync_suppressed_total 23413
telemt_desync_frames_bucket_total{bucket="1_2"} 8859
telemt_desync_frames_bucket_total{bucket="3_10"} 13392
telemt_desync_frames_bucket_total{bucket="gt_10"} 12753
telemt_pool_swap_total 156
telemt_pool_force_close_total 4885
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 660
telemt_me_draining_writers_reap_progress_total 48415
telemt_me_writer_removed_unexpected_total 1738
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4854
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45213
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4363
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 522
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43530
telemt_me_writer_teardown_success_total{mode="normal"} 50067
telemt_me_writer_teardown_noop_total 48482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98549
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3163.832750
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98549
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 660
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 1598
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 7546570
telemt_user_connections_current{user="hello"} 4187
telemt_user_octets_from_client{user="hello"} 176387334281 (164.27 GB)
telemt_user_octets_to_client{user="hello"} 3148586637309 (2.86 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1774
telemt_user_unique_ips_recent_window{user="hello"} 588
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 20601.3 (5h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8704460
telemt_connections_bad_total 550301
telemt_connections_current 7294
telemt_connections_me_current 7294
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 140564
telemt_upstream_connect_attempt_total 28924
telemt_upstream_connect_success_total 27496
telemt_upstream_connect_fail_total 1031
telemt_upstream_connect_attempts_per_request{bucket="1"} 28527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6886
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4743
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1031
telemt_me_keepalive_timeout_total 822
telemt_me_reconnect_attempts_total 5517
telemt_me_reconnect_success_total 594
telemt_me_reader_eof_total 388
telemt_me_idle_close_by_peer_total 388
telemt_me_route_drop_no_conn_total 21364146
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7237893
telemt_me_endpoint_quarantine_total 127
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 63
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 63
telemt_me_single_endpoint_shadow_rotate_total 158
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_me_writers_active_current 101
telemt_desync_total 10750
telemt_desync_full_logged_total 2767
telemt_desync_suppressed_total 7983
telemt_desync_frames_bucket_total{bucket="1_2"} 1884
telemt_desync_frames_bucket_total{bucket="3_10"} 4338
telemt_desync_frames_bucket_total{bucket="gt_10"} 4528
telemt_pool_swap_total 18
telemt_pool_force_close_total 745
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 273
telemt_me_draining_writers_reap_progress_total 5397
telemt_me_writer_removed_unexpected_total 508
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 960
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4912
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 535
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4652
telemt_me_writer_teardown_success_total{mode="normal"} 5872
telemt_me_writer_teardown_noop_total 5400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11272
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 24.413070
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11272
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 273
telemt_me_refill_failed_total 284
telemt_me_writer_restored_same_endpoint_total 424
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 7252798
telemt_user_connections_current{user="hello"} 7294
telemt_user_octets_from_client{user="hello"} 41943431187 (39.06 GB)
telemt_user_octets_to_client{user="hello"} 212793093992 (198.18 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2576
telemt_user_unique_ips_recent_window{user="hello"} 1407
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 150328.1 (41h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9735600
telemt_connections_bad_total 809885
telemt_connections_current 5219
telemt_connections_me_current 5219
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 210888
telemt_upstream_connect_attempt_total 90684
telemt_upstream_connect_success_total 89770
telemt_upstream_connect_fail_total 791
telemt_upstream_connect_attempts_per_request{bucket="1"} 90561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32787
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1255
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 791
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71401
telemt_me_reconnect_success_total 2469
telemt_me_reader_eof_total 2200
telemt_me_idle_close_by_peer_total 2199
telemt_me_route_drop_no_conn_total 4801615
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7682087
telemt_me_endpoint_quarantine_total 1001
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1118
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_me_writers_active_current 88
telemt_me_writers_warm_current 2
telemt_desync_total 39543
telemt_desync_full_logged_total 13520
telemt_desync_suppressed_total 26023
telemt_desync_frames_bucket_total{bucket="1_2"} 8045
telemt_desync_frames_bucket_total{bucket="3_10"} 15337
telemt_desync_frames_bucket_total{bucket="gt_10"} 16161
telemt_pool_swap_total 153
telemt_pool_force_close_total 4532
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 555
telemt_me_draining_writers_reap_progress_total 51170
telemt_me_writer_removed_unexpected_total 2227
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5415
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47999
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3915
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 617
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46638
telemt_me_writer_teardown_success_total{mode="normal"} 53414
telemt_me_writer_teardown_noop_total 51171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104585
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.837432
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104585
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 555
telemt_me_refill_failed_total 4253
telemt_me_writer_restored_same_endpoint_total 2077
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 7683133
telemt_user_connections_current{user="hello"} 5219
telemt_user_octets_from_client{user="hello"} 176031570391 (163.94 GB)
telemt_user_octets_to_client{user="hello"} 2906020051729 (2.64 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2173
telemt_user_unique_ips_recent_window{user="hello"} 639
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 87164.0 (24h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9851416
telemt_connections_bad_total 358696
telemt_connections_current 4496
telemt_connections_me_current 4496
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4140135
telemt_upstream_connect_attempt_total 42775
telemt_upstream_connect_success_total 42465
telemt_upstream_connect_fail_total 303
telemt_upstream_connect_attempts_per_request{bucket="1"} 42768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 303
telemt_me_reconnect_attempts_total 47938
telemt_me_reconnect_success_total 1451
telemt_me_reader_eof_total 1121
telemt_me_idle_close_by_peer_total 1121
telemt_me_route_drop_no_conn_total 3625567
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4746085
telemt_me_endpoint_quarantine_total 570
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 656
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
telemt_desync_total 25938
telemt_desync_full_logged_total 8728
telemt_desync_suppressed_total 17210
telemt_desync_frames_bucket_total{bucket="1_2"} 5234
telemt_desync_frames_bucket_total{bucket="3_10"} 10293
telemt_desync_frames_bucket_total{bucket="gt_10"} 10411
telemt_pool_swap_total 91
telemt_pool_force_close_total 2830
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 291
telemt_me_draining_writers_reap_progress_total 30089
telemt_me_writer_removed_unexpected_total 1186
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2723
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28580
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2421
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 409
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27259
telemt_me_writer_teardown_success_total{mode="normal"} 31303
telemt_me_writer_teardown_noop_total 30096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61399
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.211830
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61399
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 291
telemt_me_refill_failed_total 2702
telemt_me_writer_restored_same_endpoint_total 1298
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4740423
telemt_user_connections_current{user="hello"} 4496
telemt_user_octets_from_client{user="hello"} 103211407492 (96.12 GB)
telemt_user_octets_to_client{user="hello"} 1796562080058 (1.63 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1742
telemt_user_unique_ips_recent_window{user="hello"} 731
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 68134.6 (18h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 830551
telemt_connections_bad_total 10728
telemt_connections_current 962
telemt_connections_me_current 962
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 15588
telemt_upstream_connect_attempt_total 34323
telemt_upstream_connect_success_total 34238
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 34307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 456
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 1564
telemt_me_reconnect_success_total 667
telemt_me_reader_eof_total 642
telemt_me_idle_close_by_peer_total 642
telemt_me_route_drop_no_conn_total 285476
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 741215
telemt_me_endpoint_quarantine_total 610
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 567
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
telemt_me_writers_active_current 44
telemt_desync_total 4070
telemt_desync_full_logged_total 1236
telemt_desync_suppressed_total 2834
telemt_desync_frames_bucket_total{bucket="1_2"} 986
telemt_desync_frames_bucket_total{bucket="3_10"} 1626
telemt_desync_frames_bucket_total{bucket="gt_10"} 1458
telemt_pool_swap_total 72
telemt_pool_force_close_total 1798
telemt_me_writer_close_signal_drop_total 104
telemt_me_draining_writers_reap_progress_total 28215
telemt_me_writer_removed_unexpected_total 621
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2174
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26685
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1720
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26417
telemt_me_writer_teardown_success_total{mode="normal"} 28859
telemt_me_writer_teardown_noop_total 28217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57076
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.134420
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57076
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 104
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 570
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 742410
telemt_user_connections_current{user="hello"} 962
telemt_user_octets_from_client{user="hello"} 13791402417 (12.84 GB)
telemt_user_octets_to_client{user="hello"} 346963905751 (323.14 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 358
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 150332.3 (41h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11884535
telemt_connections_bad_total 1385369
telemt_connections_current 6047
telemt_connections_me_current 6047
telemt_handshake_timeouts_total 325069
telemt_upstream_connect_attempt_total 56476
telemt_upstream_connect_success_total 56254
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 56426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28473
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_reconnect_attempts_total 2203
telemt_me_reconnect_success_total 1180
telemt_me_reader_eof_total 1142
telemt_me_idle_close_by_peer_total 1142
telemt_me_route_drop_no_conn_total 3844355
telemt_me_route_drop_channel_closed_total 112
telemt_me_route_drop_queue_full_total 35
telemt_me_route_drop_queue_full_profile_total{profile="high"} 35
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8953329
telemt_me_endpoint_quarantine_total 1025
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1123
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
telemt_me_writers_warm_current 4
telemt_desync_total 36788
telemt_desync_full_logged_total 12031
telemt_desync_suppressed_total 24757
telemt_desync_frames_bucket_total{bucket="1_2"} 8788
telemt_desync_frames_bucket_total{bucket="3_10"} 13624
telemt_desync_frames_bucket_total{bucket="gt_10"} 14376
telemt_pool_swap_total 166
telemt_pool_force_close_total 4582
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 582
telemt_me_draining_writers_reap_progress_total 50875
telemt_me_writer_removed_unexpected_total 1098
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4179
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47824
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4418
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 164
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46293
telemt_me_writer_teardown_success_total{mode="normal"} 52003
telemt_me_writer_teardown_noop_total 50877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102880
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.109992
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102880
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 582
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1034
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 8923344
telemt_user_connections_current{user="hello"} 6047
telemt_user_octets_from_client{user="hello"} 171984922380 (160.17 GB)
telemt_user_octets_to_client{user="hello"} 3989306298336 (3.63 TB)
telemt_user_unique_ips_current{user="hello"} 2234
telemt_user_unique_ips_recent_window{user="hello"} 820
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 150329.0 (41h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10270574
telemt_connections_bad_total 1149636
telemt_connections_current 4853
telemt_connections_me_current 4853
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 267566
telemt_upstream_connect_attempt_total 82039
telemt_upstream_connect_success_total 81435
telemt_upstream_connect_fail_total 523
telemt_upstream_connect_attempts_per_request{bucket="1"} 81958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33522
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2008
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 523
telemt_me_reconnect_attempts_total 8674
telemt_me_reconnect_success_total 1958
telemt_me_reader_eof_total 1825
telemt_me_idle_close_by_peer_total 1825
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 4789037
telemt_me_route_drop_channel_closed_total 327
telemt_me_route_drop_queue_full_total 17
telemt_me_route_drop_queue_full_profile_total{profile="high"} 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7919544
telemt_me_endpoint_quarantine_total 1143
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1127
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_me_writers_warm_current 1
telemt_desync_total 36157
telemt_desync_full_logged_total 11736
telemt_desync_suppressed_total 24421
telemt_desync_frames_bucket_total{bucket="1_2"} 8943
telemt_desync_frames_bucket_total{bucket="3_10"} 13495
telemt_desync_frames_bucket_total{bucket="gt_10"} 13719
telemt_pool_swap_total 159
telemt_pool_force_close_total 4442
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 574
telemt_me_draining_writers_reap_progress_total 50172
telemt_me_writer_removed_unexpected_total 1850
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5200
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46889
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4034
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 408
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45730
telemt_me_writer_teardown_success_total{mode="normal"} 52089
telemt_me_writer_teardown_noop_total 50176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102265
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.693508
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102265
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 574
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 1587
telemt_me_writer_restored_fallback_total 98
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 7926243
telemt_user_connections_current{user="hello"} 4853
telemt_user_octets_from_client{user="hello"} 139284339273 (129.72 GB)
telemt_user_octets_to_client{user="hello"} 3083441546059 (2.80 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 2063
telemt_user_unique_ips_recent_window{user="hello"} 701
```
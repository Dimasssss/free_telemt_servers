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

# Server Metrics 2026-03-22 14:01:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 60894.0 (16h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1925360
telemt_connections_bad_total 83265
telemt_connections_current 1976
telemt_connections_me_current 1976
telemt_handshake_timeouts_total 80218
telemt_upstream_connect_attempt_total 22777
telemt_upstream_connect_success_total 22776
telemt_upstream_connect_attempts_per_request{bucket="1"} 22776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14821
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 915
telemt_me_reconnect_success_total 369
telemt_me_reader_eof_total 373
telemt_me_idle_close_by_peer_total 373
telemt_me_route_drop_no_conn_total 1343366
telemt_me_route_drop_channel_closed_total 623
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1639490
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 418
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 481
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
telemt_desync_total 8901
telemt_desync_full_logged_total 2739
telemt_desync_suppressed_total 6162
telemt_desync_frames_bucket_total{bucket="1_2"} 2472
telemt_desync_frames_bucket_total{bucket="3_10"} 3353
telemt_desync_frames_bucket_total{bucket="gt_10"} 3076
telemt_pool_swap_total 67
telemt_pool_force_close_total 2004
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 329
telemt_me_draining_writers_reap_progress_total 20776
telemt_me_writer_removed_unexpected_total 364
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1480
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19519
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1968
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18772
telemt_me_writer_teardown_success_total{mode="normal"} 20999
telemt_me_writer_teardown_noop_total 20780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41779
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 158.942458
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41779
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 329
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 327
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1636550
telemt_user_connections_current{user="hello"} 1976
telemt_user_octets_from_client{user="hello"} 25675286084 (23.91 GB)
telemt_user_octets_to_client{user="hello"} 477636000136 (444.83 GB)
telemt_user_unique_ips_current{user="hello"} 723
telemt_user_unique_ips_recent_window{user="hello"} 542
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 74260.1 (20h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3106552
telemt_connections_bad_total 290172
telemt_connections_current 2614
telemt_connections_me_current 2614
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 73897
telemt_upstream_connect_attempt_total 47654
telemt_upstream_connect_success_total 47084
telemt_upstream_connect_fail_total 505
telemt_upstream_connect_attempts_per_request{bucket="1"} 47589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18775
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 505
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3740
telemt_me_reconnect_success_total 1718
telemt_me_reader_eof_total 1592
telemt_me_idle_close_by_peer_total 1592
telemt_me_route_drop_no_conn_total 2908233
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2445053
telemt_me_endpoint_quarantine_total 613
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 580
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
telemt_desync_total 9702
telemt_desync_full_logged_total 5414
telemt_desync_suppressed_total 4288
telemt_desync_frames_bucket_total{bucket="1_2"} 2280
telemt_desync_frames_bucket_total{bucket="3_10"} 3821
telemt_desync_frames_bucket_total{bucket="gt_10"} 3601
telemt_pool_swap_total 72
telemt_pool_force_close_total 2070
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 173
telemt_me_draining_writers_reap_progress_total 29343
telemt_me_writer_removed_unexpected_total 1549
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3253
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27640
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1824
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 246
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27273
telemt_me_writer_teardown_success_total{mode="normal"} 30893
telemt_me_writer_teardown_noop_total 29343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60236
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.819020
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60236
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 173
telemt_me_refill_failed_total 91
telemt_me_writer_restored_same_endpoint_total 1439
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 2456621
telemt_user_connections_current{user="hello"} 2614
telemt_user_octets_from_client{user="hello"} 29587953547 (27.56 GB)
telemt_user_octets_to_client{user="hello"} 562914699898 (524.26 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1570
telemt_user_unique_ips_recent_window{user="hello"} 729
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 149120.0 (41h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14038351
telemt_connections_bad_total 1237813
telemt_connections_current 5525
telemt_connections_me_current 5525
telemt_handshake_timeouts_total 353585
telemt_upstream_connect_attempt_total 54056
telemt_upstream_connect_success_total 53974
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 53982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29295
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2457
telemt_me_reconnect_success_total 1281
telemt_me_reader_eof_total 1224
telemt_me_idle_close_by_peer_total 1223
telemt_me_route_drop_no_conn_total 12208122
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11257933
telemt_me_endpoint_quarantine_total 951
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1110
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
telemt_desync_total 45787
telemt_desync_full_logged_total 14517
telemt_desync_suppressed_total 31270
telemt_desync_frames_bucket_total{bucket="1_2"} 10374
telemt_desync_frames_bucket_total{bucket="3_10"} 17915
telemt_desync_frames_bucket_total{bucket="gt_10"} 17498
telemt_pool_swap_total 160
telemt_pool_force_close_total 5473
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 867
telemt_me_draining_writers_reap_progress_total 49305
telemt_me_writer_removed_unexpected_total 1180
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4275
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45545
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5037
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 436
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43832
telemt_me_writer_teardown_success_total{mode="normal"} 49820
telemt_me_writer_teardown_noop_total 49354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99174
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 254.354260
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99174
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 867
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1103
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 11245669
telemt_user_connections_current{user="hello"} 5525
telemt_user_octets_from_client{user="hello"} 161361049004 (150.28 GB)
telemt_user_octets_to_client{user="hello"} 2994187878016 (2.72 TB)
telemt_user_unique_ips_current{user="hello"} 1990
telemt_user_unique_ips_recent_window{user="hello"} 1070
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 149121.4 (41h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10415513
telemt_connections_bad_total 990411
telemt_connections_current 5031
telemt_connections_me_current 5031
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 311149
telemt_upstream_connect_attempt_total 80416
telemt_upstream_connect_success_total 79275
telemt_upstream_connect_fail_total 820
telemt_upstream_connect_attempts_per_request{bucket="1"} 80095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31828
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3678
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 820
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3695
telemt_me_reconnect_success_total 1468
telemt_me_reader_eof_total 1342
telemt_me_idle_close_by_peer_total 1342
telemt_me_route_drop_no_conn_total 4135143
telemt_me_route_drop_channel_closed_total 451
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7772414
telemt_me_endpoint_quarantine_total 931
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1130
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
telemt_desync_total 34698
telemt_desync_full_logged_total 11669
telemt_desync_suppressed_total 23029
telemt_desync_frames_bucket_total{bucket="1_2"} 8559
telemt_desync_frames_bucket_total{bucket="3_10"} 13331
telemt_desync_frames_bucket_total{bucket="gt_10"} 12808
telemt_pool_swap_total 159
telemt_pool_force_close_total 4907
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 618
telemt_me_draining_writers_reap_progress_total 47503
telemt_me_writer_removed_unexpected_total 1375
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4309
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44425
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4484
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 423
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42596
telemt_me_writer_teardown_success_total{mode="normal"} 48734
telemt_me_writer_teardown_noop_total 47518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96252
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 91.830718
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96252
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 618
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1245
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 7711862
telemt_user_connections_current{user="hello"} 5031
telemt_user_octets_from_client{user="hello"} 195651545617 (182.21 GB)
telemt_user_octets_to_client{user="hello"} 3477360515406 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1930
telemt_user_unique_ips_recent_window{user="hello"} 703
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 149085.4 (41h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9863845
telemt_connections_bad_total 831706
telemt_connections_current 4401
telemt_connections_me_current 4401
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 318244
telemt_upstream_connect_attempt_total 65876
telemt_upstream_connect_success_total 64972
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 65153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30550
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2014
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4181
telemt_me_reconnect_success_total 1808
telemt_me_reader_eof_total 1575
telemt_me_idle_close_by_peer_total 1574
telemt_me_route_drop_no_conn_total 4862926
telemt_me_route_drop_channel_closed_total 330
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7448556
telemt_me_endpoint_quarantine_total 1020
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1094
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 34511
telemt_desync_full_logged_total 11443
telemt_desync_suppressed_total 23068
telemt_desync_frames_bucket_total{bucket="1_2"} 8737
telemt_desync_frames_bucket_total{bucket="3_10"} 13222
telemt_desync_frames_bucket_total{bucket="gt_10"} 12552
telemt_pool_swap_total 155
telemt_pool_force_close_total 4848
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 48144
telemt_me_writer_removed_unexpected_total 1720
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4819
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44958
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4333
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 515
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43296
telemt_me_writer_teardown_success_total{mode="normal"} 49777
telemt_me_writer_teardown_noop_total 48211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97988
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3158.788938
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97988
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 122
telemt_me_writer_restored_same_endpoint_total 1578
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 7442439
telemt_user_connections_current{user="hello"} 4401
telemt_user_octets_from_client{user="hello"} 174679777709 (162.68 GB)
telemt_user_octets_to_client{user="hello"} 3106501437621 (2.83 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1787
telemt_user_unique_ips_recent_window{user="hello"} 678
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 19365.4 (5h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8168063
telemt_connections_bad_total 510897
telemt_connections_current 7276
telemt_connections_me_current 7276
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 131341
telemt_upstream_connect_attempt_total 28422
telemt_upstream_connect_success_total 27024
telemt_upstream_connect_fail_total 1024
telemt_upstream_connect_attempts_per_request{bucket="1"} 28048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6644
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4730
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1024
telemt_me_keepalive_timeout_total 692
telemt_me_reconnect_attempts_total 5463
telemt_me_reconnect_success_total 546
telemt_me_reader_eof_total 328
telemt_me_idle_close_by_peer_total 328
telemt_me_route_drop_no_conn_total 19994224
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6805377
telemt_me_endpoint_quarantine_total 126
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 63
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 63
telemt_me_single_endpoint_shadow_rotate_total 151
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_me_writers_active_current 59
telemt_desync_total 9883
telemt_desync_full_logged_total 2548
telemt_desync_suppressed_total 7335
telemt_desync_frames_bucket_total{bucket="1_2"} 1764
telemt_desync_frames_bucket_total{bucket="3_10"} 3997
telemt_desync_frames_bucket_total{bucket="gt_10"} 4122
telemt_pool_swap_total 18
telemt_pool_force_close_total 745
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 268
telemt_me_draining_writers_reap_progress_total 5067
telemt_me_writer_removed_unexpected_total 458
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 886
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4596
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 535
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4322
telemt_me_writer_teardown_success_total{mode="normal"} 5482
telemt_me_writer_teardown_noop_total 5070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 9508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 9884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 10290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 10475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 10546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 10552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 10552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 10552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 10552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 10552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 10552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 10552
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.969619
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 10552
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 268
telemt_me_refill_failed_total 284
telemt_me_writer_restored_same_endpoint_total 376
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 6820311
telemt_user_connections_current{user="hello"} 7277
telemt_user_octets_from_client{user="hello"} 38672251271 (36.02 GB)
telemt_user_octets_to_client{user="hello"} 200070151992 (186.33 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2592
telemt_user_unique_ips_recent_window{user="hello"} 1584
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 149092.3 (41h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9576809
telemt_connections_bad_total 792264
telemt_connections_current 5419
telemt_connections_me_current 5419
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 207362
telemt_upstream_connect_attempt_total 90167
telemt_upstream_connect_success_total 89262
telemt_upstream_connect_fail_total 783
telemt_upstream_connect_attempts_per_request{bucket="1"} 90045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32505
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1253
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 783
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71354
telemt_me_reconnect_success_total 2424
telemt_me_reader_eof_total 2154
telemt_me_idle_close_by_peer_total 2153
telemt_me_route_drop_no_conn_total 4659006
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7558675
telemt_me_endpoint_quarantine_total 1000
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1112
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
telemt_me_writers_active_current 46
telemt_desync_total 38778
telemt_desync_full_logged_total 13252
telemt_desync_suppressed_total 25526
telemt_desync_frames_bucket_total{bucket="1_2"} 7863
telemt_desync_frames_bucket_total{bucket="3_10"} 15012
telemt_desync_frames_bucket_total{bucket="gt_10"} 15903
telemt_pool_swap_total 153
telemt_pool_force_close_total 4532
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 554
telemt_me_draining_writers_reap_progress_total 50778
telemt_me_writer_removed_unexpected_total 2181
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5356
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47620
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3915
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 617
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46246
telemt_me_writer_teardown_success_total{mode="normal"} 52976
telemt_me_writer_teardown_noop_total 50779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103755
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.831100
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103755
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 554
telemt_me_refill_failed_total 4253
telemt_me_writer_restored_same_endpoint_total 2032
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 7559736
telemt_user_connections_current{user="hello"} 5419
telemt_user_octets_from_client{user="hello"} 174060009883 (162.11 GB)
telemt_user_octets_to_client{user="hello"} 2874095493013 (2.61 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2074
telemt_user_unique_ips_recent_window{user="hello"} 806
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 85928.3 (23h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9589549
telemt_connections_bad_total 344130
telemt_connections_current 4927
telemt_connections_me_current 4927
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4027196
telemt_upstream_connect_attempt_total 42412
telemt_upstream_connect_success_total 42103
telemt_upstream_connect_fail_total 302
telemt_upstream_connect_attempts_per_request{bucket="1"} 42405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17923
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 302
telemt_me_reconnect_attempts_total 47928
telemt_me_reconnect_success_total 1442
telemt_me_reader_eof_total 1110
telemt_me_idle_close_by_peer_total 1110
telemt_me_route_drop_no_conn_total 3503184
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4625546
telemt_me_endpoint_quarantine_total 562
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 648
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
telemt_me_writers_active_current 47
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 25332
telemt_desync_full_logged_total 8499
telemt_desync_suppressed_total 16833
telemt_desync_frames_bucket_total{bucket="1_2"} 5113
telemt_desync_frames_bucket_total{bucket="3_10"} 10032
telemt_desync_frames_bucket_total{bucket="gt_10"} 10187
telemt_pool_swap_total 90
telemt_pool_force_close_total 2803
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 289
telemt_me_draining_writers_reap_progress_total 29774
telemt_me_writer_removed_unexpected_total 1175
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2690
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28287
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2394
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 409
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26971
telemt_me_writer_teardown_success_total{mode="normal"} 30977
telemt_me_writer_teardown_noop_total 29781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60758
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.206252
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60758
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 289
telemt_me_refill_failed_total 2702
telemt_me_writer_restored_same_endpoint_total 1289
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4619978
telemt_user_connections_current{user="hello"} 4927
telemt_user_octets_from_client{user="hello"} 101042600928 (94.10 GB)
telemt_user_octets_to_client{user="hello"} 1764216144802 (1.60 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1852
telemt_user_unique_ips_recent_window{user="hello"} 760
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 66899.4 (18h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 802482
telemt_connections_bad_total 10670
telemt_connections_current 1027
telemt_connections_me_current 1027
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 15126
telemt_upstream_connect_attempt_total 33835
telemt_upstream_connect_success_total 33750
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 33819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 435
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 1557
telemt_me_reconnect_success_total 660
telemt_me_reader_eof_total 635
telemt_me_idle_close_by_peer_total 635
telemt_me_route_drop_no_conn_total 275367
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 717980
telemt_me_endpoint_quarantine_total 601
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 558
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
telemt_me_writers_active_current 48
telemt_desync_total 3973
telemt_desync_full_logged_total 1200
telemt_desync_suppressed_total 2773
telemt_desync_frames_bucket_total{bucket="1_2"} 968
telemt_desync_frames_bucket_total{bucket="3_10"} 1586
telemt_desync_frames_bucket_total{bucket="gt_10"} 1419
telemt_pool_swap_total 71
telemt_pool_force_close_total 1769
telemt_me_writer_close_signal_drop_total 103
telemt_me_draining_writers_reap_progress_total 27791
telemt_me_writer_removed_unexpected_total 614
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2145
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26283
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1691
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26022
telemt_me_writer_teardown_success_total{mode="normal"} 28428
telemt_me_writer_teardown_noop_total 27793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56221
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.054892
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56221
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 103
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 563
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 719220
telemt_user_connections_current{user="hello"} 1027
telemt_user_octets_from_client{user="hello"} 13423171529 (12.50 GB)
telemt_user_octets_to_client{user="hello"} 337855231099 (314.65 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 394
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 149096.6 (41h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11680762
telemt_connections_bad_total 1361592
telemt_connections_current 6435
telemt_connections_me_current 6435
telemt_handshake_timeouts_total 319044
telemt_upstream_connect_attempt_total 56129
telemt_upstream_connect_success_total 55912
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 56081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28289
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_reconnect_attempts_total 2192
telemt_me_reconnect_success_total 1168
telemt_me_reader_eof_total 1133
telemt_me_idle_close_by_peer_total 1133
telemt_me_route_drop_no_conn_total 3697631
telemt_me_route_drop_channel_closed_total 102
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8788944
telemt_me_endpoint_quarantine_total 1019
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1117
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
telemt_me_writers_active_current 48
telemt_desync_total 36187
telemt_desync_full_logged_total 11848
telemt_desync_suppressed_total 24339
telemt_desync_frames_bucket_total{bucket="1_2"} 8627
telemt_desync_frames_bucket_total{bucket="3_10"} 13403
telemt_desync_frames_bucket_total{bucket="gt_10"} 14157
telemt_pool_swap_total 165
telemt_pool_force_close_total 4546
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 571
telemt_me_draining_writers_reap_progress_total 50582
telemt_me_writer_removed_unexpected_total 1088
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4147
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47553
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4390
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 156
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46036
telemt_me_writer_teardown_success_total{mode="normal"} 51700
telemt_me_writer_teardown_noop_total 50584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102284
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.513666
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102284
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 571
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1024
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 8759299
telemt_user_connections_current{user="hello"} 6435
telemt_user_octets_from_client{user="hello"} 169145651932 (157.53 GB)
telemt_user_octets_to_client{user="hello"} 3945558813644 (3.59 TB)
telemt_user_unique_ips_current{user="hello"} 2306
telemt_user_unique_ips_recent_window{user="hello"} 921
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 149093.4 (41h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10099923
telemt_connections_bad_total 1133488
telemt_connections_current 5336
telemt_connections_me_current 5336
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 264212
telemt_upstream_connect_attempt_total 81769
telemt_upstream_connect_success_total 81166
telemt_upstream_connect_fail_total 522
telemt_upstream_connect_attempts_per_request{bucket="1"} 81688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33370
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2008
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 522
telemt_me_reconnect_attempts_total 8599
telemt_me_reconnect_success_total 1952
telemt_me_reader_eof_total 1817
telemt_me_idle_close_by_peer_total 1817
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 4593190
telemt_me_route_drop_channel_closed_total 323
telemt_me_route_drop_queue_full_total 17
telemt_me_route_drop_queue_full_profile_total{profile="high"} 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7778926
telemt_me_endpoint_quarantine_total 1140
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1120
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
telemt_me_writers_active_current 44
telemt_desync_total 35343
telemt_desync_full_logged_total 11499
telemt_desync_suppressed_total 23844
telemt_desync_frames_bucket_total{bucket="1_2"} 8722
telemt_desync_frames_bucket_total{bucket="3_10"} 13163
telemt_desync_frames_bucket_total{bucket="gt_10"} 13458
telemt_pool_swap_total 158
telemt_pool_force_close_total 4407
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 570
telemt_me_draining_writers_reap_progress_total 49925
telemt_me_writer_removed_unexpected_total 1842
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5178
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46656
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4003
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 404
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45518
telemt_me_writer_teardown_success_total{mode="normal"} 51834
telemt_me_writer_teardown_noop_total 49929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101763
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.406727
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101763
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 570
telemt_me_refill_failed_total 341
telemt_me_writer_restored_same_endpoint_total 1583
telemt_me_writer_restored_fallback_total 98
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 7785781
telemt_user_connections_current{user="hello"} 5336
telemt_user_octets_from_client{user="hello"} 137115386997 (127.70 GB)
telemt_user_octets_to_client{user="hello"} 3053668387999 (2.78 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1984
telemt_user_unique_ips_recent_window{user="hello"} 835
```
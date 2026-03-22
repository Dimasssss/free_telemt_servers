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

# Server Metrics 2026-03-22 09:14:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 43679.4 (12h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1083361
telemt_connections_bad_total 59729
telemt_connections_current 1680
telemt_connections_me_current 1680
telemt_handshake_timeouts_total 49205
telemt_upstream_connect_attempt_total 17193
telemt_upstream_connect_success_total 17192
telemt_upstream_connect_attempts_per_request{bucket="1"} 17192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11152
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 490
telemt_me_reconnect_success_total 263
telemt_me_reader_eof_total 261
telemt_me_idle_close_by_peer_total 261
telemt_me_route_drop_no_conn_total 594061
telemt_me_route_drop_channel_closed_total 219
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 901820
telemt_me_endpoint_quarantine_total 308
telemt_me_single_endpoint_shadow_rotate_total 351
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 6533
telemt_desync_full_logged_total 1867
telemt_desync_suppressed_total 4666
telemt_desync_frames_bucket_total{bucket="1_2"} 1936
telemt_desync_frames_bucket_total{bucket="3_10"} 2456
telemt_desync_frames_bucket_total{bucket="gt_10"} 2141
telemt_pool_swap_total 48
telemt_pool_force_close_total 1362
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 157
telemt_me_draining_writers_reap_progress_total 15624
telemt_me_writer_removed_unexpected_total 258
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1078
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14755
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1334
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14262
telemt_me_writer_teardown_success_total{mode="normal"} 15833
telemt_me_writer_teardown_noop_total 15626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31459
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 59.157377
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31459
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 157
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 241
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 900167
telemt_user_connections_current{user="hello"} 1680
telemt_user_octets_from_client{user="hello"} 13499166948 (12.57 GB)
telemt_user_octets_to_client{user="hello"} 288305438620 (268.51 GB)
telemt_user_unique_ips_current{user="hello"} 625
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 57045.7 (15h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1618872
telemt_connections_bad_total 154528
telemt_connections_current 1205
telemt_connections_me_current 1205
telemt_handshake_timeouts_total 44265
telemt_upstream_connect_attempt_total 34167
telemt_upstream_connect_success_total 33724
telemt_upstream_connect_fail_total 389
telemt_upstream_connect_attempts_per_request{bucket="1"} 34113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 389
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2573
telemt_me_reconnect_success_total 1096
telemt_me_reader_eof_total 990
telemt_me_idle_close_by_peer_total 990
telemt_me_route_drop_no_conn_total 822097
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1228147
telemt_me_endpoint_quarantine_total 505
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 452
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
telemt_desync_total 5501
telemt_desync_full_logged_total 3173
telemt_desync_suppressed_total 2328
telemt_desync_frames_bucket_total{bucket="1_2"} 1208
telemt_desync_frames_bucket_total{bucket="3_10"} 2145
telemt_desync_frames_bucket_total{bucket="gt_10"} 2148
telemt_pool_swap_total 59
telemt_pool_force_close_total 1610
telemt_me_writer_close_signal_drop_total 132
telemt_me_draining_writers_reap_progress_total 23181
telemt_me_writer_removed_unexpected_total 958
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2295
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21835
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1486
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21571
telemt_me_writer_teardown_success_total{mode="normal"} 24130
telemt_me_writer_teardown_noop_total 23181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47311
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.166960
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47311
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 132
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 877
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1234297
telemt_user_connections_current{user="hello"} 1205
telemt_user_octets_from_client{user="hello"} 18480250018 (17.21 GB)
telemt_user_octets_to_client{user="hello"} 403918760404 (376.18 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 785
telemt_user_unique_ips_recent_window{user="hello"} 567
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 131905.6 (36h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10148855
telemt_connections_bad_total 904596
telemt_connections_current 4802
telemt_connections_me_current 4802
telemt_handshake_timeouts_total 297257
telemt_upstream_connect_attempt_total 48544
telemt_upstream_connect_success_total 48464
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 48472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26344
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1973
telemt_me_reconnect_success_total 1028
telemt_me_reader_eof_total 1025
telemt_me_idle_close_by_peer_total 1024
telemt_me_route_drop_no_conn_total 6067510
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7979830
telemt_me_endpoint_quarantine_total 839
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 986
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
telemt_me_writers_active_current 44
telemt_desync_total 34437
telemt_desync_full_logged_total 11271
telemt_desync_suppressed_total 23166
telemt_desync_frames_bucket_total{bucket="1_2"} 7570
telemt_desync_frames_bucket_total{bucket="3_10"} 13417
telemt_desync_frames_bucket_total{bucket="gt_10"} 13450
telemt_pool_swap_total 142
telemt_pool_force_close_total 4746
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 728
telemt_me_draining_writers_reap_progress_total 44294
telemt_me_writer_removed_unexpected_total 985
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3743
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40993
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4428
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 318
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39548
telemt_me_writer_teardown_success_total{mode="normal"} 44736
telemt_me_writer_teardown_noop_total 44338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89074
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 192.907133
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89074
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 728
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 911
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 7969791
telemt_user_connections_current{user="hello"} 4802
telemt_user_octets_from_client{user="hello"} 129285830612 (120.41 GB)
telemt_user_octets_to_client{user="hello"} 2599062781772 (2.36 TB)
telemt_user_unique_ips_current{user="hello"} 1779
telemt_user_unique_ips_recent_window{user="hello"} 753
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 131907.0 (36h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8200267
telemt_connections_bad_total 735523
telemt_connections_current 3623
telemt_connections_me_current 3623
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 261124
telemt_upstream_connect_attempt_total 54525
telemt_upstream_connect_success_total 54041
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 54287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26437
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2937
telemt_me_reconnect_success_total 1113
telemt_me_reader_eof_total 1026
telemt_me_idle_close_by_peer_total 1026
telemt_me_route_drop_no_conn_total 2802611
telemt_me_route_drop_channel_closed_total 329
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6070170
telemt_me_endpoint_quarantine_total 837
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 1016
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
telemt_me_writers_active_current 47
telemt_desync_total 27914
telemt_desync_full_logged_total 9474
telemt_desync_suppressed_total 18440
telemt_desync_frames_bucket_total{bucket="1_2"} 6757
telemt_desync_frames_bucket_total{bucket="3_10"} 10795
telemt_desync_frames_bucket_total{bucket="gt_10"} 10362
telemt_pool_swap_total 144
telemt_pool_force_close_total 4337
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 470
telemt_me_draining_writers_reap_progress_total 42481
telemt_me_writer_removed_unexpected_total 1044
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3636
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39782
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4075
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 262
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38144
telemt_me_writer_teardown_success_total{mode="normal"} 43418
telemt_me_writer_teardown_noop_total 42487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85905
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 61.919745
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85905
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 470
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 938
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 5992486
telemt_user_connections_current{user="hello"} 3623
telemt_user_octets_from_client{user="hello"} 163732164763 (152.49 GB)
telemt_user_octets_to_client{user="hello"} 2856175151742 (2.60 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1402
telemt_user_unique_ips_recent_window{user="hello"} 585
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 131871.1 (36h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7864402
telemt_connections_bad_total 657242
telemt_connections_current 4810
telemt_connections_me_current 4810
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 260145
telemt_upstream_connect_attempt_total 59152
telemt_upstream_connect_success_total 58468
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 58615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27523
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2989
telemt_me_reconnect_success_total 1363
telemt_me_reader_eof_total 1258
telemt_me_idle_close_by_peer_total 1258
telemt_me_route_drop_no_conn_total 3173104
telemt_me_route_drop_channel_closed_total 202
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5862452
telemt_me_endpoint_quarantine_total 915
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 969
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
telemt_me_writers_active_current 128
telemt_desync_total 27516
telemt_desync_full_logged_total 9370
telemt_desync_suppressed_total 18146
telemt_desync_frames_bucket_total{bucket="1_2"} 6655
telemt_desync_frames_bucket_total{bucket="3_10"} 10564
telemt_desync_frames_bucket_total{bucket="gt_10"} 10297
telemt_pool_swap_total 139
telemt_pool_force_close_total 4147
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 486
telemt_me_draining_writers_reap_progress_total 43443
telemt_me_writer_removed_unexpected_total 1276
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3982
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40721
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3834
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39296
telemt_me_writer_teardown_success_total{mode="normal"} 44703
telemt_me_writer_teardown_noop_total 43455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88158
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.024455
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88158
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 486
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 1200
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 5855304
telemt_user_connections_current{user="hello"} 4810
telemt_user_octets_from_client{user="hello"} 150517290995 (140.18 GB)
telemt_user_octets_to_client{user="hello"} 2597616192779 (2.36 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1993
telemt_user_unique_ips_recent_window{user="hello"} 598
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 2151.0 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 860955
telemt_connections_bad_total 75233
telemt_connections_current 6377
telemt_connections_me_current 6377
telemt_handshake_timeouts_total 10097
telemt_upstream_connect_attempt_total 857
telemt_upstream_connect_success_total 805
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 155
telemt_me_reconnect_success_total 56
telemt_me_reader_eof_total 54
telemt_me_idle_close_by_peer_total 54
telemt_me_route_drop_no_conn_total 1898707
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 707911
telemt_me_endpoint_quarantine_total 11
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 22
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
telemt_me_writers_active_current 43
telemt_desync_total 1242
telemt_desync_full_logged_total 318
telemt_desync_suppressed_total 924
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 494
telemt_desync_frames_bucket_total{bucket="gt_10"} 498
telemt_pool_swap_total 1
telemt_pool_force_close_total 62
telemt_me_writer_close_signal_drop_total 19
telemt_me_draining_writers_reap_progress_total 622
telemt_me_writer_removed_unexpected_total 55
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 97
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 580
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 26
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 560
telemt_me_writer_teardown_success_total{mode="normal"} 677
telemt_me_writer_teardown_noop_total 622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1299
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.510213
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1299
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 19
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 46
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 707740
telemt_user_connections_current{user="hello"} 6373
telemt_user_octets_from_client{user="hello"} 4995367660 (4.65 GB)
telemt_user_octets_to_client{user="hello"} 21819023688 (20.32 GB)
telemt_user_unique_ips_current{user="hello"} 2296
telemt_user_unique_ips_recent_window{user="hello"} 1281
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 131877.9 (36h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7497716
telemt_connections_bad_total 672319
telemt_connections_current 5584
telemt_connections_me_current 5584
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 153844
telemt_upstream_connect_attempt_total 75328
telemt_upstream_connect_success_total 74508
telemt_upstream_connect_fail_total 702
telemt_upstream_connect_attempts_per_request{bucket="1"} 75210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28587
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 442
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 702
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70430
telemt_me_reconnect_success_total 2071
telemt_me_reader_eof_total 1816
telemt_me_idle_close_by_peer_total 1815
telemt_me_route_drop_no_conn_total 2976037
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5893256
telemt_me_endpoint_quarantine_total 885
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 996
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
telemt_me_writers_active_current 92
telemt_desync_total 29748
telemt_desync_full_logged_total 10326
telemt_desync_suppressed_total 19422
telemt_desync_frames_bucket_total{bucket="1_2"} 5942
telemt_desync_frames_bucket_total{bucket="3_10"} 11445
telemt_desync_frames_bucket_total{bucket="gt_10"} 12361
telemt_pool_swap_total 137
telemt_pool_force_close_total 3932
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 466
telemt_me_draining_writers_reap_progress_total 45676
telemt_me_writer_removed_unexpected_total 1846
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4654
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42894
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3490
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 442
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41744
telemt_me_writer_teardown_success_total{mode="normal"} 47548
telemt_me_writer_teardown_noop_total 45677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93225
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.378361
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93225
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 466
telemt_me_refill_failed_total 4229
telemt_me_writer_restored_same_endpoint_total 1719
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 5891362
telemt_user_connections_current{user="hello"} 5584
telemt_user_octets_from_client{user="hello"} 148249849507 (138.07 GB)
telemt_user_octets_to_client{user="hello"} 2421512110651 (2.20 TB)
telemt_user_msgs_from_client{user="hello"} 115484
telemt_user_msgs_to_client{user="hello"} 517108
telemt_user_unique_ips_current{user="hello"} 2144
telemt_user_unique_ips_recent_window{user="hello"} 618
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 68713.8 (19h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6062248
telemt_connections_bad_total 236561
telemt_connections_current 3224
telemt_connections_me_current 3224
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2422341
telemt_upstream_connect_attempt_total 36800
telemt_upstream_connect_success_total 36543
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 36793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14900
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_reconnect_attempts_total 47465
telemt_me_reconnect_success_total 1241
telemt_me_reader_eof_total 907
telemt_me_idle_close_by_peer_total 907
telemt_me_route_drop_no_conn_total 1552693
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3034209
telemt_me_endpoint_quarantine_total 477
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 53
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 53
telemt_me_single_endpoint_shadow_rotate_total 525
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 16637
telemt_desync_full_logged_total 5621
telemt_desync_suppressed_total 11016
telemt_desync_frames_bucket_total{bucket="1_2"} 3269
telemt_desync_frames_bucket_total{bucket="3_10"} 6395
telemt_desync_frames_bucket_total{bucket="gt_10"} 6973
telemt_pool_swap_total 73
telemt_pool_force_close_total 2213
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 211
telemt_me_draining_writers_reap_progress_total 24824
telemt_me_writer_removed_unexpected_total 978
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2174
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23650
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1903
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 310
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22611
telemt_me_writer_teardown_success_total{mode="normal"} 25824
telemt_me_writer_teardown_noop_total 24830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50654
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.715255
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50654
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 211
telemt_me_refill_failed_total 2688
telemt_me_writer_restored_same_endpoint_total 1108
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3034965
telemt_user_connections_current{user="hello"} 3224
telemt_user_octets_from_client{user="hello"} 76261079960 (71.02 GB)
telemt_user_octets_to_client{user="hello"} 1312670773486 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1308
telemt_user_unique_ips_recent_window{user="hello"} 560
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 49684.7 (13h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 457595
telemt_connections_bad_total 3413
telemt_connections_current 872
telemt_connections_me_current 872
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 8761
telemt_upstream_connect_attempt_total 26307
telemt_upstream_connect_success_total 26244
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 26302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13662
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 258
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1039
telemt_me_reconnect_success_total 411
telemt_me_reader_eof_total 408
telemt_me_idle_close_by_peer_total 408
telemt_me_route_drop_no_conn_total 148175
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 413199
telemt_me_endpoint_quarantine_total 462
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 425
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_me_writers_active_current 54
telemt_me_writers_warm_current 32
telemt_desync_total 1938
telemt_desync_full_logged_total 561
telemt_desync_suppressed_total 1377
telemt_desync_frames_bucket_total{bucket="1_2"} 556
telemt_desync_frames_bucket_total{bucket="3_10"} 755
telemt_desync_frames_bucket_total{bucket="gt_10"} 627
telemt_pool_swap_total 53
telemt_pool_force_close_total 1222
telemt_me_writer_close_signal_drop_total 47
telemt_me_draining_writers_reap_progress_total 21143
telemt_me_writer_removed_unexpected_total 391
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1507
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20044
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1194
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19921
telemt_me_writer_teardown_success_total{mode="normal"} 21551
telemt_me_writer_teardown_noop_total 21143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42694
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.972039
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42694
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 47
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 360
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 415329
telemt_user_connections_current{user="hello"} 872
telemt_user_octets_from_client{user="hello"} 8291672985 (7.72 GB)
telemt_user_octets_to_client{user="hello"} 208496626179 (194.18 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 131882.1 (36h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9238038
telemt_connections_bad_total 1072383
telemt_connections_current 5385
telemt_connections_me_current 5385
telemt_handshake_timeouts_total 253375
telemt_upstream_connect_attempt_total 51110
telemt_upstream_connect_success_total 50915
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 51066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25683
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_reconnect_attempts_total 1914
telemt_me_reconnect_success_total 1044
telemt_me_reader_eof_total 1015
telemt_me_idle_close_by_peer_total 1015
telemt_me_route_drop_no_conn_total 2609253
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6845970
telemt_me_endpoint_quarantine_total 937
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1004
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 27617
telemt_desync_full_logged_total 9042
telemt_desync_suppressed_total 18575
telemt_desync_frames_bucket_total{bucket="1_2"} 6827
telemt_desync_frames_bucket_total{bucket="3_10"} 10071
telemt_desync_frames_bucket_total{bucket="gt_10"} 10719
telemt_pool_swap_total 146
telemt_pool_force_close_total 3930
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 478
telemt_me_draining_writers_reap_progress_total 46106
telemt_me_writer_removed_unexpected_total 976
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3696
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43416
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3828
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 102
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42176
telemt_me_writer_teardown_success_total{mode="normal"} 47112
telemt_me_writer_teardown_noop_total 46108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93220
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.754878
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93220
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 478
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 916
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 6818731
telemt_user_connections_current{user="hello"} 5385
telemt_user_octets_from_client{user="hello"} 132425966960 (123.33 GB)
telemt_user_octets_to_client{user="hello"} 3197754240568 (2.91 TB)
telemt_user_unique_ips_current{user="hello"} 2053
telemt_user_unique_ips_recent_window{user="hello"} 674
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 131878.8 (36h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8031892
telemt_connections_bad_total 891220
telemt_connections_current 4315
telemt_connections_me_current 4315
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 211661
telemt_upstream_connect_attempt_total 75530
telemt_upstream_connect_success_total 74997
telemt_upstream_connect_fail_total 464
telemt_upstream_connect_attempts_per_request{bucket="1"} 75461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30148
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1965
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 464
telemt_me_reconnect_attempts_total 6478
telemt_me_reconnect_success_total 1491
telemt_me_reader_eof_total 1334
telemt_me_idle_close_by_peer_total 1334
telemt_me_seq_mismatch_total 62
telemt_me_route_drop_no_conn_total 2806228
telemt_me_route_drop_channel_closed_total 240
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6115976
telemt_me_endpoint_quarantine_total 1033
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1001
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
telemt_desync_total 26542
telemt_desync_full_logged_total 8814
telemt_desync_suppressed_total 17728
telemt_desync_frames_bucket_total{bucket="1_2"} 6527
telemt_desync_frames_bucket_total{bucket="3_10"} 9750
telemt_desync_frames_bucket_total{bucket="gt_10"} 10265
telemt_pool_swap_total 143
telemt_pool_force_close_total 3853
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 475
telemt_me_draining_writers_reap_progress_total 44718
telemt_me_writer_removed_unexpected_total 1350
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4332
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41798
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3576
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 277
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40865
telemt_me_writer_teardown_success_total{mode="normal"} 46130
telemt_me_writer_teardown_noop_total 44722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90852
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.286611
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90852
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 475
telemt_me_refill_failed_total 287
telemt_me_writer_restored_same_endpoint_total 1164
telemt_me_writer_restored_fallback_total 86
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 112
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 6124758
telemt_user_connections_current{user="hello"} 4315
telemt_user_octets_from_client{user="hello"} 112317805153 (104.60 GB)
telemt_user_octets_to_client{user="hello"} 2619265942503 (2.38 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1616
telemt_user_unique_ips_recent_window{user="hello"} 598
```
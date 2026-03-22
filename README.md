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

# Server Metrics 2026-03-22 10:46:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 49200.3 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1327644
telemt_connections_bad_total 69202
telemt_connections_current 1950
telemt_connections_me_current 1950
telemt_handshake_timeouts_total 61006
telemt_upstream_connect_attempt_total 18980
telemt_upstream_connect_success_total 18979
telemt_upstream_connect_attempts_per_request{bucket="1"} 18979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12367
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 626
telemt_me_reconnect_success_total 301
telemt_me_reader_eof_total 300
telemt_me_idle_close_by_peer_total 300
telemt_me_route_drop_no_conn_total 728282
telemt_me_route_drop_channel_closed_total 352
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1110800
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 346
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 395
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
telemt_me_writers_active_current 44
telemt_desync_total 7265
telemt_desync_full_logged_total 2141
telemt_desync_suppressed_total 5124
telemt_desync_frames_bucket_total{bucket="1_2"} 2107
telemt_desync_frames_bucket_total{bucket="3_10"} 2741
telemt_desync_frames_bucket_total{bucket="gt_10"} 2417
telemt_pool_swap_total 54
telemt_pool_force_close_total 1578
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 213
telemt_me_draining_writers_reap_progress_total 17273
telemt_me_writer_removed_unexpected_total 295
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1201
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16287
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1543
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15695
telemt_me_writer_teardown_success_total{mode="normal"} 17488
telemt_me_writer_teardown_noop_total 17275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34763
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 93.741418
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34763
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 213
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1108855
telemt_user_connections_current{user="hello"} 1950
telemt_user_octets_from_client{user="hello"} 17842988356 (16.62 GB)
telemt_user_octets_to_client{user="hello"} 349774980860 (325.75 GB)
telemt_user_unique_ips_current{user="hello"} 658
telemt_user_unique_ips_recent_window{user="hello"} 291
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 62566.7 (17h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2134070
telemt_connections_bad_total 177377
telemt_connections_current 1316
telemt_connections_me_current 1316
telemt_handshake_timeouts_total 51085
telemt_upstream_connect_attempt_total 36689
telemt_upstream_connect_success_total 36192
telemt_upstream_connect_fail_total 437
telemt_upstream_connect_attempts_per_request{bucket="1"} 36629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 437
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3172
telemt_me_reconnect_success_total 1419
telemt_me_reader_eof_total 1304
telemt_me_idle_close_by_peer_total 1304
telemt_me_route_drop_no_conn_total 1626621
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1675155
telemt_me_endpoint_quarantine_total 538
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 495
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
telemt_me_writers_active_current 43
telemt_desync_total 6918
telemt_desync_full_logged_total 3914
telemt_desync_suppressed_total 3004
telemt_desync_frames_bucket_total{bucket="1_2"} 1575
telemt_desync_frames_bucket_total{bucket="3_10"} 2705
telemt_desync_frames_bucket_total{bucket="gt_10"} 2638
telemt_pool_swap_total 63
telemt_pool_force_close_total 1783
telemt_me_writer_close_signal_drop_total 145
telemt_me_draining_writers_reap_progress_total 25187
telemt_me_writer_removed_unexpected_total 1270
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2739
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23712
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1599
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 184
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23404
telemt_me_writer_teardown_success_total{mode="normal"} 26451
telemt_me_writer_teardown_noop_total 25187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51638
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.573514
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51638
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 145
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1179
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1681113
telemt_user_connections_current{user="hello"} 1316
telemt_user_octets_from_client{user="hello"} 22780888774 (21.22 GB)
telemt_user_octets_to_client{user="hello"} 457182032456 (425.78 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 845
telemt_user_unique_ips_recent_window{user="hello"} 566
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 137427.4 (38h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11489511
telemt_connections_bad_total 973008
telemt_connections_current 4684
telemt_connections_me_current 4684
telemt_handshake_timeouts_total 313021
telemt_upstream_connect_attempt_total 50157
telemt_upstream_connect_success_total 50077
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 50085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 205
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2142
telemt_me_reconnect_success_total 1101
telemt_me_reader_eof_total 1082
telemt_me_idle_close_by_peer_total 1081
telemt_me_route_drop_no_conn_total 8374723
telemt_me_route_drop_channel_closed_total 99
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9156477
telemt_me_endpoint_quarantine_total 880
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1024
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
telemt_me_writers_active_current 44
telemt_desync_total 38042
telemt_desync_full_logged_total 12308
telemt_desync_suppressed_total 25734
telemt_desync_frames_bucket_total{bucket="1_2"} 8566
telemt_desync_frames_bucket_total{bucket="3_10"} 14805
telemt_desync_frames_bucket_total{bucket="gt_10"} 14671
telemt_pool_swap_total 148
telemt_pool_force_close_total 4973
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 777
telemt_me_draining_writers_reap_progress_total 45749
telemt_me_writer_removed_unexpected_total 1042
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3917
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42298
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4639
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 334
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40776
telemt_me_writer_teardown_success_total{mode="normal"} 46215
telemt_me_writer_teardown_noop_total 45793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92008
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 209.520311
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92008
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 777
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 958
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 9145769
telemt_user_connections_current{user="hello"} 4684
telemt_user_octets_from_client{user="hello"} 141496993620 (131.78 GB)
telemt_user_octets_to_client{user="hello"} 2718622940928 (2.47 TB)
telemt_user_unique_ips_current{user="hello"} 1774
telemt_user_unique_ips_recent_window{user="hello"} 764
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 137428.0 (38h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8946857
telemt_connections_bad_total 801051
telemt_connections_current 4687
telemt_connections_me_current 4687
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 273964
telemt_upstream_connect_attempt_total 56575
telemt_upstream_connect_success_total 56006
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 56267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27475
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3086
telemt_me_reconnect_success_total 1239
telemt_me_reader_eof_total 1128
telemt_me_idle_close_by_peer_total 1128
telemt_me_route_drop_no_conn_total 3618374
telemt_me_route_drop_channel_closed_total 370
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6662746
telemt_me_endpoint_quarantine_total 869
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 1053
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
telemt_me_writers_active_current 44
telemt_desync_total 30086
telemt_desync_full_logged_total 10188
telemt_desync_suppressed_total 19898
telemt_desync_frames_bucket_total{bucket="1_2"} 7341
telemt_desync_frames_bucket_total{bucket="3_10"} 11597
telemt_desync_frames_bucket_total{bucket="gt_10"} 11148
telemt_pool_swap_total 148
telemt_pool_force_close_total 4513
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 510
telemt_me_draining_writers_reap_progress_total 44216
telemt_me_writer_removed_unexpected_total 1163
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3852
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41421
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4182
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 331
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39703
telemt_me_writer_teardown_success_total{mode="normal"} 45273
telemt_me_writer_teardown_noop_total 44222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89495
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 66.107400
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89495
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 510
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 1057
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 6584369
telemt_user_connections_current{user="hello"} 4687
telemt_user_octets_from_client{user="hello"} 173040849047 (161.16 GB)
telemt_user_octets_to_client{user="hello"} 3037173760318 (2.76 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1820
telemt_user_unique_ips_recent_window{user="hello"} 665
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 137393.3 (38h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8487852
telemt_connections_bad_total 708311
telemt_connections_current 4325
telemt_connections_me_current 4325
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 273189
telemt_upstream_connect_attempt_total 60897
telemt_upstream_connect_success_total 60193
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 60340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28399
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 999
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1379
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3582
telemt_me_reconnect_success_total 1485
telemt_me_reader_eof_total 1372
telemt_me_idle_close_by_peer_total 1372
telemt_me_route_drop_no_conn_total 3583328
telemt_me_route_drop_channel_closed_total 238
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6367060
telemt_me_endpoint_quarantine_total 946
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 1006
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 29407
telemt_desync_full_logged_total 10018
telemt_desync_suppressed_total 19389
telemt_desync_frames_bucket_total{bucket="1_2"} 7091
telemt_desync_frames_bucket_total{bucket="3_10"} 11337
telemt_desync_frames_bucket_total{bucket="gt_10"} 10979
telemt_pool_swap_total 145
telemt_pool_force_close_total 4427
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 526
telemt_me_draining_writers_reap_progress_total 45012
telemt_me_writer_removed_unexpected_total 1397
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4230
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42117
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4031
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 396
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40585
telemt_me_writer_teardown_success_total{mode="normal"} 46347
telemt_me_writer_teardown_noop_total 45029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91376
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.653805
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91376
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 526
telemt_me_refill_failed_total 108
telemt_me_writer_restored_same_endpoint_total 1306
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 6358636
telemt_user_connections_current{user="hello"} 4325
telemt_user_octets_from_client{user="hello"} 157600351035 (146.78 GB)
telemt_user_octets_to_client{user="hello"} 2764390078179 (2.51 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1686
telemt_user_unique_ips_recent_window{user="hello"} 588
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 7672.0 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3283392
telemt_connections_bad_total 221684
telemt_connections_current 6671
telemt_connections_me_current 6671
telemt_handshake_timeouts_total 49802
telemt_upstream_connect_attempt_total 9361
telemt_upstream_connect_success_total 8864
telemt_upstream_connect_fail_total 347
telemt_upstream_connect_attempts_per_request{bucket="1"} 9211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1972
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2715
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 347
telemt_me_keepalive_timeout_total 373
telemt_me_reconnect_attempts_total 547
telemt_me_reconnect_success_total 220
telemt_me_reader_eof_total 152
telemt_me_idle_close_by_peer_total 152
telemt_me_route_drop_no_conn_total 7479545
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2737799
telemt_me_endpoint_quarantine_total 52
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_writers_active_current 50
telemt_desync_total 4011
telemt_desync_full_logged_total 1045
telemt_desync_suppressed_total 2966
telemt_desync_frames_bucket_total{bucket="1_2"} 723
telemt_desync_frames_bucket_total{bucket="3_10"} 1555
telemt_desync_frames_bucket_total{bucket="gt_10"} 1733
telemt_pool_swap_total 6
telemt_pool_force_close_total 270
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 100
telemt_me_draining_writers_reap_progress_total 2048
telemt_me_writer_removed_unexpected_total 196
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 352
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1874
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 164
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 106
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1778
telemt_me_writer_teardown_success_total{mode="normal"} 2226
telemt_me_writer_teardown_noop_total 2050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4276
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.815648
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4276
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 100
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 156
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 2741703
telemt_user_connections_current{user="hello"} 6672
telemt_user_octets_from_client{user="hello"} 14300367778 (13.32 GB)
telemt_user_octets_to_client{user="hello"} 80921906891 (75.36 GB)
telemt_user_msgs_from_client{user="hello"} 6014
telemt_user_msgs_to_client{user="hello"} 4995
telemt_user_unique_ips_current{user="hello"} 2473
telemt_user_unique_ips_recent_window{user="hello"} 1377
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 137398.8 (38h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8179521
telemt_connections_bad_total 709688
telemt_connections_current 4867
telemt_connections_me_current 4867
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 167725
telemt_upstream_connect_attempt_total 86162
telemt_upstream_connect_success_total 85307
telemt_upstream_connect_fail_total 735
telemt_upstream_connect_attempts_per_request{bucket="1"} 86042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30362
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 735
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70649
telemt_me_reconnect_success_total 2176
telemt_me_reader_eof_total 1913
telemt_me_idle_close_by_peer_total 1912
telemt_me_route_drop_no_conn_total 3598579
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6461630
telemt_me_endpoint_quarantine_total 923
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1033
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
telemt_me_writers_active_current 44
telemt_desync_total 32716
telemt_desync_full_logged_total 11293
telemt_desync_suppressed_total 21423
telemt_desync_frames_bucket_total{bucket="1_2"} 6685
telemt_desync_frames_bucket_total{bucket="3_10"} 12569
telemt_desync_frames_bucket_total{bucket="gt_10"} 13462
telemt_pool_swap_total 142
telemt_pool_force_close_total 4130
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 502
telemt_me_draining_writers_reap_progress_total 47349
telemt_me_writer_removed_unexpected_total 1942
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4889
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44427
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3600
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 530
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43219
telemt_me_writer_teardown_success_total{mode="normal"} 49316
telemt_me_writer_teardown_noop_total 47350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96666
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.547691
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96666
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 502
telemt_me_refill_failed_total 4234
telemt_me_writer_restored_same_endpoint_total 1808
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 6465209
telemt_user_connections_current{user="hello"} 4867
telemt_user_octets_from_client{user="hello"} 156251632459 (145.52 GB)
telemt_user_octets_to_client{user="hello"} 2564775312885 (2.33 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1983
telemt_user_unique_ips_recent_window{user="hello"} 693
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 74234.9 (20h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7223343
telemt_connections_bad_total 268675
telemt_connections_current 3892
telemt_connections_me_current 3892
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2964435
telemt_upstream_connect_attempt_total 38713
telemt_upstream_connect_success_total 38432
telemt_upstream_connect_fail_total 274
telemt_upstream_connect_attempts_per_request{bucket="1"} 38706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 274
telemt_me_reconnect_attempts_total 47693
telemt_me_reconnect_success_total 1331
telemt_me_reader_eof_total 994
telemt_me_idle_close_by_peer_total 994
telemt_me_route_drop_no_conn_total 2215087
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3571314
telemt_me_endpoint_quarantine_total 508
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 567
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 19292
telemt_desync_full_logged_total 6481
telemt_desync_suppressed_total 12811
telemt_desync_frames_bucket_total{bucket="1_2"} 3933
telemt_desync_frames_bucket_total{bucket="3_10"} 7409
telemt_desync_frames_bucket_total{bucket="gt_10"} 7950
telemt_pool_swap_total 78
telemt_pool_force_close_total 2395
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 234
telemt_me_draining_writers_reap_progress_total 26490
telemt_me_writer_removed_unexpected_total 1063
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2365
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25212
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2041
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 354
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24095
telemt_me_writer_teardown_success_total{mode="normal"} 27577
telemt_me_writer_teardown_noop_total 26496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54073
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.228592
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54073
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 234
telemt_me_refill_failed_total 2695
telemt_me_writer_restored_same_endpoint_total 1186
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3570247
telemt_user_connections_current{user="hello"} 3892
telemt_user_octets_from_client{user="hello"} 84814754156 (78.99 GB)
telemt_user_octets_to_client{user="hello"} 1456029569546 (1.32 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1575
telemt_user_unique_ips_recent_window{user="hello"} 619
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 55205.6 (15h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 565886
telemt_connections_bad_total 3931
telemt_connections_current 961
telemt_connections_me_current 961
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 10419
telemt_upstream_connect_attempt_total 29038
telemt_upstream_connect_success_total 28971
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 29031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15189
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 302
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 1206
telemt_me_reconnect_success_total 513
telemt_me_reader_eof_total 510
telemt_me_idle_close_by_peer_total 510
telemt_me_route_drop_no_conn_total 185858
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 512765
telemt_me_endpoint_quarantine_total 498
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 467
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
telemt_me_writers_active_current 43
telemt_desync_total 2665
telemt_desync_full_logged_total 764
telemt_desync_suppressed_total 1901
telemt_desync_frames_bucket_total{bucket="1_2"} 750
telemt_desync_frames_bucket_total{bucket="3_10"} 1034
telemt_desync_frames_bucket_total{bucket="gt_10"} 881
telemt_pool_swap_total 58
telemt_pool_force_close_total 1408
telemt_me_writer_close_signal_drop_total 73
telemt_me_draining_writers_reap_progress_total 23618
telemt_me_writer_removed_unexpected_total 494
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1751
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22378
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1332
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22210
telemt_me_writer_teardown_success_total{mode="normal"} 24129
telemt_me_writer_teardown_noop_total 23618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47747
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.560994
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47747
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 73
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 459
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 514697
telemt_user_connections_current{user="hello"} 961
telemt_user_octets_from_client{user="hello"} 9934409129 (9.25 GB)
telemt_user_octets_to_client{user="hello"} 244831627627 (228.02 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 360
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 137403.7 (38h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9946863
telemt_connections_bad_total 1163921
telemt_connections_current 5690
telemt_connections_me_current 5690
telemt_handshake_timeouts_total 265669
telemt_upstream_connect_attempt_total 52702
telemt_upstream_connect_success_total 52502
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 52656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26523
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_reconnect_attempts_total 2035
telemt_me_reconnect_success_total 1082
telemt_me_reader_eof_total 1049
telemt_me_idle_close_by_peer_total 1049
telemt_me_route_drop_no_conn_total 2860642
telemt_me_route_drop_channel_closed_total 73
telemt_me_route_drop_queue_full_total 29
telemt_me_route_drop_queue_full_profile_total{profile="high"} 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7409336
telemt_me_endpoint_quarantine_total 964
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1036
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
telemt_desync_total 30115
telemt_desync_full_logged_total 9878
telemt_desync_suppressed_total 20237
telemt_desync_frames_bucket_total{bucket="1_2"} 7397
telemt_desync_frames_bucket_total{bucket="3_10"} 11021
telemt_desync_frames_bucket_total{bucket="gt_10"} 11697
telemt_pool_swap_total 152
telemt_pool_force_close_total 4117
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 502
telemt_me_draining_writers_reap_progress_total 47530
telemt_me_writer_removed_unexpected_total 1008
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3836
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44734
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3999
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 118
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43413
telemt_me_writer_teardown_success_total{mode="normal"} 48570
telemt_me_writer_teardown_noop_total 47532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96102
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.176438
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96102
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 502
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 947
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 7381182
telemt_user_connections_current{user="hello"} 5690
telemt_user_octets_from_client{user="hello"} 142625381732 (132.83 GB)
telemt_user_octets_to_client{user="hello"} 3431055587732 (3.12 TB)
telemt_user_unique_ips_current{user="hello"} 2090
telemt_user_unique_ips_recent_window{user="hello"} 779
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 137399.9 (38h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8650726
telemt_connections_bad_total 978995
telemt_connections_current 5006
telemt_connections_me_current 5006
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 222517
telemt_upstream_connect_attempt_total 77211
telemt_upstream_connect_success_total 76663
telemt_upstream_connect_fail_total 479
telemt_upstream_connect_attempts_per_request{bucket="1"} 77142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30990
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1968
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 479
telemt_me_reconnect_attempts_total 6594
telemt_me_reconnect_success_total 1554
telemt_me_reader_eof_total 1378
telemt_me_idle_close_by_peer_total 1378
telemt_me_seq_mismatch_total 65
telemt_me_route_drop_no_conn_total 3110735
telemt_me_route_drop_channel_closed_total 272
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6608654
telemt_me_endpoint_quarantine_total 1066
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1039
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
telemt_me_writers_active_current 44
telemt_desync_total 29272
telemt_desync_full_logged_total 9653
telemt_desync_suppressed_total 19619
telemt_desync_frames_bucket_total{bucket="1_2"} 7216
telemt_desync_frames_bucket_total{bucket="3_10"} 10810
telemt_desync_frames_bucket_total{bucket="gt_10"} 11246
telemt_pool_swap_total 149
telemt_pool_force_close_total 4050
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 498
telemt_me_draining_writers_reap_progress_total 46228
telemt_me_writer_removed_unexpected_total 1396
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4487
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43200
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3751
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 299
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42178
telemt_me_writer_teardown_success_total{mode="normal"} 47687
telemt_me_writer_teardown_noop_total 46232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93919
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.651507
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93919
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 498
telemt_me_refill_failed_total 290
telemt_me_writer_restored_same_endpoint_total 1210
telemt_me_writer_restored_fallback_total 89
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 6616749
telemt_user_connections_current{user="hello"} 5006
telemt_user_octets_from_client{user="hello"} 119600343613 (111.39 GB)
telemt_user_octets_to_client{user="hello"} 2776296555295 (2.53 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1897
telemt_user_unique_ips_recent_window{user="hello"} 677
```
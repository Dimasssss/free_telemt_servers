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

# Server Metrics 2026-03-22 17:56:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 74992.9 (20h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2717386
telemt_connections_bad_total 157897
telemt_connections_current 1474
telemt_connections_me_current 1474
telemt_handshake_timeouts_total 92888
telemt_upstream_connect_attempt_total 27611
telemt_upstream_connect_success_total 27610
telemt_upstream_connect_attempts_per_request{bucket="1"} 27610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17951
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 65
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1123
telemt_me_reconnect_success_total 475
telemt_me_reader_eof_total 477
telemt_me_idle_close_by_peer_total 477
telemt_me_route_drop_no_conn_total 2225384
telemt_me_route_drop_channel_closed_total 933
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2311088
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 512
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 585
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
telemt_desync_total 10631
telemt_desync_full_logged_total 3369
telemt_desync_suppressed_total 7262
telemt_desync_frames_bucket_total{bucket="1_2"} 2845
telemt_desync_frames_bucket_total{bucket="3_10"} 3953
telemt_desync_frames_bucket_total{bucket="gt_10"} 3833
telemt_pool_swap_total 83
telemt_pool_force_close_total 2570
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 528
telemt_me_draining_writers_reap_progress_total 25220
telemt_me_writer_removed_unexpected_total 463
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1850
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23602
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2518
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 52
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22650
telemt_me_writer_teardown_success_total{mode="normal"} 25452
telemt_me_writer_teardown_noop_total 25230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50682
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 251.546526
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50682
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 528
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 420
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 2307280
telemt_user_connections_current{user="hello"} 1474
telemt_user_octets_from_client{user="hello"} 34055710900 (31.72 GB)
telemt_user_octets_to_client{user="hello"} 611302459292 (569.32 GB)
telemt_user_unique_ips_current{user="hello"} 539
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 88359.6 (24h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3705543
telemt_connections_bad_total 335339
telemt_connections_current 1034
telemt_connections_me_current 1034
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 94337
telemt_upstream_connect_attempt_total 54363
telemt_upstream_connect_success_total 53690
telemt_upstream_connect_fail_total 593
telemt_upstream_connect_attempts_per_request{bucket="1"} 54283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 593
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6261
telemt_me_reconnect_success_total 2269
telemt_me_reader_eof_total 2201
telemt_me_idle_close_by_peer_total 2201
telemt_me_route_drop_no_conn_total 3566378
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2940351
telemt_me_endpoint_quarantine_total 700
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 681
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
telemt_me_writers_active_current 45
telemt_desync_total 11581
telemt_desync_full_logged_total 6471
telemt_desync_suppressed_total 5110
telemt_desync_frames_bucket_total{bucket="1_2"} 2685
telemt_desync_frames_bucket_total{bucket="3_10"} 4541
telemt_desync_frames_bucket_total{bucket="gt_10"} 4355
telemt_pool_swap_total 84
telemt_pool_force_close_total 2495
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 211
telemt_me_draining_writers_reap_progress_total 34993
telemt_me_writer_removed_unexpected_total 2151
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4170
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32985
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2133
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 362
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32498
telemt_me_writer_teardown_success_total{mode="normal"} 37155
telemt_me_writer_teardown_noop_total 34993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72148
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.283420
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72148
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 211
telemt_me_refill_failed_total 158
telemt_me_writer_restored_same_endpoint_total 1959
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 2951249
telemt_user_connections_current{user="hello"} 1034
telemt_user_octets_from_client{user="hello"} 37992375447 (35.38 GB)
telemt_user_octets_to_client{user="hello"} 676032264250 (629.60 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 632
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 163220.0 (45h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15615366
telemt_connections_bad_total 1492625
telemt_connections_current 1969
telemt_connections_me_current 1969
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 383507
telemt_upstream_connect_attempt_total 73217
telemt_upstream_connect_success_total 73120
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 73137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34801
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1681
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2740
telemt_me_reconnect_success_total 1395
telemt_me_reader_eof_total 1335
telemt_me_idle_close_by_peer_total 1333
telemt_me_route_drop_no_conn_total 13879981
telemt_me_route_drop_channel_closed_total 141
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12449491
telemt_me_endpoint_quarantine_total 1028
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1217
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
telemt_me_writers_active_current 43
telemt_desync_total 51070
telemt_desync_full_logged_total 16033
telemt_desync_suppressed_total 35037
telemt_desync_frames_bucket_total{bucket="1_2"} 11408
telemt_desync_frames_bucket_total{bucket="3_10"} 19930
telemt_desync_frames_bucket_total{bucket="gt_10"} 19732
telemt_pool_swap_total 176
telemt_pool_force_close_total 5965
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 965
telemt_me_draining_writers_reap_progress_total 53644
telemt_me_writer_removed_unexpected_total 1289
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4690
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49534
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5503
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 462
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47679
telemt_me_writer_teardown_success_total{mode="normal"} 54224
telemt_me_writer_teardown_noop_total 53694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107918
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 305.457699
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107918
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 965
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1200
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 12450391
telemt_user_connections_current{user="hello"} 1969
telemt_user_octets_from_client{user="hello"} 180027784309 (167.66 GB)
telemt_user_octets_to_client{user="hello"} 3249427372751 (2.96 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 742
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 163220.7 (45h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11263363
telemt_connections_bad_total 1102766
telemt_connections_current 1398
telemt_connections_me_current 1398
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 337632
telemt_upstream_connect_attempt_total 85640
telemt_upstream_connect_success_total 84440
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 85278
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34707
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3701
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4047
telemt_me_reconnect_success_total 1677
telemt_me_reader_eof_total 1546
telemt_me_idle_close_by_peer_total 1546
telemt_me_route_drop_no_conn_total 4420696
telemt_me_route_drop_channel_closed_total 489
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8392945
telemt_me_endpoint_quarantine_total 1034
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1234
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
telemt_desync_total 37346
telemt_desync_full_logged_total 12565
telemt_desync_suppressed_total 24781
telemt_desync_frames_bucket_total{bucket="1_2"} 9179
telemt_desync_frames_bucket_total{bucket="3_10"} 14382
telemt_desync_frames_bucket_total{bucket="gt_10"} 13785
telemt_pool_swap_total 173
telemt_pool_force_close_total 5390
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 687
telemt_me_draining_writers_reap_progress_total 52058
telemt_me_writer_removed_unexpected_total 1585
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4832
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48655
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4892
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 498
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46668
telemt_me_writer_teardown_success_total{mode="normal"} 53487
telemt_me_writer_teardown_noop_total 52081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105568
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 102.411138
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105568
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 687
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 1437
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 8331426
telemt_user_connections_current{user="hello"} 1398
telemt_user_octets_from_client{user="hello"} 207981470341 (193.70 GB)
telemt_user_octets_to_client{user="hello"} 3756087372250 (3.42 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 554
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 163184.6 (45h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10614516
telemt_connections_bad_total 914557
telemt_connections_current 1395
telemt_connections_me_current 1395
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 339988
telemt_upstream_connect_attempt_total 70804
telemt_upstream_connect_success_total 69806
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 69988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33259
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1417
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4799
telemt_me_reconnect_success_total 1945
telemt_me_reader_eof_total 1698
telemt_me_idle_close_by_peer_total 1697
telemt_me_route_drop_no_conn_total 5181893
telemt_me_route_drop_channel_closed_total 368
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8012512
telemt_me_endpoint_quarantine_total 1112
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1203
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 36848
telemt_desync_full_logged_total 12190
telemt_desync_suppressed_total 24658
telemt_desync_frames_bucket_total{bucket="1_2"} 9314
telemt_desync_frames_bucket_total{bucket="3_10"} 14097
telemt_desync_frames_bucket_total{bucket="gt_10"} 13437
telemt_pool_swap_total 171
telemt_pool_force_close_total 5320
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 691
telemt_me_draining_writers_reap_progress_total 52389
telemt_me_writer_removed_unexpected_total 1838
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5254
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48888
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4777
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 543
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47069
telemt_me_writer_teardown_success_total{mode="normal"} 54142
telemt_me_writer_teardown_noop_total 52460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106602
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3172.338751
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106602
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 691
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 1682
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 8005260
telemt_user_connections_current{user="hello"} 1395
telemt_user_octets_from_client{user="hello"} 184862401445 (172.17 GB)
telemt_user_octets_to_client{user="hello"} 3332052928453 (3.03 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 506
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 33464.2 (9h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10452336
telemt_connections_bad_total 640674
telemt_connections_current 2474
telemt_connections_me_current 2474
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 207088
telemt_upstream_connect_attempt_total 41773
telemt_upstream_connect_success_total 39669
telemt_upstream_connect_fail_total 1483
telemt_upstream_connect_attempts_per_request{bucket="1"} 41152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20400
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11963
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5917
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1483
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6220
telemt_me_reconnect_success_total 798
telemt_me_reader_eof_total 502
telemt_me_idle_close_by_peer_total 502
telemt_me_route_drop_no_conn_total 25061579
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8687095
telemt_me_endpoint_quarantine_total 215
telemt_me_single_endpoint_outage_enter_total 60
telemt_me_single_endpoint_outage_exit_total 60
telemt_me_single_endpoint_outage_reconnect_attempt_total 111
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 111
telemt_me_single_endpoint_shadow_rotate_total 264
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_writers_active_current 45
telemt_desync_total 13797
telemt_desync_full_logged_total 3592
telemt_desync_suppressed_total 10205
telemt_desync_frames_bucket_total{bucket="1_2"} 2542
telemt_desync_frames_bucket_total{bucket="3_10"} 5605
telemt_desync_frames_bucket_total{bucket="gt_10"} 5650
telemt_pool_swap_total 33
telemt_pool_force_close_total 1215
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 387
telemt_me_draining_writers_reap_progress_total 9391
telemt_me_writer_removed_unexpected_total 704
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1465
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8593
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 933
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 282
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8176
telemt_me_writer_teardown_success_total{mode="normal"} 10058
telemt_me_writer_teardown_noop_total 9396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 17904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 18385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 18998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19454
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 42.175611
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19454
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 387
telemt_me_refill_failed_total 300
telemt_me_writer_restored_same_endpoint_total 534
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 8708794
telemt_user_connections_current{user="hello"} 2474
telemt_user_octets_from_client{user="hello"} 74491598711 (69.38 GB)
telemt_user_octets_to_client{user="hello"} 381852287489 (355.63 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 845
telemt_user_unique_ips_recent_window{user="hello"} 343
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 163190.9 (45h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10443990
telemt_connections_bad_total 878973
telemt_connections_current 1521
telemt_connections_me_current 1521
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 231586
telemt_upstream_connect_attempt_total 99506
telemt_upstream_connect_success_total 98475
telemt_upstream_connect_fail_total 876
telemt_upstream_connect_attempts_per_request{bucket="1"} 99351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36408
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1320
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 876
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72148
telemt_me_reconnect_success_total 2687
telemt_me_reader_eof_total 2388
telemt_me_idle_close_by_peer_total 2386
telemt_me_route_drop_no_conn_total 5120225
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8240886
telemt_me_endpoint_quarantine_total 1092
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1217
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 43523
telemt_desync_full_logged_total 14847
telemt_desync_suppressed_total 28676
telemt_desync_frames_bucket_total{bucket="1_2"} 8842
telemt_desync_frames_bucket_total{bucket="3_10"} 16750
telemt_desync_frames_bucket_total{bucket="gt_10"} 17931
telemt_pool_swap_total 167
telemt_pool_force_close_total 4966
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 619
telemt_me_draining_writers_reap_progress_total 55474
telemt_me_writer_removed_unexpected_total 2429
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5934
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51992
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4277
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 689
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50508
telemt_me_writer_teardown_success_total{mode="normal"} 57926
telemt_me_writer_teardown_noop_total 55475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113401
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.670955
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113401
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 619
telemt_me_refill_failed_total 4281
telemt_me_writer_restored_same_endpoint_total 2250
telemt_me_writer_restored_fallback_total 46
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7365
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 8244527
telemt_user_connections_current{user="hello"} 1521
telemt_user_octets_from_client{user="hello"} 187060193545 (174.21 GB)
telemt_user_octets_to_client{user="hello"} 3115714668352 (2.83 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 565
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 100027.1 (27h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10923658
telemt_connections_bad_total 419160
telemt_connections_current 1916
telemt_connections_me_current 1916
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4541883
telemt_upstream_connect_attempt_total 47722
telemt_upstream_connect_success_total 47363
telemt_upstream_connect_fail_total 350
telemt_upstream_connect_attempts_per_request{bucket="1"} 47713
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 350
telemt_me_reconnect_attempts_total 48239
telemt_me_reconnect_success_total 1573
telemt_me_reader_eof_total 1231
telemt_me_idle_close_by_peer_total 1230
telemt_me_route_drop_no_conn_total 3970706
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5251534
telemt_me_endpoint_quarantine_total 649
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 752
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 29289
telemt_desync_full_logged_total 9920
telemt_desync_suppressed_total 19369
telemt_desync_frames_bucket_total{bucket="1_2"} 5899
telemt_desync_frames_bucket_total{bucket="3_10"} 11555
telemt_desync_frames_bucket_total{bucket="gt_10"} 11835
telemt_pool_swap_total 106
telemt_pool_force_close_total 3223
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 335
telemt_me_draining_writers_reap_progress_total 34446
telemt_me_writer_removed_unexpected_total 1291
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3086
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32684
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2801
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 422
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31223
telemt_me_writer_teardown_success_total{mode="normal"} 35770
telemt_me_writer_teardown_noop_total 34453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70223
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.140093
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70223
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 335
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1397
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5244754
telemt_user_connections_current{user="hello"} 1916
telemt_user_octets_from_client{user="hello"} 113335611976 (105.55 GB)
telemt_user_octets_to_client{user="hello"} 1993912511602 (1.81 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 731
telemt_user_unique_ips_recent_window{user="hello"} 252
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 80997.8 (22h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1150665
telemt_connections_bad_total 20804
telemt_connections_current 1137
telemt_connections_me_current 1137
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 21572
telemt_upstream_connect_attempt_total 39083
telemt_upstream_connect_success_total 38969
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 39058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20702
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 611
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1754
telemt_me_reconnect_success_total 747
telemt_me_reader_eof_total 723
telemt_me_idle_close_by_peer_total 723
telemt_me_route_drop_no_conn_total 402557
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1022507
telemt_me_endpoint_quarantine_total 683
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 665
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 5926
telemt_desync_full_logged_total 1811
telemt_desync_suppressed_total 4115
telemt_desync_frames_bucket_total{bucket="1_2"} 1386
telemt_desync_frames_bucket_total{bucket="3_10"} 2324
telemt_desync_frames_bucket_total{bucket="gt_10"} 2216
telemt_pool_swap_total 86
telemt_pool_force_close_total 2208
telemt_me_writer_close_signal_drop_total 126
telemt_me_draining_writers_reap_progress_total 32442
telemt_me_writer_removed_unexpected_total 697
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2507
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30660
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2125
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30234
telemt_me_writer_teardown_success_total{mode="normal"} 33167
telemt_me_writer_teardown_noop_total 32445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65612
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.844660
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65612
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 126
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 637
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1018886
telemt_user_connections_current{user="hello"} 1137
telemt_user_octets_from_client{user="hello"} 18748919485 (17.46 GB)
telemt_user_octets_to_client{user="hello"} 437722138507 (407.66 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 427
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 163202.1 (45h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12731942
telemt_connections_bad_total 1480385
telemt_connections_current 2175
telemt_connections_me_current 2175
telemt_handshake_timeouts_total 357728
telemt_upstream_connect_attempt_total 61463
telemt_upstream_connect_success_total 61167
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 61355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30912
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_reconnect_attempts_total 2418
telemt_me_reconnect_success_total 1282
telemt_me_reader_eof_total 1246
telemt_me_idle_close_by_peer_total 1246
telemt_me_route_drop_no_conn_total 4287915
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9630728
telemt_me_endpoint_quarantine_total 1087
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1221
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
telemt_me_writers_active_current 46
telemt_desync_total 39549
telemt_desync_full_logged_total 12905
telemt_desync_suppressed_total 26644
telemt_desync_frames_bucket_total{bucket="1_2"} 9417
telemt_desync_frames_bucket_total{bucket="3_10"} 14626
telemt_desync_frames_bucket_total{bucket="gt_10"} 15506
telemt_pool_swap_total 181
telemt_pool_force_close_total 4991
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 636
telemt_me_draining_writers_reap_progress_total 55306
telemt_me_writer_removed_unexpected_total 1197
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4557
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51981
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4817
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50315
telemt_me_writer_teardown_success_total{mode="normal"} 56538
telemt_me_writer_teardown_noop_total 55308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111846
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.803039
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111846
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 636
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 1120
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 9598832
telemt_user_connections_current{user="hello"} 2175
telemt_user_octets_from_client{user="hello"} 188006174384 (175.09 GB)
telemt_user_octets_to_client{user="hello"} 4238182841728 (3.85 TB)
telemt_user_unique_ips_current{user="hello"} 679
telemt_user_unique_ips_recent_window{user="hello"} 309
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 163192.4 (45h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11048257
telemt_connections_bad_total 1237700
telemt_connections_current 1357
telemt_connections_me_current 1357
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 288042
telemt_upstream_connect_attempt_total 87540
telemt_upstream_connect_success_total 86784
telemt_upstream_connect_fail_total 582
telemt_upstream_connect_attempts_per_request{bucket="1"} 87366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36179
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2052
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 582
telemt_me_reconnect_attempts_total 9179
telemt_me_reconnect_success_total 2196
telemt_me_reader_eof_total 2046
telemt_me_idle_close_by_peer_total 2046
telemt_me_seq_mismatch_total 76
telemt_me_route_drop_no_conn_total 5507679
telemt_me_route_drop_channel_closed_total 351
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8545523
telemt_me_endpoint_quarantine_total 1251
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 43
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 43
telemt_me_single_endpoint_shadow_rotate_total 1223
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_desync_total 38872
telemt_desync_full_logged_total 12553
telemt_desync_suppressed_total 26319
telemt_desync_frames_bucket_total{bucket="1_2"} 9683
telemt_desync_frames_bucket_total{bucket="3_10"} 14476
telemt_desync_frames_bucket_total{bucket="gt_10"} 14713
telemt_pool_swap_total 172
telemt_pool_force_close_total 4818
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 620
telemt_me_draining_writers_reap_progress_total 54929
telemt_me_writer_removed_unexpected_total 2072
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5752
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51320
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4362
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 456
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50111
telemt_me_writer_teardown_success_total{mode="normal"} 57072
telemt_me_writer_teardown_noop_total 54934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112006
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.866445
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112006
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 620
telemt_me_refill_failed_total 358
telemt_me_writer_restored_same_endpoint_total 1784
telemt_me_writer_restored_fallback_total 104
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 8551352
telemt_user_connections_current{user="hello"} 1357
telemt_user_octets_from_client{user="hello"} 150200329369 (139.88 GB)
telemt_user_octets_to_client{user="hello"} 3278802929479 (2.98 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 544
telemt_user_unique_ips_recent_window{user="hello"} 203
```
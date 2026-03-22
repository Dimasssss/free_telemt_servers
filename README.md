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

# Server Metrics 2026-03-22 06:46:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 34789.6 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 679656
telemt_connections_bad_total 42005
telemt_connections_current 1442
telemt_connections_me_current 1442
telemt_handshake_timeouts_total 32704
telemt_upstream_connect_attempt_total 14223
telemt_upstream_connect_success_total 14222
telemt_upstream_connect_attempts_per_request{bucket="1"} 14222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9252
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 372
telemt_me_reconnect_success_total 220
telemt_me_reader_eof_total 217
telemt_me_idle_close_by_peer_total 217
telemt_me_route_drop_no_conn_total 242864
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 563122
telemt_me_endpoint_quarantine_total 255
telemt_me_single_endpoint_shadow_rotate_total 287
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 4675
telemt_desync_full_logged_total 1305
telemt_desync_suppressed_total 3370
telemt_desync_frames_bucket_total{bucket="1_2"} 1532
telemt_desync_frames_bucket_total{bucket="3_10"} 1748
telemt_desync_frames_bucket_total{bucket="gt_10"} 1395
telemt_pool_swap_total 38
telemt_pool_force_close_total 1018
telemt_me_writer_close_signal_drop_total 109
telemt_me_draining_writers_reap_progress_total 12867
telemt_me_writer_removed_unexpected_total 214
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 892
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12176
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1007
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11849
telemt_me_writer_teardown_success_total{mode="normal"} 13068
telemt_me_writer_teardown_noop_total 12868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25936
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.318407
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25936
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 109
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 201
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 562002
telemt_user_connections_current{user="hello"} 1442
telemt_user_octets_from_client{user="hello"} 7883059204 (7.34 GB)
telemt_user_octets_to_client{user="hello"} 197229408944 (183.68 GB)
telemt_user_unique_ips_current{user="hello"} 582
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 48155.7 (13h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1152158
telemt_connections_bad_total 111299
telemt_connections_current 985
telemt_connections_me_current 985
telemt_handshake_timeouts_total 36957
telemt_upstream_connect_attempt_total 25621
telemt_upstream_connect_success_total 25242
telemt_upstream_connect_fail_total 328
telemt_upstream_connect_attempts_per_request{bucket="1"} 25570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12313
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 328
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 1909
telemt_me_reconnect_success_total 746
telemt_me_reader_eof_total 652
telemt_me_idle_close_by_peer_total 652
telemt_me_route_drop_no_conn_total 423646
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 872214
telemt_me_endpoint_quarantine_total 442
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 389
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
telemt_me_writers_active_current 44
telemt_desync_total 3682
telemt_desync_full_logged_total 2155
telemt_desync_suppressed_total 1527
telemt_desync_frames_bucket_total{bucket="1_2"} 774
telemt_desync_frames_bucket_total{bucket="3_10"} 1427
telemt_desync_frames_bucket_total{bucket="gt_10"} 1481
telemt_pool_swap_total 51
telemt_pool_force_close_total 1358
telemt_me_writer_close_signal_drop_total 109
telemt_me_draining_writers_reap_progress_total 19911
telemt_me_writer_removed_unexpected_total 626
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1753
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18768
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1293
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 65
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18553
telemt_me_writer_teardown_success_total{mode="normal"} 20521
telemt_me_writer_teardown_noop_total 19911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40432
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.130779
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40432
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 109
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 562
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 874035
telemt_user_connections_current{user="hello"} 985
telemt_user_octets_from_client{user="hello"} 14080848038 (13.11 GB)
telemt_user_octets_to_client{user="hello"} 325024096075 (302.70 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 627
telemt_user_unique_ips_recent_window{user="hello"} 360
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 123016.6 (34h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8747154
telemt_connections_bad_total 801180
telemt_connections_current 3993
telemt_connections_me_current 3993
telemt_handshake_timeouts_total 277415
telemt_upstream_connect_attempt_total 45563
telemt_upstream_connect_success_total 45485
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 45493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24746
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1745
telemt_me_reconnect_success_total 907
telemt_me_reader_eof_total 910
telemt_me_idle_close_by_peer_total 910
telemt_me_route_drop_no_conn_total 4783072
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6927562
telemt_me_endpoint_quarantine_total 783
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 925
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
telemt_desync_total 29641
telemt_desync_full_logged_total 9824
telemt_desync_suppressed_total 19817
telemt_desync_frames_bucket_total{bucket="1_2"} 6422
telemt_desync_frames_bucket_total{bucket="3_10"} 11547
telemt_desync_frames_bucket_total{bucket="gt_10"} 11672
telemt_pool_swap_total 133
telemt_pool_force_close_total 4395
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 661
telemt_me_draining_writers_reap_progress_total 41594
telemt_me_writer_removed_unexpected_total 875
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3460
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38508
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4131
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 264
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37199
telemt_me_writer_teardown_success_total{mode="normal"} 41968
telemt_me_writer_teardown_noop_total 41638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83606
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 174.793311
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83606
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 661
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 810
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 6918535
telemt_user_connections_current{user="hello"} 3993
telemt_user_octets_from_client{user="hello"} 116873307132 (108.85 GB)
telemt_user_octets_to_client{user="hello"} 2364429893224 (2.15 TB)
telemt_user_unique_ips_current{user="hello"} 1638
telemt_user_unique_ips_recent_window{user="hello"} 549
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 123016.8 (34h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7223439
telemt_connections_bad_total 636983
telemt_connections_current 3805
telemt_connections_me_current 3805
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 238910
telemt_upstream_connect_attempt_total 49567
telemt_upstream_connect_success_total 49161
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 49370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24306
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 559
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2612
telemt_me_reconnect_success_total 970
telemt_me_reader_eof_total 937
telemt_me_idle_close_by_peer_total 937
telemt_me_route_drop_no_conn_total 2433219
telemt_me_route_drop_channel_closed_total 298
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5346343
telemt_me_endpoint_quarantine_total 780
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 949
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 24723
telemt_desync_full_logged_total 8487
telemt_desync_suppressed_total 16236
telemt_desync_frames_bucket_total{bucket="1_2"} 5915
telemt_desync_frames_bucket_total{bucket="3_10"} 9604
telemt_desync_frames_bucket_total{bucket="gt_10"} 9204
telemt_pool_swap_total 134
telemt_pool_force_close_total 3991
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 412
telemt_me_draining_writers_reap_progress_total 40052
telemt_me_writer_removed_unexpected_total 914
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3306
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37589
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3766
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 225
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36061
telemt_me_writer_teardown_success_total{mode="normal"} 40895
telemt_me_writer_teardown_noop_total 40058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80953
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.305682
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80953
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 412
telemt_me_refill_failed_total 92
telemt_me_writer_restored_same_endpoint_total 848
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 5267554
telemt_user_connections_current{user="hello"} 3805
telemt_user_octets_from_client{user="hello"} 151068555193 (140.69 GB)
telemt_user_octets_to_client{user="hello"} 2549394130119 (2.32 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1529
telemt_user_unique_ips_recent_window{user="hello"} 514
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 122988.5 (34h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6969150
telemt_connections_bad_total 581475
telemt_connections_current 3155
telemt_connections_me_current 3155
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 234227
telemt_upstream_connect_attempt_total 56005
telemt_upstream_connect_success_total 55392
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 55536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25872
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 2647
telemt_me_reconnect_success_total 1123
telemt_me_reader_eof_total 1046
telemt_me_idle_close_by_peer_total 1046
telemt_me_route_drop_no_conn_total 2531232
telemt_me_route_drop_channel_closed_total 159
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5185050
telemt_me_endpoint_quarantine_total 876
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 912
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 24589
telemt_desync_full_logged_total 8347
telemt_desync_suppressed_total 16242
telemt_desync_frames_bucket_total{bucket="1_2"} 5956
telemt_desync_frames_bucket_total{bucket="3_10"} 9444
telemt_desync_frames_bucket_total{bucket="gt_10"} 9189
telemt_pool_swap_total 132
telemt_pool_force_close_total 3865
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 432
telemt_me_draining_writers_reap_progress_total 40984
telemt_me_writer_removed_unexpected_total 1037
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3572
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38462
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3609
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 256
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37119
telemt_me_writer_teardown_success_total{mode="normal"} 42034
telemt_me_writer_teardown_noop_total 40996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83030
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 41.170272
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83030
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 432
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 967
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 5178968
telemt_user_connections_current{user="hello"} 3155
telemt_user_octets_from_client{user="hello"} 140627597943 (130.97 GB)
telemt_user_octets_to_client{user="hello"} 2352091527767 (2.14 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1276
telemt_user_unique_ips_recent_window{user="hello"} 432
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 123020.1 (34h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22319698
telemt_connections_bad_total 1889264
telemt_connections_current 4927
telemt_connections_me_current 4927
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 670337
telemt_upstream_connect_attempt_total 238334
telemt_upstream_connect_success_total 218719
telemt_upstream_connect_fail_total 17674
telemt_upstream_connect_attempts_per_request{bucket="1"} 236393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51175
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2477
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17674
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 66387
telemt_me_reconnect_success_total 2616
telemt_me_reader_eof_total 1646
telemt_me_idle_close_by_peer_total 1644
telemt_me_route_drop_no_conn_total 42242585
telemt_me_route_drop_channel_closed_total 134
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17935836
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 961
telemt_me_single_endpoint_outage_enter_total 155
telemt_me_single_endpoint_outage_exit_total 155
telemt_me_single_endpoint_outage_reconnect_attempt_total 324
telemt_me_single_endpoint_outage_reconnect_success_total 81
telemt_me_single_endpoint_quarantine_bypass_total 324
telemt_me_single_endpoint_shadow_rotate_total 965
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
telemt_me_writers_active_current 47
telemt_desync_total 34624
telemt_desync_full_logged_total 10410
telemt_desync_suppressed_total 24214
telemt_desync_frames_bucket_total{bucket="1_2"} 7677
telemt_desync_frames_bucket_total{bucket="3_10"} 15282
telemt_desync_frames_bucket_total{bucket="gt_10"} 11665
telemt_pool_swap_total 127
telemt_pool_force_close_total 4025
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 920
telemt_me_draining_writers_reap_progress_total 38547
telemt_me_writer_removed_unexpected_total 2422
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5224
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35476
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3450
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 575
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34522
telemt_me_writer_teardown_success_total{mode="normal"} 40700
telemt_me_writer_teardown_noop_total 38577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79277
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 279.145119
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79277
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 920
telemt_me_refill_failed_total 3863
telemt_me_writer_restored_same_endpoint_total 1779
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14705
telemt_me_writer_removed_unexpected_minus_restored_total 621
telemt_user_connections_total{user="hello"} 18100689
telemt_user_connections_current{user="hello"} 4927
telemt_user_octets_from_client{user="hello"} 267395738803 (249.03 GB)
telemt_user_octets_to_client{user="hello"} 1380940379818 (1.26 TB)
telemt_user_msgs_from_client{user="hello"} 500908
telemt_user_msgs_to_client{user="hello"} 1006528
telemt_user_unique_ips_current{user="hello"} 1865
telemt_user_unique_ips_recent_window{user="hello"} 878
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 122987.4 (34h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6692074
telemt_connections_bad_total 622087
telemt_connections_current 3546
telemt_connections_me_current 3546
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 139020
telemt_upstream_connect_attempt_total 64627
telemt_upstream_connect_success_total 63885
telemt_upstream_connect_fail_total 635
telemt_upstream_connect_attempts_per_request{bucket="1"} 64520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26873
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 635
telemt_me_reconnect_attempts_total 69995
telemt_me_reconnect_success_total 1914
telemt_me_reader_eof_total 1691
telemt_me_idle_close_by_peer_total 1690
telemt_me_route_drop_no_conn_total 2562650
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5230245
telemt_me_endpoint_quarantine_total 826
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 935
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
telemt_desync_total 26134
telemt_desync_full_logged_total 9105
telemt_desync_suppressed_total 17029
telemt_desync_frames_bucket_total{bucket="1_2"} 5216
telemt_desync_frames_bucket_total{bucket="3_10"} 10039
telemt_desync_frames_bucket_total{bucket="gt_10"} 10879
telemt_pool_swap_total 128
telemt_pool_force_close_total 3672
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 433
telemt_me_draining_writers_reap_progress_total 43228
telemt_me_writer_removed_unexpected_total 1722
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4330
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40657
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3263
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 409
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39556
telemt_me_writer_teardown_success_total{mode="normal"} 44987
telemt_me_writer_teardown_noop_total 43229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88216
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.913850
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88216
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 433
telemt_me_refill_failed_total 4217
telemt_me_writer_restored_same_endpoint_total 1598
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 5221779
telemt_user_connections_current{user="hello"} 3546
telemt_user_octets_from_client{user="hello"} 134291313016 (125.07 GB)
telemt_user_octets_to_client{user="hello"} 2184540875722 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1510
telemt_user_unique_ips_recent_window{user="hello"} 486
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 59823.4 (16h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4858703
telemt_connections_bad_total 200065
telemt_connections_current 3009
telemt_connections_me_current 3009
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1919622
telemt_upstream_connect_attempt_total 33485
telemt_upstream_connect_success_total 33256
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 33478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13168
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_reconnect_attempts_total 46193
telemt_me_reconnect_success_total 1071
telemt_me_reader_eof_total 761
telemt_me_idle_close_by_peer_total 761
telemt_me_route_drop_no_conn_total 1195385
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2418623
telemt_me_endpoint_quarantine_total 421
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 461
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 12910
telemt_desync_full_logged_total 4455
telemt_desync_suppressed_total 8455
telemt_desync_frames_bucket_total{bucket="1_2"} 2522
telemt_desync_frames_bucket_total{bucket="3_10"} 4933
telemt_desync_frames_bucket_total{bucket="gt_10"} 5455
telemt_pool_swap_total 65
telemt_pool_force_close_total 1910
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 165
telemt_me_draining_writers_reap_progress_total 21914
telemt_me_writer_removed_unexpected_total 831
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1858
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20917
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1691
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 219
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20004
telemt_me_writer_teardown_success_total{mode="normal"} 22775
telemt_me_writer_teardown_noop_total 21916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44691
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.776004
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44691
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 165
telemt_me_refill_failed_total 2621
telemt_me_writer_restored_same_endpoint_total 955
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2420617
telemt_user_connections_current{user="hello"} 3009
telemt_user_octets_from_client{user="hello"} 62909283816 (58.59 GB)
telemt_user_octets_to_client{user="hello"} 1073070836206 (999.38 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1300
telemt_user_unique_ips_recent_window{user="hello"} 494
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 40794.5 (11h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305525
telemt_connections_bad_total 2119
telemt_connections_current 620
telemt_connections_me_current 620
telemt_handshake_timeouts_total 7190
telemt_upstream_connect_attempt_total 19626
telemt_upstream_connect_success_total 19577
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 19622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11231
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_reconnect_attempts_total 832
telemt_me_reconnect_success_total 283
telemt_me_reader_eof_total 278
telemt_me_idle_close_by_peer_total 278
telemt_me_route_drop_no_conn_total 89523
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 275755
telemt_me_endpoint_quarantine_total 387
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 356
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
telemt_me_writers_active_current 45
telemt_desync_total 1341
telemt_desync_full_logged_total 377
telemt_desync_suppressed_total 964
telemt_desync_frames_bucket_total{bucket="1_2"} 455
telemt_desync_frames_bucket_total{bucket="3_10"} 512
telemt_desync_frames_bucket_total{bucket="gt_10"} 374
telemt_pool_swap_total 45
telemt_pool_force_close_total 1009
telemt_me_writer_close_signal_drop_total 36
telemt_me_draining_writers_reap_progress_total 17763
telemt_me_writer_removed_unexpected_total 266
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1152
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16889
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1007
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16754
telemt_me_writer_teardown_success_total{mode="normal"} 18041
telemt_me_writer_teardown_noop_total 17763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35804
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.372345
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35804
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 36
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 242
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 275336
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 4662004692 (4.34 GB)
telemt_user_octets_to_client{user="hello"} 158163016524 (147.30 GB)
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 122992.1 (34h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8130055
telemt_connections_bad_total 833451
telemt_connections_current 3913
telemt_connections_me_current 3913
telemt_handshake_timeouts_total 229688
telemt_upstream_connect_attempt_total 48343
telemt_upstream_connect_success_total 48167
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 48304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24258
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 1774
telemt_me_reconnect_success_total 955
telemt_me_reader_eof_total 938
telemt_me_idle_close_by_peer_total 938
telemt_me_route_drop_no_conn_total 2295495
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6068906
telemt_me_endpoint_quarantine_total 874
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 941
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
telemt_desync_total 23978
telemt_desync_full_logged_total 7896
telemt_desync_suppressed_total 16082
telemt_desync_frames_bucket_total{bucket="1_2"} 5978
telemt_desync_frames_bucket_total{bucket="3_10"} 8743
telemt_desync_frames_bucket_total{bucket="gt_10"} 9257
telemt_pool_swap_total 136
telemt_pool_force_close_total 3630
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 431
telemt_me_draining_writers_reap_progress_total 43643
telemt_me_writer_removed_unexpected_total 901
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3418
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41153
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3538
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 92
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40013
telemt_me_writer_teardown_success_total{mode="normal"} 44571
telemt_me_writer_teardown_noop_total 43645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88216
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.266847
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88216
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 431
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 850
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 6042917
telemt_user_connections_current{user="hello"} 3913
telemt_user_octets_from_client{user="hello"} 118221734360 (110.10 GB)
telemt_user_octets_to_client{user="hello"} 2833012397064 (2.58 TB)
telemt_user_unique_ips_current{user="hello"} 1553
telemt_user_unique_ips_recent_window{user="hello"} 548
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 122988.6 (34h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7116178
telemt_connections_bad_total 734288
telemt_connections_current 3769
telemt_connections_me_current 3769
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 190032
telemt_upstream_connect_attempt_total 64097
telemt_upstream_connect_success_total 63608
telemt_upstream_connect_fail_total 426
telemt_upstream_connect_attempts_per_request{bucket="1"} 64034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 426
telemt_me_reconnect_attempts_total 5891
telemt_me_reconnect_success_total 1321
telemt_me_reader_eof_total 1186
telemt_me_idle_close_by_peer_total 1186
telemt_me_seq_mismatch_total 59
telemt_me_route_drop_no_conn_total 2356228
telemt_me_route_drop_channel_closed_total 197
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5430888
telemt_me_endpoint_quarantine_total 971
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 942
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
telemt_me_writers_active_current 44
telemt_desync_total 22924
telemt_desync_full_logged_total 7610
telemt_desync_suppressed_total 15314
telemt_desync_frames_bucket_total{bucket="1_2"} 5696
telemt_desync_frames_bucket_total{bucket="3_10"} 8383
telemt_desync_frames_bucket_total{bucket="gt_10"} 8845
telemt_pool_swap_total 134
telemt_pool_force_close_total 3579
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 431
telemt_me_draining_writers_reap_progress_total 42091
telemt_me_writer_removed_unexpected_total 1199
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3969
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39382
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3352
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 227
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38512
telemt_me_writer_teardown_success_total{mode="normal"} 43351
telemt_me_writer_teardown_noop_total 42095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85446
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.272077
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85446
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 431
telemt_me_refill_failed_total 263
telemt_me_writer_restored_same_endpoint_total 1027
telemt_me_writer_restored_fallback_total 78
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 5432855
telemt_user_connections_current{user="hello"} 3769
telemt_user_octets_from_client{user="hello"} 101154872661 (94.21 GB)
telemt_user_octets_to_client{user="hello"} 2362220917240 (2.15 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1495
telemt_user_unique_ips_recent_window{user="hello"} 475
```
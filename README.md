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

# Server Metrics 2026-03-22 13:30:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 59062.9 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1836670
telemt_connections_bad_total 81922
telemt_connections_current 1836
telemt_connections_me_current 1836
telemt_handshake_timeouts_total 78651
telemt_upstream_connect_attempt_total 22177
telemt_upstream_connect_success_total 22176
telemt_upstream_connect_attempts_per_request{bucket="1"} 22176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14454
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 904
telemt_me_reconnect_success_total 359
telemt_me_reader_eof_total 363
telemt_me_idle_close_by_peer_total 363
telemt_me_route_drop_no_conn_total 1280961
telemt_me_route_drop_channel_closed_total 578
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1560876
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 407
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 467
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_desync_total 8696
telemt_desync_full_logged_total 2655
telemt_desync_suppressed_total 6041
telemt_desync_frames_bucket_total{bucket="1_2"} 2433
telemt_desync_frames_bucket_total{bucket="3_10"} 3272
telemt_desync_frames_bucket_total{bucket="gt_10"} 2991
telemt_pool_swap_total 65
telemt_pool_force_close_total 1947
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 313
telemt_me_draining_writers_reap_progress_total 20235
telemt_me_writer_removed_unexpected_total 354
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1442
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19009
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1911
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18288
telemt_me_writer_teardown_success_total{mode="normal"} 20451
telemt_me_writer_teardown_noop_total 20239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40690
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 151.248928
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40690
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 313
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 1557980
telemt_user_connections_current{user="hello"} 1836
telemt_user_octets_from_client{user="hello"} 24464726528 (22.78 GB)
telemt_user_octets_to_client{user="hello"} 455068898348 (423.82 GB)
telemt_user_unique_ips_current{user="hello"} 666
telemt_user_unique_ips_recent_window{user="hello"} 299
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 72429.1 (20h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3003528
telemt_connections_bad_total 282006
telemt_connections_current 1530
telemt_connections_me_current 1530
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 70344
telemt_upstream_connect_attempt_total 46704
telemt_upstream_connect_success_total 46153
telemt_upstream_connect_fail_total 486
telemt_upstream_connect_attempts_per_request{bucket="1"} 46639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 486
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3652
telemt_me_reconnect_success_total 1630
telemt_me_reader_eof_total 1500
telemt_me_idle_close_by_peer_total 1500
telemt_me_route_drop_no_conn_total 2800321
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2360986
telemt_me_endpoint_quarantine_total 612
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 568
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
telemt_desync_total 9242
telemt_desync_full_logged_total 5164
telemt_desync_suppressed_total 4078
telemt_desync_frames_bucket_total{bucket="1_2"} 2172
telemt_desync_frames_bucket_total{bucket="3_10"} 3611
telemt_desync_frames_bucket_total{bucket="gt_10"} 3459
telemt_pool_swap_total 72
telemt_pool_force_close_total 2070
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 172
telemt_me_draining_writers_reap_progress_total 28640
telemt_me_writer_removed_unexpected_total 1458
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3137
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26961
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1824
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 246
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26570
telemt_me_writer_teardown_success_total{mode="normal"} 30098
telemt_me_writer_teardown_noop_total 28640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58738
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.737777
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58738
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 172
telemt_me_refill_failed_total 91
telemt_me_writer_restored_same_endpoint_total 1351
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 2372560
telemt_user_connections_current{user="hello"} 1530
telemt_user_octets_from_client{user="hello"} 28657402103 (26.69 GB)
telemt_user_octets_to_client{user="hello"} 545327315106 (507.88 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 966
telemt_user_unique_ips_recent_window{user="hello"} 657
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 147288.9 (40h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13747976
telemt_connections_bad_total 1205014
telemt_connections_current 5059
telemt_connections_me_current 5059
telemt_handshake_timeouts_total 346539
telemt_upstream_connect_attempt_total 53507
telemt_upstream_connect_success_total 53425
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 53433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29002
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2433
telemt_me_reconnect_success_total 1276
telemt_me_reader_eof_total 1218
telemt_me_idle_close_by_peer_total 1217
telemt_me_route_drop_no_conn_total 11926233
telemt_me_route_drop_channel_closed_total 118
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11024672
telemt_me_endpoint_quarantine_total 937
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1096
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
telemt_desync_total 44877
telemt_desync_full_logged_total 14249
telemt_desync_suppressed_total 30628
telemt_desync_frames_bucket_total{bucket="1_2"} 10159
telemt_desync_frames_bucket_total{bucket="3_10"} 17557
telemt_desync_frames_bucket_total{bucket="gt_10"} 17161
telemt_pool_swap_total 158
telemt_pool_force_close_total 5408
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 856
telemt_me_draining_writers_reap_progress_total 48802
telemt_me_writer_removed_unexpected_total 1175
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4244
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45067
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4977
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 431
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43394
telemt_me_writer_teardown_success_total{mode="normal"} 49311
telemt_me_writer_teardown_noop_total 48851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98162
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 249.988773
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98162
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 856
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 1099
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 11012672
telemt_user_connections_current{user="hello"} 5059
telemt_user_octets_from_client{user="hello"} 158807660392 (147.90 GB)
telemt_user_octets_to_client{user="hello"} 2942546130004 (2.68 TB)
telemt_user_unique_ips_current{user="hello"} 2018
telemt_user_unique_ips_recent_window{user="hello"} 845
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 147290.5 (40h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10203943
telemt_connections_bad_total 954292
telemt_connections_current 5103
telemt_connections_me_current 5103
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 305656
telemt_upstream_connect_attempt_total 79889
telemt_upstream_connect_success_total 78751
telemt_upstream_connect_fail_total 817
telemt_upstream_connect_attempts_per_request{bucket="1"} 79568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31556
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3678
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 817
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3674
telemt_me_reconnect_success_total 1464
telemt_me_reader_eof_total 1337
telemt_me_idle_close_by_peer_total 1337
telemt_me_route_drop_no_conn_total 4074798
telemt_me_route_drop_channel_closed_total 430
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7617695
telemt_me_endpoint_quarantine_total 926
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 29
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
telemt_me_writers_active_current 46
telemt_desync_total 34080
telemt_desync_full_logged_total 11481
telemt_desync_suppressed_total 22599
telemt_desync_frames_bucket_total{bucket="1_2"} 8398
telemt_desync_frames_bucket_total{bucket="3_10"} 13114
telemt_desync_frames_bucket_total{bucket="gt_10"} 12568
telemt_pool_swap_total 157
telemt_pool_force_close_total 4830
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 602
telemt_me_draining_writers_reap_progress_total 47002
telemt_me_writer_removed_unexpected_total 1370
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4264
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43976
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4412
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 418
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42172
telemt_me_writer_teardown_success_total{mode="normal"} 48240
telemt_me_writer_teardown_noop_total 47017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95257
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 88.152074
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95257
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 602
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 1241
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 7557417
telemt_user_connections_current{user="hello"} 5103
telemt_user_octets_from_client{user="hello"} 192992641997 (179.74 GB)
telemt_user_octets_to_client{user="hello"} 3414941615206 (3.11 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 2052
telemt_user_unique_ips_recent_window{user="hello"} 734
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 147254.2 (40h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9674494
telemt_connections_bad_total 808605
telemt_connections_current 3544
telemt_connections_me_current 3544
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 313413
telemt_upstream_connect_attempt_total 65338
telemt_upstream_connect_success_total 64435
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 64616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30972
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30265
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2013
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4165
telemt_me_reconnect_success_total 1789
telemt_me_reader_eof_total 1558
telemt_me_idle_close_by_peer_total 1557
telemt_me_route_drop_no_conn_total 4799766
telemt_me_route_drop_channel_closed_total 325
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7300004
telemt_me_endpoint_quarantine_total 1015
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1080
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
telemt_me_writers_active_current 44
telemt_desync_total 33871
telemt_desync_full_logged_total 11241
telemt_desync_suppressed_total 22630
telemt_desync_frames_bucket_total{bucket="1_2"} 8606
telemt_desync_frames_bucket_total{bucket="3_10"} 12986
telemt_desync_frames_bucket_total{bucket="gt_10"} 12279
telemt_pool_swap_total 153
telemt_pool_force_close_total 4775
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 652
telemt_me_draining_writers_reap_progress_total 47661
telemt_me_writer_removed_unexpected_total 1705
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4758
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44530
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4264
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 511
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42886
telemt_me_writer_teardown_success_total{mode="normal"} 49288
telemt_me_writer_teardown_noop_total 47728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97016
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3153.660807
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97016
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 652
telemt_me_refill_failed_total 122
telemt_me_writer_restored_same_endpoint_total 1563
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 7294157
telemt_user_connections_current{user="hello"} 3544
telemt_user_octets_from_client{user="hello"} 171182705089 (159.43 GB)
telemt_user_octets_to_client{user="hello"} 3045858806861 (2.77 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1497
telemt_user_unique_ips_recent_window{user="hello"} 657
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 17534.5 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7388508
telemt_connections_bad_total 479008
telemt_connections_current 6867
telemt_connections_me_current 6867
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 116712
telemt_upstream_connect_attempt_total 27820
telemt_upstream_connect_success_total 26471
telemt_upstream_connect_fail_total 1010
telemt_upstream_connect_attempts_per_request{bucket="1"} 27481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6394
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4704
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1010
telemt_me_keepalive_timeout_total 651
telemt_me_reconnect_attempts_total 2638
telemt_me_reconnect_success_total 477
telemt_me_reader_eof_total 301
telemt_me_idle_close_by_peer_total 301
telemt_me_route_drop_no_conn_total 17714477
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6139980
telemt_me_endpoint_quarantine_total 112
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 140
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
telemt_me_writers_active_current 42
telemt_desync_total 8985
telemt_desync_full_logged_total 2306
telemt_desync_suppressed_total 6679
telemt_desync_frames_bucket_total{bucket="1_2"} 1616
telemt_desync_frames_bucket_total{bucket="3_10"} 3644
telemt_desync_frames_bucket_total{bucket="gt_10"} 3725
telemt_pool_swap_total 16
telemt_pool_force_close_total 656
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 251
telemt_me_draining_writers_reap_progress_total 4619
telemt_me_writer_removed_unexpected_total 432
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 811
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4198
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 474
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 182
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3963
telemt_me_writer_teardown_success_total{mode="normal"} 5009
telemt_me_writer_teardown_noop_total 4622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 9063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 9569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 9630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 9631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 9631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 9631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 9631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 9631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 9631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 9631
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.122204
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 9631
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 251
telemt_me_refill_failed_total 114
telemt_me_writer_restored_same_endpoint_total 319
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 6155171
telemt_user_connections_current{user="hello"} 6867
telemt_user_octets_from_client{user="hello"} 34318024331 (31.96 GB)
telemt_user_octets_to_client{user="hello"} 182357267460 (169.83 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2509
telemt_user_unique_ips_recent_window{user="hello"} 1452
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 147260.8 (40h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9379114
telemt_connections_bad_total 779668
telemt_connections_current 5083
telemt_connections_me_current 5083
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 202382
telemt_upstream_connect_attempt_total 89641
telemt_upstream_connect_success_total 88741
telemt_upstream_connect_fail_total 778
telemt_upstream_connect_attempts_per_request{bucket="1"} 89519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32207
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 778
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71305
telemt_me_reconnect_success_total 2403
telemt_me_reader_eof_total 2137
telemt_me_idle_close_by_peer_total 2136
telemt_me_route_drop_no_conn_total 4558077
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7404717
telemt_me_endpoint_quarantine_total 983
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1100
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 37873
telemt_desync_full_logged_total 12948
telemt_desync_suppressed_total 24925
telemt_desync_frames_bucket_total{bucket="1_2"} 7671
telemt_desync_frames_bucket_total{bucket="3_10"} 14654
telemt_desync_frames_bucket_total{bucket="gt_10"} 15548
telemt_pool_swap_total 151
telemt_pool_force_close_total 4466
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 544
telemt_me_draining_writers_reap_progress_total 50309
telemt_me_writer_removed_unexpected_total 2165
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5308
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47182
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3854
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 612
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45843
telemt_me_writer_teardown_success_total{mode="normal"} 52490
telemt_me_writer_teardown_noop_total 50310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102800
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.563401
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102800
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 544
telemt_me_refill_failed_total 4252
telemt_me_writer_restored_same_endpoint_total 2017
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 7406146
telemt_user_connections_current{user="hello"} 5083
telemt_user_octets_from_client{user="hello"} 171371581887 (159.60 GB)
telemt_user_octets_to_client{user="hello"} 2824555423413 (2.57 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1977
telemt_user_unique_ips_recent_window{user="hello"} 725
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 84096.8 (23h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9265585
telemt_connections_bad_total 328424
telemt_connections_current 4776
telemt_connections_me_current 4776
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3900970
telemt_upstream_connect_attempt_total 41882
telemt_upstream_connect_success_total 41580
telemt_upstream_connect_fail_total 295
telemt_upstream_connect_attempts_per_request{bucket="1"} 41875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17633
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 295
telemt_me_reconnect_attempts_total 47902
telemt_me_reconnect_success_total 1433
telemt_me_reader_eof_total 1100
telemt_me_idle_close_by_peer_total 1100
telemt_me_route_drop_no_conn_total 3361148
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4468892
telemt_me_endpoint_quarantine_total 554
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 634
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 24445
telemt_desync_full_logged_total 8191
telemt_desync_suppressed_total 16254
telemt_desync_frames_bucket_total{bucket="1_2"} 4949
telemt_desync_frames_bucket_total{bucket="3_10"} 9626
telemt_desync_frames_bucket_total{bucket="gt_10"} 9870
telemt_pool_swap_total 88
telemt_pool_force_close_total 2739
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 284
telemt_me_draining_writers_reap_progress_total 29299
telemt_me_writer_removed_unexpected_total 1165
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2655
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27837
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2333
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 406
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26560
telemt_me_writer_teardown_success_total{mode="normal"} 30492
telemt_me_writer_teardown_noop_total 29306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59798
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.042364
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59798
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 284
telemt_me_refill_failed_total 2701
telemt_me_writer_restored_same_endpoint_total 1280
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4463741
telemt_user_connections_current{user="hello"} 4776
telemt_user_octets_from_client{user="hello"} 98444073496 (91.68 GB)
telemt_user_octets_to_client{user="hello"} 1715091968118 (1.56 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1845
telemt_user_unique_ips_recent_window{user="hello"} 775
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 65067.8 (18h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 760936
telemt_connections_bad_total 9026
telemt_connections_current 1033
telemt_connections_me_current 1033
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 14364
telemt_upstream_connect_attempt_total 33078
telemt_upstream_connect_success_total 32995
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 33064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17445
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 402
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 1460
telemt_me_reconnect_success_total 628
telemt_me_reader_eof_total 610
telemt_me_idle_close_by_peer_total 610
telemt_me_route_drop_no_conn_total 256189
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 684000
telemt_me_endpoint_quarantine_total 584
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 545
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 3788
telemt_desync_full_logged_total 1129
telemt_desync_suppressed_total 2659
telemt_desync_frames_bucket_total{bucket="1_2"} 921
telemt_desync_frames_bucket_total{bucket="3_10"} 1507
telemt_desync_frames_bucket_total{bucket="gt_10"} 1360
telemt_pool_swap_total 69
telemt_pool_force_close_total 1707
telemt_me_writer_close_signal_drop_total 98
telemt_me_draining_writers_reap_progress_total 27165
telemt_me_writer_removed_unexpected_total 590
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2083
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25694
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1630
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25458
telemt_me_writer_teardown_success_total{mode="normal"} 27777
telemt_me_writer_teardown_noop_total 27167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54944
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.007989
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54944
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 98
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 545
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 685494
telemt_user_connections_current{user="hello"} 1033
telemt_user_octets_from_client{user="hello"} 12892409585 (12.01 GB)
telemt_user_octets_to_client{user="hello"} 325215622647 (302.88 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 379
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 147265.5 (40h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11453269
telemt_connections_bad_total 1344124
telemt_connections_current 6419
telemt_connections_me_current 6419
telemt_handshake_timeouts_total 309266
telemt_upstream_connect_attempt_total 55615
telemt_upstream_connect_success_total 55400
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 55567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28046
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_reconnect_attempts_total 2183
telemt_me_reconnect_success_total 1159
telemt_me_reader_eof_total 1124
telemt_me_idle_close_by_peer_total 1124
telemt_me_route_drop_no_conn_total 3618290
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 32
telemt_me_route_drop_queue_full_profile_total{profile="high"} 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8599794
telemt_me_endpoint_quarantine_total 1011
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1104
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
telemt_me_writers_active_current 44
telemt_desync_total 35197
telemt_desync_full_logged_total 11560
telemt_desync_suppressed_total 23637
telemt_desync_frames_bucket_total{bucket="1_2"} 8385
telemt_desync_frames_bucket_total{bucket="3_10"} 13057
telemt_desync_frames_bucket_total{bucket="gt_10"} 13755
telemt_pool_swap_total 163
telemt_pool_force_close_total 4477
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 563
telemt_me_draining_writers_reap_progress_total 50104
telemt_me_writer_removed_unexpected_total 1079
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4103
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47116
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4324
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 153
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45627
telemt_me_writer_teardown_success_total{mode="normal"} 51219
telemt_me_writer_teardown_noop_total 50106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101325
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.134732
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101325
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 563
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1015
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 8570434
telemt_user_connections_current{user="hello"} 6419
telemt_user_octets_from_client{user="hello"} 165714513608 (154.33 GB)
telemt_user_octets_to_client{user="hello"} 3860034315816 (3.51 TB)
telemt_user_unique_ips_current{user="hello"} 2304
telemt_user_unique_ips_recent_window{user="hello"} 936
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 147261.7 (40h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9877832
telemt_connections_bad_total 1104893
telemt_connections_current 4546
telemt_connections_me_current 4546
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 258745
telemt_upstream_connect_attempt_total 81182
telemt_upstream_connect_success_total 80589
telemt_upstream_connect_fail_total 513
telemt_upstream_connect_attempts_per_request{bucket="1"} 81102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33076
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2008
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 513
telemt_me_reconnect_attempts_total 8561
telemt_me_reconnect_success_total 1927
telemt_me_reader_eof_total 1797
telemt_me_idle_close_by_peer_total 1797
telemt_me_seq_mismatch_total 71
telemt_me_route_drop_no_conn_total 4419063
telemt_me_route_drop_channel_closed_total 315
telemt_me_route_drop_queue_full_total 16
telemt_me_route_drop_queue_full_profile_total{profile="high"} 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7602181
telemt_me_endpoint_quarantine_total 1126
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1107
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 34398
telemt_desync_full_logged_total 11214
telemt_desync_suppressed_total 23184
telemt_desync_frames_bucket_total{bucket="1_2"} 8506
telemt_desync_frames_bucket_total{bucket="3_10"} 12819
telemt_desync_frames_bucket_total{bucket="gt_10"} 13073
telemt_pool_swap_total 156
telemt_pool_force_close_total 4339
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 555
telemt_me_draining_writers_reap_progress_total 49432
telemt_me_writer_removed_unexpected_total 1821
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5124
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46196
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3945
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 394
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45093
telemt_me_writer_teardown_success_total{mode="normal"} 51320
telemt_me_writer_teardown_noop_total 49436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100756
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.229325
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100756
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 555
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 1567
telemt_me_writer_restored_fallback_total 95
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 7609344
telemt_user_connections_current{user="hello"} 4546
telemt_user_octets_from_client{user="hello"} 134873722953 (125.61 GB)
telemt_user_octets_to_client{user="hello"} 3006284792635 (2.73 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1788
telemt_user_unique_ips_recent_window{user="hello"} 755
```
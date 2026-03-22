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

# Server Metrics 2026-03-22 06:10:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 32653.1 (9h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 612587
telemt_connections_bad_total 38217
telemt_connections_current 1314
telemt_connections_me_current 1314
telemt_handshake_timeouts_total 30226
telemt_upstream_connect_attempt_total 13387
telemt_upstream_connect_success_total 13386
telemt_upstream_connect_attempts_per_request{bucket="1"} 13386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8666
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 358
telemt_me_reconnect_success_total 208
telemt_me_reader_eof_total 204
telemt_me_idle_close_by_peer_total 204
telemt_me_route_drop_no_conn_total 225287
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 507934
telemt_me_endpoint_quarantine_total 245
telemt_me_single_endpoint_shadow_rotate_total 273
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
telemt_me_writers_active_current 44
telemt_desync_total 4289
telemt_desync_full_logged_total 1192
telemt_desync_suppressed_total 3097
telemt_desync_frames_bucket_total{bucket="1_2"} 1429
telemt_desync_frames_bucket_total{bucket="3_10"} 1620
telemt_desync_frames_bucket_total{bucket="gt_10"} 1240
telemt_pool_swap_total 36
telemt_pool_force_close_total 961
telemt_me_writer_close_signal_drop_total 104
telemt_me_draining_writers_reap_progress_total 12123
telemt_me_writer_removed_unexpected_total 201
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 837
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11474
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 951
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11162
telemt_me_writer_teardown_success_total{mode="normal"} 12311
telemt_me_writer_teardown_noop_total 12124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 23742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24435
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.223691
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24435
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 104
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 189
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 506835
telemt_user_connections_current{user="hello"} 1314
telemt_user_octets_from_client{user="hello"} 6508654072 (6.06 GB)
telemt_user_octets_to_client{user="hello"} 175894742196 (163.81 GB)
telemt_user_unique_ips_current{user="hello"} 516
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 46020.0 (12h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1064120
telemt_connections_bad_total 94974
telemt_connections_current 1494
telemt_connections_me_current 1494
telemt_handshake_timeouts_total 35307
telemt_upstream_connect_attempt_total 24279
telemt_upstream_connect_success_total 23941
telemt_upstream_connect_fail_total 306
telemt_upstream_connect_attempts_per_request{bucket="1"} 24247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11701
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 306
telemt_me_reconnect_attempts_total 1813
telemt_me_reconnect_success_total 659
telemt_me_reader_eof_total 582
telemt_me_idle_close_by_peer_total 582
telemt_me_route_drop_no_conn_total 396165
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 814020
telemt_me_endpoint_quarantine_total 420
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 370
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 32
telemt_desync_total 3427
telemt_desync_full_logged_total 1999
telemt_desync_suppressed_total 1428
telemt_desync_frames_bucket_total{bucket="1_2"} 722
telemt_desync_frames_bucket_total{bucket="3_10"} 1319
telemt_desync_frames_bucket_total{bucket="gt_10"} 1386
telemt_pool_swap_total 49
telemt_pool_force_close_total 1287
telemt_me_writer_close_signal_drop_total 97
telemt_me_draining_writers_reap_progress_total 18886
telemt_me_writer_removed_unexpected_total 556
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1608
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17847
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1265
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17599
telemt_me_writer_teardown_success_total{mode="normal"} 19455
telemt_me_writer_teardown_noop_total 18886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38341
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.400764
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38341
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 97
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 497
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 815689
telemt_user_connections_current{user="hello"} 1494
telemt_user_octets_from_client{user="hello"} 13380234807 (12.46 GB)
telemt_user_octets_to_client{user="hello"} 300826374530 (280.17 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 932
telemt_user_unique_ips_recent_window{user="hello"} 437
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 120880.0 (33h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8490846
telemt_connections_bad_total 756141
telemt_connections_current 3211
telemt_connections_me_current 3211
telemt_handshake_timeouts_total 274177
telemt_upstream_connect_attempt_total 44925
telemt_upstream_connect_success_total 44846
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 44854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24376
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1712
telemt_me_reconnect_success_total 877
telemt_me_reader_eof_total 890
telemt_me_idle_close_by_peer_total 890
telemt_me_route_drop_no_conn_total 4702652
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6777042
telemt_me_endpoint_quarantine_total 768
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 907
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
telemt_me_writers_active_current 43
telemt_desync_total 28841
telemt_desync_full_logged_total 9587
telemt_desync_suppressed_total 19254
telemt_desync_frames_bucket_total{bucket="1_2"} 6245
telemt_desync_frames_bucket_total{bucket="3_10"} 11253
telemt_desync_frames_bucket_total{bucket="gt_10"} 11343
telemt_pool_swap_total 131
telemt_pool_force_close_total 4324
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 650
telemt_me_draining_writers_reap_progress_total 41019
telemt_me_writer_removed_unexpected_total 856
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3399
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37982
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4073
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 251
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36695
telemt_me_writer_teardown_success_total{mode="normal"} 41381
telemt_me_writer_teardown_noop_total 41063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82444
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 170.831309
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82444
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 650
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 784
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 6768227
telemt_user_connections_current{user="hello"} 3211
telemt_user_octets_from_client{user="hello"} 115179146420 (107.27 GB)
telemt_user_octets_to_client{user="hello"} 2309933119860 (2.10 TB)
telemt_user_unique_ips_current{user="hello"} 1243
telemt_user_unique_ips_recent_window{user="hello"} 578
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 120880.5 (33h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7010150
telemt_connections_bad_total 623776
telemt_connections_current 3511
telemt_connections_me_current 3511
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 233463
telemt_upstream_connect_attempt_total 48873
telemt_upstream_connect_success_total 48470
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 48676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23957
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 558
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2060
telemt_me_reconnect_success_total 936
telemt_me_reader_eof_total 915
telemt_me_idle_close_by_peer_total 915
telemt_me_route_drop_no_conn_total 2382461
telemt_me_route_drop_channel_closed_total 290
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5215351
telemt_me_endpoint_quarantine_total 766
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 930
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
telemt_me_writers_active_current 43
telemt_desync_total 24085
telemt_desync_full_logged_total 8288
telemt_desync_suppressed_total 15797
telemt_desync_frames_bucket_total{bucket="1_2"} 5774
telemt_desync_frames_bucket_total{bucket="3_10"} 9356
telemt_desync_frames_bucket_total{bucket="gt_10"} 8955
telemt_pool_swap_total 132
telemt_pool_force_close_total 3932
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 397
telemt_me_draining_writers_reap_progress_total 39456
telemt_me_writer_removed_unexpected_total 893
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3250
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37027
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3710
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 222
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35524
telemt_me_writer_teardown_success_total{mode="normal"} 40277
telemt_me_writer_teardown_noop_total 39462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79739
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 51.497806
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79739
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 397
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 817
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 5136610
telemt_user_connections_current{user="hello"} 3511
telemt_user_octets_from_client{user="hello"} 148316627789 (138.13 GB)
telemt_user_octets_to_client{user="hello"} 2470289818323 (2.25 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1347
telemt_user_unique_ips_recent_window{user="hello"} 714
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 120845.6 (33h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6813968
telemt_connections_bad_total 571834
telemt_connections_current 3012
telemt_connections_me_current 3012
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 228935
telemt_upstream_connect_attempt_total 55311
telemt_upstream_connect_success_total 54720
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 54864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25491
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 795
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 2582
telemt_me_reconnect_success_total 1114
telemt_me_reader_eof_total 1037
telemt_me_idle_close_by_peer_total 1037
telemt_me_route_drop_no_conn_total 2459568
telemt_me_route_drop_channel_closed_total 153
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5070707
telemt_me_endpoint_quarantine_total 868
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 17
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 17
telemt_me_single_endpoint_shadow_rotate_total 899
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
telemt_me_writers_active_current 44
telemt_desync_total 24028
telemt_desync_full_logged_total 8155
telemt_desync_suppressed_total 15873
telemt_desync_frames_bucket_total{bucket="1_2"} 5838
telemt_desync_frames_bucket_total{bucket="3_10"} 9228
telemt_desync_frames_bucket_total{bucket="gt_10"} 8962
telemt_pool_swap_total 130
telemt_pool_force_close_total 3796
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 426
telemt_me_draining_writers_reap_progress_total 40388
telemt_me_writer_removed_unexpected_total 1028
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3509
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37924
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3548
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 248
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36592
telemt_me_writer_teardown_success_total{mode="normal"} 41433
telemt_me_writer_teardown_noop_total 40400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81833
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 38.112431
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81833
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 426
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 961
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 5064916
telemt_user_connections_current{user="hello"} 3012
telemt_user_octets_from_client{user="hello"} 139087155335 (129.54 GB)
telemt_user_octets_to_client{user="hello"} 2303419860879 (2.09 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1076
telemt_user_unique_ips_recent_window{user="hello"} 695
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 120883.9 (33h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21757193
telemt_connections_bad_total 1843670
telemt_connections_current 4766
telemt_connections_me_current 4766
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 659475
telemt_upstream_connect_attempt_total 225042
telemt_upstream_connect_success_total 205893
telemt_upstream_connect_fail_total 17224
telemt_upstream_connect_attempts_per_request{bucket="1"} 223117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 145218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48525
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1954
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17224
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 66315
telemt_me_reconnect_success_total 2582
telemt_me_reader_eof_total 1620
telemt_me_idle_close_by_peer_total 1619
telemt_me_route_drop_no_conn_total 41127437
telemt_me_route_drop_channel_closed_total 131
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17481254
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 949
telemt_me_single_endpoint_outage_enter_total 154
telemt_me_single_endpoint_outage_exit_total 154
telemt_me_single_endpoint_outage_reconnect_attempt_total 323
telemt_me_single_endpoint_outage_reconnect_success_total 81
telemt_me_single_endpoint_quarantine_bypass_total 323
telemt_me_single_endpoint_shadow_rotate_total 952
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
telemt_me_writers_active_current 44
telemt_desync_total 33797
telemt_desync_full_logged_total 10148
telemt_desync_suppressed_total 23649
telemt_desync_frames_bucket_total{bucket="1_2"} 7435
telemt_desync_frames_bucket_total{bucket="3_10"} 14987
telemt_desync_frames_bucket_total{bucket="gt_10"} 11375
telemt_pool_swap_total 125
telemt_pool_force_close_total 3979
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 903
telemt_me_draining_writers_reap_progress_total 38012
telemt_me_writer_removed_unexpected_total 2397
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5165
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34992
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3416
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 563
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34033
telemt_me_writer_teardown_success_total{mode="normal"} 40157
telemt_me_writer_teardown_noop_total 38039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78196
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 227.196849
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78196
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 903
telemt_me_refill_failed_total 3862
telemt_me_writer_restored_same_endpoint_total 1755
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14705
telemt_me_writer_removed_unexpected_minus_restored_total 620
telemt_user_connections_total{user="hello"} 17633940
telemt_user_connections_current{user="hello"} 4766
telemt_user_octets_from_client{user="hello"} 260608504941 (242.71 GB)
telemt_user_octets_to_client{user="hello"} 1357188279051 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 454370
telemt_user_msgs_to_client{user="hello"} 903931
telemt_user_unique_ips_current{user="hello"} 1682
telemt_user_unique_ips_recent_window{user="hello"} 827
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 120851.6 (33h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6556137
telemt_connections_bad_total 617010
telemt_connections_current 2492
telemt_connections_me_current 2492
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 137233
telemt_upstream_connect_attempt_total 63959
telemt_upstream_connect_success_total 63220
telemt_upstream_connect_fail_total 633
telemt_upstream_connect_attempts_per_request{bucket="1"} 63853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26506
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 633
telemt_me_reconnect_attempts_total 69967
telemt_me_reconnect_success_total 1905
telemt_me_reader_eof_total 1681
telemt_me_idle_close_by_peer_total 1680
telemt_me_route_drop_no_conn_total 2517112
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5111268
telemt_me_endpoint_quarantine_total 817
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 918
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
telemt_desync_total 25402
telemt_desync_full_logged_total 8891
telemt_desync_suppressed_total 16511
telemt_desync_frames_bucket_total{bucket="1_2"} 5029
telemt_desync_frames_bucket_total{bucket="3_10"} 9785
telemt_desync_frames_bucket_total{bucket="gt_10"} 10588
telemt_pool_swap_total 126
telemt_pool_force_close_total 3608
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 426
telemt_me_draining_writers_reap_progress_total 42623
telemt_me_writer_removed_unexpected_total 1714
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4291
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40081
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3202
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 406
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39015
telemt_me_writer_teardown_success_total{mode="normal"} 44372
telemt_me_writer_teardown_noop_total 42624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86996
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.707188
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86996
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 426
telemt_me_refill_failed_total 4216
telemt_me_writer_restored_same_endpoint_total 1591
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 5103107
telemt_user_connections_current{user="hello"} 2492
telemt_user_octets_from_client{user="hello"} 131366214044 (122.34 GB)
telemt_user_octets_to_client{user="hello"} 2129780708590 (1.94 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 998
telemt_user_unique_ips_recent_window{user="hello"} 493
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 57687.7 (16h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4637006
telemt_connections_bad_total 193761
telemt_connections_current 3750
telemt_connections_me_current 3750
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1831267
telemt_upstream_connect_attempt_total 32723
telemt_upstream_connect_success_total 32505
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 32715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12760
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_reconnect_attempts_total 46108
telemt_me_reconnect_success_total 1042
telemt_me_reader_eof_total 733
telemt_me_idle_close_by_peer_total 733
telemt_me_route_drop_no_conn_total 1151433
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2300059
telemt_me_endpoint_quarantine_total 407
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 444
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
telemt_me_writers_warm_current 28
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 12309
telemt_desync_full_logged_total 4237
telemt_desync_suppressed_total 8072
telemt_desync_frames_bucket_total{bucket="1_2"} 2378
telemt_desync_frames_bucket_total{bucket="3_10"} 4702
telemt_desync_frames_bucket_total{bucket="gt_10"} 5229
telemt_pool_swap_total 62
telemt_pool_force_close_total 1820
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 159
telemt_me_draining_writers_reap_progress_total 21241
telemt_me_writer_removed_unexpected_total 803
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1799
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20275
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1607
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19421
telemt_me_writer_teardown_success_total{mode="normal"} 22074
telemt_me_writer_teardown_noop_total 21243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43317
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.708227
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43317
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 159
telemt_me_refill_failed_total 2618
telemt_me_writer_restored_same_endpoint_total 930
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2302277
telemt_user_connections_current{user="hello"} 3750
telemt_user_octets_from_client{user="hello"} 60687219540 (56.52 GB)
telemt_user_octets_to_client{user="hello"} 1019866726382 (949.82 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1574
telemt_user_unique_ips_recent_window{user="hello"} 535
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 38658.1 (10h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282005
telemt_connections_bad_total 2019
telemt_connections_current 639
telemt_connections_me_current 639
telemt_handshake_timeouts_total 6868
telemt_upstream_connect_attempt_total 18571
telemt_upstream_connect_success_total 18526
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 18567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10653
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 485
telemt_me_reconnect_success_total 255
telemt_me_reader_eof_total 256
telemt_me_idle_close_by_peer_total 256
telemt_me_route_drop_no_conn_total 81073
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 253109
telemt_me_endpoint_quarantine_total 364
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 333
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
telemt_desync_total 1288
telemt_desync_full_logged_total 357
telemt_desync_suppressed_total 931
telemt_desync_frames_bucket_total{bucket="1_2"} 438
telemt_desync_frames_bucket_total{bucket="3_10"} 495
telemt_desync_frames_bucket_total{bucket="gt_10"} 355
telemt_pool_swap_total 42
telemt_pool_force_close_total 936
telemt_me_writer_close_signal_drop_total 35
telemt_me_draining_writers_reap_progress_total 16818
telemt_me_writer_removed_unexpected_total 245
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1073
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16001
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 934
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15882
telemt_me_writer_teardown_success_total{mode="normal"} 17074
telemt_me_writer_teardown_noop_total 16818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33892
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.311209
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33892
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 35
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 221
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 252711
telemt_user_connections_current{user="hello"} 639
telemt_user_octets_from_client{user="hello"} 4205726888 (3.92 GB)
telemt_user_octets_to_client{user="hello"} 151165541856 (140.78 GB)
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 120856.3 (33h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7951105
telemt_connections_bad_total 800600
telemt_connections_current 3524
telemt_connections_me_current 3524
telemt_handshake_timeouts_total 225107
telemt_upstream_connect_attempt_total 47597
telemt_upstream_connect_success_total 47424
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 47560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23918
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_reconnect_attempts_total 1758
telemt_me_reconnect_success_total 940
telemt_me_reader_eof_total 924
telemt_me_idle_close_by_peer_total 924
telemt_me_route_drop_no_conn_total 2249818
telemt_me_route_drop_channel_closed_total 53
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5932389
telemt_me_endpoint_quarantine_total 865
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 927
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
telemt_desync_total 23269
telemt_desync_full_logged_total 7667
telemt_desync_suppressed_total 15602
telemt_desync_frames_bucket_total{bucket="1_2"} 5819
telemt_desync_frames_bucket_total{bucket="3_10"} 8481
telemt_desync_frames_bucket_total{bucket="gt_10"} 8969
telemt_pool_swap_total 134
telemt_pool_force_close_total 3572
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 422
telemt_me_draining_writers_reap_progress_total 42972
telemt_me_writer_removed_unexpected_total 887
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3370
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40516
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3481
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 91
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39400
telemt_me_writer_teardown_success_total{mode="normal"} 43886
telemt_me_writer_teardown_noop_total 42974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86860
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.201103
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86860
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 422
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 836
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 5906701
telemt_user_connections_current{user="hello"} 3524
telemt_user_octets_from_client{user="hello"} 115953739612 (107.99 GB)
telemt_user_octets_to_client{user="hello"} 2771439675304 (2.52 TB)
telemt_user_unique_ips_current{user="hello"} 1295
telemt_user_unique_ips_recent_window{user="hello"} 539
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 120852.9 (33h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6915562
telemt_connections_bad_total 673122
telemt_connections_current 3674
telemt_connections_me_current 3674
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 186499
telemt_upstream_connect_attempt_total 63386
telemt_upstream_connect_success_total 62900
telemt_upstream_connect_fail_total 423
telemt_upstream_connect_attempts_per_request{bucket="1"} 63323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 423
telemt_me_reconnect_attempts_total 5860
telemt_me_reconnect_success_total 1309
telemt_me_reader_eof_total 1174
telemt_me_idle_close_by_peer_total 1174
telemt_me_seq_mismatch_total 58
telemt_me_route_drop_no_conn_total 2309437
telemt_me_route_drop_channel_closed_total 193
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5299713
telemt_me_endpoint_quarantine_total 956
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 927
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
telemt_me_writers_active_current 46
telemt_desync_total 22163
telemt_desync_full_logged_total 7375
telemt_desync_suppressed_total 14788
telemt_desync_frames_bucket_total{bucket="1_2"} 5558
telemt_desync_frames_bucket_total{bucket="3_10"} 8102
telemt_desync_frames_bucket_total{bucket="gt_10"} 8503
telemt_pool_swap_total 132
telemt_pool_force_close_total 3519
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 423
telemt_me_draining_writers_reap_progress_total 41449
telemt_me_writer_removed_unexpected_total 1188
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3924
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38772
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3294
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 225
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37930
telemt_me_writer_teardown_success_total{mode="normal"} 42696
telemt_me_writer_teardown_noop_total 41453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84149
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.903063
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84149
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 423
telemt_me_refill_failed_total 262
telemt_me_writer_restored_same_endpoint_total 1018
telemt_me_writer_restored_fallback_total 77
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 5302055
telemt_user_connections_current{user="hello"} 3674
telemt_user_octets_from_client{user="hello"} 99177772085 (92.37 GB)
telemt_user_octets_to_client{user="hello"} 2302600797436 (2.09 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1407
telemt_user_unique_ips_recent_window{user="hello"} 550
```
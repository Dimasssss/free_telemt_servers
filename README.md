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

# Server Metrics 2026-03-22 12:48:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 56553.2 (15h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1709311
telemt_connections_bad_total 79075
telemt_connections_current 1641
telemt_connections_me_current 1641
telemt_handshake_timeouts_total 75311
telemt_upstream_connect_attempt_total 21352
telemt_upstream_connect_success_total 21351
telemt_upstream_connect_attempts_per_request{bucket="1"} 21351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13914
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 889
telemt_me_reconnect_success_total 347
telemt_me_reader_eof_total 350
telemt_me_idle_close_by_peer_total 350
telemt_me_route_drop_no_conn_total 1136143
telemt_me_route_drop_channel_closed_total 518
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1447072
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 398
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 449
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
telemt_me_writers_active_current 41
telemt_desync_total 8469
telemt_desync_full_logged_total 2570
telemt_desync_suppressed_total 5899
telemt_desync_frames_bucket_total{bucket="1_2"} 2377
telemt_desync_frames_bucket_total{bucket="3_10"} 3194
telemt_desync_frames_bucket_total{bucket="gt_10"} 2898
telemt_pool_swap_total 62
telemt_pool_force_close_total 1853
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 284
telemt_me_draining_writers_reap_progress_total 19478
telemt_me_writer_removed_unexpected_total 342
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1380
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18315
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1818
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17625
telemt_me_writer_teardown_success_total{mode="normal"} 19695
telemt_me_writer_teardown_noop_total 19480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39175
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 138.272540
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39175
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 284
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 306
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 1444296
telemt_user_connections_current{user="hello"} 1641
telemt_user_octets_from_client{user="hello"} 23088663540 (21.50 GB)
telemt_user_octets_to_client{user="hello"} 429052183648 (399.59 GB)
telemt_user_unique_ips_current{user="hello"} 644
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 69919.3 (19h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2760991
telemt_connections_bad_total 260422
telemt_connections_current 2080
telemt_connections_me_current 2080
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 65294
telemt_upstream_connect_attempt_total 45826
telemt_upstream_connect_success_total 45291
telemt_upstream_connect_fail_total 473
telemt_upstream_connect_attempts_per_request{bucket="1"} 45764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 473
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3486
telemt_me_reconnect_success_total 1583
telemt_me_reader_eof_total 1465
telemt_me_idle_close_by_peer_total 1465
telemt_me_route_drop_no_conn_total 2437542
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2160243
telemt_me_endpoint_quarantine_total 592
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 547
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
telemt_me_writers_active_current 46
telemt_desync_total 8596
telemt_desync_full_logged_total 4830
telemt_desync_suppressed_total 3766
telemt_desync_frames_bucket_total{bucket="1_2"} 2024
telemt_desync_frames_bucket_total{bucket="3_10"} 3347
telemt_desync_frames_bucket_total{bucket="gt_10"} 3225
telemt_pool_swap_total 69
telemt_pool_force_close_total 1975
telemt_me_writer_close_signal_drop_total 165
telemt_me_draining_writers_reap_progress_total 27855
telemt_me_writer_removed_unexpected_total 1425
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3048
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26232
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1737
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 238
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25880
telemt_me_writer_teardown_success_total{mode="normal"} 29280
telemt_me_writer_teardown_noop_total 27855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57135
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.026619
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57135
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 165
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 1320
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 2171948
telemt_user_connections_current{user="hello"} 2080
telemt_user_octets_from_client{user="hello"} 26737074391 (24.90 GB)
telemt_user_octets_to_client{user="hello"} 524235969822 (488.23 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1219
telemt_user_unique_ips_recent_window{user="hello"} 776
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 144780.5 (40h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13089077
telemt_connections_bad_total 1156610
telemt_connections_current 5917
telemt_connections_me_current 5917
telemt_handshake_timeouts_total 338616
telemt_upstream_connect_attempt_total 52667
telemt_upstream_connect_success_total 52587
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 52595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28568
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2381
telemt_me_reconnect_success_total 1231
telemt_me_reader_eof_total 1194
telemt_me_idle_close_by_peer_total 1193
telemt_me_route_drop_no_conn_total 10781041
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10461034
telemt_me_endpoint_quarantine_total 914
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1076
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
telemt_me_writers_active_current 46
telemt_desync_total 43146
telemt_desync_full_logged_total 13764
telemt_desync_suppressed_total 29382
telemt_desync_frames_bucket_total{bucket="1_2"} 9755
telemt_desync_frames_bucket_total{bucket="3_10"} 16854
telemt_desync_frames_bucket_total{bucket="gt_10"} 16537
telemt_pool_swap_total 155
telemt_pool_force_close_total 5294
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 838
telemt_me_draining_writers_reap_progress_total 48018
telemt_me_writer_removed_unexpected_total 1152
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4172
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44355
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4875
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42724
telemt_me_writer_teardown_success_total{mode="normal"} 48527
telemt_me_writer_teardown_noop_total 48066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96593
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 233.602596
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96593
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 838
telemt_me_refill_failed_total 63
telemt_me_writer_restored_same_endpoint_total 1067
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 10449425
telemt_user_connections_current{user="hello"} 5917
telemt_user_octets_from_client{user="hello"} 154153951404 (143.57 GB)
telemt_user_octets_to_client{user="hello"} 2890342021116 (2.63 TB)
telemt_user_unique_ips_current{user="hello"} 2341
telemt_user_unique_ips_recent_window{user="hello"} 959
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 144780.8 (40h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9868589
telemt_connections_bad_total 906735
telemt_connections_current 4770
telemt_connections_me_current 4770
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 297496
telemt_upstream_connect_attempt_total 79117
telemt_upstream_connect_success_total 77986
telemt_upstream_connect_fail_total 815
telemt_upstream_connect_attempts_per_request{bucket="1"} 78801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31170
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3673
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 815
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3388
telemt_me_reconnect_success_total 1411
telemt_me_reader_eof_total 1297
telemt_me_idle_close_by_peer_total 1297
telemt_me_route_drop_no_conn_total 3954452
telemt_me_route_drop_channel_closed_total 409
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7361678
telemt_me_endpoint_quarantine_total 904
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1101
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
telemt_me_writers_active_current 88
telemt_desync_total 33281
telemt_desync_full_logged_total 11232
telemt_desync_suppressed_total 22049
telemt_desync_frames_bucket_total{bucket="1_2"} 8176
telemt_desync_frames_bucket_total{bucket="3_10"} 12822
telemt_desync_frames_bucket_total{bucket="gt_10"} 12283
telemt_pool_swap_total 154
telemt_pool_force_close_total 4706
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 576
telemt_me_draining_writers_reap_progress_total 46302
telemt_me_writer_removed_unexpected_total 1328
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4161
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43337
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4327
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 379
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41596
telemt_me_writer_teardown_success_total{mode="normal"} 47498
telemt_me_writer_teardown_noop_total 46313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93811
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 83.246577
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93811
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 576
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 1212
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 7301988
telemt_user_connections_current{user="hello"} 4770
telemt_user_octets_from_client{user="hello"} 188875956045 (175.90 GB)
telemt_user_octets_to_client{user="hello"} 3317164597290 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 2083
telemt_user_unique_ips_recent_window{user="hello"} 615
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 144744.8 (40h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9301660
telemt_connections_bad_total 787076
telemt_connections_current 3546
telemt_connections_me_current 3546
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 295502
telemt_upstream_connect_attempt_total 64297
telemt_upstream_connect_success_total 63541
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 63703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29817
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1964
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 306
telemt_me_reconnect_attempts_total 3887
telemt_me_reconnect_success_total 1687
telemt_me_reader_eof_total 1509
telemt_me_idle_close_by_peer_total 1508
telemt_me_route_drop_no_conn_total 4026647
telemt_me_route_drop_channel_closed_total 292
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7007671
telemt_me_endpoint_quarantine_total 992
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1060
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 33096
telemt_desync_full_logged_total 10974
telemt_desync_suppressed_total 22122
telemt_desync_frames_bucket_total{bucket="1_2"} 8424
telemt_desync_frames_bucket_total{bucket="3_10"} 12658
telemt_desync_frames_bucket_total{bucket="gt_10"} 12014
telemt_pool_swap_total 151
telemt_pool_force_close_total 4700
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 610
telemt_me_draining_writers_reap_progress_total 47021
telemt_me_writer_removed_unexpected_total 1589
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4563
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43969
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4210
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 490
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42321
telemt_me_writer_teardown_success_total{mode="normal"} 48532
telemt_me_writer_teardown_noop_total 47088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95620
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3093.096489
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95620
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 610
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1468
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 6999319
telemt_user_connections_current{user="hello"} 3546
telemt_user_octets_from_client{user="hello"} 168505091165 (156.93 GB)
telemt_user_octets_to_client{user="hello"} 2991362940605 (2.72 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1490
telemt_user_unique_ips_recent_window{user="hello"} 593
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 15024.5 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6349637
telemt_connections_bad_total 396184
telemt_connections_current 6592
telemt_connections_me_current 6592
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 100128
telemt_upstream_connect_attempt_total 24482
telemt_upstream_connect_success_total 23382
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 24220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5108
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4634
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_timeout_total 524
telemt_me_reconnect_attempts_total 2349
telemt_me_reconnect_success_total 374
telemt_me_reader_eof_total 241
telemt_me_idle_close_by_peer_total 241
telemt_me_route_drop_no_conn_total 15155786
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5299304
telemt_me_endpoint_quarantine_total 97
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 123
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
telemt_me_writers_active_current 43
telemt_desync_total 8061
telemt_desync_full_logged_total 2043
telemt_desync_suppressed_total 6018
telemt_desync_frames_bucket_total{bucket="1_2"} 1442
telemt_desync_frames_bucket_total{bucket="3_10"} 3226
telemt_desync_frames_bucket_total{bucket="gt_10"} 3393
telemt_pool_swap_total 14
telemt_pool_force_close_total 570
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 223
telemt_me_draining_writers_reap_progress_total 3896
telemt_me_writer_removed_unexpected_total 329
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 651
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3531
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 424
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 146
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3326
telemt_me_writer_teardown_success_total{mode="normal"} 4182
telemt_me_writer_teardown_noop_total 3899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8081
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.617004
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8081
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 223
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 253
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 5312620
telemt_user_connections_current{user="hello"} 6592
telemt_user_octets_from_client{user="hello"} 28922608030 (26.94 GB)
telemt_user_octets_to_client{user="hello"} 155923635795 (145.22 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2488
telemt_user_unique_ips_recent_window{user="hello"} 1281
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 144751.2 (40h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9079292
telemt_connections_bad_total 760659
telemt_connections_current 4857
telemt_connections_me_current 4857
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 194326
telemt_upstream_connect_attempt_total 88824
telemt_upstream_connect_success_total 87950
telemt_upstream_connect_fail_total 752
telemt_upstream_connect_attempts_per_request{bucket="1"} 88702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31782
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1250
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 752
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71137
telemt_me_reconnect_success_total 2371
telemt_me_reader_eof_total 2112
telemt_me_idle_close_by_peer_total 2111
telemt_me_route_drop_no_conn_total 4363567
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7173232
telemt_me_endpoint_quarantine_total 966
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1080
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
telemt_desync_total 36749
telemt_desync_full_logged_total 12597
telemt_desync_suppressed_total 24152
telemt_desync_frames_bucket_total{bucket="1_2"} 7485
telemt_desync_frames_bucket_total{bucket="3_10"} 14147
telemt_desync_frames_bucket_total{bucket="gt_10"} 15117
telemt_pool_swap_total 148
telemt_pool_force_close_total 4355
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 525
telemt_me_draining_writers_reap_progress_total 49606
telemt_me_writer_removed_unexpected_total 2140
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5231
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46541
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3761
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 594
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45251
telemt_me_writer_teardown_success_total{mode="normal"} 51772
telemt_me_writer_teardown_noop_total 49607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101379
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.057493
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101379
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 525
telemt_me_refill_failed_total 4245
telemt_me_writer_restored_same_endpoint_total 1990
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 7175378
telemt_user_connections_current{user="hello"} 4857
telemt_user_octets_from_client{user="hello"} 167948087155 (156.41 GB)
telemt_user_octets_to_client{user="hello"} 2757574492689 (2.51 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1980
telemt_user_unique_ips_recent_window{user="hello"} 631
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 81587.2 (22h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8701360
telemt_connections_bad_total 308993
telemt_connections_current 4092
telemt_connections_me_current 4092
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3654322
telemt_upstream_connect_attempt_total 41105
telemt_upstream_connect_success_total 40815
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 41098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_reconnect_attempts_total 47862
telemt_me_reconnect_success_total 1416
telemt_me_reader_eof_total 1085
telemt_me_idle_close_by_peer_total 1085
telemt_me_route_drop_no_conn_total 3027211
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4221259
telemt_me_endpoint_quarantine_total 542
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 615
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 23236
telemt_desync_full_logged_total 7777
telemt_desync_suppressed_total 15459
telemt_desync_frames_bucket_total{bucket="1_2"} 4750
telemt_desync_frames_bucket_total{bucket="3_10"} 9081
telemt_desync_frames_bucket_total{bucket="gt_10"} 9405
telemt_pool_swap_total 85
telemt_pool_force_close_total 2637
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 270
telemt_me_draining_writers_reap_progress_total 28590
telemt_me_writer_removed_unexpected_total 1150
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2586
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27182
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2242
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 395
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25953
telemt_me_writer_teardown_success_total{mode="normal"} 29768
telemt_me_writer_teardown_noop_total 28597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58365
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.841653
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58365
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 270
telemt_me_refill_failed_total 2700
telemt_me_writer_restored_same_endpoint_total 1267
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4216983
telemt_user_connections_current{user="hello"} 4092
telemt_user_octets_from_client{user="hello"} 94222828724 (87.75 GB)
telemt_user_octets_to_client{user="hello"} 1650082935258 (1.50 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1646
telemt_user_unique_ips_recent_window{user="hello"} 587
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 62558.4 (17h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 709304
telemt_connections_bad_total 8385
telemt_connections_current 1004
telemt_connections_me_current 1004
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 13809
telemt_upstream_connect_attempt_total 32041
telemt_upstream_connect_success_total 31962
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 32029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 372
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_reconnect_attempts_total 1405
telemt_me_reconnect_success_total 612
telemt_me_reader_eof_total 592
telemt_me_idle_close_by_peer_total 592
telemt_me_route_drop_no_conn_total 237632
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 640203
telemt_me_endpoint_quarantine_total 568
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 525
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
telemt_me_writers_active_current 48
telemt_desync_total 3452
telemt_desync_full_logged_total 1022
telemt_desync_suppressed_total 2430
telemt_desync_frames_bucket_total{bucket="1_2"} 851
telemt_desync_frames_bucket_total{bucket="3_10"} 1377
telemt_desync_frames_bucket_total{bucket="gt_10"} 1224
telemt_pool_swap_total 66
telemt_pool_force_close_total 1624
telemt_me_writer_close_signal_drop_total 96
telemt_me_draining_writers_reap_progress_total 26243
telemt_me_writer_removed_unexpected_total 574
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2000
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24837
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1547
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24619
telemt_me_writer_teardown_success_total{mode="normal"} 26837
telemt_me_writer_teardown_noop_total 26245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53082
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.894332
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53082
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 96
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 531
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 641892
telemt_user_connections_current{user="hello"} 1004
telemt_user_octets_from_client{user="hello"} 12318908561 (11.47 GB)
telemt_user_octets_to_client{user="hello"} 309037140123 (287.81 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 354
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 144755.7 (40h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11072705
telemt_connections_bad_total 1283793
telemt_connections_current 6117
telemt_connections_me_current 6117
telemt_handshake_timeouts_total 297247
telemt_upstream_connect_attempt_total 54901
telemt_upstream_connect_success_total 54688
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 54853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27673
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_reconnect_attempts_total 2153
telemt_me_reconnect_success_total 1146
telemt_me_reader_eof_total 1109
telemt_me_idle_close_by_peer_total 1109
telemt_me_route_drop_no_conn_total 3474686
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 32
telemt_me_route_drop_queue_full_profile_total{profile="high"} 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8317461
telemt_me_endpoint_quarantine_total 1000
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1087
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
telemt_me_writers_active_current 46
telemt_desync_total 33868
telemt_desync_full_logged_total 11094
telemt_desync_suppressed_total 22774
telemt_desync_frames_bucket_total{bucket="1_2"} 8122
telemt_desync_frames_bucket_total{bucket="3_10"} 12523
telemt_desync_frames_bucket_total{bucket="gt_10"} 13223
telemt_pool_swap_total 160
telemt_pool_force_close_total 4380
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 547
telemt_me_draining_writers_reap_progress_total 49468
telemt_me_writer_removed_unexpected_total 1065
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4036
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46532
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4234
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 146
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45088
telemt_me_writer_teardown_success_total{mode="normal"} 50568
telemt_me_writer_teardown_noop_total 49470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100038
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.601011
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100038
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 547
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 1002
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 8288488
telemt_user_connections_current{user="hello"} 6117
telemt_user_octets_from_client{user="hello"} 158817906276 (147.91 GB)
telemt_user_octets_to_client{user="hello"} 3750982486144 (3.41 TB)
telemt_user_unique_ips_current{user="hello"} 2310
telemt_user_unique_ips_recent_window{user="hello"} 766
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 144752.2 (40h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9600720
telemt_connections_bad_total 1078009
telemt_connections_current 4028
telemt_connections_me_current 4028
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 249619
telemt_upstream_connect_attempt_total 80182
telemt_upstream_connect_success_total 79598
telemt_upstream_connect_fail_total 506
telemt_upstream_connect_attempts_per_request{bucket="1"} 80104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32570
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1996
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 506
telemt_me_reconnect_attempts_total 8494
telemt_me_reconnect_success_total 1865
telemt_me_reader_eof_total 1736
telemt_me_idle_close_by_peer_total 1736
telemt_me_seq_mismatch_total 70
telemt_me_route_drop_no_conn_total 4155934
telemt_me_route_drop_channel_closed_total 302
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7383545
telemt_me_endpoint_quarantine_total 1107
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1092
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
telemt_me_writers_active_current 42
telemt_desync_total 33218
telemt_desync_full_logged_total 10860
telemt_desync_suppressed_total 22358
telemt_desync_frames_bucket_total{bucket="1_2"} 8219
telemt_desync_frames_bucket_total{bucket="3_10"} 12372
telemt_desync_frames_bucket_total{bucket="gt_10"} 12627
telemt_pool_swap_total 154
telemt_pool_force_close_total 4256
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 537
telemt_me_draining_writers_reap_progress_total 48568
telemt_me_writer_removed_unexpected_total 1761
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5000
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45394
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3893
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 363
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44312
telemt_me_writer_teardown_success_total{mode="normal"} 50394
telemt_me_writer_teardown_noop_total 48572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98966
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.329564
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98966
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 537
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 1509
telemt_me_writer_restored_fallback_total 94
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 7391115
telemt_user_connections_current{user="hello"} 4028
telemt_user_octets_from_client{user="hello"} 130394084481 (121.44 GB)
telemt_user_octets_to_client{user="hello"} 2946242633987 (2.68 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1705
telemt_user_unique_ips_recent_window{user="hello"} 597
```
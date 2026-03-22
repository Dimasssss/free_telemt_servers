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

# Server Metrics 2026-03-22 13:09:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 57774.3 (16h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1780704
telemt_connections_bad_total 80419
telemt_connections_current 1755
telemt_connections_me_current 1755
telemt_handshake_timeouts_total 77561
telemt_upstream_connect_attempt_total 21782
telemt_upstream_connect_success_total 21781
telemt_upstream_connect_attempts_per_request{bucket="1"} 21781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14200
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 896
telemt_me_reconnect_success_total 352
telemt_me_reader_eof_total 356
telemt_me_idle_close_by_peer_total 356
telemt_me_route_drop_no_conn_total 1264052
telemt_me_route_drop_channel_closed_total 555
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1511698
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 404
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 458
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
telemt_desync_total 8600
telemt_desync_full_logged_total 2621
telemt_desync_suppressed_total 5979
telemt_desync_frames_bucket_total{bucket="1_2"} 2411
telemt_desync_frames_bucket_total{bucket="3_10"} 3238
telemt_desync_frames_bucket_total{bucket="gt_10"} 2951
telemt_pool_swap_total 64
telemt_pool_force_close_total 1884
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 303
telemt_me_draining_writers_reap_progress_total 19832
telemt_me_writer_removed_unexpected_total 347
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1406
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18649
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1848
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17948
telemt_me_writer_teardown_success_total{mode="normal"} 20055
telemt_me_writer_teardown_noop_total 19834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39889
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 146.770992
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39889
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 303
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 311
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 1508837
telemt_user_connections_current{user="hello"} 1755
telemt_user_octets_from_client{user="hello"} 23571127420 (21.95 GB)
telemt_user_octets_to_client{user="hello"} 442145028220 (411.78 GB)
telemt_user_unique_ips_current{user="hello"} 655
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 71141.0 (19h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2886773
telemt_connections_bad_total 274149
telemt_connections_current 2587
telemt_connections_me_current 2587
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 68115
telemt_upstream_connect_attempt_total 46202
telemt_upstream_connect_success_total 45662
telemt_upstream_connect_fail_total 478
telemt_upstream_connect_attempts_per_request{bucket="1"} 46140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 478
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3531
telemt_me_reconnect_success_total 1593
telemt_me_reader_eof_total 1473
telemt_me_idle_close_by_peer_total 1473
telemt_me_route_drop_no_conn_total 2614471
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2262005
telemt_me_endpoint_quarantine_total 596
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 553
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 7
telemt_desync_total 8904
telemt_desync_full_logged_total 4986
telemt_desync_suppressed_total 3918
telemt_desync_frames_bucket_total{bucket="1_2"} 2085
telemt_desync_frames_bucket_total{bucket="3_10"} 3479
telemt_desync_frames_bucket_total{bucket="gt_10"} 3340
telemt_pool_swap_total 70
telemt_pool_force_close_total 2006
telemt_me_writer_close_signal_drop_total 169
telemt_me_draining_writers_reap_progress_total 28191
telemt_me_writer_removed_unexpected_total 1433
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3076
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26548
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1766
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 240
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26185
telemt_me_writer_teardown_success_total{mode="normal"} 29624
telemt_me_writer_teardown_noop_total 28191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57815
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.340566
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57815
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 169
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1326
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 2273673
telemt_user_connections_current{user="hello"} 2587
telemt_user_octets_from_client{user="hello"} 27898505839 (25.98 GB)
telemt_user_octets_to_client{user="hello"} 534605172390 (497.89 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1581
telemt_user_unique_ips_recent_window{user="hello"} 993
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 146000.2 (40h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13405710
telemt_connections_bad_total 1182511
telemt_connections_current 4282
telemt_connections_me_current 4282
telemt_handshake_timeouts_total 343075
telemt_upstream_connect_attempt_total 53158
telemt_upstream_connect_success_total 53076
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 53084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28804
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2429
telemt_me_reconnect_success_total 1272
telemt_me_reader_eof_total 1214
telemt_me_idle_close_by_peer_total 1213
telemt_me_route_drop_no_conn_total 11323378
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10731510
telemt_me_endpoint_quarantine_total 931
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1086
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
telemt_desync_total 43945
telemt_desync_full_logged_total 13999
telemt_desync_suppressed_total 29946
telemt_desync_frames_bucket_total{bucket="1_2"} 9945
telemt_desync_frames_bucket_total{bucket="3_10"} 17163
telemt_desync_frames_bucket_total{bucket="gt_10"} 16837
telemt_pool_swap_total 157
telemt_pool_force_close_total 5376
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 849
telemt_me_draining_writers_reap_progress_total 48482
telemt_me_writer_removed_unexpected_total 1171
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4221
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44766
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4946
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 430
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43106
telemt_me_writer_teardown_success_total{mode="normal"} 48987
telemt_me_writer_teardown_noop_total 48530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97517
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 244.113577
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97517
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 849
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 1095
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 10719625
telemt_user_connections_current{user="hello"} 4281
telemt_user_octets_from_client{user="hello"} 156637416836 (145.88 GB)
telemt_user_octets_to_client{user="hello"} 2918306255612 (2.65 TB)
telemt_user_unique_ips_current{user="hello"} 1460
telemt_user_unique_ips_recent_window{user="hello"} 1279
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 146002.2 (40h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10023009
telemt_connections_bad_total 926010
telemt_connections_current 5747
telemt_connections_me_current 5747
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 301731
telemt_upstream_connect_attempt_total 79559
telemt_upstream_connect_success_total 78422
telemt_upstream_connect_fail_total 816
telemt_upstream_connect_attempts_per_request{bucket="1"} 79238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31389
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3676
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 816
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3617
telemt_me_reconnect_success_total 1441
telemt_me_reader_eof_total 1320
telemt_me_idle_close_by_peer_total 1320
telemt_me_route_drop_no_conn_total 4012830
telemt_me_route_drop_channel_closed_total 417
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7482170
telemt_me_endpoint_quarantine_total 916
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 1108
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
telemt_desync_total 33707
telemt_desync_full_logged_total 11367
telemt_desync_suppressed_total 22340
telemt_desync_frames_bucket_total{bucket="1_2"} 8315
telemt_desync_frames_bucket_total{bucket="3_10"} 12964
telemt_desync_frames_bucket_total{bucket="gt_10"} 12428
telemt_pool_swap_total 156
telemt_pool_force_close_total 4767
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 593
telemt_me_draining_writers_reap_progress_total 46701
telemt_me_writer_removed_unexpected_total 1352
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4221
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43700
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4355
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 412
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41934
telemt_me_writer_teardown_success_total{mode="normal"} 47921
telemt_me_writer_teardown_noop_total 46713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94634
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 85.623612
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94634
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 593
telemt_me_refill_failed_total 118
telemt_me_writer_restored_same_endpoint_total 1226
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 7422227
telemt_user_connections_current{user="hello"} 5747
telemt_user_octets_from_client{user="hello"} 191063008049 (177.94 GB)
telemt_user_octets_to_client{user="hello"} 3363002980902 (3.06 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 2336
telemt_user_unique_ips_recent_window{user="hello"} 751
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 145987.0 (40h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9482826
telemt_connections_bad_total 799051
telemt_connections_current 6496
telemt_connections_me_current 6496
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 302355
telemt_upstream_connect_attempt_total 64682
telemt_upstream_connect_success_total 63911
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 64080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30011
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1971
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_timeout_total 317
telemt_me_reconnect_attempts_total 3908
telemt_me_reconnect_success_total 1706
telemt_me_reader_eof_total 1520
telemt_me_idle_close_by_peer_total 1519
telemt_me_route_drop_no_conn_total 4178683
telemt_me_route_drop_channel_closed_total 299
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7145961
telemt_me_endpoint_quarantine_total 1000
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1068
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
telemt_me_writers_active_current 55
telemt_me_writers_warm_current 14
telemt_desync_total 33553
telemt_desync_full_logged_total 11136
telemt_desync_suppressed_total 22417
telemt_desync_frames_bucket_total{bucket="1_2"} 8530
telemt_desync_frames_bucket_total{bucket="3_10"} 12851
telemt_desync_frames_bucket_total{bucket="gt_10"} 12172
telemt_pool_swap_total 152
telemt_pool_force_close_total 4730
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 621
telemt_me_draining_writers_reap_progress_total 47293
telemt_me_writer_removed_unexpected_total 1612
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4606
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44221
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 491
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42563
telemt_me_writer_teardown_success_total{mode="normal"} 48826
telemt_me_writer_teardown_noop_total 47360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96186
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3104.137574
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96186
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 621
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1486
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 7140996
telemt_user_connections_current{user="hello"} 6496
telemt_user_octets_from_client{user="hello"} 170263486213 (158.57 GB)
telemt_user_octets_to_client{user="hello"} 3026449870097 (2.75 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1753
telemt_user_unique_ips_recent_window{user="hello"} 991
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 16245.6 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6847860
telemt_connections_bad_total 433269
telemt_connections_current 6894
telemt_connections_me_current 6894
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 107929
telemt_upstream_connect_attempt_total 25017
telemt_upstream_connect_success_total 23885
telemt_upstream_connect_fail_total 845
telemt_upstream_connect_attempts_per_request{bucket="1"} 24730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5375
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4651
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 845
telemt_me_keepalive_timeout_total 622
telemt_me_reconnect_attempts_total 2397
telemt_me_reconnect_success_total 418
telemt_me_reader_eof_total 284
telemt_me_idle_close_by_peer_total 284
telemt_me_route_drop_no_conn_total 16563416
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5704272
telemt_me_endpoint_quarantine_total 97
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 129
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
telemt_me_writers_active_current 85
telemt_me_writers_warm_current 14
telemt_desync_total 8500
telemt_desync_full_logged_total 2176
telemt_desync_suppressed_total 6324
telemt_desync_frames_bucket_total{bucket="1_2"} 1539
telemt_desync_frames_bucket_total{bucket="3_10"} 3423
telemt_desync_frames_bucket_total{bucket="gt_10"} 3538
telemt_pool_swap_total 14
telemt_pool_force_close_total 570
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 223
telemt_me_draining_writers_reap_progress_total 4274
telemt_me_writer_removed_unexpected_total 374
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 706
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3899
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 424
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 146
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3704
telemt_me_writer_teardown_success_total{mode="normal"} 4605
telemt_me_writer_teardown_noop_total 4277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 8354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 8689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8882
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.929694
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8882
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 223
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 297
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 5717534
telemt_user_connections_current{user="hello"} 6895
telemt_user_octets_from_client{user="hello"} 31065543218 (28.93 GB)
telemt_user_octets_to_client{user="hello"} 169584134543 (157.94 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2553
telemt_user_unique_ips_recent_window{user="hello"} 1389
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 145972.5 (40h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9219019
telemt_connections_bad_total 771858
telemt_connections_current 4429
telemt_connections_me_current 4429
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 198671
telemt_upstream_connect_attempt_total 89246
telemt_upstream_connect_success_total 88352
telemt_upstream_connect_fail_total 771
telemt_upstream_connect_attempts_per_request{bucket="1"} 89123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31976
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 771
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71231
telemt_me_reconnect_success_total 2395
telemt_me_reader_eof_total 2126
telemt_me_idle_close_by_peer_total 2125
telemt_me_route_drop_no_conn_total 4451410
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7285438
telemt_me_endpoint_quarantine_total 977
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1091
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_me_writers_active_current 49
telemt_desync_total 37291
telemt_desync_full_logged_total 12773
telemt_desync_suppressed_total 24518
telemt_desync_frames_bucket_total{bucket="1_2"} 7576
telemt_desync_frames_bucket_total{bucket="3_10"} 14386
telemt_desync_frames_bucket_total{bucket="gt_10"} 15329
telemt_pool_swap_total 150
telemt_pool_force_close_total 4403
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 532
telemt_me_draining_writers_reap_progress_total 49931
telemt_me_writer_removed_unexpected_total 2154
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5277
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46824
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3798
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 605
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45528
telemt_me_writer_teardown_success_total{mode="normal"} 52101
telemt_me_writer_teardown_noop_total 49932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102033
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.337953
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102033
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 532
telemt_me_refill_failed_total 4248
telemt_me_writer_restored_same_endpoint_total 2010
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 7287363
telemt_user_connections_current{user="hello"} 4429
telemt_user_octets_from_client{user="hello"} 169644221183 (157.99 GB)
telemt_user_octets_to_client{user="hello"} 2790165663309 (2.54 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1785
telemt_user_unique_ips_recent_window{user="hello"} 681
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 82808.3 (23h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8991335
telemt_connections_bad_total 318934
telemt_connections_current 5292
telemt_connections_me_current 5292
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3778862
telemt_upstream_connect_attempt_total 41433
telemt_upstream_connect_success_total 41137
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 41426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_reconnect_attempts_total 47893
telemt_me_reconnect_success_total 1424
telemt_me_reader_eof_total 1092
telemt_me_idle_close_by_peer_total 1092
telemt_me_route_drop_no_conn_total 3212684
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4347165
telemt_me_endpoint_quarantine_total 549
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 622
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
telemt_me_writers_active_current 42
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 23892
telemt_desync_full_logged_total 7999
telemt_desync_suppressed_total 15893
telemt_desync_frames_bucket_total{bucket="1_2"} 4849
telemt_desync_frames_bucket_total{bucket="3_10"} 9395
telemt_desync_frames_bucket_total{bucket="gt_10"} 9648
telemt_pool_swap_total 86
telemt_pool_force_close_total 2671
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 274
telemt_me_draining_writers_reap_progress_total 28893
telemt_me_writer_removed_unexpected_total 1157
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2617
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27461
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2273
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 398
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26222
telemt_me_writer_teardown_success_total{mode="normal"} 30078
telemt_me_writer_teardown_noop_total 28900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58978
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.262225
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58978
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 274
telemt_me_refill_failed_total 2701
telemt_me_writer_restored_same_endpoint_total 1272
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4342334
telemt_user_connections_current{user="hello"} 5292
telemt_user_octets_from_client{user="hello"} 96618954248 (89.98 GB)
telemt_user_octets_to_client{user="hello"} 1681094261802 (1.53 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 2064
telemt_user_unique_ips_recent_window{user="hello"} 716
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 63779.2 (17h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 732065
telemt_connections_bad_total 8518
telemt_connections_current 1001
telemt_connections_me_current 1001
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 13973
telemt_upstream_connect_attempt_total 32535
telemt_upstream_connect_success_total 32453
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 32522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17148
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 390
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 1452
telemt_me_reconnect_success_total 621
telemt_me_reader_eof_total 601
telemt_me_idle_close_by_peer_total 601
telemt_me_route_drop_no_conn_total 246361
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 660685
telemt_me_endpoint_quarantine_total 573
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 532
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
telemt_desync_total 3634
telemt_desync_full_logged_total 1071
telemt_desync_suppressed_total 2563
telemt_desync_frames_bucket_total{bucket="1_2"} 886
telemt_desync_frames_bucket_total{bucket="3_10"} 1439
telemt_desync_frames_bucket_total{bucket="gt_10"} 1309
telemt_pool_swap_total 67
telemt_pool_force_close_total 1654
telemt_me_writer_close_signal_drop_total 97
telemt_me_draining_writers_reap_progress_total 26671
telemt_me_writer_removed_unexpected_total 583
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2033
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25241
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1577
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25017
telemt_me_writer_teardown_success_total{mode="normal"} 27274
telemt_me_writer_teardown_noop_total 26673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53947
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.924926
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53947
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 97
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 538
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 662365
telemt_user_connections_current{user="hello"} 1001
telemt_user_octets_from_client{user="hello"} 12580785817 (11.72 GB)
telemt_user_octets_to_client{user="hello"} 316635872847 (294.89 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 367
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 145976.9 (40h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11249061
telemt_connections_bad_total 1304569
telemt_connections_current 5948
telemt_connections_me_current 5948
telemt_handshake_timeouts_total 302517
telemt_upstream_connect_attempt_total 55273
telemt_upstream_connect_success_total 55058
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 55225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27856
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_reconnect_attempts_total 2175
telemt_me_reconnect_success_total 1152
telemt_me_reader_eof_total 1117
telemt_me_idle_close_by_peer_total 1117
telemt_me_route_drop_no_conn_total 3547253
telemt_me_route_drop_channel_closed_total 94
telemt_me_route_drop_queue_full_total 32
telemt_me_route_drop_queue_full_profile_total{profile="high"} 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8454494
telemt_me_endpoint_quarantine_total 1006
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1097
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
telemt_desync_total 34547
telemt_desync_full_logged_total 11323
telemt_desync_suppressed_total 23224
telemt_desync_frames_bucket_total{bucket="1_2"} 8261
telemt_desync_frames_bucket_total{bucket="3_10"} 12785
telemt_desync_frames_bucket_total{bucket="gt_10"} 13501
telemt_pool_swap_total 162
telemt_pool_force_close_total 4415
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 552
telemt_me_draining_writers_reap_progress_total 49782
telemt_me_writer_removed_unexpected_total 1072
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4069
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46821
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4264
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 151
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45367
telemt_me_writer_teardown_success_total{mode="normal"} 50890
telemt_me_writer_teardown_noop_total 49784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100674
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.957072
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100674
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 552
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1008
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 8425364
telemt_user_connections_current{user="hello"} 5948
telemt_user_octets_from_client{user="hello"} 162556601568 (151.39 GB)
telemt_user_octets_to_client{user="hello"} 3803856066296 (3.46 TB)
telemt_user_unique_ips_current{user="hello"} 2235
telemt_user_unique_ips_recent_window{user="hello"} 715
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 145973.9 (40h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9743972
telemt_connections_bad_total 1092672
telemt_connections_current 4569
telemt_connections_me_current 4569
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 253412
telemt_upstream_connect_attempt_total 80597
telemt_upstream_connect_success_total 80009
telemt_upstream_connect_fail_total 510
telemt_upstream_connect_attempts_per_request{bucket="1"} 80519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32781
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2000
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 510
telemt_me_reconnect_attempts_total 8526
telemt_me_reconnect_success_total 1897
telemt_me_reader_eof_total 1768
telemt_me_idle_close_by_peer_total 1768
telemt_me_seq_mismatch_total 71
telemt_me_route_drop_no_conn_total 4308265
telemt_me_route_drop_channel_closed_total 304
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7498803
telemt_me_endpoint_quarantine_total 1115
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 36
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
telemt_me_writers_active_current 68
telemt_me_writers_warm_current 19
telemt_desync_total 33779
telemt_desync_full_logged_total 11035
telemt_desync_suppressed_total 22744
telemt_desync_frames_bucket_total{bucket="1_2"} 8365
telemt_desync_frames_bucket_total{bucket="3_10"} 12588
telemt_desync_frames_bucket_total{bucket="gt_10"} 12826
telemt_pool_swap_total 155
telemt_pool_force_close_total 4284
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 540
telemt_me_draining_writers_reap_progress_total 48874
telemt_me_writer_removed_unexpected_total 1793
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5055
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45678
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3921
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 363
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44590
telemt_me_writer_teardown_success_total{mode="normal"} 50733
telemt_me_writer_teardown_noop_total 48878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99611
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.882274
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99611
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 540
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 1540
telemt_me_writer_restored_fallback_total 95
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 7506169
telemt_user_connections_current{user="hello"} 4569
telemt_user_octets_from_client{user="hello"} 133030825201 (123.89 GB)
telemt_user_octets_to_client{user="hello"} 2975001309507 (2.71 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1846
telemt_user_unique_ips_recent_window{user="hello"} 655
```
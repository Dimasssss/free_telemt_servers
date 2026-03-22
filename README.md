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

# Server Metrics 2026-03-22 10:05:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 46735.1 (12h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1214291
telemt_connections_bad_total 64655
telemt_connections_current 1874
telemt_connections_me_current 1874
telemt_handshake_timeouts_total 55859
telemt_upstream_connect_attempt_total 18126
telemt_upstream_connect_success_total 18125
telemt_upstream_connect_attempts_per_request{bucket="1"} 18125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11778
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 43
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 547
telemt_me_reconnect_success_total 279
telemt_me_reader_eof_total 278
telemt_me_idle_close_by_peer_total 278
telemt_me_route_drop_no_conn_total 660094
telemt_me_route_drop_channel_closed_total 276
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1012307
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 326
telemt_me_single_endpoint_shadow_rotate_total 374
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
telemt_me_writers_active_current 44
telemt_desync_total 6924
telemt_desync_full_logged_total 2020
telemt_desync_suppressed_total 4904
telemt_desync_frames_bucket_total{bucket="1_2"} 2032
telemt_desync_frames_bucket_total{bucket="3_10"} 2619
telemt_desync_frames_bucket_total{bucket="gt_10"} 2273
telemt_pool_swap_total 51
telemt_pool_force_close_total 1485
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 180
telemt_me_draining_writers_reap_progress_total 16508
telemt_me_writer_removed_unexpected_total 275
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1137
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15565
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1454
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15023
telemt_me_writer_teardown_success_total{mode="normal"} 16702
telemt_me_writer_teardown_noop_total 16510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33212
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 74.133207
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33212
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 180
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 255
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1010525
telemt_user_connections_current{user="hello"} 1874
telemt_user_octets_from_client{user="hello"} 15875403864 (14.79 GB)
telemt_user_octets_to_client{user="hello"} 321795581436 (299.70 GB)
telemt_user_unique_ips_current{user="hello"} 657
telemt_user_unique_ips_recent_window{user="hello"} 406
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 60101.6 (16h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1857527
telemt_connections_bad_total 166141
telemt_connections_current 2447
telemt_connections_me_current 2447
telemt_handshake_timeouts_total 47922
telemt_upstream_connect_attempt_total 35768
telemt_upstream_connect_success_total 35297
telemt_upstream_connect_fail_total 415
telemt_upstream_connect_attempts_per_request{bucket="1"} 35712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 415
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3122
telemt_me_reconnect_success_total 1376
telemt_me_reader_eof_total 1273
telemt_me_idle_close_by_peer_total 1273
telemt_me_route_drop_no_conn_total 1091542
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1431799
telemt_me_endpoint_quarantine_total 511
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 474
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
telemt_me_writers_active_current 46
telemt_desync_total 6258
telemt_desync_full_logged_total 3572
telemt_desync_suppressed_total 2686
telemt_desync_frames_bucket_total{bucket="1_2"} 1407
telemt_desync_frames_bucket_total{bucket="3_10"} 2450
telemt_desync_frames_bucket_total{bucket="gt_10"} 2401
telemt_pool_swap_total 60
telemt_pool_force_close_total 1692
telemt_me_writer_close_signal_drop_total 137
telemt_me_draining_writers_reap_progress_total 24387
telemt_me_writer_removed_unexpected_total 1240
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2646
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22974
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1513
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 179
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22695
telemt_me_writer_teardown_success_total{mode="normal"} 25620
telemt_me_writer_teardown_noop_total 24387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50007
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.533623
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50007
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 137
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1150
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1437869
telemt_user_connections_current{user="hello"} 2447
telemt_user_octets_from_client{user="hello"} 20651850062 (19.23 GB)
telemt_user_octets_to_client{user="hello"} 442632459484 (412.23 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 1446
telemt_user_unique_ips_recent_window{user="hello"} 1017
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 134962.3 (37h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10772361
telemt_connections_bad_total 954336
telemt_connections_current 6593
telemt_connections_me_current 6593
telemt_handshake_timeouts_total 305806
telemt_upstream_connect_attempt_total 49438
telemt_upstream_connect_success_total 49358
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 49366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26831
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 201
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2083
telemt_me_reconnect_success_total 1068
telemt_me_reader_eof_total 1059
telemt_me_idle_close_by_peer_total 1058
telemt_me_route_drop_no_conn_total 6945486
telemt_me_route_drop_channel_closed_total 91
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8509290
telemt_me_endpoint_quarantine_total 857
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 1005
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
telemt_me_writers_active_current 43
telemt_desync_total 36389
telemt_desync_full_logged_total 11840
telemt_desync_suppressed_total 24549
telemt_desync_frames_bucket_total{bucket="1_2"} 8143
telemt_desync_frames_bucket_total{bucket="3_10"} 14133
telemt_desync_frames_bucket_total{bucket="gt_10"} 14113
telemt_pool_swap_total 145
telemt_pool_force_close_total 4851
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 749
telemt_me_draining_writers_reap_progress_total 45086
telemt_me_writer_removed_unexpected_total 1017
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3830
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41723
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4524
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 327
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40235
telemt_me_writer_teardown_success_total{mode="normal"} 45553
telemt_me_writer_teardown_noop_total 45130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90683
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 202.756042
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90683
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 749
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 937
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 8498858
telemt_user_connections_current{user="hello"} 6593
telemt_user_octets_from_client{user="hello"} 134490779076 (125.25 GB)
telemt_user_octets_to_client{user="hello"} 2673270884248 (2.43 TB)
telemt_user_unique_ips_current{user="hello"} 2457
telemt_user_unique_ips_recent_window{user="hello"} 1271
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 134962.2 (37h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8622347
telemt_connections_bad_total 776202
telemt_connections_current 7020
telemt_connections_me_current 7020
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 268178
telemt_upstream_connect_attempt_total 55611
telemt_upstream_connect_success_total 55099
telemt_upstream_connect_fail_total 252
telemt_upstream_connect_attempts_per_request{bucket="1"} 55351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26997
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 252
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 3022
telemt_me_reconnect_success_total 1182
telemt_me_reader_eof_total 1087
telemt_me_idle_close_by_peer_total 1087
telemt_me_route_drop_no_conn_total 3113554
telemt_me_route_drop_channel_closed_total 352
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6391859
telemt_me_endpoint_quarantine_total 856
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 1036
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
telemt_desync_total 29103
telemt_desync_full_logged_total 9865
telemt_desync_suppressed_total 19238
telemt_desync_frames_bucket_total{bucket="1_2"} 7031
telemt_desync_frames_bucket_total{bucket="3_10"} 11266
telemt_desync_frames_bucket_total{bucket="gt_10"} 10806
telemt_pool_swap_total 146
telemt_pool_force_close_total 4430
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 490
telemt_me_draining_writers_reap_progress_total 43423
telemt_me_writer_removed_unexpected_total 1103
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3755
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40666
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4128
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 302
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38993
telemt_me_writer_teardown_success_total{mode="normal"} 44421
telemt_me_writer_teardown_noop_total 43429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87850
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 63.372655
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87850
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 490
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 1002
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 6313827
telemt_user_connections_current{user="hello"} 7020
telemt_user_octets_from_client{user="hello"} 168528327627 (156.95 GB)
telemt_user_octets_to_client{user="hello"} 2961224133066 (2.69 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1858
telemt_user_unique_ips_recent_window{user="hello"} 981
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 134927.8 (37h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8223169
telemt_connections_bad_total 692825
telemt_connections_current 5586
telemt_connections_me_current 5586
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 267259
telemt_upstream_connect_attempt_total 60193
telemt_upstream_connect_success_total 59494
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 59641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28039
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 984
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3423
telemt_me_reconnect_success_total 1463
telemt_me_reader_eof_total 1351
telemt_me_idle_close_by_peer_total 1351
telemt_me_route_drop_no_conn_total 3439834
telemt_me_route_drop_channel_closed_total 222
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6145580
telemt_me_endpoint_quarantine_total 925
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 989
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
telemt_me_writers_active_current 46
telemt_desync_total 28564
telemt_desync_full_logged_total 9710
telemt_desync_suppressed_total 18854
telemt_desync_frames_bucket_total{bucket="1_2"} 6903
telemt_desync_frames_bucket_total{bucket="3_10"} 10974
telemt_desync_frames_bucket_total{bucket="gt_10"} 10687
telemt_pool_swap_total 142
telemt_pool_force_close_total 4324
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 510
telemt_me_draining_writers_reap_progress_total 44386
telemt_me_writer_removed_unexpected_total 1378
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4150
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41560
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3941
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 383
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40062
telemt_me_writer_teardown_success_total{mode="normal"} 45710
telemt_me_writer_teardown_noop_total 44403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90113
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.211525
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90113
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 510
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 1289
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 6137837
telemt_user_connections_current{user="hello"} 5586
telemt_user_octets_from_client{user="hello"} 154205193459 (143.61 GB)
telemt_user_octets_to_client{user="hello"} 2681738628087 (2.44 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 2093
telemt_user_unique_ips_recent_window{user="hello"} 880
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 5206.7 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2204488
telemt_connections_bad_total 171774
telemt_connections_current 7418
telemt_connections_me_current 7418
telemt_handshake_timeouts_total 27952
telemt_upstream_connect_attempt_total 8418
telemt_upstream_connect_success_total 7975
telemt_upstream_connect_fail_total 339
telemt_upstream_connect_attempts_per_request{bucket="1"} 8314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1486
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2680
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 339
telemt_me_keepalive_timeout_total 207
telemt_me_reconnect_attempts_total 360
telemt_me_reconnect_success_total 124
telemt_me_reader_eof_total 72
telemt_me_idle_close_by_peer_total 72
telemt_me_route_drop_no_conn_total 4873705
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1825840
telemt_me_endpoint_quarantine_total 26
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 44
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
telemt_me_writers_active_current 45
telemt_desync_total 2792
telemt_desync_full_logged_total 703
telemt_desync_suppressed_total 2089
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 1059
telemt_desync_frames_bucket_total{bucket="gt_10"} 1219
telemt_pool_swap_total 4
telemt_pool_force_close_total 156
telemt_me_writer_close_signal_drop_total 62
telemt_me_draining_writers_reap_progress_total 1300
telemt_me_writer_removed_unexpected_total 116
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 214
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1202
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 48
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1144
telemt_me_writer_teardown_success_total{mode="normal"} 1416
telemt_me_writer_teardown_noop_total 1300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2716
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.319042
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2716
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 62
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 76
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1831652
telemt_user_connections_current{user="hello"} 7418
telemt_user_octets_from_client{user="hello"} 10012027354 (9.32 GB)
telemt_user_octets_to_client{user="hello"} 53647788295 (49.96 GB)
telemt_user_msgs_from_client{user="hello"} 6014
telemt_user_msgs_to_client{user="hello"} 4995
telemt_user_unique_ips_current{user="hello"} 2496
telemt_user_unique_ips_recent_window{user="hello"} 1527
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 134933.3 (37h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7823223
telemt_connections_bad_total 692713
telemt_connections_current 5645
telemt_connections_me_current 5645
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 161161
telemt_upstream_connect_attempt_total 76479
telemt_upstream_connect_success_total 75646
telemt_upstream_connect_fail_total 713
telemt_upstream_connect_attempts_per_request{bucket="1"} 76359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45978
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29223
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 444
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 713
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70516
telemt_me_reconnect_success_total 2133
telemt_me_reader_eof_total 1878
telemt_me_idle_close_by_peer_total 1877
telemt_me_route_drop_no_conn_total 3235127
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6166951
telemt_me_endpoint_quarantine_total 896
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1014
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
telemt_me_writers_active_current 87
telemt_desync_total 31176
telemt_desync_full_logged_total 10801
telemt_desync_suppressed_total 20375
telemt_desync_frames_bucket_total{bucket="1_2"} 6299
telemt_desync_frames_bucket_total{bucket="3_10"} 11953
telemt_desync_frames_bucket_total{bucket="gt_10"} 12924
telemt_pool_swap_total 139
telemt_pool_force_close_total 4031
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 483
telemt_me_draining_writers_reap_progress_total 46667
telemt_me_writer_removed_unexpected_total 1907
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4783
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43818
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3544
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 487
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42636
telemt_me_writer_teardown_success_total{mode="normal"} 48601
telemt_me_writer_teardown_noop_total 46668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95269
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.705263
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95269
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 483
telemt_me_refill_failed_total 4230
telemt_me_writer_restored_same_endpoint_total 1779
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 6162757
telemt_user_connections_current{user="hello"} 5645
telemt_user_octets_from_client{user="hello"} 152758486555 (142.27 GB)
telemt_user_octets_to_client{user="hello"} 2502633126327 (2.28 TB)
telemt_user_msgs_from_client{user="hello"} 115484
telemt_user_msgs_to_client{user="hello"} 517108
telemt_user_unique_ips_current{user="hello"} 2187
telemt_user_unique_ips_recent_window{user="hello"} 849
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 71769.3 (19h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6641556
telemt_connections_bad_total 253647
telemt_connections_current 4335
telemt_connections_me_current 4335
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2690373
telemt_upstream_connect_attempt_total 37716
telemt_upstream_connect_success_total 37447
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 37709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_reconnect_attempts_total 47567
telemt_me_reconnect_success_total 1265
telemt_me_reader_eof_total 929
telemt_me_idle_close_by_peer_total 929
telemt_me_route_drop_no_conn_total 1829818
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3304328
telemt_me_endpoint_quarantine_total 493
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 547
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 17970
telemt_desync_full_logged_total 6051
telemt_desync_suppressed_total 11919
telemt_desync_frames_bucket_total{bucket="1_2"} 3600
telemt_desync_frames_bucket_total{bucket="3_10"} 6881
telemt_desync_frames_bucket_total{bucket="gt_10"} 7489
telemt_pool_swap_total 76
telemt_pool_force_close_total 2310
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 222
telemt_me_draining_writers_reap_progress_total 25640
telemt_me_writer_removed_unexpected_total 999
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2238
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24424
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1988
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23330
telemt_me_writer_teardown_success_total{mode="normal"} 26662
telemt_me_writer_teardown_noop_total 25646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52308
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.907648
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52308
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 222
telemt_me_refill_failed_total 2692
telemt_me_writer_restored_same_endpoint_total 1125
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3304215
telemt_user_connections_current{user="hello"} 4335
telemt_user_octets_from_client{user="hello"} 81280983828 (75.70 GB)
telemt_user_octets_to_client{user="hello"} 1392711053334 (1.27 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1592
telemt_user_unique_ips_recent_window{user="hello"} 832
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 52740.2 (14h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 517915
telemt_connections_bad_total 3744
telemt_connections_current 1210
telemt_connections_me_current 1210
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 9592
telemt_upstream_connect_attempt_total 27757
telemt_upstream_connect_success_total 27694
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 27752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 285
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1134
telemt_me_reconnect_success_total 459
telemt_me_reader_eof_total 457
telemt_me_idle_close_by_peer_total 457
telemt_me_route_drop_no_conn_total 168338
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 468230
telemt_me_endpoint_quarantine_total 484
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 452
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
telemt_desync_total 2217
telemt_desync_full_logged_total 651
telemt_desync_suppressed_total 1566
telemt_desync_frames_bucket_total{bucket="1_2"} 658
telemt_desync_frames_bucket_total{bucket="3_10"} 850
telemt_desync_frames_bucket_total{bucket="gt_10"} 709
telemt_pool_swap_total 56
telemt_pool_force_close_total 1327
telemt_me_writer_close_signal_drop_total 65
telemt_me_draining_writers_reap_progress_total 22470
telemt_me_writer_removed_unexpected_total 440
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1650
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21277
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1276
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21143
telemt_me_writer_teardown_success_total{mode="normal"} 22927
telemt_me_writer_teardown_noop_total 22470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45397
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.205987
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45397
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 65
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 406
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 470281
telemt_user_connections_current{user="hello"} 1210
telemt_user_octets_from_client{user="hello"} 9371258201 (8.73 GB)
telemt_user_octets_to_client{user="hello"} 229255249067 (213.51 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 388
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 134937.8 (37h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9615796
telemt_connections_bad_total 1121774
telemt_connections_current 6022
telemt_connections_me_current 6022
telemt_handshake_timeouts_total 260046
telemt_upstream_connect_attempt_total 51967
telemt_upstream_connect_success_total 51769
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 51921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26140
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 1933
telemt_me_reconnect_success_total 1060
telemt_me_reader_eof_total 1032
telemt_me_idle_close_by_peer_total 1032
telemt_me_route_drop_no_conn_total 2732684
telemt_me_route_drop_channel_closed_total 70
telemt_me_route_drop_queue_full_total 28
telemt_me_route_drop_queue_full_profile_total{profile="high"} 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7147235
telemt_me_endpoint_quarantine_total 950
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1020
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
telemt_desync_total 28975
telemt_desync_full_logged_total 9505
telemt_desync_suppressed_total 19470
telemt_desync_frames_bucket_total{bucket="1_2"} 7163
telemt_desync_frames_bucket_total{bucket="3_10"} 10572
telemt_desync_frames_bucket_total{bucket="gt_10"} 11240
telemt_pool_swap_total 149
telemt_pool_force_close_total 4021
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 487
telemt_me_draining_writers_reap_progress_total 46867
telemt_me_writer_removed_unexpected_total 992
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3764
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44126
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3913
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42846
telemt_me_writer_teardown_success_total{mode="normal"} 47890
telemt_me_writer_teardown_noop_total 46869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94759
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.960145
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94759
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 487
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 931
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 7119709
telemt_user_connections_current{user="hello"} 6022
telemt_user_octets_from_client{user="hello"} 137823180956 (128.36 GB)
telemt_user_octets_to_client{user="hello"} 3325813139084 (3.02 TB)
telemt_user_unique_ips_current{user="hello"} 2153
telemt_user_unique_ips_recent_window{user="hello"} 884
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 134934.1 (37h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8345527
telemt_connections_bad_total 929355
telemt_connections_current 5125
telemt_connections_me_current 5125
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 217511
telemt_upstream_connect_attempt_total 76445
telemt_upstream_connect_success_total 75904
telemt_upstream_connect_fail_total 472
telemt_upstream_connect_attempts_per_request{bucket="1"} 76376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30629
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1967
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 472
telemt_me_reconnect_attempts_total 6562
telemt_me_reconnect_success_total 1524
telemt_me_reader_eof_total 1355
telemt_me_idle_close_by_peer_total 1355
telemt_me_seq_mismatch_total 64
telemt_me_route_drop_no_conn_total 2946598
telemt_me_route_drop_channel_closed_total 260
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6373332
telemt_me_endpoint_quarantine_total 1051
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1020
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
telemt_desync_total 28042
telemt_desync_full_logged_total 9279
telemt_desync_suppressed_total 18763
telemt_desync_frames_bucket_total{bucket="1_2"} 6898
telemt_desync_frames_bucket_total{bucket="3_10"} 10310
telemt_desync_frames_bucket_total{bucket="gt_10"} 10834
telemt_pool_swap_total 146
telemt_pool_force_close_total 3953
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 489
telemt_me_draining_writers_reap_progress_total 45545
telemt_me_writer_removed_unexpected_total 1373
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4415
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42565
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3662
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 291
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41592
telemt_me_writer_teardown_success_total{mode="normal"} 46980
telemt_me_writer_teardown_noop_total 45549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92529
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.499752
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92529
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 489
telemt_me_refill_failed_total 290
telemt_me_writer_restored_same_endpoint_total 1188
telemt_me_writer_restored_fallback_total 88
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 6381648
telemt_user_connections_current{user="hello"} 5125
telemt_user_octets_from_client{user="hello"} 116419681041 (108.42 GB)
telemt_user_octets_to_client{user="hello"} 2709370563843 (2.46 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1991
telemt_user_unique_ips_recent_window{user="hello"} 732
```
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

# Server Metrics 2026-03-22 12:38:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 55942.0 (15h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1681566
telemt_connections_bad_total 78482
telemt_connections_current 1770
telemt_connections_me_current 1770
telemt_handshake_timeouts_total 74402
telemt_upstream_connect_attempt_total 21234
telemt_upstream_connect_success_total 21233
telemt_upstream_connect_attempts_per_request{bucket="1"} 21233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13835
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 885
telemt_me_reconnect_success_total 344
telemt_me_reader_eof_total 349
telemt_me_idle_close_by_peer_total 349
telemt_me_route_drop_no_conn_total 1114307
telemt_me_route_drop_channel_closed_total 506
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1422575
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 397
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 444
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
telemt_me_writers_active_current 39
telemt_desync_total 8389
telemt_desync_full_logged_total 2539
telemt_desync_suppressed_total 5850
telemt_desync_frames_bucket_total{bucket="1_2"} 2357
telemt_desync_frames_bucket_total{bucket="3_10"} 3165
telemt_desync_frames_bucket_total{bucket="gt_10"} 2867
telemt_pool_swap_total 62
telemt_pool_force_close_total 1825
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 281
telemt_me_draining_writers_reap_progress_total 19344
telemt_me_writer_removed_unexpected_total 341
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1374
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18186
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1790
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17519
telemt_me_writer_teardown_success_total{mode="normal"} 19560
telemt_me_writer_teardown_noop_total 19346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38906
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 136.810517
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38906
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 281
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 305
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 1419839
telemt_user_connections_current{user="hello"} 1770
telemt_user_octets_from_client{user="hello"} 22742184552 (21.18 GB)
telemt_user_octets_to_client{user="hello"} 421297872296 (392.36 GB)
telemt_user_unique_ips_current{user="hello"} 677
telemt_user_unique_ips_recent_window{user="hello"} 293
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 69308.0 (19h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2711915
telemt_connections_bad_total 250559
telemt_connections_current 1955
telemt_connections_me_current 1955
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 63504
telemt_upstream_connect_attempt_total 45534
telemt_upstream_connect_success_total 45006
telemt_upstream_connect_fail_total 467
telemt_upstream_connect_attempts_per_request{bucket="1"} 45473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17596
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 467
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3463
telemt_me_reconnect_success_total 1567
telemt_me_reader_eof_total 1453
telemt_me_idle_close_by_peer_total 1453
telemt_me_route_drop_no_conn_total 2378305
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2125600
telemt_me_endpoint_quarantine_total 582
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 541
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
telemt_me_writers_active_current 45
telemt_desync_total 8452
telemt_desync_full_logged_total 4754
telemt_desync_suppressed_total 3698
telemt_desync_frames_bucket_total{bucket="1_2"} 1983
telemt_desync_frames_bucket_total{bucket="3_10"} 3288
telemt_desync_frames_bucket_total{bucket="gt_10"} 3181
telemt_pool_swap_total 68
telemt_pool_force_close_total 1946
telemt_me_writer_close_signal_drop_total 161
telemt_me_draining_writers_reap_progress_total 27615
telemt_me_writer_removed_unexpected_total 1413
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3021
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26007
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1708
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 238
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25669
telemt_me_writer_teardown_success_total{mode="normal"} 29028
telemt_me_writer_teardown_noop_total 27615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56643
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.430904
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56643
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 161
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 1310
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 2137335
telemt_user_connections_current{user="hello"} 1955
telemt_user_octets_from_client{user="hello"} 26410460511 (24.60 GB)
telemt_user_octets_to_client{user="hello"} 520142352034 (484.42 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1225
telemt_user_unique_ips_recent_window{user="hello"} 504
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 144168.9 (40h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12992493
telemt_connections_bad_total 1149538
telemt_connections_current 4848
telemt_connections_me_current 4848
telemt_handshake_timeouts_total 336400
telemt_upstream_connect_attempt_total 52517
telemt_upstream_connect_success_total 52437
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 52445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28485
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2378
telemt_me_reconnect_success_total 1228
telemt_me_reader_eof_total 1191
telemt_me_idle_close_by_peer_total 1190
telemt_me_route_drop_no_conn_total 10690835
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10378792
telemt_me_endpoint_quarantine_total 914
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1072
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
telemt_me_writers_active_current 45
telemt_desync_total 42754
telemt_desync_full_logged_total 13646
telemt_desync_suppressed_total 29108
telemt_desync_frames_bucket_total{bucket="1_2"} 9667
telemt_desync_frames_bucket_total{bucket="3_10"} 16683
telemt_desync_frames_bucket_total{bucket="gt_10"} 16404
telemt_pool_swap_total 155
telemt_pool_force_close_total 5267
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 836
telemt_me_draining_writers_reap_progress_total 47861
telemt_me_writer_removed_unexpected_total 1149
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4161
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44206
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4848
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42594
telemt_me_writer_teardown_success_total{mode="normal"} 48367
telemt_me_writer_teardown_noop_total 47909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96276
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 229.416094
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96276
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 836
telemt_me_refill_failed_total 63
telemt_me_writer_restored_same_endpoint_total 1064
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 10367213
telemt_user_connections_current{user="hello"} 4848
telemt_user_octets_from_client{user="hello"} 153263486692 (142.74 GB)
telemt_user_octets_to_client{user="hello"} 2874907927464 (2.61 TB)
telemt_user_unique_ips_current{user="hello"} 1983
telemt_user_unique_ips_recent_window{user="hello"} 678
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 144170.3 (40h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9802814
telemt_connections_bad_total 900294
telemt_connections_current 5178
telemt_connections_me_current 5178
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 295808
telemt_upstream_connect_attempt_total 78818
telemt_upstream_connect_success_total 77689
telemt_upstream_connect_fail_total 815
telemt_upstream_connect_attempts_per_request{bucket="1"} 78504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3671
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 815
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3358
telemt_me_reconnect_success_total 1382
telemt_me_reader_eof_total 1268
telemt_me_idle_close_by_peer_total 1268
telemt_me_route_drop_no_conn_total 3928866
telemt_me_route_drop_channel_closed_total 404
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7310424
telemt_me_endpoint_quarantine_total 904
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 27
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
telemt_me_writers_active_current 64
telemt_me_writers_warm_current 24
telemt_desync_total 33025
telemt_desync_full_logged_total 11164
telemt_desync_suppressed_total 21861
telemt_desync_frames_bucket_total{bucket="1_2"} 8129
telemt_desync_frames_bucket_total{bucket="3_10"} 12714
telemt_desync_frames_bucket_total{bucket="gt_10"} 12182
telemt_pool_swap_total 154
telemt_pool_force_close_total 4706
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 571
telemt_me_draining_writers_reap_progress_total 46057
telemt_me_writer_removed_unexpected_total 1299
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4124
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43100
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4327
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 379
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41351
telemt_me_writer_teardown_success_total{mode="normal"} 47224
telemt_me_writer_teardown_noop_total 46068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93292
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 83.069120
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93292
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 571
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 1183
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 7250744
telemt_user_connections_current{user="hello"} 5178
telemt_user_octets_from_client{user="hello"} 187372367701 (174.50 GB)
telemt_user_octets_to_client{user="hello"} 3292243426198 (2.99 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 2123
telemt_user_unique_ips_recent_window{user="hello"} 886
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 144133.4 (40h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9236191
telemt_connections_bad_total 779007
telemt_connections_current 3292
telemt_connections_me_current 3292
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 293970
telemt_upstream_connect_attempt_total 64159
telemt_upstream_connect_success_total 63404
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 63566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29740
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1964
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 306
telemt_me_reconnect_attempts_total 3885
telemt_me_reconnect_success_total 1685
telemt_me_reader_eof_total 1507
telemt_me_idle_close_by_peer_total 1506
telemt_me_route_drop_no_conn_total 4005743
telemt_me_route_drop_channel_closed_total 286
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6955587
telemt_me_endpoint_quarantine_total 992
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1057
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
telemt_me_writers_active_current 43
telemt_desync_total 32807
telemt_desync_full_logged_total 10907
telemt_desync_suppressed_total 21900
telemt_desync_frames_bucket_total{bucket="1_2"} 8310
telemt_desync_frames_bucket_total{bucket="3_10"} 12571
telemt_desync_frames_bucket_total{bucket="gt_10"} 11926
telemt_pool_swap_total 151
telemt_pool_force_close_total 4674
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 607
telemt_me_draining_writers_reap_progress_total 46870
telemt_me_writer_removed_unexpected_total 1587
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4552
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43827
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4184
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 490
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42196
telemt_me_writer_teardown_success_total{mode="normal"} 48379
telemt_me_writer_teardown_noop_total 46936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95315
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3092.415945
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95315
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 607
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1466
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 6947326
telemt_user_connections_current{user="hello"} 3292
telemt_user_octets_from_client{user="hello"} 167826040741 (156.30 GB)
telemt_user_octets_to_client{user="hello"} 2968175656493 (2.70 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1275
telemt_user_unique_ips_recent_window{user="hello"} 1139
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 14413.9 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6119406
telemt_connections_bad_total 386627
telemt_connections_current 6890
telemt_connections_me_current 6890
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 96319
telemt_upstream_connect_attempt_total 24260
telemt_upstream_connect_success_total 23168
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 24006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4989
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4633
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_timeout_total 523
telemt_me_reconnect_attempts_total 2299
telemt_me_reconnect_success_total 361
telemt_me_reader_eof_total 232
telemt_me_idle_close_by_peer_total 232
telemt_me_route_drop_no_conn_total 14487279
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 24
telemt_me_route_drop_queue_full_profile_total{profile="high"} 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5103849
telemt_me_endpoint_quarantine_total 92
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 117
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
telemt_desync_total 7776
telemt_desync_full_logged_total 1969
telemt_desync_suppressed_total 5807
telemt_desync_frames_bucket_total{bucket="1_2"} 1412
telemt_desync_frames_bucket_total{bucket="3_10"} 3094
telemt_desync_frames_bucket_total{bucket="gt_10"} 3270
telemt_pool_swap_total 13
telemt_pool_force_close_total 540
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 212
telemt_me_draining_writers_reap_progress_total 3718
telemt_me_writer_removed_unexpected_total 320
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 623
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3372
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 395
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 145
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3178
telemt_me_writer_teardown_success_total{mode="normal"} 3995
telemt_me_writer_teardown_noop_total 3721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 7655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 7715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 7716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 7716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 7716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 7716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 7716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 7716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 7716
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.203738
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 7716
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 212
telemt_me_refill_failed_total 107
telemt_me_writer_restored_same_endpoint_total 246
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 5117226
telemt_user_connections_current{user="hello"} 6890
telemt_user_octets_from_client{user="hello"} 27898102454 (25.98 GB)
telemt_user_octets_to_client{user="hello"} 149154116851 (138.91 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2447
telemt_user_unique_ips_recent_window{user="hello"} 1387
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 144140.5 (40h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9009855
telemt_connections_bad_total 759452
telemt_connections_current 4973
telemt_connections_me_current 4973
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 192332
telemt_upstream_connect_attempt_total 88690
telemt_upstream_connect_success_total 87816
telemt_upstream_connect_fail_total 752
telemt_upstream_connect_attempts_per_request{bucket="1"} 88568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31707
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1249
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 752
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71133
telemt_me_reconnect_success_total 2368
telemt_me_reader_eof_total 2109
telemt_me_idle_close_by_peer_total 2108
telemt_me_route_drop_no_conn_total 4324315
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7115946
telemt_me_endpoint_quarantine_total 965
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1077
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
telemt_desync_total 36321
telemt_desync_full_logged_total 12486
telemt_desync_suppressed_total 23835
telemt_desync_frames_bucket_total{bucket="1_2"} 7409
telemt_desync_frames_bucket_total{bucket="3_10"} 13962
telemt_desync_frames_bucket_total{bucket="gt_10"} 14950
telemt_pool_swap_total 148
telemt_pool_force_close_total 4327
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 524
telemt_me_draining_writers_reap_progress_total 49466
telemt_me_writer_removed_unexpected_total 2137
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5208
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46421
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3733
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 594
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45139
telemt_me_writer_teardown_success_total{mode="normal"} 51629
telemt_me_writer_teardown_noop_total 49467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101096
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.047927
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101096
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 524
telemt_me_refill_failed_total 4245
telemt_me_writer_restored_same_endpoint_total 1987
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 7118173
telemt_user_connections_current{user="hello"} 4973
telemt_user_octets_from_client{user="hello"} 167188702483 (155.71 GB)
telemt_user_octets_to_client{user="hello"} 2741128517989 (2.49 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2020
telemt_user_unique_ips_recent_window{user="hello"} 745
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 80976.4 (22h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8590549
telemt_connections_bad_total 303669
telemt_connections_current 4403
telemt_connections_me_current 4403
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3605630
telemt_upstream_connect_attempt_total 40893
telemt_upstream_connect_success_total 40603
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 40886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_reconnect_attempts_total 47853
telemt_me_reconnect_success_total 1407
telemt_me_reader_eof_total 1076
telemt_me_idle_close_by_peer_total 1076
telemt_me_route_drop_no_conn_total 2977784
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4173488
telemt_me_endpoint_quarantine_total 539
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 610
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 22942
telemt_desync_full_logged_total 7669
telemt_desync_suppressed_total 15273
telemt_desync_frames_bucket_total{bucket="1_2"} 4700
telemt_desync_frames_bucket_total{bucket="3_10"} 8954
telemt_desync_frames_bucket_total{bucket="gt_10"} 9288
telemt_pool_swap_total 84
telemt_pool_force_close_total 2608
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 266
telemt_me_draining_writers_reap_progress_total 28400
telemt_me_writer_removed_unexpected_total 1141
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2561
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27008
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2213
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 395
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25792
telemt_me_writer_teardown_success_total{mode="normal"} 29569
telemt_me_writer_teardown_noop_total 28407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57976
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.830494
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57976
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 266
telemt_me_refill_failed_total 2700
telemt_me_writer_restored_same_endpoint_total 1258
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4169492
telemt_user_connections_current{user="hello"} 4403
telemt_user_octets_from_client{user="hello"} 93522933940 (87.10 GB)
telemt_user_octets_to_client{user="hello"} 1633461044926 (1.49 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1776
telemt_user_unique_ips_recent_window{user="hello"} 630
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 61947.1 (17h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 697512
telemt_connections_bad_total 8057
telemt_connections_current 1028
telemt_connections_me_current 1028
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 13552
telemt_upstream_connect_attempt_total 31756
telemt_upstream_connect_success_total 31678
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 31745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_reconnect_attempts_total 1396
telemt_me_reconnect_success_total 604
telemt_me_reader_eof_total 584
telemt_me_idle_close_by_peer_total 584
telemt_me_route_drop_no_conn_total 233334
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 629857
telemt_me_endpoint_quarantine_total 564
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 518
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
telemt_me_writers_active_current 44
telemt_desync_total 3417
telemt_desync_full_logged_total 1007
telemt_desync_suppressed_total 2410
telemt_desync_frames_bucket_total{bucket="1_2"} 847
telemt_desync_frames_bucket_total{bucket="3_10"} 1355
telemt_desync_frames_bucket_total{bucket="gt_10"} 1215
telemt_pool_swap_total 65
telemt_pool_force_close_total 1598
telemt_me_writer_close_signal_drop_total 92
telemt_me_draining_writers_reap_progress_total 25996
telemt_me_writer_removed_unexpected_total 566
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1972
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24609
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1521
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24398
telemt_me_writer_teardown_success_total{mode="normal"} 26581
telemt_me_writer_teardown_noop_total 25998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52579
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.852529
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52579
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 92
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 525
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 631603
telemt_user_connections_current{user="hello"} 1028
telemt_user_octets_from_client{user="hello"} 12152656549 (11.32 GB)
telemt_user_octets_to_client{user="hello"} 305216955583 (284.26 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 355
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 144145.3 (40h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10983379
telemt_connections_bad_total 1268297
telemt_connections_current 6806
telemt_connections_me_current 6806
telemt_handshake_timeouts_total 294772
telemt_upstream_connect_attempt_total 54774
telemt_upstream_connect_success_total 54561
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 54726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27598
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_reconnect_attempts_total 2151
telemt_me_reconnect_success_total 1144
telemt_me_reader_eof_total 1107
telemt_me_idle_close_by_peer_total 1107
telemt_me_route_drop_no_conn_total 3441853
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 32
telemt_me_route_drop_queue_full_profile_total{profile="high"} 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8249764
telemt_me_endpoint_quarantine_total 999
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1083
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
telemt_desync_total 33520
telemt_desync_full_logged_total 10995
telemt_desync_suppressed_total 22525
telemt_desync_frames_bucket_total{bucket="1_2"} 8054
telemt_desync_frames_bucket_total{bucket="3_10"} 12395
telemt_desync_frames_bucket_total{bucket="gt_10"} 13071
telemt_pool_swap_total 160
telemt_pool_force_close_total 4351
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 543
telemt_me_draining_writers_reap_progress_total 49330
telemt_me_writer_removed_unexpected_total 1063
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4025
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46403
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4205
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 146
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44979
telemt_me_writer_teardown_success_total{mode="normal"} 50428
telemt_me_writer_teardown_noop_total 49332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99760
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.483457
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99760
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 543
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 1000
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 8220855
telemt_user_connections_current{user="hello"} 6806
telemt_user_octets_from_client{user="hello"} 157255590500 (146.46 GB)
telemt_user_octets_to_client{user="hello"} 3722965743236 (3.39 TB)
telemt_user_unique_ips_current{user="hello"} 2446
telemt_user_unique_ips_recent_window{user="hello"} 1574
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 144141.9 (40h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9543431
telemt_connections_bad_total 1072846
telemt_connections_current 3260
telemt_connections_me_current 3260
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 247687
telemt_upstream_connect_attempt_total 80030
telemt_upstream_connect_success_total 79446
telemt_upstream_connect_fail_total 506
telemt_upstream_connect_attempts_per_request{bucket="1"} 79952
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32491
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1996
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 506
telemt_me_reconnect_attempts_total 8491
telemt_me_reconnect_success_total 1860
telemt_me_reader_eof_total 1733
telemt_me_idle_close_by_peer_total 1733
telemt_me_seq_mismatch_total 70
telemt_me_route_drop_no_conn_total 4129255
telemt_me_route_drop_channel_closed_total 300
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7335814
telemt_me_endpoint_quarantine_total 1106
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1086
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
telemt_me_writers_active_current 40
telemt_desync_total 32950
telemt_desync_full_logged_total 10775
telemt_desync_suppressed_total 22175
telemt_desync_frames_bucket_total{bucket="1_2"} 8170
telemt_desync_frames_bucket_total{bucket="3_10"} 12271
telemt_desync_frames_bucket_total{bucket="gt_10"} 12509
telemt_pool_swap_total 154
telemt_pool_force_close_total 4229
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 536
telemt_me_draining_writers_reap_progress_total 48411
telemt_me_writer_removed_unexpected_total 1758
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4987
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45247
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3866
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 363
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44182
telemt_me_writer_teardown_success_total{mode="normal"} 50234
telemt_me_writer_teardown_noop_total 48415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98649
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.310058
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98649
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 536
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 1506
telemt_me_writer_restored_fallback_total 94
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 7343444
telemt_user_connections_current{user="hello"} 3260
telemt_user_octets_from_client{user="hello"} 129493011101 (120.60 GB)
telemt_user_octets_to_client{user="hello"} 2929353867291 (2.66 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1467
telemt_user_unique_ips_recent_window{user="hello"} 1009
```
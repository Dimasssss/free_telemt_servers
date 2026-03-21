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

# Server Metrics 2026-03-21 22:41:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 5716.6 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101858
telemt_connections_bad_total 7206
telemt_connections_current 716
telemt_connections_me_current 716
telemt_handshake_timeouts_total 4775
telemt_upstream_connect_attempt_total 2257
telemt_upstream_connect_success_total 2256
telemt_upstream_connect_attempts_per_request{bucket="1"} 2256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1430
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 45
telemt_me_reconnect_success_total 26
telemt_me_reader_eof_total 27
telemt_me_idle_close_by_peer_total 27
telemt_me_route_drop_no_conn_total 21107
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83102
telemt_me_endpoint_quarantine_total 35
telemt_me_single_endpoint_shadow_rotate_total 52
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 560
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 384
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 6
telemt_pool_force_close_total 161
telemt_me_writer_close_signal_drop_total 13
telemt_me_draining_writers_reap_progress_total 1989
telemt_me_writer_removed_unexpected_total 25
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 146
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1870
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 157
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1828
telemt_me_writer_teardown_success_total{mode="normal"} 2016
telemt_me_writer_teardown_noop_total 1989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4005
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.458105
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4005
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 13
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 83022
telemt_user_connections_current{user="hello"} 716
telemt_user_octets_from_client{user="hello"} 1115205268 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 31254518228 (29.11 GB)
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 19083.0 (5h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 614297
telemt_connections_bad_total 28169
telemt_connections_current 1041
telemt_connections_me_current 1041
telemt_handshake_timeouts_total 22516
telemt_upstream_connect_attempt_total 7830
telemt_upstream_connect_success_total 7684
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 7815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4216
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_reconnect_attempts_total 646
telemt_me_reconnect_success_total 244
telemt_me_reader_eof_total 203
telemt_me_idle_close_by_peer_total 203
telemt_me_route_drop_no_conn_total 315387
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 500711
telemt_me_endpoint_quarantine_total 161
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 155
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_me_writers_active_current 48
telemt_desync_total 2232
telemt_desync_full_logged_total 1270
telemt_desync_suppressed_total 962
telemt_desync_frames_bucket_total{bucket="1_2"} 468
telemt_desync_frames_bucket_total{bucket="3_10"} 844
telemt_desync_frames_bucket_total{bucket="gt_10"} 920
telemt_pool_swap_total 21
telemt_pool_force_close_total 579
telemt_me_writer_close_signal_drop_total 44
telemt_me_draining_writers_reap_progress_total 6849
telemt_me_writer_removed_unexpected_total 192
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 603
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6436
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 572
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6270
telemt_me_writer_teardown_success_total{mode="normal"} 7039
telemt_me_writer_teardown_noop_total 6849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13888
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.116370
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13888
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 44
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 169
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 500059
telemt_user_connections_current{user="hello"} 1041
telemt_user_octets_from_client{user="hello"} 8563135096 (7.98 GB)
telemt_user_octets_to_client{user="hello"} 171609174576 (159.82 GB)
telemt_user_unique_ips_current{user="hello"} 670
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 93942.8 (26h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7276733
telemt_connections_bad_total 555411
telemt_connections_current 1649
telemt_connections_me_current 1649
telemt_handshake_timeouts_total 230117
telemt_upstream_connect_attempt_total 33857
telemt_upstream_connect_success_total 33789
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 33796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18372
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1465
telemt_me_reconnect_success_total 719
telemt_me_reader_eof_total 728
telemt_me_idle_close_by_peer_total 728
telemt_me_route_drop_no_conn_total 4471109
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5957477
telemt_me_endpoint_quarantine_total 595
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 694
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
telemt_me_writers_active_current 45
telemt_desync_total 25225
telemt_desync_full_logged_total 8308
telemt_desync_suppressed_total 16917
telemt_desync_frames_bucket_total{bucket="1_2"} 5413
telemt_desync_frames_bucket_total{bucket="3_10"} 9865
telemt_desync_frames_bucket_total{bucket="gt_10"} 9947
telemt_pool_swap_total 101
telemt_pool_force_close_total 3419
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 558
telemt_me_draining_writers_reap_progress_total 30822
telemt_me_writer_removed_unexpected_total 700
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2638
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28461
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3180
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27403
telemt_me_writer_teardown_success_total{mode="normal"} 31099
telemt_me_writer_teardown_noop_total 30866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61965
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 151.314326
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61965
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 558
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 642
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 5950190
telemt_user_connections_current{user="hello"} 1649
telemt_user_octets_from_client{user="hello"} 102151353376 (95.14 GB)
telemt_user_octets_to_client{user="hello"} 1931505598692 (1.76 TB)
telemt_user_unique_ips_current{user="hello"} 778
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 93944.2 (26h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5978683
telemt_connections_bad_total 574489
telemt_connections_current 1754
telemt_connections_me_current 1754
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 195707
telemt_upstream_connect_attempt_total 37835
telemt_upstream_connect_success_total 37500
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 37675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18044
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1743
telemt_me_reconnect_success_total 745
telemt_me_reader_eof_total 721
telemt_me_idle_close_by_peer_total 721
telemt_me_route_drop_no_conn_total 2103490
telemt_me_route_drop_channel_closed_total 242
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4470268
telemt_me_endpoint_quarantine_total 573
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 717
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
telemt_me_writers_active_current 44
telemt_desync_total 21515
telemt_desync_full_logged_total 7211
telemt_desync_suppressed_total 14304
telemt_desync_frames_bucket_total{bucket="1_2"} 5205
telemt_desync_frames_bucket_total{bucket="3_10"} 8322
telemt_desync_frames_bucket_total{bucket="gt_10"} 7988
telemt_pool_swap_total 103
telemt_pool_force_close_total 3115
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 341
telemt_me_draining_writers_reap_progress_total 29438
telemt_me_writer_removed_unexpected_total 697
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2534
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27534
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2916
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26323
telemt_me_writer_teardown_success_total{mode="normal"} 30068
telemt_me_writer_teardown_noop_total 29444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59512
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.807200
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59512
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 341
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 643
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 4431817
telemt_user_connections_current{user="hello"} 1754
telemt_user_octets_from_client{user="hello"} 136734812201 (127.34 GB)
telemt_user_octets_to_client{user="hello"} 2064960899607 (1.88 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 841
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 93908.2 (26h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5898611
telemt_connections_bad_total 533559
telemt_connections_current 1732
telemt_connections_me_current 1732
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 186477
telemt_upstream_connect_attempt_total 44187
telemt_upstream_connect_success_total 43890
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 44025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19471
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1045
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1784
telemt_me_reconnect_success_total 801
telemt_me_reader_eof_total 748
telemt_me_idle_close_by_peer_total 748
telemt_me_route_drop_no_conn_total 2077268
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4413278
telemt_me_endpoint_quarantine_total 631
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 700
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
telemt_desync_total 21372
telemt_desync_full_logged_total 7026
telemt_desync_suppressed_total 14346
telemt_desync_frames_bucket_total{bucket="1_2"} 5268
telemt_desync_frames_bucket_total{bucket="3_10"} 8126
telemt_desync_frames_bucket_total{bucket="gt_10"} 7978
telemt_pool_swap_total 101
telemt_pool_force_close_total 2994
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 361
telemt_me_draining_writers_reap_progress_total 30825
telemt_me_writer_removed_unexpected_total 716
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2612
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28935
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2779
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27831
telemt_me_writer_teardown_success_total{mode="normal"} 31547
telemt_me_writer_teardown_noop_total 30836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62383
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.107984
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62383
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 361
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 692
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4414844
telemt_user_connections_current{user="hello"} 1732
telemt_user_octets_from_client{user="hello"} 129830149611 (120.91 GB)
telemt_user_octets_to_client{user="hello"} 2018041479875 (1.84 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 807
telemt_user_unique_ips_recent_window{user="hello"} 196
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 93947.7 (26h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19716915
telemt_connections_bad_total 1394930
telemt_connections_current 2514
telemt_connections_me_current 2514
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 562256
telemt_upstream_connect_attempt_total 183877
telemt_upstream_connect_success_total 166546
telemt_upstream_connect_fail_total 15826
telemt_upstream_connect_attempts_per_request{bucket="1"} 182372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38276
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8858
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15826
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 60262
telemt_me_reconnect_success_total 1992
telemt_me_reader_eof_total 1293
telemt_me_idle_close_by_peer_total 1292
telemt_me_route_drop_no_conn_total 39411850
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16114432
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 693
telemt_me_single_endpoint_outage_enter_total 112
telemt_me_single_endpoint_outage_exit_total 112
telemt_me_single_endpoint_outage_reconnect_attempt_total 240
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 240
telemt_me_single_endpoint_shadow_rotate_total 727
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
telemt_me_writers_active_current 42
telemt_desync_total 30934
telemt_desync_full_logged_total 9165
telemt_desync_suppressed_total 21769
telemt_desync_frames_bucket_total{bucket="1_2"} 6777
telemt_desync_frames_bucket_total{bucket="3_10"} 13705
telemt_desync_frames_bucket_total{bucket="gt_10"} 10452
telemt_pool_swap_total 96
telemt_pool_force_close_total 3236
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 727
telemt_me_draining_writers_reap_progress_total 29074
telemt_me_writer_removed_unexpected_total 1867
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3937
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26731
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2723
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 513
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25838
telemt_me_writer_teardown_success_total{mode="normal"} 30668
telemt_me_writer_teardown_noop_total 29100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59768
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 209.081891
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59768
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 727
telemt_me_refill_failed_total 3550
telemt_me_writer_restored_same_endpoint_total 1401
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14284
telemt_me_writer_removed_unexpected_minus_restored_total 452
telemt_user_connections_total{user="hello"} 16239312
telemt_user_connections_current{user="hello"} 2514
telemt_user_octets_from_client{user="hello"} 173718967738 (161.79 GB)
telemt_user_octets_to_client{user="hello"} 1066068685782 (992.85 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1092
telemt_user_unique_ips_recent_window{user="hello"} 275
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 93915.1 (26h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5716596
telemt_connections_bad_total 534938
telemt_connections_current 1553
telemt_connections_me_current 1553
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 118346
telemt_upstream_connect_attempt_total 51642
telemt_upstream_connect_success_total 51089
telemt_upstream_connect_fail_total 467
telemt_upstream_connect_attempts_per_request{bucket="1"} 51556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19989
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 335
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 467
telemt_me_reconnect_attempts_total 11805
telemt_me_reconnect_success_total 1350
telemt_me_reader_eof_total 1256
telemt_me_idle_close_by_peer_total 1256
telemt_me_route_drop_no_conn_total 2336501
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4454499
telemt_me_endpoint_quarantine_total 589
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 702
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
telemt_desync_total 22495
telemt_desync_full_logged_total 7831
telemt_desync_suppressed_total 14664
telemt_desync_frames_bucket_total{bucket="1_2"} 4285
telemt_desync_frames_bucket_total{bucket="3_10"} 8733
telemt_desync_frames_bucket_total{bucket="gt_10"} 9477
telemt_pool_swap_total 96
telemt_pool_force_close_total 2812
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 362
telemt_me_draining_writers_reap_progress_total 31786
telemt_me_writer_removed_unexpected_total 1258
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3243
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29816
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2444
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28974
telemt_me_writer_teardown_success_total{mode="normal"} 33059
telemt_me_writer_teardown_noop_total 31787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64846
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.647257
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64846
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 362
telemt_me_refill_failed_total 627
telemt_me_writer_restored_same_endpoint_total 1126
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 1544
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 4447591
telemt_user_connections_current{user="hello"} 1553
telemt_user_octets_from_client{user="hello"} 118888779384 (110.72 GB)
telemt_user_octets_to_client{user="hello"} 1810301602774 (1.65 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 734
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 30750.9 (8h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3563526
telemt_connections_bad_total 126037
telemt_connections_current 1925
telemt_connections_me_current 1925
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1502419
telemt_upstream_connect_attempt_total 15696
telemt_upstream_connect_success_total 15568
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 15690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5868
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_reconnect_attempts_total 22128
telemt_me_reconnect_success_total 547
telemt_me_reader_eof_total 378
telemt_me_idle_close_by_peer_total 378
telemt_me_route_drop_no_conn_total 977019
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1705197
telemt_me_endpoint_quarantine_total 189
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 229
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
telemt_me_floor_cap_block_total 13
telemt_me_floor_swap_idle_failed_total 13
telemt_desync_total 9479
telemt_desync_full_logged_total 3196
telemt_desync_suppressed_total 6283
telemt_desync_frames_bucket_total{bucket="1_2"} 1684
telemt_desync_frames_bucket_total{bucket="3_10"} 3631
telemt_desync_frames_bucket_total{bucket="gt_10"} 4164
telemt_pool_swap_total 33
telemt_pool_force_close_total 1053
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 104
telemt_me_draining_writers_reap_progress_total 9348
telemt_me_writer_removed_unexpected_total 416
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 963
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8815
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 904
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 149
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8295
telemt_me_writer_teardown_success_total{mode="normal"} 9778
telemt_me_writer_teardown_noop_total 9349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 19021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19127
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.732307
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19127
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 104
telemt_me_refill_failed_total 1214
telemt_me_writer_restored_same_endpoint_total 477
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 160
telemt_me_async_recovery_trigger_total 2130
telemt_user_connections_total{user="hello"} 1705347
telemt_user_connections_current{user="hello"} 1925
telemt_user_octets_from_client{user="hello"} 49267210256 (45.88 GB)
telemt_user_octets_to_client{user="hello"} 734063823126 (683.65 GB)
telemt_user_msgs_from_client{user="hello"} 43112
telemt_user_msgs_to_client{user="hello"} 113951
telemt_user_unique_ips_current{user="hello"} 901
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 11722.1 (3h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135428
telemt_connections_bad_total 1350
telemt_connections_current 403
telemt_connections_me_current 403
telemt_handshake_timeouts_total 3335
telemt_upstream_connect_attempt_total 5115
telemt_upstream_connect_success_total 5099
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 5113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2922
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 109
telemt_me_reconnect_success_total 60
telemt_me_reader_eof_total 64
telemt_me_idle_close_by_peer_total 64
telemt_me_route_drop_no_conn_total 38659
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117611
telemt_me_endpoint_quarantine_total 91
telemt_me_single_endpoint_shadow_rotate_total 101
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_warm_current 3
telemt_desync_total 929
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 699
telemt_desync_frames_bucket_total{bucket="1_2"} 377
telemt_desync_frames_bucket_total{bucket="3_10"} 339
telemt_desync_frames_bucket_total{bucket="gt_10"} 213
telemt_pool_swap_total 12
telemt_pool_force_close_total 299
telemt_me_writer_close_signal_drop_total 15
telemt_me_draining_writers_reap_progress_total 4510
telemt_me_writer_removed_unexpected_total 62
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 291
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4283
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 297
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4211
telemt_me_writer_teardown_success_total{mode="normal"} 4574
telemt_me_writer_teardown_noop_total 4510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 9059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 9074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 9084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 9084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 9084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 9084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 9084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 9084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 9084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 9084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 9084
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.612732
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 9084
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 15
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 57
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 117444
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 2265781900 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 71052400716 (66.17 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 93919.5 (26h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6834444
telemt_connections_bad_total 691928
telemt_connections_current 2104
telemt_connections_me_current 2104
telemt_handshake_timeouts_total 195029
telemt_upstream_connect_attempt_total 35627
telemt_upstream_connect_success_total 35485
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 35590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17847
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_reconnect_attempts_total 1446
telemt_me_reconnect_success_total 746
telemt_me_reader_eof_total 727
telemt_me_idle_close_by_peer_total 727
telemt_me_route_drop_no_conn_total 2072518
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5208653
telemt_me_endpoint_quarantine_total 626
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 719
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
telemt_me_writers_active_current 45
telemt_desync_total 19981
telemt_desync_full_logged_total 6682
telemt_desync_suppressed_total 13299
telemt_desync_frames_bucket_total{bucket="1_2"} 4859
telemt_desync_frames_bucket_total{bucket="3_10"} 7280
telemt_desync_frames_bucket_total{bucket="gt_10"} 7842
telemt_pool_swap_total 104
telemt_pool_force_close_total 2850
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 358
telemt_me_draining_writers_reap_progress_total 32003
telemt_me_writer_removed_unexpected_total 705
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2612
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30108
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2762
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29153
telemt_me_writer_teardown_success_total{mode="normal"} 32720
telemt_me_writer_teardown_noop_total 32005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64725
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.464623
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64725
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 358
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 668
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 5184055
telemt_user_connections_current{user="hello"} 2104
telemt_user_octets_from_client{user="hello"} 104451996184 (97.28 GB)
telemt_user_octets_to_client{user="hello"} 2436722823988 (2.22 TB)
telemt_user_unique_ips_current{user="hello"} 851
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 93916.1 (26h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5838289
telemt_connections_bad_total 554430
telemt_connections_current 2006
telemt_connections_me_current 2006
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 164087
telemt_upstream_connect_attempt_total 51739
telemt_upstream_connect_success_total 51345
telemt_upstream_connect_fail_total 335
telemt_upstream_connect_attempts_per_request{bucket="1"} 51680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19607
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 335
telemt_me_reconnect_attempts_total 5231
telemt_me_reconnect_success_total 1054
telemt_me_reader_eof_total 931
telemt_me_idle_close_by_peer_total 931
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2124814
telemt_me_route_drop_channel_closed_total 188
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4578027
telemt_me_endpoint_quarantine_total 733
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 712
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 18711
telemt_desync_full_logged_total 6315
telemt_desync_suppressed_total 12396
telemt_desync_frames_bucket_total{bucket="1_2"} 4646
telemt_desync_frames_bucket_total{bucket="3_10"} 6827
telemt_desync_frames_bucket_total{bucket="gt_10"} 7238
telemt_pool_swap_total 102
telemt_pool_force_close_total 2807
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 359
telemt_me_draining_writers_reap_progress_total 30929
telemt_me_writer_removed_unexpected_total 941
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3095
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28818
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2584
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28122
telemt_me_writer_teardown_success_total{mode="normal"} 31913
telemt_me_writer_teardown_noop_total 30933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62846
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.550812
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62846
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 359
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 817
telemt_me_writer_restored_fallback_total 49
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 4581520
telemt_user_connections_current{user="hello"} 2006
telemt_user_octets_from_client{user="hello"} 87675633373 (81.65 GB)
telemt_user_octets_to_client{user="hello"} 1968504558996 (1.79 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 819
telemt_user_unique_ips_recent_window{user="hello"} 205
```
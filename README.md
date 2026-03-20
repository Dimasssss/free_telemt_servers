# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

**Принимаю донаты криптой для добавления и продления серверов:**  
- TON: UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```
Этот сервер пользуется большим спросом. Я арендовал еще один такой же, чтобы распределить нагрузку.

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

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su
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

# Server Metrics 2026-03-20 16:19:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 427.7 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27245
telemt_connections_bad_total 977
telemt_connections_current 1552
telemt_connections_direct_current 1552
telemt_relay_adaptive_promotions_total 30
telemt_relay_adaptive_demotions_total 866
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 271
telemt_upstream_connect_attempt_total 23760
telemt_upstream_connect_success_total 23754
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 23760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23752
telemt_user_connections_current{user="hello"} 1552
telemt_user_octets_from_client{user="hello"} 382126956 (364.42 MB)
telemt_user_octets_to_client{user="hello"} 5067216711 (4.72 GB)
telemt_user_msgs_from_client{user="hello"} 288749
telemt_user_msgs_to_client{user="hello"} 308824
telemt_user_unique_ips_current{user="hello"} 498
telemt_user_unique_ips_recent_window{user="hello"} 265
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 7450.7 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 931193
telemt_connections_bad_total 48982
telemt_connections_current 4572
telemt_connections_me_current 4572
telemt_handshake_timeouts_total 14957
telemt_upstream_connect_attempt_total 2443
telemt_upstream_connect_success_total 2420
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 156
telemt_me_reconnect_success_total 93
telemt_me_reader_eof_total 78
telemt_me_idle_close_by_peer_total 78
telemt_me_route_drop_no_conn_total 380315
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 699140
telemt_me_endpoint_quarantine_total 33
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 2421
telemt_desync_full_logged_total 825
telemt_desync_suppressed_total 1596
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 970
telemt_desync_frames_bucket_total{bucket="gt_10"} 937
telemt_pool_swap_total 7
telemt_pool_force_close_total 297
telemt_me_writer_close_signal_drop_total 42
telemt_me_draining_writers_reap_progress_total 2103
telemt_me_writer_removed_unexpected_total 78
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 231
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1922
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 234
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 63
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1806
telemt_me_writer_teardown_success_total{mode="normal"} 2153
telemt_me_writer_teardown_noop_total 2109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4262
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.060010
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4262
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 42
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 84
telemt_me_writer_restored_fallback_total 1
telemt_me_no_writer_failfast_total 41
telemt_me_async_recovery_trigger_total 396
telemt_user_connections_total{user="hello"} 698395
telemt_user_connections_current{user="hello"} 4572
telemt_user_octets_from_client{user="hello"} 8900670964 (8.29 GB)
telemt_user_octets_to_client{user="hello"} 208436618292 (194.12 GB)
telemt_user_unique_ips_current{user="hello"} 1475
telemt_user_unique_ips_recent_window{user="hello"} 754
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 7444.8 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 667206
telemt_connections_bad_total 43140
telemt_connections_current 4016
telemt_connections_me_current 4016
telemt_handshake_timeouts_total 9825
telemt_upstream_connect_attempt_total 3218
telemt_upstream_connect_success_total 3147
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 3215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_reconnect_attempts_total 365
telemt_me_reconnect_success_total 235
telemt_me_reader_eof_total 202
telemt_me_idle_close_by_peer_total 202
telemt_me_route_drop_no_conn_total 275563
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 562147
telemt_me_endpoint_quarantine_total 48
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 54
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
telemt_me_writers_active_current 42
telemt_desync_total 1986
telemt_desync_full_logged_total 636
telemt_desync_suppressed_total 1350
telemt_desync_frames_bucket_total{bucket="1_2"} 386
telemt_desync_frames_bucket_total{bucket="3_10"} 804
telemt_desync_frames_bucket_total{bucket="gt_10"} 796
telemt_pool_swap_total 5
telemt_pool_force_close_total 324
telemt_pool_stale_pick_total 1363
telemt_me_writer_close_signal_drop_total 56
telemt_me_draining_writers_reap_progress_total 2748
telemt_me_writer_removed_unexpected_total 197
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 390
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2503
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 148
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 176
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2424
telemt_me_writer_teardown_success_total{mode="normal"} 2893
telemt_me_writer_teardown_noop_total 2748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5641
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 24.668183
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5641
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 56
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 220
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 561599
telemt_user_connections_current{user="hello"} 4016
telemt_user_octets_from_client{user="hello"} 9648641156 (8.99 GB)
telemt_user_octets_to_client{user="hello"} 199014271276 (185.35 GB)
telemt_user_unique_ips_current{user="hello"} 1367
telemt_user_unique_ips_recent_window{user="hello"} 756
```

## koara.io

```
telemt 3.3.27

telemt_uptime_seconds 21502.7 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3753525
telemt_connections_bad_total 383593
telemt_connections_current 6026
telemt_connections_me_current 6026
telemt_handshake_timeouts_total 68332
telemt_upstream_connect_attempt_total 6908
telemt_upstream_connect_success_total 6868
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 6897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3723
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 661
telemt_me_reconnect_success_total 420
telemt_me_reader_eof_total 427
telemt_me_idle_close_by_peer_total 427
telemt_me_route_drop_no_conn_total 2405360
telemt_me_route_drop_channel_closed_total 157
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2978793
telemt_me_writer_pick_total{mode="p2c",result="full"} 1
telemt_me_endpoint_quarantine_total 88
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 136
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
telemt_desync_total 8174
telemt_desync_full_logged_total 2325
telemt_desync_suppressed_total 5849
telemt_desync_frames_bucket_total{bucket="1_2"} 2084
telemt_desync_frames_bucket_total{bucket="3_10"} 3173
telemt_desync_frames_bucket_total{bucket="gt_10"} 2917
telemt_pool_swap_total 16
telemt_pool_force_close_total 834
telemt_me_writer_close_signal_drop_total 200
telemt_me_draining_writers_reap_progress_total 5934
telemt_me_writer_removed_unexpected_total 423
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 802
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5478
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 495
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 339
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5100
telemt_me_writer_teardown_success_total{mode="normal"} 6280
telemt_me_writer_teardown_noop_total 5944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12224
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 60.954502
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12224
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 200
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 403
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 2975480
telemt_user_connections_current{user="hello"} 6026
telemt_user_octets_from_client{user="hello"} 33251408928 (30.97 GB)
telemt_user_octets_to_client{user="hello"} 806691940244 (751.29 GB)
telemt_user_unique_ips_current{user="hello"} 1862
telemt_user_unique_ips_recent_window{user="hello"} 734
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 7442.8 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2774925
telemt_connections_bad_total 65687
telemt_connections_current 4872
telemt_connections_me_current 4872
telemt_handshake_timeouts_total 30718
telemt_upstream_connect_attempt_total 11334
telemt_upstream_connect_success_total 10725
telemt_upstream_connect_fail_total 459
telemt_upstream_connect_attempts_per_request{bucket="1"} 11184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2628
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 459
telemt_me_keepalive_timeout_total 185
telemt_me_reconnect_attempts_total 647
telemt_me_reconnect_success_total 338
telemt_me_reader_eof_total 244
telemt_me_idle_close_by_peer_total 244
telemt_me_route_drop_no_conn_total 5630467
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2509329
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_me_writers_active_current 57
telemt_desync_total 3168
telemt_desync_full_logged_total 904
telemt_desync_suppressed_total 2264
telemt_desync_frames_bucket_total{bucket="1_2"} 655
telemt_desync_frames_bucket_total{bucket="3_10"} 1418
telemt_desync_frames_bucket_total{bucket="gt_10"} 1095
telemt_pool_swap_total 5
telemt_pool_force_close_total 218
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 93
telemt_me_draining_writers_reap_progress_total 2132
telemt_me_writer_removed_unexpected_total 372
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 524
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1978
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 147
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 71
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1914
telemt_me_writer_teardown_success_total{mode="normal"} 2502
telemt_me_writer_teardown_noop_total 2133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4635
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.846862
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4635
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 93
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 263
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 2516622
telemt_user_connections_current{user="hello"} 4872
telemt_user_octets_from_client{user="hello"} 10610727999 (9.88 GB)
telemt_user_octets_to_client{user="hello"} 80593601892 (75.06 GB)
telemt_user_msgs_from_client{user="hello"} 8736
telemt_user_msgs_to_client{user="hello"} 7574
telemt_user_unique_ips_current{user="hello"} 1577
telemt_user_unique_ips_recent_window{user="hello"} 1257
```

## rdp-onedash.ru

```
telemt 3.3.28

telemt_uptime_seconds 7447.5 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2456688
telemt_connections_bad_total 170899
telemt_connections_current 6156
telemt_connections_me_current 6156
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 22445
telemt_upstream_connect_attempt_total 19298
telemt_upstream_connect_success_total 19291
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 19298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 724
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 220
telemt_me_reconnect_success_total 68
telemt_me_reader_eof_total 69
telemt_me_idle_close_by_peer_total 69
telemt_me_route_drop_no_conn_total 4197159
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2084802
telemt_me_endpoint_quarantine_total 47
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 53
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
telemt_me_writers_active_current 41
telemt_desync_total 3493
telemt_desync_full_logged_total 1020
telemt_desync_suppressed_total 2473
telemt_desync_frames_bucket_total{bucket="1_2"} 904
telemt_desync_frames_bucket_total{bucket="3_10"} 1513
telemt_desync_frames_bucket_total{bucket="gt_10"} 1076
telemt_pool_swap_total 8
telemt_pool_force_close_total 246
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 1712
telemt_me_writer_removed_unexpected_total 66
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 209
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1539
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 214
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1466
telemt_me_writer_teardown_success_total{mode="normal"} 1748
telemt_me_writer_teardown_noop_total 1716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3464
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 114.253679
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3464
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 2098311
telemt_user_connections_current{user="hello"} 6156
telemt_user_octets_from_client{user="hello"} 16269515412 (15.15 GB)
telemt_user_octets_to_client{user="hello"} 152287585311 (141.83 GB)
telemt_user_msgs_from_client{user="hello"} 75809
telemt_user_msgs_to_client{user="hello"} 92195
telemt_user_unique_ips_current{user="hello"} 1877
telemt_user_unique_ips_recent_window{user="hello"} 973
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 6875.3 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141588
telemt_connections_bad_total 1314
telemt_connections_current 848
telemt_connections_me_current 848
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 2384
telemt_upstream_connect_attempt_total 4170
telemt_upstream_connect_success_total 4167
telemt_upstream_connect_attempts_per_request{bucket="1"} 4167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2964
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 124
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 215
telemt_me_reconnect_success_total 56
telemt_me_reader_eof_total 53
telemt_me_idle_close_by_peer_total 53
telemt_me_route_drop_no_conn_total 117726
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124308
telemt_me_endpoint_quarantine_total 48
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_desync_total 414
telemt_desync_full_logged_total 134
telemt_desync_suppressed_total 280
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 163
telemt_desync_frames_bucket_total{bucket="gt_10"} 179
telemt_pool_swap_total 7
telemt_pool_force_close_total 194
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 47
telemt_me_draining_writers_reap_progress_total 2159
telemt_me_writer_removed_unexpected_total 53
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 231
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1966
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 193
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1965
telemt_me_writer_teardown_success_total{mode="normal"} 2197
telemt_me_writer_teardown_noop_total 2160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4357
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.453170
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4357
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 47
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 42
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 125296
telemt_user_connections_current{user="hello"} 848
telemt_user_octets_from_client{user="hello"} 1484479982 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 23314539505 (21.71 GB)
telemt_user_msgs_from_client{user="hello"} 5317
telemt_user_msgs_to_client{user="hello"} 6420
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## 4vps.su

```
telemt 3.3.28

telemt_uptime_seconds 7446.4 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1312881
telemt_connections_bad_total 79769
telemt_connections_current 7388
telemt_connections_me_current 7388
telemt_handshake_timeouts_total 43907
telemt_upstream_connect_attempt_total 2239
telemt_upstream_connect_success_total 2237
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1198
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 149
telemt_me_reconnect_success_total 76
telemt_me_reader_eof_total 80
telemt_me_idle_close_by_peer_total 80
telemt_me_route_drop_no_conn_total 640265
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1116107
telemt_me_endpoint_quarantine_total 35
telemt_me_single_endpoint_shadow_rotate_total 52
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
telemt_desync_total 4098
telemt_desync_full_logged_total 1160
telemt_desync_suppressed_total 2938
telemt_desync_frames_bucket_total{bucket="1_2"} 1011
telemt_desync_frames_bucket_total{bucket="3_10"} 1557
telemt_desync_frames_bucket_total{bucket="gt_10"} 1530
telemt_pool_swap_total 7
telemt_pool_force_close_total 263
telemt_me_writer_close_signal_drop_total 42
telemt_me_draining_writers_reap_progress_total 1897
telemt_me_writer_removed_unexpected_total 78
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 220
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1759
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1634
telemt_me_writer_teardown_success_total{mode="normal"} 1979
telemt_me_writer_teardown_noop_total 1898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3877
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.352999
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3877
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 42
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 69
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 1114844
telemt_user_connections_current{user="hello"} 7388
telemt_user_octets_from_client{user="hello"} 14593110780 (13.59 GB)
telemt_user_octets_to_client{user="hello"} 343727637284 (320.12 GB)
telemt_user_unique_ips_current{user="hello"} 2157
telemt_user_unique_ips_recent_window{user="hello"} 984
```
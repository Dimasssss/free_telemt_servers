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

# Server Metrics 2026-03-20 15:53:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 5889.4 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286787
telemt_connections_bad_total 12911
telemt_connections_current 1695
telemt_connections_me_current 1695
telemt_handshake_timeouts_total 6193
telemt_upstream_connect_attempt_total 2421
telemt_upstream_connect_success_total 2411
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1486
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 469
telemt_me_reconnect_success_total 199
telemt_me_reader_eof_total 209
telemt_me_idle_close_by_peer_total 209
telemt_me_route_drop_no_conn_total 309231
telemt_me_route_drop_channel_closed_total 115
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252053
telemt_me_endpoint_quarantine_total 38
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 954
telemt_desync_full_logged_total 298
telemt_desync_suppressed_total 656
telemt_desync_frames_bucket_total{bucket="1_2"} 180
telemt_desync_frames_bucket_total{bucket="3_10"} 423
telemt_desync_frames_bucket_total{bucket="gt_10"} 351
telemt_pool_swap_total 4
telemt_pool_force_close_total 167
telemt_me_writer_close_signal_drop_total 61
telemt_me_draining_writers_reap_progress_total 1987
telemt_me_writer_removed_unexpected_total 208
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 324
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1863
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 116
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1820
telemt_me_writer_teardown_success_total{mode="normal"} 2187
telemt_me_writer_teardown_noop_total 1987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4174
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 21.878620
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4174
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 61
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 192
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 251845
telemt_user_connections_current{user="hello"} 1695
telemt_user_octets_from_client{user="hello"} 2560575984 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 48252865228 (44.94 GB)
telemt_user_unique_ips_current{user="hello"} 585
telemt_user_unique_ips_recent_window{user="hello"} 255
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 5898.8 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 732778
telemt_connections_bad_total 43201
telemt_connections_current 4312
telemt_connections_me_current 4312
telemt_handshake_timeouts_total 11306
telemt_upstream_connect_attempt_total 1998
telemt_upstream_connect_success_total 1976
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 1998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1094
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 149
telemt_me_reconnect_success_total 87
telemt_me_reader_eof_total 72
telemt_me_idle_close_by_peer_total 72
telemt_me_route_drop_no_conn_total 267243
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 547834
telemt_me_endpoint_quarantine_total 26
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_desync_total 1810
telemt_desync_full_logged_total 632
telemt_desync_suppressed_total 1178
telemt_desync_frames_bucket_total{bucket="1_2"} 394
telemt_desync_frames_bucket_total{bucket="3_10"} 714
telemt_desync_frames_bucket_total{bucket="gt_10"} 702
telemt_pool_swap_total 5
telemt_pool_force_close_total 230
telemt_me_writer_close_signal_drop_total 35
telemt_me_draining_writers_reap_progress_total 1699
telemt_me_writer_removed_unexpected_total 72
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1551
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 57
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1469
telemt_me_writer_teardown_success_total{mode="normal"} 1743
telemt_me_writer_teardown_noop_total 1705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3448
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.661077
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3448
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 35
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 78
telemt_me_writer_restored_fallback_total 1
telemt_me_no_writer_failfast_total 41
telemt_me_async_recovery_trigger_total 396
telemt_user_connections_total{user="hello"} 547375
telemt_user_connections_current{user="hello"} 4312
telemt_user_octets_from_client{user="hello"} 6704977244 (6.24 GB)
telemt_user_octets_to_client{user="hello"} 163273211072 (152.06 GB)
telemt_user_unique_ips_current{user="hello"} 1493
telemt_user_unique_ips_recent_window{user="hello"} 625
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 5893.0 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 521326
telemt_connections_bad_total 31212
telemt_connections_current 3845
telemt_connections_me_current 3845
telemt_handshake_timeouts_total 6944
telemt_upstream_connect_attempt_total 2503
telemt_upstream_connect_success_total 2447
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 2500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1291
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 300
telemt_me_reconnect_success_total 187
telemt_me_reader_eof_total 150
telemt_me_idle_close_by_peer_total 150
telemt_me_route_drop_no_conn_total 202481
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 442222
telemt_me_endpoint_quarantine_total 43
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 44
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
telemt_me_writers_active_current 51
telemt_desync_total 1306
telemt_desync_full_logged_total 453
telemt_desync_suppressed_total 853
telemt_desync_frames_bucket_total{bucket="1_2"} 231
telemt_desync_frames_bucket_total{bucket="3_10"} 521
telemt_desync_frames_bucket_total{bucket="gt_10"} 554
telemt_pool_swap_total 4
telemt_pool_force_close_total 236
telemt_pool_stale_pick_total 1363
telemt_me_writer_close_signal_drop_total 38
telemt_me_draining_writers_reap_progress_total 2092
telemt_me_writer_removed_unexpected_total 147
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 294
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1910
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 119
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 117
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1856
telemt_me_writer_teardown_success_total{mode="normal"} 2204
telemt_me_writer_teardown_noop_total 2092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4296
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.612060
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4296
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 38
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 173
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 441860
telemt_user_connections_current{user="hello"} 3845
telemt_user_octets_from_client{user="hello"} 7695541896 (7.17 GB)
telemt_user_octets_to_client{user="hello"} 152976663672 (142.47 GB)
telemt_user_unique_ips_current{user="hello"} 1401
telemt_user_unique_ips_recent_window{user="hello"} 545
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 5891.6 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2243314
telemt_connections_bad_total 49210
telemt_connections_current 5376
telemt_connections_me_current 5376
telemt_handshake_timeouts_total 26002
telemt_upstream_connect_attempt_total 8176
telemt_upstream_connect_success_total 7785
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 8068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_keepalive_timeout_total 185
telemt_me_reconnect_attempts_total 387
telemt_me_reconnect_success_total 230
telemt_me_reader_eof_total 191
telemt_me_idle_close_by_peer_total 191
telemt_me_route_drop_no_conn_total 4543567
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2032268
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 47
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
telemt_me_writers_active_current 49
telemt_desync_total 2673
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1936
telemt_desync_frames_bucket_total{bucket="1_2"} 564
telemt_desync_frames_bucket_total{bucket="3_10"} 1196
telemt_desync_frames_bucket_total{bucket="gt_10"} 913
telemt_pool_swap_total 4
telemt_pool_force_close_total 183
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 59
telemt_me_draining_writers_reap_progress_total 1740
telemt_me_writer_removed_unexpected_total 234
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 360
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1612
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 120
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 63
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1557
telemt_me_writer_teardown_success_total{mode="normal"} 1972
telemt_me_writer_teardown_noop_total 1741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3713
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.385819
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3713
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 59
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 192
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 2037403
telemt_user_connections_current{user="hello"} 5374
telemt_user_octets_from_client{user="hello"} 8494692560 (7.91 GB)
telemt_user_octets_to_client{user="hello"} 63495045130 (59.13 GB)
telemt_user_msgs_from_client{user="hello"} 4517
telemt_user_msgs_to_client{user="hello"} 3964
telemt_user_unique_ips_current{user="hello"} 1752
telemt_user_unique_ips_recent_window{user="hello"} 1007
```

## rdp-onedash.ru

```
telemt 3.3.28

telemt_uptime_seconds 5896.3 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1900247
telemt_connections_bad_total 130936
telemt_connections_current 5870
telemt_connections_me_current 5870
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 17936
telemt_upstream_connect_attempt_total 18877
telemt_upstream_connect_success_total 18870
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 18877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5393
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 722
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 194
telemt_me_reconnect_success_total 58
telemt_me_reader_eof_total 56
telemt_me_idle_close_by_peer_total 56
telemt_me_route_drop_no_conn_total 3182117
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1605481
telemt_me_endpoint_quarantine_total 32
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 43
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
telemt_desync_total 2599
telemt_desync_full_logged_total 753
telemt_desync_suppressed_total 1846
telemt_desync_frames_bucket_total{bucket="1_2"} 643
telemt_desync_frames_bucket_total{bucket="3_10"} 1110
telemt_desync_frames_bucket_total{bucket="gt_10"} 846
telemt_pool_swap_total 6
telemt_pool_force_close_total 176
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 60
telemt_me_draining_writers_reap_progress_total 1334
telemt_me_writer_removed_unexpected_total 54
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 156
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1201
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 152
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1158
telemt_me_writer_teardown_success_total{mode="normal"} 1357
telemt_me_writer_teardown_noop_total 1338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2695
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 113.962558
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2695
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 60
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 1620086
telemt_user_connections_current{user="hello"} 5870
telemt_user_octets_from_client{user="hello"} 12649010700 (11.78 GB)
telemt_user_octets_to_client{user="hello"} 121483020627 (113.14 GB)
telemt_user_msgs_from_client{user="hello"} 75809
telemt_user_msgs_to_client{user="hello"} 92195
telemt_user_unique_ips_current{user="hello"} 1942
telemt_user_unique_ips_recent_window{user="hello"} 804
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 5323.7 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105801
telemt_connections_bad_total 1131
telemt_connections_current 639
telemt_connections_me_current 639
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 1702
telemt_upstream_connect_attempt_total 3598
telemt_upstream_connect_success_total 3594
telemt_upstream_connect_attempts_per_request{bucket="1"} 3594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2561
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 191
telemt_me_reconnect_success_total 48
telemt_me_reader_eof_total 43
telemt_me_idle_close_by_peer_total 43
telemt_me_route_drop_no_conn_total 87890
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95601
telemt_me_endpoint_quarantine_total 35
telemt_me_single_endpoint_shadow_rotate_total 40
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
telemt_desync_total 273
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 173
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 108
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 5
telemt_pool_force_close_total 121
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 38
telemt_me_draining_writers_reap_progress_total 1619
telemt_me_writer_removed_unexpected_total 43
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 178
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1485
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 120
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1498
telemt_me_writer_teardown_success_total{mode="normal"} 1663
telemt_me_writer_teardown_noop_total 1619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3282
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.084070
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3282
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 38
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 34
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 96626
telemt_user_connections_current{user="hello"} 639
telemt_user_octets_from_client{user="hello"} 984609846 (939.00 MB)
telemt_user_octets_to_client{user="hello"} 18669520989 (17.39 GB)
telemt_user_msgs_from_client{user="hello"} 5317
telemt_user_msgs_to_client{user="hello"} 6420
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## 4vps.su

```
telemt 3.3.28

telemt_uptime_seconds 5894.3 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1013481
telemt_connections_bad_total 68423
telemt_connections_current 7091
telemt_connections_me_current 7091
telemt_handshake_timeouts_total 35185
telemt_upstream_connect_attempt_total 1789
telemt_upstream_connect_success_total 1787
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 958
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 65
telemt_me_reconnect_success_total 65
telemt_me_reader_eof_total 66
telemt_me_idle_close_by_peer_total 66
telemt_me_route_drop_no_conn_total 434639
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 851272
telemt_me_endpoint_quarantine_total 28
telemt_me_single_endpoint_shadow_rotate_total 39
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
telemt_me_writers_active_current 43
telemt_desync_total 3128
telemt_desync_full_logged_total 879
telemt_desync_suppressed_total 2249
telemt_desync_frames_bucket_total{bucket="1_2"} 735
telemt_desync_frames_bucket_total{bucket="3_10"} 1197
telemt_desync_frames_bucket_total{bucket="gt_10"} 1196
telemt_pool_swap_total 5
telemt_pool_force_close_total 196
telemt_me_writer_close_signal_drop_total 24
telemt_me_draining_writers_reap_progress_total 1484
telemt_me_writer_removed_unexpected_total 66
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 167
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1385
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 151
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1288
telemt_me_writer_teardown_success_total{mode="normal"} 1552
telemt_me_writer_teardown_noop_total 1485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3037
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.972307
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3037
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 24
telemt_me_writer_restored_same_endpoint_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 850460
telemt_user_connections_current{user="hello"} 7091
telemt_user_octets_from_client{user="hello"} 11851685424 (11.04 GB)
telemt_user_octets_to_client{user="hello"} 276863507128 (257.85 GB)
telemt_user_unique_ips_current{user="hello"} 2199
telemt_user_unique_ips_recent_window{user="hello"} 934
```
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

# Server Metrics 2026-03-20 16:14:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 119.7 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9530
telemt_connections_bad_total 287
telemt_connections_current 1505
telemt_connections_direct_current 1505
telemt_relay_adaptive_promotions_total 27
telemt_relay_adaptive_hard_promotions_total 26
telemt_handshake_timeouts_total 62
telemt_upstream_connect_attempt_total 8381
telemt_upstream_connect_success_total 8378
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 8381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 736
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8376
telemt_user_connections_current{user="hello"} 1505
telemt_user_octets_from_client{user="hello"} 53127449 (50.67 MB)
telemt_user_octets_to_client{user="hello"} 1657520022 (1.54 GB)
telemt_user_msgs_from_client{user="hello"} 65698
telemt_user_msgs_to_client{user="hello"} 91016
telemt_user_unique_ips_current{user="hello"} 505
telemt_user_unique_ips_recent_window{user="hello"} 408
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 7142.7 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 885739
telemt_connections_bad_total 48367
telemt_connections_current 4060
telemt_connections_me_current 4060
telemt_handshake_timeouts_total 14069
telemt_upstream_connect_attempt_total 2315
telemt_upstream_connect_success_total 2292
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 155
telemt_me_reconnect_success_total 92
telemt_me_reader_eof_total 77
telemt_me_idle_close_by_peer_total 77
telemt_me_route_drop_no_conn_total 359811
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 667599
telemt_me_endpoint_quarantine_total 31
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 52
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
telemt_desync_total 2320
telemt_desync_full_logged_total 789
telemt_desync_suppressed_total 1531
telemt_desync_frames_bucket_total{bucket="1_2"} 490
telemt_desync_frames_bucket_total{bucket="3_10"} 924
telemt_desync_frames_bucket_total{bucket="gt_10"} 906
telemt_pool_swap_total 6
telemt_pool_force_close_total 265
telemt_me_writer_close_signal_drop_total 40
telemt_me_draining_writers_reap_progress_total 1981
telemt_me_writer_removed_unexpected_total 77
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 219
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1811
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 204
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1716
telemt_me_writer_teardown_success_total{mode="normal"} 2030
telemt_me_writer_teardown_noop_total 1987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4017
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.880426
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4017
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 40
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 83
telemt_me_writer_restored_fallback_total 1
telemt_me_no_writer_failfast_total 41
telemt_me_async_recovery_trigger_total 396
telemt_user_connections_total{user="hello"} 666927
telemt_user_connections_current{user="hello"} 4060
telemt_user_octets_from_client{user="hello"} 8554125108 (7.97 GB)
telemt_user_octets_to_client{user="hello"} 199928213000 (186.20 GB)
telemt_user_unique_ips_current{user="hello"} 1335
telemt_user_unique_ips_recent_window{user="hello"} 604
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 7137.4 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 635742
telemt_connections_bad_total 40568
telemt_connections_current 4495
telemt_connections_me_current 4495
telemt_handshake_timeouts_total 9353
telemt_upstream_connect_attempt_total 3045
telemt_upstream_connect_success_total 2977
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 3042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1575
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_reconnect_attempts_total 347
telemt_me_reconnect_success_total 233
telemt_me_reader_eof_total 199
telemt_me_idle_close_by_peer_total 199
telemt_me_route_drop_no_conn_total 258351
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 535551
telemt_me_endpoint_quarantine_total 44
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 50
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
telemt_me_writers_active_current 93
telemt_desync_total 1878
telemt_desync_full_logged_total 606
telemt_desync_suppressed_total 1272
telemt_desync_frames_bucket_total{bucket="1_2"} 362
telemt_desync_frames_bucket_total{bucket="3_10"} 765
telemt_desync_frames_bucket_total{bucket="gt_10"} 751
telemt_pool_swap_total 4
telemt_pool_force_close_total 236
telemt_pool_stale_pick_total 1363
telemt_me_writer_close_signal_drop_total 39
telemt_me_draining_writers_reap_progress_total 2514
telemt_me_writer_removed_unexpected_total 194
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 360
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2315
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 119
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 117
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2278
telemt_me_writer_teardown_success_total{mode="normal"} 2675
telemt_me_writer_teardown_noop_total 2514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5189
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.691696
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5189
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 39
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 219
telemt_me_async_recovery_trigger_total 48
telemt_user_connections_total{user="hello"} 535150
telemt_user_connections_current{user="hello"} 4495
telemt_user_octets_from_client{user="hello"} 9374896644 (8.73 GB)
telemt_user_octets_to_client{user="hello"} 190085433492 (177.03 GB)
telemt_user_unique_ips_current{user="hello"} 1699
telemt_user_unique_ips_recent_window{user="hello"} 537
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 7135.5 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2672634
telemt_connections_bad_total 61737
telemt_connections_current 5202
telemt_connections_me_current 5202
telemt_handshake_timeouts_total 29844
telemt_upstream_connect_attempt_total 11168
telemt_upstream_connect_success_total 10582
telemt_upstream_connect_fail_total 437
telemt_upstream_connect_attempts_per_request{bucket="1"} 11019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2563
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 437
telemt_me_keepalive_timeout_total 185
telemt_me_reconnect_attempts_total 589
telemt_me_reconnect_success_total 313
telemt_me_reader_eof_total 237
telemt_me_idle_close_by_peer_total 237
telemt_me_route_drop_no_conn_total 5418286
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2418039
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 59
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
telemt_desync_total 3064
telemt_desync_full_logged_total 871
telemt_desync_suppressed_total 2193
telemt_desync_frames_bucket_total{bucket="1_2"} 639
telemt_desync_frames_bucket_total{bucket="3_10"} 1371
telemt_desync_frames_bucket_total{bucket="gt_10"} 1054
telemt_pool_swap_total 4
telemt_pool_force_close_total 183
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 89
telemt_me_draining_writers_reap_progress_total 2006
telemt_me_writer_removed_unexpected_total 365
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 501
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1868
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 120
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 63
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1823
telemt_me_writer_teardown_success_total{mode="normal"} 2369
telemt_me_writer_teardown_noop_total 2007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4376
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.609929
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4376
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 89
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 242
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 2425399
telemt_user_connections_current{user="hello"} 5201
telemt_user_octets_from_client{user="hello"} 10297163219 (9.59 GB)
telemt_user_octets_to_client{user="hello"} 76848710600 (71.57 GB)
telemt_user_msgs_from_client{user="hello"} 8736
telemt_user_msgs_to_client{user="hello"} 7574
telemt_user_unique_ips_current{user="hello"} 1700
telemt_user_unique_ips_recent_window{user="hello"} 1042
```

## rdp-onedash.ru

```
telemt 3.3.28

telemt_uptime_seconds 7140.5 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2367254
telemt_connections_bad_total 166674
telemt_connections_current 7307
telemt_connections_me_current 7307
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 21530
telemt_upstream_connect_attempt_total 19179
telemt_upstream_connect_success_total 19172
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 19179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 723
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 197
telemt_me_reconnect_success_total 61
telemt_me_reader_eof_total 60
telemt_me_idle_close_by_peer_total 60
telemt_me_route_drop_no_conn_total 4040776
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2005595
telemt_me_endpoint_quarantine_total 38
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 49
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
telemt_me_writers_active_current 43
telemt_desync_total 3289
telemt_desync_full_logged_total 974
telemt_desync_suppressed_total 2315
telemt_desync_frames_bucket_total{bucket="1_2"} 849
telemt_desync_frames_bucket_total{bucket="3_10"} 1428
telemt_desync_frames_bucket_total{bucket="gt_10"} 1012
telemt_pool_swap_total 7
telemt_pool_force_close_total 211
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 74
telemt_me_draining_writers_reap_progress_total 1600
telemt_me_writer_removed_unexpected_total 58
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 186
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1441
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 183
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1389
telemt_me_writer_teardown_success_total{mode="normal"} 1627
telemt_me_writer_teardown_noop_total 1604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3231
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 114.099501
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3231
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 74
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 2019261
telemt_user_connections_current{user="hello"} 7307
telemt_user_octets_from_client{user="hello"} 15406575404 (14.35 GB)
telemt_user_octets_to_client{user="hello"} 145944854439 (135.92 GB)
telemt_user_msgs_from_client{user="hello"} 75809
telemt_user_msgs_to_client{user="hello"} 92195
telemt_user_unique_ips_current{user="hello"} 1979
telemt_user_unique_ips_recent_window{user="hello"} 936
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 6563.9 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134343
telemt_connections_bad_total 1314
telemt_connections_current 746
telemt_connections_me_current 746
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 2285
telemt_upstream_connect_attempt_total 4090
telemt_upstream_connect_success_total 4087
telemt_upstream_connect_attempts_per_request{bucket="1"} 4087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2903
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 117
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 215
telemt_me_reconnect_success_total 56
telemt_me_reader_eof_total 53
telemt_me_idle_close_by_peer_total 53
telemt_me_route_drop_no_conn_total 112638
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118629
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
telemt_desync_total 385
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 257
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 150
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 7
telemt_pool_force_close_total 194
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 47
telemt_me_draining_writers_reap_progress_total 2085
telemt_me_writer_removed_unexpected_total 53
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 228
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1895
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 193
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1891
telemt_me_writer_teardown_success_total{mode="normal"} 2123
telemt_me_writer_teardown_noop_total 2086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4209
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.403671
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4209
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 47
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 42
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 119617
telemt_user_connections_current{user="hello"} 746
telemt_user_octets_from_client{user="hello"} 1373709154 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 22464797993 (20.92 GB)
telemt_user_msgs_from_client{user="hello"} 5317
telemt_user_msgs_to_client{user="hello"} 6420
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## 4vps.su

```
telemt 3.3.28

telemt_uptime_seconds 7138.6 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1246084
telemt_connections_bad_total 77888
telemt_connections_current 7665
telemt_connections_me_current 7665
telemt_handshake_timeouts_total 42607
telemt_upstream_connect_attempt_total 2105
telemt_upstream_connect_success_total 2103
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1133
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 129
telemt_me_reconnect_success_total 72
telemt_me_reader_eof_total 74
telemt_me_idle_close_by_peer_total 74
telemt_me_route_drop_no_conn_total 595076
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1055568
telemt_me_endpoint_quarantine_total 30
telemt_me_single_endpoint_shadow_rotate_total 45
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
telemt_me_writers_active_current 46
telemt_desync_total 3880
telemt_desync_full_logged_total 1098
telemt_desync_suppressed_total 2782
telemt_desync_frames_bucket_total{bucket="1_2"} 972
telemt_desync_frames_bucket_total{bucket="3_10"} 1459
telemt_desync_frames_bucket_total{bucket="gt_10"} 1449
telemt_pool_swap_total 6
telemt_pool_force_close_total 229
telemt_me_writer_close_signal_drop_total 28
telemt_me_draining_writers_reap_progress_total 1768
telemt_me_writer_removed_unexpected_total 73
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 193
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1651
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 183
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1539
telemt_me_writer_teardown_success_total{mode="normal"} 1844
telemt_me_writer_teardown_noop_total 1769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3613
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.027418
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3613
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 28
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 65
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 1054534
telemt_user_connections_current{user="hello"} 7665
telemt_user_octets_from_client{user="hello"} 14172674872 (13.20 GB)
telemt_user_octets_to_client{user="hello"} 331687232772 (308.91 GB)
telemt_user_unique_ips_current{user="hello"} 2239
telemt_user_unique_ips_recent_window{user="hello"} 856
```
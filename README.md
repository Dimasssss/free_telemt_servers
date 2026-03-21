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

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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
- Оплачен до: 25 марта
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

# Server Metrics 2026-03-21 09:26:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 46213.4 (12h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1290397
telemt_connections_bad_total 66141
telemt_connections_current 1591
telemt_connections_me_current 1591
telemt_handshake_timeouts_total 52762
telemt_upstream_connect_attempt_total 18169
telemt_upstream_connect_success_total 18088
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 18145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11539
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 763
telemt_me_reconnect_success_total 320
telemt_me_reader_eof_total 327
telemt_me_idle_close_by_peer_total 327
telemt_me_route_drop_no_conn_total 714638
telemt_me_route_drop_channel_closed_total 213
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 971600
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 329
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 373
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
telemt_desync_total 4102
telemt_desync_full_logged_total 1403
telemt_desync_suppressed_total 2699
telemt_desync_frames_bucket_total{bucket="1_2"} 858
telemt_desync_frames_bucket_total{bucket="3_10"} 1607
telemt_desync_frames_bucket_total{bucket="gt_10"} 1637
telemt_pool_swap_total 51
telemt_pool_force_close_total 1431
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 197
telemt_me_draining_writers_reap_progress_total 16295
telemt_me_writer_removed_unexpected_total 306
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1261
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15241
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1409
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14864
telemt_me_writer_teardown_success_total{mode="normal"} 16502
telemt_me_writer_teardown_noop_total 16296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32798
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 80.275911
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32798
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 197
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 280
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 970803
telemt_user_connections_current{user="hello"} 1591
telemt_user_octets_from_client{user="hello"} 13789355831 (12.84 GB)
telemt_user_octets_to_client{user="hello"} 270221185271 (251.66 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 530
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 46214.7 (12h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3189643
telemt_connections_bad_total 352719
telemt_connections_current 4586
telemt_connections_me_current 4586
telemt_handshake_timeouts_total 94519
telemt_upstream_connect_attempt_total 16684
telemt_upstream_connect_success_total 16608
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 16660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9665
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_reconnect_attempts_total 980
telemt_me_reconnect_success_total 374
telemt_me_reader_eof_total 368
telemt_me_idle_close_by_peer_total 367
telemt_me_route_drop_no_conn_total 1216782
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2108628
telemt_me_endpoint_quarantine_total 296
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 360
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
telemt_desync_total 9199
telemt_desync_full_logged_total 3092
telemt_desync_suppressed_total 6107
telemt_desync_frames_bucket_total{bucket="1_2"} 1879
telemt_desync_frames_bucket_total{bucket="3_10"} 3599
telemt_desync_frames_bucket_total{bucket="gt_10"} 3721
telemt_pool_swap_total 50
telemt_pool_force_close_total 1516
telemt_me_writer_close_signal_drop_total 178
telemt_me_draining_writers_reap_progress_total 14928
telemt_me_writer_removed_unexpected_total 345
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1374
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13895
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1426
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 90
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13412
telemt_me_writer_teardown_success_total{mode="normal"} 15269
telemt_me_writer_teardown_noop_total 14928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30197
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.988234
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30197
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 178
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 300
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2104441
telemt_user_connections_current{user="hello"} 4586
telemt_user_octets_from_client{user="hello"} 30448340792 (28.36 GB)
telemt_user_octets_to_client{user="hello"} 752253212648 (700.59 GB)
telemt_user_unique_ips_current{user="hello"} 1631
telemt_user_unique_ips_recent_window{user="hello"} 672
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 46211.2 (12h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2318272
telemt_connections_bad_total 277935
telemt_connections_current 3963
telemt_connections_me_current 3963
telemt_handshake_timeouts_total 84751
telemt_upstream_connect_attempt_total 18131
telemt_upstream_connect_success_total 18121
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 18122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9861
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 609
telemt_me_reconnect_success_total 341
telemt_me_reader_eof_total 354
telemt_me_idle_close_by_peer_total 354
telemt_me_route_drop_no_conn_total 875306
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1803878
telemt_me_endpoint_quarantine_total 308
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 364
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
telemt_me_writers_active_current 44
telemt_desync_total 7714
telemt_desync_full_logged_total 2703
telemt_desync_suppressed_total 5011
telemt_desync_frames_bucket_total{bucket="1_2"} 1638
telemt_desync_frames_bucket_total{bucket="3_10"} 3005
telemt_desync_frames_bucket_total{bucket="gt_10"} 3071
telemt_pool_swap_total 50
telemt_pool_force_close_total 1479
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 195
telemt_me_draining_writers_reap_progress_total 16498
telemt_me_writer_removed_unexpected_total 334
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1357
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15372
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1398
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15019
telemt_me_writer_teardown_success_total{mode="normal"} 16729
telemt_me_writer_teardown_noop_total 16508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33237
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 34.246644
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33237
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 195
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 304
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 1800829
telemt_user_connections_current{user="hello"} 3963
telemt_user_octets_from_client{user="hello"} 27620602240 (25.72 GB)
telemt_user_octets_to_client{user="hello"} 708119593644 (659.49 GB)
telemt_user_unique_ips_current{user="hello"} 1422
telemt_user_unique_ips_recent_window{user="hello"} 657
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 46212.4 (12h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1928401
telemt_connections_bad_total 227187
telemt_connections_current 3301
telemt_connections_me_current 3301
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 81179
telemt_upstream_connect_attempt_total 23047
telemt_upstream_connect_success_total 22812
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 22937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10252
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 386
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 986
telemt_me_reconnect_success_total 431
telemt_me_reader_eof_total 398
telemt_me_idle_close_by_peer_total 398
telemt_me_route_drop_no_conn_total 549426
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1340339
telemt_me_endpoint_quarantine_total 329
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 367
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
telemt_me_writers_active_current 45
telemt_desync_total 6296
telemt_desync_full_logged_total 2152
telemt_desync_suppressed_total 4144
telemt_desync_frames_bucket_total{bucket="1_2"} 1556
telemt_desync_frames_bucket_total{bucket="3_10"} 2512
telemt_desync_frames_bucket_total{bucket="gt_10"} 2228
telemt_pool_swap_total 50
telemt_pool_force_close_total 1363
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 87
telemt_me_draining_writers_reap_progress_total 16364
telemt_me_writer_removed_unexpected_total 391
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1313
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15456
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1282
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15001
telemt_me_writer_teardown_success_total{mode="normal"} 16769
telemt_me_writer_teardown_noop_total 16365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33134
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.793826
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33134
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 87
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 361
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 1342413
telemt_user_connections_current{user="hello"} 3301
telemt_user_octets_from_client{user="hello"} 27633269669 (25.74 GB)
telemt_user_octets_to_client{user="hello"} 647689138239 (603.21 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1253
telemt_user_unique_ips_recent_window{user="hello"} 459
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 46176.4 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1859916
telemt_connections_bad_total 217353
telemt_connections_current 3084
telemt_connections_me_current 3084
telemt_handshake_timeouts_total 60159
telemt_upstream_connect_attempt_total 19092
telemt_upstream_connect_success_total 19067
telemt_upstream_connect_attempts_per_request{bucket="1"} 19067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10466
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 578
telemt_me_reconnect_success_total 399
telemt_me_reader_eof_total 359
telemt_me_idle_close_by_peer_total 359
telemt_me_route_drop_no_conn_total 513261
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1339487
telemt_me_endpoint_quarantine_total 359
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 357
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
telemt_me_writers_active_current 67
telemt_desync_total 6194
telemt_desync_full_logged_total 2174
telemt_desync_suppressed_total 4020
telemt_desync_frames_bucket_total{bucket="1_2"} 1620
telemt_desync_frames_bucket_total{bucket="3_10"} 2390
telemt_desync_frames_bucket_total{bucket="gt_10"} 2184
telemt_pool_swap_total 50
telemt_pool_force_close_total 1323
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 117
telemt_me_draining_writers_reap_progress_total 17175
telemt_me_writer_removed_unexpected_total 334
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1270
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16268
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1264
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 59
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15852
telemt_me_writer_teardown_success_total{mode="normal"} 17538
telemt_me_writer_teardown_noop_total 17178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34716
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.868414
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34716
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 117
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 352
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1337153
telemt_user_connections_current{user="hello"} 3084
telemt_user_octets_from_client{user="hello"} 31814610164 (29.63 GB)
telemt_user_octets_to_client{user="hello"} 665707048296 (619.99 GB)
telemt_user_unique_ips_current{user="hello"} 1155
telemt_user_unique_ips_recent_window{user="hello"} 448
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 46215.6 (12h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5378846
telemt_connections_bad_total 281649
telemt_connections_current 5266
telemt_connections_me_current 5266
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 222144
telemt_upstream_connect_attempt_total 45070
telemt_upstream_connect_success_total 43056
telemt_upstream_connect_fail_total 1380
telemt_upstream_connect_attempts_per_request{bucket="1"} 44436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12090
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1284
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1380
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 2555
telemt_me_reconnect_success_total 928
telemt_me_reader_eof_total 670
telemt_me_idle_close_by_peer_total 669
telemt_me_route_drop_no_conn_total 8618674
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4541531
telemt_me_endpoint_quarantine_total 367
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 364
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 9462
telemt_desync_full_logged_total 3123
telemt_desync_suppressed_total 6339
telemt_desync_frames_bucket_total{bucket="1_2"} 2087
telemt_desync_frames_bucket_total{bucket="3_10"} 4077
telemt_desync_frames_bucket_total{bucket="gt_10"} 3298
telemt_pool_swap_total 47
telemt_pool_force_close_total 1458
telemt_me_writer_close_signal_drop_total 261
telemt_me_draining_writers_reap_progress_total 15849
telemt_me_writer_removed_unexpected_total 894
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1959
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14711
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1252
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14391
telemt_me_writer_teardown_success_total{mode="normal"} 16670
telemt_me_writer_teardown_noop_total 15855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32525
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 35.613008
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32525
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 261
telemt_me_refill_failed_total 63
telemt_me_writer_restored_same_endpoint_total 659
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 4563382
telemt_user_connections_current{user="hello"} 5266
telemt_user_octets_from_client{user="hello"} 45477782406 (42.35 GB)
telemt_user_octets_to_client{user="hello"} 561164415622 (522.63 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1851
telemt_user_unique_ips_recent_window{user="hello"} 1087
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 46183.1 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1904962
telemt_connections_bad_total 245465
telemt_connections_current 3147
telemt_connections_me_current 3147
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 36867
telemt_upstream_connect_attempt_total 20572
telemt_upstream_connect_success_total 20367
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 20553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_reconnect_attempts_total 1913
telemt_me_reconnect_success_total 585
telemt_me_reader_eof_total 593
telemt_me_idle_close_by_peer_total 593
telemt_me_route_drop_no_conn_total 552459
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1423465
telemt_me_endpoint_quarantine_total 288
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 365
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
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
telemt_desync_total 6495
telemt_desync_full_logged_total 2368
telemt_desync_suppressed_total 4127
telemt_desync_frames_bucket_total{bucket="1_2"} 1276
telemt_desync_frames_bucket_total{bucket="3_10"} 2624
telemt_desync_frames_bucket_total{bucket="gt_10"} 2595
telemt_pool_swap_total 49
telemt_pool_force_close_total 1283
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 93
telemt_me_draining_writers_reap_progress_total 17050
telemt_me_writer_removed_unexpected_total 570
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1510
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16133
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1199
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 84
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15767
telemt_me_writer_teardown_success_total{mode="normal"} 17643
telemt_me_writer_teardown_noop_total 17050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34693
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.575204
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34693
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 93
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 488
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 1420115
telemt_user_connections_current{user="hello"} 3147
telemt_user_octets_from_client{user="hello"} 25511002668 (23.76 GB)
telemt_user_octets_to_client{user="hello"} 658657222358 (613.42 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1243
telemt_user_unique_ips_recent_window{user="hello"} 442
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 46177.7 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2610944
telemt_connections_bad_total 151967
telemt_connections_current 2846
telemt_connections_me_current 2846
telemt_handshake_timeouts_total 1043362
telemt_upstream_connect_attempt_total 19353
telemt_upstream_connect_success_total 19319
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 19322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 280
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 512
telemt_me_reconnect_success_total 293
telemt_me_reader_eof_total 294
telemt_me_idle_close_by_peer_total 294
telemt_me_route_drop_no_conn_total 492050
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1261320
telemt_me_endpoint_quarantine_total 361
telemt_me_single_endpoint_shadow_rotate_total 367
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
telemt_desync_total 6248
telemt_desync_full_logged_total 2203
telemt_desync_suppressed_total 4045
telemt_desync_frames_bucket_total{bucket="1_2"} 1102
telemt_desync_frames_bucket_total{bucket="3_10"} 2512
telemt_desync_frames_bucket_total{bucket="gt_10"} 2634
telemt_pool_swap_total 51
telemt_pool_force_close_total 1239
telemt_me_writer_close_signal_drop_total 99
telemt_me_draining_writers_reap_progress_total 17355
telemt_me_writer_removed_unexpected_total 284
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1098
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16560
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1222
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16116
telemt_me_writer_teardown_success_total{mode="normal"} 17658
telemt_me_writer_teardown_noop_total 17355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35013
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.868850
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35013
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 99
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 260
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1257122
telemt_user_connections_current{user="hello"} 2846
telemt_user_octets_from_client{user="hello"} 22229646880 (20.70 GB)
telemt_user_octets_to_client{user="hello"} 627022973912 (583.96 GB)
telemt_user_unique_ips_current{user="hello"} 1145
telemt_user_unique_ips_recent_window{user="hello"} 427
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 44169.2 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 556456
telemt_connections_bad_total 19834
telemt_connections_current 634
telemt_connections_me_current 634
telemt_handshake_timeouts_total 202517
telemt_upstream_connect_attempt_total 21656
telemt_upstream_connect_success_total 21654
telemt_upstream_connect_attempts_per_request{bucket="1"} 21654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 911
telemt_me_reconnect_success_total 360
telemt_me_reader_eof_total 357
telemt_me_idle_close_by_peer_total 357
telemt_me_route_drop_no_conn_total 118365
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 291542
telemt_me_endpoint_quarantine_total 426
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 376
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
telemt_me_writers_warm_current 22
telemt_desync_total 1859
telemt_desync_full_logged_total 747
telemt_desync_suppressed_total 1112
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 737
telemt_desync_frames_bucket_total{bucket="gt_10"} 768
telemt_pool_swap_total 48
telemt_pool_force_close_total 1034
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 64
telemt_me_draining_writers_reap_progress_total 19302
telemt_me_writer_removed_unexpected_total 338
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1386
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18258
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1032
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18268
telemt_me_writer_teardown_success_total{mode="normal"} 19644
telemt_me_writer_teardown_noop_total 19302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38946
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.794059
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38946
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 64
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 294
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 291702
telemt_user_connections_current{user="hello"} 634
telemt_user_octets_from_client{user="hello"} 4262751315 (3.97 GB)
telemt_user_octets_to_client{user="hello"} 115474457129 (107.54 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 46187.6 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1967210
telemt_connections_bad_total 171807
telemt_connections_current 3702
telemt_connections_me_current 3702
telemt_handshake_timeouts_total 49869
telemt_upstream_connect_attempt_total 20053
telemt_upstream_connect_success_total 19966
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 20023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9950
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 740
telemt_me_reconnect_success_total 430
telemt_me_reader_eof_total 398
telemt_me_idle_close_by_peer_total 398
telemt_me_route_drop_no_conn_total 480279
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1554373
telemt_me_endpoint_quarantine_total 367
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 367
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
telemt_desync_total 6169
telemt_desync_full_logged_total 2076
telemt_desync_suppressed_total 4093
telemt_desync_frames_bucket_total{bucket="1_2"} 1504
telemt_desync_frames_bucket_total{bucket="3_10"} 2330
telemt_desync_frames_bucket_total{bucket="gt_10"} 2335
telemt_pool_swap_total 51
telemt_pool_force_close_total 1256
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 115
telemt_me_draining_writers_reap_progress_total 18073
telemt_me_writer_removed_unexpected_total 397
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1334
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17145
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1233
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16817
telemt_me_writer_teardown_success_total{mode="normal"} 18479
telemt_me_writer_teardown_noop_total 18073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36552
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.368362
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36552
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 115
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 386
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1548916
telemt_user_connections_current{user="hello"} 3702
telemt_user_octets_from_client{user="hello"} 34956983972 (32.56 GB)
telemt_user_octets_to_client{user="hello"} 723188260316 (673.52 GB)
telemt_user_unique_ips_current{user="hello"} 1306
telemt_user_unique_ips_recent_window{user="hello"} 492
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 46184.3 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1855333
telemt_connections_bad_total 151219
telemt_connections_current 3508
telemt_connections_me_current 3508
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 45911
telemt_upstream_connect_attempt_total 28717
telemt_upstream_connect_success_total 28509
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 28675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10462
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_reconnect_attempts_total 2937
telemt_me_reconnect_success_total 594
telemt_me_reader_eof_total 520
telemt_me_idle_close_by_peer_total 520
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 497940
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1488643
telemt_me_endpoint_quarantine_total 419
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 365
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
telemt_me_writers_active_current 45
telemt_desync_total 5748
telemt_desync_full_logged_total 1912
telemt_desync_suppressed_total 3836
telemt_desync_frames_bucket_total{bucket="1_2"} 1588
telemt_desync_frames_bucket_total{bucket="3_10"} 2112
telemt_desync_frames_bucket_total{bucket="gt_10"} 2048
telemt_pool_swap_total 50
telemt_pool_force_close_total 1229
telemt_me_writer_close_signal_drop_total 106
telemt_me_draining_writers_reap_progress_total 17366
telemt_me_writer_removed_unexpected_total 528
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1587
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16333
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1153
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16137
telemt_me_writer_teardown_success_total{mode="normal"} 17920
telemt_me_writer_teardown_noop_total 17367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35287
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.345802
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35287
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 106
telemt_me_refill_failed_total 133
telemt_me_writer_restored_same_endpoint_total 459
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1492544
telemt_user_connections_current{user="hello"} 3508
telemt_user_octets_from_client{user="hello"} 23256172143 (21.66 GB)
telemt_user_octets_to_client{user="hello"} 662506434835 (617.01 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1321
telemt_user_unique_ips_recent_window{user="hello"} 475
```
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

# Server Metrics 2026-03-21 11:59:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 55407.7 (15h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1716366
telemt_connections_bad_total 87297
telemt_connections_current 1728
telemt_connections_me_current 1728
telemt_handshake_timeouts_total 67841
telemt_upstream_connect_attempt_total 21633
telemt_upstream_connect_success_total 21525
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 21595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13813
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 1098
telemt_me_reconnect_success_total 489
telemt_me_reader_eof_total 474
telemt_me_idle_close_by_peer_total 474
telemt_me_route_drop_no_conn_total 1067468
telemt_me_route_drop_channel_closed_total 415
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1327905
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 389
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 439
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 5331
telemt_desync_full_logged_total 1888
telemt_desync_suppressed_total 3443
telemt_desync_frames_bucket_total{bucket="1_2"} 1136
telemt_desync_frames_bucket_total{bucket="3_10"} 2048
telemt_desync_frames_bucket_total{bucket="gt_10"} 2147
telemt_pool_swap_total 60
telemt_pool_force_close_total 1757
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 327
telemt_me_draining_writers_reap_progress_total 19324
telemt_me_writer_removed_unexpected_total 454
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1591
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18046
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1693
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 64
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17567
telemt_me_writer_teardown_success_total{mode="normal"} 19637
telemt_me_writer_teardown_noop_total 19328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38965
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 133.773672
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38965
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 327
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 427
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1326913
telemt_user_connections_current{user="hello"} 1728
telemt_user_octets_from_client{user="hello"} 18994843807 (17.69 GB)
telemt_user_octets_to_client{user="hello"} 361086743771 (336.29 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 625
telemt_user_unique_ips_recent_window{user="hello"} 293
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 1053.0 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59733
telemt_connections_bad_total 5416
telemt_connections_current 2512
telemt_connections_me_current 2512
telemt_handshake_timeouts_total 1900
telemt_upstream_connect_attempt_total 442
telemt_upstream_connect_success_total 426
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 31
telemt_me_reconnect_success_total 10
telemt_me_reader_eof_total 8
telemt_me_idle_close_by_peer_total 8
telemt_me_route_drop_no_conn_total 24868
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48088
telemt_me_endpoint_quarantine_total 16
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 12
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
telemt_me_writers_active_current 39
telemt_desync_total 210
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 1
telemt_pool_force_close_total 2
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 297
telemt_me_writer_removed_unexpected_total 8
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 283
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 295
telemt_me_writer_teardown_success_total{mode="normal"} 305
telemt_me_writer_teardown_noop_total 297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 602
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.112767
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 602
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_writer_restored_same_endpoint_total 8
telemt_user_connections_total{user="hello"} 48086
telemt_user_connections_current{user="hello"} 2512
telemt_user_octets_from_client{user="hello"} 666434216 (635.56 MB)
telemt_user_octets_to_client{user="hello"} 13229536308 (12.32 GB)
telemt_user_unique_ips_current{user="hello"} 1353
telemt_user_unique_ips_recent_window{user="hello"} 566
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 55405.6 (15h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3302571
telemt_connections_bad_total 356072
telemt_connections_current 3646
telemt_connections_me_current 3646
telemt_handshake_timeouts_total 121588
telemt_upstream_connect_attempt_total 20970
telemt_upstream_connect_success_total 20957
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 20958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11409
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 730
telemt_me_reconnect_success_total 391
telemt_me_reader_eof_total 404
telemt_me_idle_close_by_peer_total 404
telemt_me_route_drop_no_conn_total 1424168
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2632688
telemt_me_endpoint_quarantine_total 361
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 427
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
telemt_desync_total 11538
telemt_desync_full_logged_total 3892
telemt_desync_suppressed_total 7646
telemt_desync_frames_bucket_total{bucket="1_2"} 2430
telemt_desync_frames_bucket_total{bucket="3_10"} 4486
telemt_desync_frames_bucket_total{bucket="gt_10"} 4622
telemt_pool_swap_total 60
telemt_pool_force_close_total 1857
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 260
telemt_me_draining_writers_reap_progress_total 19097
telemt_me_writer_removed_unexpected_total 381
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1570
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17748
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 14
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1757
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 100
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17240
telemt_me_writer_teardown_success_total{mode="normal"} 19318
telemt_me_writer_teardown_noop_total 19111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38429
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.084253
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38429
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 260
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 347
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 2629034
telemt_user_connections_current{user="hello"} 3646
telemt_user_octets_from_client{user="hello"} 43305190072 (40.33 GB)
telemt_user_octets_to_client{user="hello"} 954400536692 (888.85 GB)
telemt_user_unique_ips_current{user="hello"} 1428
telemt_user_unique_ips_recent_window{user="hello"} 577
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 55406.8 (15h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2749739
telemt_connections_bad_total 306235
telemt_connections_current 3213
telemt_connections_me_current 3213
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 112562
telemt_upstream_connect_attempt_total 25893
telemt_upstream_connect_success_total 25629
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 25760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11730
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 453
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 1079
telemt_me_reconnect_success_total 506
telemt_me_reader_eof_total 468
telemt_me_idle_close_by_peer_total 468
telemt_me_route_drop_no_conn_total 820205
telemt_me_route_drop_channel_closed_total 68
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1944070
telemt_me_endpoint_quarantine_total 371
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 427
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
telemt_me_writers_active_current 42
telemt_desync_total 8890
telemt_desync_full_logged_total 3041
telemt_desync_suppressed_total 5849
telemt_desync_frames_bucket_total{bucket="1_2"} 2223
telemt_desync_frames_bucket_total{bucket="3_10"} 3468
telemt_desync_frames_bucket_total{bucket="gt_10"} 3199
telemt_pool_swap_total 60
telemt_pool_force_close_total 1672
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 139
telemt_me_draining_writers_reap_progress_total 18788
telemt_me_writer_removed_unexpected_total 458
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1580
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17684
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1561
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 111
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17116
telemt_me_writer_teardown_success_total{mode="normal"} 19264
telemt_me_writer_teardown_noop_total 18789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38053
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.860732
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38053
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 139
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 425
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1945423
telemt_user_connections_current{user="hello"} 3213
telemt_user_octets_from_client{user="hello"} 36869511393 (34.34 GB)
telemt_user_octets_to_client{user="hello"} 930353808175 (866.46 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1219
telemt_user_unique_ips_recent_window{user="hello"} 498
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 55370.5 (15h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2675214
telemt_connections_bad_total 300927
telemt_connections_current 3627
telemt_connections_me_current 3627
telemt_handshake_timeouts_total 79654
telemt_upstream_connect_attempt_total 22426
telemt_upstream_connect_success_total 22344
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12153
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 836
telemt_me_reconnect_success_total 580
telemt_me_reader_eof_total 522
telemt_me_idle_close_by_peer_total 522
telemt_me_route_drop_no_conn_total 795864
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1934896
telemt_me_endpoint_quarantine_total 416
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 421
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_me_writers_active_current 83
telemt_desync_total 9022
telemt_desync_full_logged_total 3038
telemt_desync_suppressed_total 5984
telemt_desync_frames_bucket_total{bucket="1_2"} 2396
telemt_desync_frames_bucket_total{bucket="3_10"} 3431
telemt_desync_frames_bucket_total{bucket="gt_10"} 3195
telemt_pool_swap_total 58
telemt_pool_force_close_total 1617
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 175
telemt_me_draining_writers_reap_progress_total 19970
telemt_me_writer_removed_unexpected_total 501
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1645
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18859
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1496
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 121
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18353
telemt_me_writer_teardown_success_total{mode="normal"} 20504
telemt_me_writer_teardown_noop_total 19973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40477
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.006736
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40477
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 175
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 506
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1932009
telemt_user_connections_current{user="hello"} 3627
telemt_user_octets_from_client{user="hello"} 43573892388 (40.58 GB)
telemt_user_octets_to_client{user="hello"} 936254226644 (871.95 GB)
telemt_user_unique_ips_current{user="hello"} 1464
telemt_user_unique_ips_recent_window{user="hello"} 510
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 55409.9 (15h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8662576
telemt_connections_bad_total 579029
telemt_connections_current 4619
telemt_connections_me_current 4619
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 301338
telemt_upstream_connect_attempt_total 88255
telemt_upstream_connect_success_total 83108
telemt_upstream_connect_fail_total 4321
telemt_upstream_connect_attempts_per_request{bucket="1"} 87429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4321
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3402
telemt_me_reconnect_success_total 1147
telemt_me_reader_eof_total 804
telemt_me_idle_close_by_peer_total 803
telemt_me_route_drop_no_conn_total 15414899
telemt_me_route_drop_channel_closed_total 56
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7183181
telemt_me_endpoint_quarantine_total 434
telemt_me_single_endpoint_outage_enter_total 66
telemt_me_single_endpoint_outage_exit_total 66
telemt_me_single_endpoint_outage_reconnect_attempt_total 151
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 151
telemt_me_single_endpoint_shadow_rotate_total 440
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
telemt_desync_total 13581
telemt_desync_full_logged_total 4381
telemt_desync_suppressed_total 9200
telemt_desync_frames_bucket_total{bucket="1_2"} 2925
telemt_desync_frames_bucket_total{bucket="3_10"} 6002
telemt_desync_frames_bucket_total{bucket="gt_10"} 4654
telemt_pool_swap_total 56
telemt_pool_force_close_total 1755
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 367
telemt_me_draining_writers_reap_progress_total 18334
telemt_me_writer_removed_unexpected_total 1114
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2387
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16957
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1503
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 252
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16579
telemt_me_writer_teardown_success_total{mode="normal"} 19344
telemt_me_writer_teardown_noop_total 18343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37687
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.017512
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37687
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 367
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 792
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 7241271
telemt_user_connections_current{user="hello"} 4619
telemt_user_octets_from_client{user="hello"} 58406989605 (54.40 GB)
telemt_user_octets_to_client{user="hello"} 662039836400 (616.57 GB)
telemt_user_msgs_from_client{user="hello"} 173886
telemt_user_msgs_to_client{user="hello"} 472410
telemt_user_unique_ips_current{user="hello"} 1710
telemt_user_unique_ips_recent_window{user="hello"} 917
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 55377.6 (15h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2715746
telemt_connections_bad_total 333821
telemt_connections_current 3734
telemt_connections_me_current 3734
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 60033
telemt_upstream_connect_attempt_total 23842
telemt_upstream_connect_success_total 23579
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 23817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12197
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_reconnect_attempts_total 2346
telemt_me_reconnect_success_total 772
telemt_me_reader_eof_total 767
telemt_me_idle_close_by_peer_total 767
telemt_me_route_drop_no_conn_total 941749
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2048796
telemt_me_endpoint_quarantine_total 348
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 426
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
telemt_me_writers_active_current 44
telemt_desync_total 9379
telemt_desync_full_logged_total 3353
telemt_desync_suppressed_total 6026
telemt_desync_frames_bucket_total{bucket="1_2"} 1843
telemt_desync_frames_bucket_total{bucket="3_10"} 3755
telemt_desync_frames_bucket_total{bucket="gt_10"} 3781
telemt_pool_swap_total 57
telemt_pool_force_close_total 1578
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 137
telemt_me_draining_writers_reap_progress_total 19845
telemt_me_writer_removed_unexpected_total 741
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1863
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18749
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1421
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 157
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18267
telemt_me_writer_teardown_success_total{mode="normal"} 20612
telemt_me_writer_teardown_noop_total 19845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40457
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.209123
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40457
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 137
telemt_me_refill_failed_total 86
telemt_me_writer_restored_same_endpoint_total 648
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 2033898
telemt_user_connections_current{user="hello"} 3734
telemt_user_octets_from_client{user="hello"} 37563306440 (34.98 GB)
telemt_user_octets_to_client{user="hello"} 904012825146 (841.93 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1439
telemt_user_unique_ips_recent_window{user="hello"} 543
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 55372.0 (15h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3993925
telemt_connections_bad_total 207753
telemt_connections_current 3128
telemt_connections_me_current 3128
telemt_handshake_timeouts_total 1727946
telemt_upstream_connect_attempt_total 22326
telemt_upstream_connect_success_total 22292
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 22295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11999
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 287
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 802
telemt_me_reconnect_success_total 399
telemt_me_reader_eof_total 398
telemt_me_idle_close_by_peer_total 398
telemt_me_route_drop_no_conn_total 779996
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1812928
telemt_me_endpoint_quarantine_total 423
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 438
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_desync_total 8891
telemt_desync_full_logged_total 3164
telemt_desync_suppressed_total 5727
telemt_desync_frames_bucket_total{bucket="1_2"} 1633
telemt_desync_frames_bucket_total{bucket="3_10"} 3557
telemt_desync_frames_bucket_total{bucket="gt_10"} 3701
telemt_pool_swap_total 60
telemt_pool_force_close_total 1523
telemt_me_writer_close_signal_drop_total 127
telemt_me_draining_writers_reap_progress_total 19980
telemt_me_writer_removed_unexpected_total 386
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1345
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19042
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1471
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 52
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18457
telemt_me_writer_teardown_success_total{mode="normal"} 20387
telemt_me_writer_teardown_noop_total 19980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40367
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.114150
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40367
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 127
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 350
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 1806618
telemt_user_connections_current{user="hello"} 3128
telemt_user_octets_from_client{user="hello"} 33203866660 (30.92 GB)
telemt_user_octets_to_client{user="hello"} 872523029076 (812.60 GB)
telemt_user_unique_ips_current{user="hello"} 1287
telemt_user_unique_ips_recent_window{user="hello"} 488
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 53363.4 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 839414
telemt_connections_bad_total 60263
telemt_connections_current 685
telemt_connections_me_current 685
telemt_handshake_timeouts_total 305966
telemt_upstream_connect_attempt_total 25592
telemt_upstream_connect_success_total 25590
telemt_upstream_connect_attempts_per_request{bucket="1"} 25590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14924
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1089
telemt_me_reconnect_success_total 421
telemt_me_reader_eof_total 416
telemt_me_idle_close_by_peer_total 416
telemt_me_route_drop_no_conn_total 179690
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 410067
telemt_me_endpoint_quarantine_total 494
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 456
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
telemt_me_writers_active_current 44
telemt_desync_total 2852
telemt_desync_full_logged_total 1084
telemt_desync_suppressed_total 1768
telemt_desync_frames_bucket_total{bucket="1_2"} 465
telemt_desync_frames_bucket_total{bucket="3_10"} 1031
telemt_desync_frames_bucket_total{bucket="gt_10"} 1356
telemt_pool_swap_total 59
telemt_pool_force_close_total 1317
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 88
telemt_me_draining_writers_reap_progress_total 22935
telemt_me_writer_removed_unexpected_total 396
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1671
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21665
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1314
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21618
telemt_me_writer_teardown_success_total{mode="normal"} 23336
telemt_me_writer_teardown_noop_total 22935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46271
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.666329
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46271
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 88
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 341
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 409932
telemt_user_connections_current{user="hello"} 685
telemt_user_octets_from_client{user="hello"} 6549135927 (6.10 GB)
telemt_user_octets_to_client{user="hello"} 157272424253 (146.47 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 55381.9 (15h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2864866
telemt_connections_bad_total 266958
telemt_connections_current 4038
telemt_connections_me_current 4038
telemt_handshake_timeouts_total 77588
telemt_upstream_connect_attempt_total 23194
telemt_upstream_connect_success_total 23096
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 23163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11558
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_reconnect_attempts_total 955
telemt_me_reconnect_success_total 532
telemt_me_reader_eof_total 496
telemt_me_idle_close_by_peer_total 496
telemt_me_route_drop_no_conn_total 763861
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2270438
telemt_me_endpoint_quarantine_total 429
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 434
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
telemt_desync_total 9104
telemt_desync_full_logged_total 3006
telemt_desync_suppressed_total 6098
telemt_desync_frames_bucket_total{bucket="1_2"} 2171
telemt_desync_frames_bucket_total{bucket="3_10"} 3394
telemt_desync_frames_bucket_total{bucket="gt_10"} 3539
telemt_pool_swap_total 61
telemt_pool_force_close_total 1535
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 163
telemt_me_draining_writers_reap_progress_total 20826
telemt_me_writer_removed_unexpected_total 487
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1611
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19719
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1508
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19291
telemt_me_writer_teardown_success_total{mode="normal"} 21330
telemt_me_writer_teardown_noop_total 20826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42156
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.586096
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42156
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 163
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 474
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 2263745
telemt_user_connections_current{user="hello"} 4038
telemt_user_octets_from_client{user="hello"} 47844334748 (44.56 GB)
telemt_user_octets_to_client{user="hello"} 1056712401260 (984.14 GB)
telemt_user_unique_ips_current{user="hello"} 1451
telemt_user_unique_ips_recent_window{user="hello"} 596
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 55378.5 (15h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2622670
telemt_connections_bad_total 208627
telemt_connections_current 3844
telemt_connections_me_current 3844
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 72733
telemt_upstream_connect_attempt_total 39328
telemt_upstream_connect_success_total 39082
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 39285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13165
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 585
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_reconnect_attempts_total 3256
telemt_me_reconnect_success_total 680
telemt_me_reader_eof_total 594
telemt_me_idle_close_by_peer_total 594
telemt_me_seq_mismatch_total 28
telemt_me_route_drop_no_conn_total 768790
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2108664
telemt_me_endpoint_quarantine_total 480
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 431
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
telemt_me_writers_active_current 45
telemt_desync_total 7995
telemt_desync_full_logged_total 2737
telemt_desync_suppressed_total 5258
telemt_desync_frames_bucket_total{bucket="1_2"} 2082
telemt_desync_frames_bucket_total{bucket="3_10"} 2973
telemt_desync_frames_bucket_total{bucket="gt_10"} 2940
telemt_pool_swap_total 60
telemt_pool_force_close_total 1488
telemt_me_writer_close_signal_drop_total 138
telemt_me_draining_writers_reap_progress_total 19980
telemt_me_writer_removed_unexpected_total 606
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1873
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18741
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1396
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 92
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18492
telemt_me_writer_teardown_success_total{mode="normal"} 20614
telemt_me_writer_teardown_noop_total 19981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40595
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.324664
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40595
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 138
telemt_me_refill_failed_total 146
telemt_me_writer_restored_same_endpoint_total 516
telemt_me_writer_restored_fallback_total 37
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 2119264
telemt_user_connections_current{user="hello"} 3844
telemt_user_octets_from_client{user="hello"} 38499453685 (35.86 GB)
telemt_user_octets_to_client{user="hello"} 932881463936 (868.81 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1418
telemt_user_unique_ips_recent_window{user="hello"} 557
```
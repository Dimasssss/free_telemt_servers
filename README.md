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

# Server Metrics 2026-03-23 00:04:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 97107.2 (26h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3434437
telemt_connections_bad_total 289359
telemt_connections_current 862
telemt_connections_me_current 862
telemt_handshake_timeouts_total 107729
telemt_upstream_connect_attempt_total 35886
telemt_upstream_connect_success_total 35885
telemt_upstream_connect_attempts_per_request{bucket="1"} 35885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23323
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1373
telemt_me_reconnect_success_total 581
telemt_me_reader_eof_total 597
telemt_me_idle_close_by_peer_total 597
telemt_me_route_drop_no_conn_total 2974337
telemt_me_route_drop_channel_closed_total 1230
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2850980
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 669
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 753
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_me_writers_active_current 46
telemt_desync_total 12254
telemt_desync_full_logged_total 3839
telemt_desync_suppressed_total 8415
telemt_desync_frames_bucket_total{bucket="1_2"} 3317
telemt_desync_frames_bucket_total{bucket="3_10"} 4457
telemt_desync_frames_bucket_total{bucket="gt_10"} 4480
telemt_pool_swap_total 107
telemt_pool_force_close_total 3324
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 646
telemt_me_draining_writers_reap_progress_total 32857
telemt_me_writer_removed_unexpected_total 576
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2386
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30694
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3268
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29533
telemt_me_writer_teardown_success_total{mode="normal"} 33080
telemt_me_writer_teardown_noop_total 32868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65948
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 375.335986
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65948
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 646
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 519
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2840217
telemt_user_connections_current{user="hello"} 862
telemt_user_octets_from_client{user="hello"} 40730296400 (37.93 GB)
telemt_user_octets_to_client{user="hello"} 776708750272 (723.37 GB)
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 110472.9 (30h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3978990
telemt_connections_bad_total 362964
telemt_connections_current 360
telemt_connections_me_current 360
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100318
telemt_upstream_connect_attempt_total 68295
telemt_upstream_connect_success_total 67473
telemt_upstream_connect_fail_total 729
telemt_upstream_connect_attempts_per_request{bucket="1"} 68202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29601
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 729
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9798
telemt_me_reconnect_success_total 3542
telemt_me_reader_eof_total 3546
telemt_me_idle_close_by_peer_total 3546
telemt_me_route_drop_no_conn_total 3638917
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3164255
telemt_me_endpoint_quarantine_total 852
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 859
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
telemt_me_writers_active_current 44
telemt_desync_total 12915
telemt_desync_full_logged_total 7237
telemt_desync_suppressed_total 5678
telemt_desync_frames_bucket_total{bucket="1_2"} 2933
telemt_desync_frames_bucket_total{bucket="3_10"} 5062
telemt_desync_frames_bucket_total{bucket="gt_10"} 4920
telemt_pool_swap_total 102
telemt_pool_force_close_total 3014
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 245
telemt_me_draining_writers_reap_progress_total 44936
telemt_me_writer_removed_unexpected_total 3480
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6025
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42420
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2556
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41922
telemt_me_writer_teardown_success_total{mode="normal"} 48445
telemt_me_writer_teardown_noop_total 44937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93382
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.560422
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93382
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 245
telemt_me_refill_failed_total 240
telemt_me_writer_restored_same_endpoint_total 3180
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 3176736
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 42901370362 (39.96 GB)
telemt_user_octets_to_client{user="hello"} 788302720284 (734.16 GB)
telemt_user_msgs_from_client{user="hello"} 47428
telemt_user_msgs_to_client{user="hello"} 180951
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 185332.8 (51h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16291179
telemt_connections_bad_total 1639677
telemt_connections_current 1047
telemt_connections_me_current 1047
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396804
telemt_upstream_connect_attempt_total 82689
telemt_upstream_connect_success_total 82586
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 82603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40257
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1709
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2969
telemt_me_reconnect_success_total 1547
telemt_me_reader_eof_total 1493
telemt_me_idle_close_by_peer_total 1491
telemt_me_route_drop_no_conn_total 14040154
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12941395
telemt_me_endpoint_quarantine_total 1213
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1389
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 53621
telemt_desync_full_logged_total 17008
telemt_desync_suppressed_total 36613
telemt_desync_frames_bucket_total{bucket="1_2"} 11942
telemt_desync_frames_bucket_total{bucket="3_10"} 20904
telemt_desync_frames_bucket_total{bucket="gt_10"} 20775
telemt_pool_swap_total 200
telemt_pool_force_close_total 6623
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1055
telemt_me_draining_writers_reap_progress_total 62275
telemt_me_writer_removed_unexpected_total 1439
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5356
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57631
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6153
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55652
telemt_me_writer_teardown_success_total{mode="normal"} 62987
telemt_me_writer_teardown_noop_total 62328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125315
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.535906
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125315
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1055
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1338
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 12941460
telemt_user_connections_current{user="hello"} 1047
telemt_user_octets_from_client{user="hello"} 190849379281 (177.74 GB)
telemt_user_octets_to_client{user="hello"} 3481035479519 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 485
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 185334.1 (51h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11832287
telemt_connections_bad_total 1223888
telemt_connections_current 582
telemt_connections_me_current 582
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344379
telemt_upstream_connect_attempt_total 97077
telemt_upstream_connect_success_total 95763
telemt_upstream_connect_fail_total 865
telemt_upstream_connect_attempts_per_request{bucket="1"} 96628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40147
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3798
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 865
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4362
telemt_me_reconnect_success_total 1849
telemt_me_reader_eof_total 1714
telemt_me_idle_close_by_peer_total 1714
telemt_me_route_drop_no_conn_total 4550655
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8788985
telemt_me_endpoint_quarantine_total 1219
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1412
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_me_writers_active_current 45
telemt_desync_total 38673
telemt_desync_full_logged_total 13016
telemt_desync_suppressed_total 25657
telemt_desync_frames_bucket_total{bucket="1_2"} 9573
telemt_desync_frames_bucket_total{bucket="3_10"} 14857
telemt_desync_frames_bucket_total{bucket="gt_10"} 14243
telemt_pool_swap_total 197
telemt_pool_force_close_total 5982
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 707
telemt_me_draining_writers_reap_progress_total 60538
telemt_me_writer_removed_unexpected_total 1745
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5469
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56669
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5470
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54556
telemt_me_writer_teardown_success_total{mode="normal"} 62138
telemt_me_writer_teardown_noop_total 60563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122701
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.376337
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122701
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 707
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1580
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 8726777
telemt_user_connections_current{user="hello"} 582
telemt_user_octets_from_client{user="hello"} 217636251848 (202.69 GB)
telemt_user_octets_to_client{user="hello"} 3950224636415 (3.59 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 185298.6 (51h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11020235
telemt_connections_bad_total 967721
telemt_connections_current 455
telemt_connections_me_current 455
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345349
telemt_upstream_connect_attempt_total 81341
telemt_upstream_connect_success_total 79784
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 79989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38594
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2023
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5693
telemt_me_reconnect_success_total 2337
telemt_me_reader_eof_total 2079
telemt_me_idle_close_by_peer_total 2078
telemt_me_route_drop_no_conn_total 5332936
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8334681
telemt_me_endpoint_quarantine_total 1294
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1368
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_me_writers_active_current 45
telemt_desync_total 37980
telemt_desync_full_logged_total 12593
telemt_desync_suppressed_total 25387
telemt_desync_frames_bucket_total{bucket="1_2"} 9596
telemt_desync_frames_bucket_total{bucket="3_10"} 14523
telemt_desync_frames_bucket_total{bucket="gt_10"} 13861
telemt_pool_swap_total 193
telemt_pool_force_close_total 5883
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 737
telemt_me_draining_writers_reap_progress_total 60906
telemt_me_writer_removed_unexpected_total 2231
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6216
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56851
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5312
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55023
telemt_me_writer_teardown_success_total{mode="normal"} 63067
telemt_me_writer_teardown_noop_total 60977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 124044
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.671721
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 124044
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 737
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 2028
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8326660
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 192524270859 (179.30 GB)
telemt_user_octets_to_client{user="hello"} 3460781092141 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 55578.2 (15h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11180650
telemt_connections_bad_total 668114
telemt_connections_current 974
telemt_connections_me_current 974
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 264289
telemt_upstream_connect_attempt_total 55340
telemt_upstream_connect_success_total 52498
telemt_upstream_connect_fail_total 1901
telemt_upstream_connect_attempts_per_request{bucket="1"} 54399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17861
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6005
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1901
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7461
telemt_me_reconnect_success_total 1156
telemt_me_reader_eof_total 731
telemt_me_idle_close_by_peer_total 730
telemt_me_route_drop_no_conn_total 25278587
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9286282
telemt_me_endpoint_quarantine_total 400
telemt_me_single_endpoint_outage_enter_total 85
telemt_me_single_endpoint_outage_exit_total 85
telemt_me_single_endpoint_outage_reconnect_attempt_total 158
telemt_me_single_endpoint_outage_reconnect_success_total 42
telemt_me_single_endpoint_quarantine_bypass_total 158
telemt_me_single_endpoint_shadow_rotate_total 438
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
telemt_me_writers_active_current 45
telemt_desync_total 16246
telemt_desync_full_logged_total 4403
telemt_desync_suppressed_total 11843
telemt_desync_frames_bucket_total{bucket="1_2"} 3085
telemt_desync_frames_bucket_total{bucket="3_10"} 6597
telemt_desync_frames_bucket_total{bucket="gt_10"} 6564
telemt_pool_swap_total 57
telemt_pool_force_close_total 1914
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 472
telemt_me_draining_writers_reap_progress_total 17011
telemt_me_writer_removed_unexpected_total 1047
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2340
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15659
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1607
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15097
telemt_me_writer_teardown_success_total{mode="normal"} 17999
telemt_me_writer_teardown_noop_total 17030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35029
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.542728
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35029
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 472
telemt_me_refill_failed_total 336
telemt_me_writer_restored_same_endpoint_total 753
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 9311735
telemt_user_connections_current{user="hello"} 974
telemt_user_octets_from_client{user="hello"} 86552182494 (80.61 GB)
telemt_user_octets_to_client{user="hello"} 596449284321 (555.49 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 410
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 185304.7 (51h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10956892
telemt_connections_bad_total 942150
telemt_connections_current 699
telemt_connections_me_current 699
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241695
telemt_upstream_connect_attempt_total 110207
telemt_upstream_connect_success_total 109070
telemt_upstream_connect_fail_total 965
telemt_upstream_connect_attempts_per_request{bucket="1"} 110035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42164
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 965
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72819
telemt_me_reconnect_success_total 3027
telemt_me_reader_eof_total 2719
telemt_me_idle_close_by_peer_total 2717
telemt_me_route_drop_no_conn_total 5255711
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8647119
telemt_me_endpoint_quarantine_total 1232
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 43
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 43
telemt_me_single_endpoint_shadow_rotate_total 1396
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_me_writers_active_current 47
telemt_desync_total 46114
telemt_desync_full_logged_total 15784
telemt_desync_suppressed_total 30330
telemt_desync_frames_bucket_total{bucket="1_2"} 9369
telemt_desync_frames_bucket_total{bucket="3_10"} 17653
telemt_desync_frames_bucket_total{bucket="gt_10"} 19092
telemt_pool_swap_total 189
telemt_pool_force_close_total 5585
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 65028
telemt_me_writer_removed_unexpected_total 2750
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6716
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61095
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4836
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59443
telemt_me_writer_teardown_success_total{mode="normal"} 67811
telemt_me_writer_teardown_noop_total 65029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 132796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 132830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 132833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 132833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 132836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 132840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 132840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 132840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 132840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 132840
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.216137
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 132840
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2558
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8650164
telemt_user_connections_current{user="hello"} 699
telemt_user_octets_from_client{user="hello"} 194271364749 (180.93 GB)
telemt_user_octets_to_client{user="hello"} 3301400690412 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 122141.0 (33h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11651590
telemt_connections_bad_total 476309
telemt_connections_current 533
telemt_connections_me_current 533
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4759255
telemt_upstream_connect_attempt_total 58358
telemt_upstream_connect_success_total 57934
telemt_upstream_connect_fail_total 413
telemt_upstream_connect_attempts_per_request{bucket="1"} 58347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 413
telemt_me_reconnect_attempts_total 48825
telemt_me_reconnect_success_total 1772
telemt_me_reader_eof_total 1443
telemt_me_idle_close_by_peer_total 1442
telemt_me_route_drop_no_conn_total 4082095
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5597085
telemt_me_endpoint_quarantine_total 817
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 933
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 31476
telemt_desync_full_logged_total 10724
telemt_desync_suppressed_total 20752
telemt_desync_frames_bucket_total{bucket="1_2"} 6266
telemt_desync_frames_bucket_total{bucket="3_10"} 12414
telemt_desync_frames_bucket_total{bucket="gt_10"} 12796
telemt_pool_swap_total 129
telemt_pool_force_close_total 3823
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 44118
telemt_me_writer_removed_unexpected_total 1494
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3683
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41972
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3382
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40295
telemt_me_writer_teardown_success_total{mode="normal"} 45655
telemt_me_writer_teardown_noop_total 44125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89780
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.675413
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89780
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 2734
telemt_me_writer_restored_same_endpoint_total 1574
telemt_me_writer_restored_fallback_total 23
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5589660
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 118902649056 (110.74 GB)
telemt_user_octets_to_client{user="hello"} 2163547248258 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 103111.8 (28h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1499771
telemt_connections_bad_total 36652
telemt_connections_current 481
telemt_connections_me_current 481
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29976
telemt_upstream_connect_attempt_total 48252
telemt_upstream_connect_success_total 48100
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 48224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 782
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2167
telemt_me_reconnect_success_total 884
telemt_me_reader_eof_total 865
telemt_me_idle_close_by_peer_total 865
telemt_me_route_drop_no_conn_total 513751
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1332273
telemt_me_endpoint_quarantine_total 836
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 852
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 8649
telemt_desync_full_logged_total 2566
telemt_desync_suppressed_total 6083
telemt_desync_frames_bucket_total{bucket="1_2"} 2320
telemt_desync_frames_bucket_total{bucket="3_10"} 3323
telemt_desync_frames_bucket_total{bucket="gt_10"} 3006
telemt_pool_swap_total 111
telemt_pool_force_close_total 2870
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 160
telemt_me_draining_writers_reap_progress_total 40667
telemt_me_writer_removed_unexpected_total 836
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3162
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38377
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2782
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37797
telemt_me_writer_teardown_success_total{mode="normal"} 41539
telemt_me_writer_teardown_noop_total 40671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82210
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.162151
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82210
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 160
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 749
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 1328113
telemt_user_connections_current{user="hello"} 481
telemt_user_octets_from_client{user="hello"} 25801244525 (24.03 GB)
telemt_user_octets_to_client{user="hello"} 570605727491 (531.42 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 185309.4 (51h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13287183
telemt_connections_bad_total 1590856
telemt_connections_current 618
telemt_connections_me_current 618
telemt_handshake_timeouts_total 386815
telemt_upstream_connect_attempt_total 72087
telemt_upstream_connect_success_total 71742
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 71951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36140
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2894
telemt_me_reconnect_success_total 1445
telemt_me_reader_eof_total 1429
telemt_me_idle_close_by_peer_total 1429
telemt_me_route_drop_no_conn_total 4479115
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10024366
telemt_me_endpoint_quarantine_total 1290
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1397
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 41925
telemt_desync_full_logged_total 13688
telemt_desync_suppressed_total 28237
telemt_desync_frames_bucket_total{bucket="1_2"} 10107
telemt_desync_frames_bucket_total{bucket="3_10"} 15413
telemt_desync_frames_bucket_total{bucket="gt_10"} 16405
telemt_pool_swap_total 205
telemt_pool_force_close_total 5520
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 673
telemt_me_draining_writers_reap_progress_total 65101
telemt_me_writer_removed_unexpected_total 1368
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5172
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61348
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5346
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59581
telemt_me_writer_teardown_success_total{mode="normal"} 66520
telemt_me_writer_teardown_noop_total 65103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 129021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 130731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 131114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 131490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 131610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 131623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 131623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 131623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 131623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 131623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 131623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 131623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 131623
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.740271
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 131623
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 673
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1267
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 9991099
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 194439014224 (181.09 GB)
telemt_user_octets_to_client{user="hello"} 4432089406756 (4.03 TB)
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 185305.8 (51h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11584589
telemt_connections_bad_total 1337589
telemt_connections_current 516
telemt_connections_me_current 516
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 309731
telemt_upstream_connect_attempt_total 98797
telemt_upstream_connect_success_total 97922
telemt_upstream_connect_fail_total 667
telemt_upstream_connect_attempts_per_request{bucket="1"} 98589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41746
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 667
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10323
telemt_me_reconnect_success_total 2535
telemt_me_reader_eof_total 2354
telemt_me_idle_close_by_peer_total 2353
telemt_me_seq_mismatch_total 93
telemt_me_route_drop_no_conn_total 5639684
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8930712
telemt_me_endpoint_quarantine_total 1472
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 1399
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 41662
telemt_desync_full_logged_total 13385
telemt_desync_suppressed_total 28277
telemt_desync_frames_bucket_total{bucket="1_2"} 10745
telemt_desync_frames_bucket_total{bucket="3_10"} 15310
telemt_desync_frames_bucket_total{bucket="gt_10"} 15607
telemt_pool_swap_total 195
telemt_pool_force_close_total 5313
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 65107
telemt_me_writer_removed_unexpected_total 2393
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6534
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61049
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4842
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59794
telemt_me_writer_teardown_success_total{mode="normal"} 67583
telemt_me_writer_teardown_noop_total 65112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 132645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 132695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 132695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 132695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 132695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 132695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 132695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 132695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 132695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 132695
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.438126
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 132695
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 403
telemt_me_writer_restored_same_endpoint_total 2047
telemt_me_writer_restored_fallback_total 128
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 8936053
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 157134625117 (146.34 GB)
telemt_user_octets_to_client{user="hello"} 3477281037783 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 54
```
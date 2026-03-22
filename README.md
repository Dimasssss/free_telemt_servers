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

# Server Metrics 2026-03-22 23:39:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 95580.5 (26h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3403245
telemt_connections_bad_total 279097
telemt_connections_current 514
telemt_connections_me_current 514
telemt_handshake_timeouts_total 107090
telemt_upstream_connect_attempt_total 35284
telemt_upstream_connect_success_total 35283
telemt_upstream_connect_attempts_per_request{bucket="1"} 35283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22937
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1363
telemt_me_reconnect_success_total 571
telemt_me_reader_eof_total 587
telemt_me_idle_close_by_peer_total 587
telemt_me_route_drop_no_conn_total 2970899
telemt_me_route_drop_channel_closed_total 1230
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2833133
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 662
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 744
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
telemt_desync_total 12132
telemt_desync_full_logged_total 3806
telemt_desync_suppressed_total 8326
telemt_desync_frames_bucket_total{bucket="1_2"} 3263
telemt_desync_frames_bucket_total{bucket="3_10"} 4430
telemt_desync_frames_bucket_total{bucket="gt_10"} 4439
telemt_pool_swap_total 106
telemt_pool_force_close_total 3298
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 645
telemt_me_draining_writers_reap_progress_total 32318
telemt_me_writer_removed_unexpected_total 567
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2351
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30180
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3242
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29020
telemt_me_writer_teardown_success_total{mode="normal"} 32531
telemt_me_writer_teardown_noop_total 32329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64860
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 375.300583
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64860
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 645
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 510
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2822391
telemt_user_connections_current{user="hello"} 514
telemt_user_octets_from_client{user="hello"} 40462488548 (37.68 GB)
telemt_user_octets_to_client{user="hello"} 769428671428 (716.59 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 108946.4 (30h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3970765
telemt_connections_bad_total 360820
telemt_connections_current 461
telemt_connections_me_current 461
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100205
telemt_upstream_connect_attempt_total 67376
telemt_upstream_connect_success_total 66562
telemt_upstream_connect_fail_total 720
telemt_upstream_connect_attempts_per_request{bucket="1"} 67282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 720
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9732
telemt_me_reconnect_success_total 3516
telemt_me_reader_eof_total 3525
telemt_me_idle_close_by_peer_total 3525
telemt_me_route_drop_no_conn_total 3638043
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3158415
telemt_me_endpoint_quarantine_total 825
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 845
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_me_writers_warm_current 8
telemt_desync_total 12891
telemt_desync_full_logged_total 7223
telemt_desync_suppressed_total 5668
telemt_desync_frames_bucket_total{bucket="1_2"} 2920
telemt_desync_frames_bucket_total{bucket="3_10"} 5057
telemt_desync_frames_bucket_total{bucket="gt_10"} 4914
telemt_pool_swap_total 100
telemt_pool_force_close_total 2975
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 244
telemt_me_draining_writers_reap_progress_total 44085
telemt_me_writer_removed_unexpected_total 3460
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5963
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41610
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2517
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41110
telemt_me_writer_teardown_success_total{mode="normal"} 47573
telemt_me_writer_teardown_noop_total 44086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91659
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.545732
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91659
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 244
telemt_me_refill_failed_total 238
telemt_me_writer_restored_same_endpoint_total 3162
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 3170902
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 42826236538 (39.89 GB)
telemt_user_octets_to_client{user="hello"} 785682447184 (731.72 GB)
telemt_user_msgs_from_client{user="hello"} 47428
telemt_user_msgs_to_client{user="hello"} 180951
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 183806.4 (51h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16270950
telemt_connections_bad_total 1634141
telemt_connections_current 616
telemt_connections_me_current 616
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396595
telemt_upstream_connect_attempt_total 81917
telemt_upstream_connect_success_total 81817
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 81834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39812
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1706
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2937
telemt_me_reconnect_success_total 1533
telemt_me_reader_eof_total 1479
telemt_me_idle_close_by_peer_total 1477
telemt_me_route_drop_no_conn_total 14037225
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12927282
telemt_me_endpoint_quarantine_total 1204
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1377
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 33
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 53456
telemt_desync_full_logged_total 16965
telemt_desync_suppressed_total 36491
telemt_desync_frames_bucket_total{bucket="1_2"} 11875
telemt_desync_frames_bucket_total{bucket="3_10"} 20828
telemt_desync_frames_bucket_total{bucket="gt_10"} 20753
telemt_pool_swap_total 199
telemt_pool_force_close_total 6600
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1053
telemt_me_draining_writers_reap_progress_total 61576
telemt_me_writer_removed_unexpected_total 1425
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5321
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56953
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6130
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54976
telemt_me_writer_teardown_success_total{mode="normal"} 62274
telemt_me_writer_teardown_noop_total 61629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123903
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.430214
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123903
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1053
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 1326
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 12927474
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 190722789253 (177.62 GB)
telemt_user_octets_to_client{user="hello"} 3477732633655 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 290
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 183807.7 (51h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11813692
telemt_connections_bad_total 1220279
telemt_connections_current 424
telemt_connections_me_current 424
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344263
telemt_upstream_connect_attempt_total 96386
telemt_upstream_connect_success_total 95072
telemt_upstream_connect_fail_total 865
telemt_upstream_connect_attempts_per_request{bucket="1"} 95937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39737
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3798
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 865
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4351
telemt_me_reconnect_success_total 1838
telemt_me_reader_eof_total 1701
telemt_me_idle_close_by_peer_total 1701
telemt_me_route_drop_no_conn_total 4548850
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8777473
telemt_me_endpoint_quarantine_total 1209
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1400
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_desync_total 38643
telemt_desync_full_logged_total 13006
telemt_desync_suppressed_total 25637
telemt_desync_frames_bucket_total{bucket="1_2"} 9557
telemt_desync_frames_bucket_total{bucket="3_10"} 14849
telemt_desync_frames_bucket_total{bucket="gt_10"} 14237
telemt_pool_swap_total 196
telemt_pool_force_close_total 5958
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 59931
telemt_me_writer_removed_unexpected_total 1734
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5442
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56076
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5446
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53973
telemt_me_writer_teardown_success_total{mode="normal"} 61518
telemt_me_writer_teardown_noop_total 59956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121474
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.291647
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121474
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1569
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 8715273
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 217567723468 (202.63 GB)
telemt_user_octets_to_client{user="hello"} 3945539579975 (3.59 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 183771.7 (51h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11005484
telemt_connections_bad_total 964305
telemt_connections_current 679
telemt_connections_me_current 679
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345249
telemt_upstream_connect_attempt_total 80470
telemt_upstream_connect_success_total 78917
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 79122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38139
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2015
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5678
telemt_me_reconnect_success_total 2324
telemt_me_reader_eof_total 2065
telemt_me_idle_close_by_peer_total 2064
telemt_me_route_drop_no_conn_total 5331022
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8325290
telemt_me_endpoint_quarantine_total 1283
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1353
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
telemt_me_writers_active_current 44
telemt_desync_total 37957
telemt_desync_full_logged_total 12584
telemt_desync_suppressed_total 25373
telemt_desync_frames_bucket_total{bucket="1_2"} 9587
telemt_desync_frames_bucket_total{bucket="3_10"} 14510
telemt_desync_frames_bucket_total{bucket="gt_10"} 13860
telemt_pool_swap_total 192
telemt_pool_force_close_total 5847
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 736
telemt_me_draining_writers_reap_progress_total 60088
telemt_me_writer_removed_unexpected_total 2218
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6166
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56069
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5276
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54241
telemt_me_writer_teardown_success_total{mode="normal"} 62235
telemt_me_writer_teardown_noop_total 60159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122394
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.659739
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122394
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 736
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 2015
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8317275
telemt_user_connections_current{user="hello"} 679
telemt_user_octets_from_client{user="hello"} 192395829507 (179.18 GB)
telemt_user_octets_to_client{user="hello"} 3458580405309 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 54051.8 (15h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11157141
telemt_connections_bad_total 667811
telemt_connections_current 989
telemt_connections_me_current 989
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 261357
telemt_upstream_connect_attempt_total 54682
telemt_upstream_connect_success_total 51866
telemt_upstream_connect_fail_total 1896
telemt_upstream_connect_attempts_per_request{bucket="1"} 53762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17536
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6001
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1896
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7410
telemt_me_reconnect_success_total 1140
telemt_me_reader_eof_total 712
telemt_me_idle_close_by_peer_total 711
telemt_me_route_drop_no_conn_total 25275743
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9266951
telemt_me_endpoint_quarantine_total 385
telemt_me_single_endpoint_outage_enter_total 85
telemt_me_single_endpoint_outage_exit_total 85
telemt_me_single_endpoint_outage_reconnect_attempt_total 158
telemt_me_single_endpoint_outage_reconnect_success_total 42
telemt_me_single_endpoint_quarantine_bypass_total 158
telemt_me_single_endpoint_shadow_rotate_total 426
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_me_writers_warm_current 15
telemt_desync_total 16131
telemt_desync_full_logged_total 4352
telemt_desync_suppressed_total 11779
telemt_desync_frames_bucket_total{bucket="1_2"} 3068
telemt_desync_frames_bucket_total{bucket="3_10"} 6535
telemt_desync_frames_bucket_total{bucket="gt_10"} 6528
telemt_pool_swap_total 55
telemt_pool_force_close_total 1871
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 469
telemt_me_draining_writers_reap_progress_total 16427
telemt_me_writer_removed_unexpected_total 1029
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2279
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15117
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1564
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14556
telemt_me_writer_teardown_success_total{mode="normal"} 17396
telemt_me_writer_teardown_noop_total 16446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33842
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.502989
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33842
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 469
telemt_me_refill_failed_total 334
telemt_me_writer_restored_same_endpoint_total 738
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 283
telemt_user_connections_total{user="hello"} 9292444
telemt_user_connections_current{user="hello"} 989
telemt_user_octets_from_client{user="hello"} 86429065586 (80.49 GB)
telemt_user_octets_to_client{user="hello"} 588473221553 (548.06 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 407
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 183778.5 (51h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10942060
telemt_connections_bad_total 940453
telemt_connections_current 725
telemt_connections_me_current 725
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241595
telemt_upstream_connect_attempt_total 109335
telemt_upstream_connect_success_total 108199
telemt_upstream_connect_fail_total 964
telemt_upstream_connect_attempts_per_request{bucket="1"} 109163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41655
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 964
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72805
telemt_me_reconnect_success_total 3014
telemt_me_reader_eof_total 2706
telemt_me_idle_close_by_peer_total 2704
telemt_me_route_drop_no_conn_total 5253248
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8634817
telemt_me_endpoint_quarantine_total 1222
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 43
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 43
telemt_me_single_endpoint_shadow_rotate_total 1382
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
telemt_me_writers_active_current 49
telemt_desync_total 46062
telemt_desync_full_logged_total 15772
telemt_desync_suppressed_total 30290
telemt_desync_frames_bucket_total{bucket="1_2"} 9350
telemt_desync_frames_bucket_total{bucket="3_10"} 17630
telemt_desync_frames_bucket_total{bucket="gt_10"} 19082
telemt_pool_swap_total 188
telemt_pool_force_close_total 5542
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 64196
telemt_me_writer_removed_unexpected_total 2737
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6672
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60294
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4793
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58654
telemt_me_writer_teardown_success_total{mode="normal"} 66966
telemt_me_writer_teardown_noop_total 64197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 129029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 130427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 130846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 131119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 131153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 131156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 131156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 131159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 131163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 131163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 131163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 131163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 131163
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.202211
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 131163
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2545
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8637873
telemt_user_connections_current{user="hello"} 725
telemt_user_octets_from_client{user="hello"} 194171682757 (180.84 GB)
telemt_user_octets_to_client{user="hello"} 3298295710996 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 352
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 120614.6 (33h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11633441
telemt_connections_bad_total 475462
telemt_connections_current 577
telemt_connections_me_current 577
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4756592
telemt_upstream_connect_attempt_total 57461
telemt_upstream_connect_success_total 57041
telemt_upstream_connect_fail_total 409
telemt_upstream_connect_attempts_per_request{bucket="1"} 57450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26094
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 409
telemt_me_reconnect_attempts_total 48783
telemt_me_reconnect_success_total 1763
telemt_me_reader_eof_total 1432
telemt_me_idle_close_by_peer_total 1431
telemt_me_route_drop_no_conn_total 4080275
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5588117
telemt_me_endpoint_quarantine_total 795
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 918
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31405
telemt_desync_full_logged_total 10701
telemt_desync_suppressed_total 20704
telemt_desync_frames_bucket_total{bucket="1_2"} 6239
telemt_desync_frames_bucket_total{bucket="3_10"} 12387
telemt_desync_frames_bucket_total{bucket="gt_10"} 12779
telemt_pool_swap_total 127
telemt_pool_force_close_total 3784
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 373
telemt_me_draining_writers_reap_progress_total 43288
telemt_me_writer_removed_unexpected_total 1483
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3647
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41167
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3343
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39504
telemt_me_writer_teardown_success_total{mode="normal"} 44814
telemt_me_writer_teardown_noop_total 43295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88109
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.647852
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88109
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 373
telemt_me_refill_failed_total 2732
telemt_me_writer_restored_same_endpoint_total 1567
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5580714
telemt_user_connections_current{user="hello"} 577
telemt_user_octets_from_client{user="hello"} 118843465048 (110.68 GB)
telemt_user_octets_to_client{user="hello"} 2160728442170 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 101585.4 (28h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1490105
telemt_connections_bad_total 36561
telemt_connections_current 466
telemt_connections_me_current 466
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29732
telemt_upstream_connect_attempt_total 47449
telemt_upstream_connect_success_total 47298
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 47421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 779
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2161
telemt_me_reconnect_success_total 878
telemt_me_reader_eof_total 858
telemt_me_idle_close_by_peer_total 858
telemt_me_route_drop_no_conn_total 511336
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1323296
telemt_me_endpoint_quarantine_total 819
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 837
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 8496
telemt_desync_full_logged_total 2538
telemt_desync_suppressed_total 5958
telemt_desync_frames_bucket_total{bucket="1_2"} 2219
telemt_desync_frames_bucket_total{bucket="3_10"} 3274
telemt_desync_frames_bucket_total{bucket="gt_10"} 3003
telemt_pool_swap_total 109
telemt_pool_force_close_total 2828
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 159
telemt_me_draining_writers_reap_progress_total 39905
telemt_me_writer_removed_unexpected_total 830
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3119
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37651
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2740
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37077
telemt_me_writer_teardown_success_total{mode="normal"} 40770
telemt_me_writer_teardown_noop_total 39909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80679
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.096502
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80679
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 159
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 745
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 1319150
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 25746132413 (23.98 GB)
telemt_user_octets_to_client{user="hello"} 568096712687 (529.08 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 183782.9 (51h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13260522
telemt_connections_bad_total 1576170
telemt_connections_current 634
telemt_connections_me_current 634
telemt_handshake_timeouts_total 384165
telemt_upstream_connect_attempt_total 71169
telemt_upstream_connect_success_total 70825
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 71033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35628
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2845
telemt_me_reconnect_success_total 1433
telemt_me_reader_eof_total 1415
telemt_me_idle_close_by_peer_total 1415
telemt_me_route_drop_no_conn_total 4477521
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10015658
telemt_me_endpoint_quarantine_total 1275
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1384
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 41849
telemt_desync_full_logged_total 13662
telemt_desync_suppressed_total 28187
telemt_desync_frames_bucket_total{bucket="1_2"} 10062
telemt_desync_frames_bucket_total{bucket="3_10"} 15388
telemt_desync_frames_bucket_total{bucket="gt_10"} 16399
telemt_pool_swap_total 204
telemt_pool_force_close_total 5488
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 670
telemt_me_draining_writers_reap_progress_total 64232
telemt_me_writer_removed_unexpected_total 1356
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5128
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60509
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5314
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58744
telemt_me_writer_teardown_success_total{mode="normal"} 65637
telemt_me_writer_teardown_noop_total 64234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 127280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 128979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 129362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 129738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 129858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 129871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 129871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 129871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 129871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 129871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 129871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 129871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 129871
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.700937
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 129871
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 670
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 1257
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 9982397
telemt_user_connections_current{user="hello"} 634
telemt_user_octets_from_client{user="hello"} 194399652828 (181.05 GB)
telemt_user_octets_to_client{user="hello"} 4429880455312 (4.03 TB)
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 183779.6 (51h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11555386
telemt_connections_bad_total 1326586
telemt_connections_current 556
telemt_connections_me_current 556
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 307664
telemt_upstream_connect_attempt_total 97838
telemt_upstream_connect_success_total 96968
telemt_upstream_connect_fail_total 662
telemt_upstream_connect_attempts_per_request{bucket="1"} 97630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41238
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 662
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10237
telemt_me_reconnect_success_total 2523
telemt_me_reader_eof_total 2343
telemt_me_idle_close_by_peer_total 2342
telemt_me_seq_mismatch_total 91
telemt_me_route_drop_no_conn_total 5637854
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8919751
telemt_me_endpoint_quarantine_total 1459
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 1386
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 33
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 41605
telemt_desync_full_logged_total 13364
telemt_desync_suppressed_total 28241
telemt_desync_frames_bucket_total{bucket="1_2"} 10732
telemt_desync_frames_bucket_total{bucket="3_10"} 15294
telemt_desync_frames_bucket_total{bucket="gt_10"} 15579
telemt_pool_swap_total 194
telemt_pool_force_close_total 5279
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 657
telemt_me_draining_writers_reap_progress_total 64178
telemt_me_writer_removed_unexpected_total 2380
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6493
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60148
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4808
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58899
telemt_me_writer_teardown_success_total{mode="normal"} 66641
telemt_me_writer_teardown_noop_total 64183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 129916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 130455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 130774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 130824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 130824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 130824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 130824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 130824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 130824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 130824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 130824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 130824
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.412042
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 130824
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 657
telemt_me_refill_failed_total 399
telemt_me_writer_restored_same_endpoint_total 2040
telemt_me_writer_restored_fallback_total 126
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 8925104
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 157071419097 (146.28 GB)
telemt_user_octets_to_client{user="hello"} 3472896671819 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 51
```
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

# Server Metrics 2026-03-22 23:49:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 96190.6 (26h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3415530
telemt_connections_bad_total 283158
telemt_connections_current 806
telemt_connections_me_current 806
telemt_handshake_timeouts_total 107260
telemt_upstream_connect_attempt_total 35505
telemt_upstream_connect_success_total 35504
telemt_upstream_connect_attempts_per_request{bucket="1"} 35504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23086
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1367
telemt_me_reconnect_success_total 575
telemt_me_reader_eof_total 592
telemt_me_idle_close_by_peer_total 592
telemt_me_route_drop_no_conn_total 2972227
telemt_me_route_drop_channel_closed_total 1230
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2840413
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 662
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 747
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
telemt_me_writers_active_current 44
telemt_desync_total 12194
telemt_desync_full_logged_total 3820
telemt_desync_suppressed_total 8374
telemt_desync_frames_bucket_total{bucket="1_2"} 3300
telemt_desync_frames_bucket_total{bucket="3_10"} 4439
telemt_desync_frames_bucket_total{bucket="gt_10"} 4455
telemt_pool_swap_total 106
telemt_pool_force_close_total 3298
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 645
telemt_me_draining_writers_reap_progress_total 32509
telemt_me_writer_removed_unexpected_total 571
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2361
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30366
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3242
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29211
telemt_me_writer_teardown_success_total{mode="normal"} 32727
telemt_me_writer_teardown_noop_total 32520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65247
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 375.311693
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65247
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 645
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 514
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2829670
telemt_user_connections_current{user="hello"} 806
telemt_user_octets_from_client{user="hello"} 40536417232 (37.75 GB)
telemt_user_octets_to_client{user="hello"} 772412700272 (719.37 GB)
telemt_user_unique_ips_current{user="hello"} 363
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 109557.0 (30h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3974155
telemt_connections_bad_total 361615
telemt_connections_current 342
telemt_connections_me_current 342
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100266
telemt_upstream_connect_attempt_total 67781
telemt_upstream_connect_success_total 66961
telemt_upstream_connect_fail_total 726
telemt_upstream_connect_attempts_per_request{bucket="1"} 67687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 726
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9754
telemt_me_reconnect_success_total 3535
telemt_me_reader_eof_total 3540
telemt_me_idle_close_by_peer_total 3540
telemt_me_route_drop_no_conn_total 3638369
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3160915
telemt_me_endpoint_quarantine_total 836
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 851
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
telemt_me_writers_active_current 46
telemt_desync_total 12909
telemt_desync_full_logged_total 7232
telemt_desync_suppressed_total 5677
telemt_desync_frames_bucket_total{bucket="1_2"} 2931
telemt_desync_frames_bucket_total{bucket="3_10"} 5061
telemt_desync_frames_bucket_total{bucket="gt_10"} 4917
telemt_pool_swap_total 101
telemt_pool_force_close_total 2993
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 245
telemt_me_draining_writers_reap_progress_total 44448
telemt_me_writer_removed_unexpected_total 3474
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5999
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41952
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2535
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41455
telemt_me_writer_teardown_success_total{mode="normal"} 47951
telemt_me_writer_teardown_noop_total 44449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92400
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.553994
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92400
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 245
telemt_me_refill_failed_total 238
telemt_me_writer_restored_same_endpoint_total 3176
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 3173399
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 42877390506 (39.93 GB)
telemt_user_octets_to_client{user="hello"} 786569462768 (732.55 GB)
telemt_user_msgs_from_client{user="hello"} 47428
telemt_user_msgs_to_client{user="hello"} 180951
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 184416.9 (51h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16277347
telemt_connections_bad_total 1635320
telemt_connections_current 1021
telemt_connections_me_current 1021
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396690
telemt_upstream_connect_attempt_total 82201
telemt_upstream_connect_success_total 82100
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 82117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39991
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1708
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2942
telemt_me_reconnect_success_total 1538
telemt_me_reader_eof_total 1485
telemt_me_idle_close_by_peer_total 1483
telemt_me_route_drop_no_conn_total 14038808
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12932316
telemt_me_endpoint_quarantine_total 1204
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1381
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 53509
telemt_desync_full_logged_total 16985
telemt_desync_suppressed_total 36524
telemt_desync_frames_bucket_total{bucket="1_2"} 11893
telemt_desync_frames_bucket_total{bucket="3_10"} 20858
telemt_desync_frames_bucket_total{bucket="gt_10"} 20758
telemt_pool_swap_total 199
telemt_pool_force_close_total 6600
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1053
telemt_me_draining_writers_reap_progress_total 61829
telemt_me_writer_removed_unexpected_total 1431
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5330
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57203
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6130
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55229
telemt_me_writer_teardown_success_total{mode="normal"} 62533
telemt_me_writer_teardown_noop_total 61882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 124376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 124406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 124407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 124411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 124413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 124415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 124415
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.437172
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 124415
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1053
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 1331
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 12932388
telemt_user_connections_current{user="hello"} 1021
telemt_user_octets_from_client{user="hello"} 190768753281 (177.67 GB)
telemt_user_octets_to_client{user="hello"} 3479221589087 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 487
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 184418.4 (51h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11820591
telemt_connections_bad_total 1221570
telemt_connections_current 603
telemt_connections_me_current 603
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344324
telemt_upstream_connect_attempt_total 96628
telemt_upstream_connect_success_total 95314
telemt_upstream_connect_fail_total 865
telemt_upstream_connect_attempts_per_request{bucket="1"} 96179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39899
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3798
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 865
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4353
telemt_me_reconnect_success_total 1840
telemt_me_reader_eof_total 1704
telemt_me_idle_close_by_peer_total 1704
telemt_me_route_drop_no_conn_total 4549484
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8781660
telemt_me_endpoint_quarantine_total 1209
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1404
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
telemt_me_writers_active_current 44
telemt_desync_total 38652
telemt_desync_full_logged_total 13009
telemt_desync_suppressed_total 25643
telemt_desync_frames_bucket_total{bucket="1_2"} 9562
telemt_desync_frames_bucket_total{bucket="3_10"} 14850
telemt_desync_frames_bucket_total{bucket="gt_10"} 14240
telemt_pool_swap_total 196
telemt_pool_force_close_total 5958
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 60144
telemt_me_writer_removed_unexpected_total 1736
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5447
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56287
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5446
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54186
telemt_me_writer_teardown_success_total{mode="normal"} 61734
telemt_me_writer_teardown_noop_total 60169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121903
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.294200
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121903
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1571
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 8719460
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 217596091528 (202.65 GB)
telemt_user_octets_to_client{user="hello"} 3947240148863 (3.59 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 184382.4 (51h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11011716
telemt_connections_bad_total 965762
telemt_connections_current 517
telemt_connections_me_current 517
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345272
telemt_upstream_connect_attempt_total 80803
telemt_upstream_connect_success_total 79249
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 79454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38318
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5688
telemt_me_reconnect_success_total 2333
telemt_me_reader_eof_total 2074
telemt_me_idle_close_by_peer_total 2073
telemt_me_route_drop_no_conn_total 5331738
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8329266
telemt_me_endpoint_quarantine_total 1284
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1360
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
telemt_me_writers_active_current 48
telemt_desync_total 37959
telemt_desync_full_logged_total 12586
telemt_desync_suppressed_total 25373
telemt_desync_frames_bucket_total{bucket="1_2"} 9587
telemt_desync_frames_bucket_total{bucket="3_10"} 14512
telemt_desync_frames_bucket_total{bucket="gt_10"} 13860
telemt_pool_swap_total 192
telemt_pool_force_close_total 5868
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 736
telemt_me_draining_writers_reap_progress_total 60400
telemt_me_writer_removed_unexpected_total 2227
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6187
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56369
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5297
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54532
telemt_me_writer_teardown_success_total{mode="normal"} 62556
telemt_me_writer_teardown_noop_total 60471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123027
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.663678
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123027
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 736
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 2024
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8321248
telemt_user_connections_current{user="hello"} 517
telemt_user_octets_from_client{user="hello"} 192490704659 (179.27 GB)
telemt_user_octets_to_client{user="hello"} 3459114663973 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 54662.0 (15h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11166946
telemt_connections_bad_total 667931
telemt_connections_current 1022
telemt_connections_me_current 1022
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 262629
telemt_upstream_connect_attempt_total 54949
telemt_upstream_connect_success_total 52122
telemt_upstream_connect_fail_total 1899
telemt_upstream_connect_attempts_per_request{bucket="1"} 54021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17671
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6002
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1899
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7450
telemt_me_reconnect_success_total 1146
telemt_me_reader_eof_total 721
telemt_me_idle_close_by_peer_total 720
telemt_me_route_drop_no_conn_total 25276908
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9275015
telemt_me_endpoint_quarantine_total 393
telemt_me_single_endpoint_outage_enter_total 85
telemt_me_single_endpoint_outage_exit_total 85
telemt_me_single_endpoint_outage_reconnect_attempt_total 158
telemt_me_single_endpoint_outage_reconnect_success_total 42
telemt_me_single_endpoint_quarantine_bypass_total 158
telemt_me_single_endpoint_shadow_rotate_total 432
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
telemt_me_writers_active_current 42
telemt_desync_total 16188
telemt_desync_full_logged_total 4378
telemt_desync_suppressed_total 11810
telemt_desync_frames_bucket_total{bucket="1_2"} 3070
telemt_desync_frames_bucket_total{bucket="3_10"} 6563
telemt_desync_frames_bucket_total{bucket="gt_10"} 6555
telemt_pool_swap_total 56
telemt_pool_force_close_total 1890
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 470
telemt_me_draining_writers_reap_progress_total 16664
telemt_me_writer_removed_unexpected_total 1037
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2307
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15335
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1583
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14774
telemt_me_writer_teardown_success_total{mode="normal"} 17642
telemt_me_writer_teardown_noop_total 16683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34325
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.525528
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34325
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 470
telemt_me_refill_failed_total 336
telemt_me_writer_restored_same_endpoint_total 744
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 9300476
telemt_user_connections_current{user="hello"} 1022
telemt_user_octets_from_client{user="hello"} 86489561574 (80.55 GB)
telemt_user_octets_to_client{user="hello"} 591266277117 (550.66 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 408
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 184388.6 (51h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10948571
telemt_connections_bad_total 941503
telemt_connections_current 736
telemt_connections_me_current 736
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241659
telemt_upstream_connect_attempt_total 109686
telemt_upstream_connect_success_total 108550
telemt_upstream_connect_fail_total 964
telemt_upstream_connect_attempts_per_request{bucket="1"} 109514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41874
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 964
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72811
telemt_me_reconnect_success_total 3019
telemt_me_reader_eof_total 2711
telemt_me_idle_close_by_peer_total 2709
telemt_me_route_drop_no_conn_total 5254311
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8639962
telemt_me_endpoint_quarantine_total 1222
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 43
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 43
telemt_me_single_endpoint_shadow_rotate_total 1388
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
telemt_me_writers_active_current 52
telemt_desync_total 46092
telemt_desync_full_logged_total 15777
telemt_desync_suppressed_total 30315
telemt_desync_frames_bucket_total{bucket="1_2"} 9358
telemt_desync_frames_bucket_total{bucket="3_10"} 17644
telemt_desync_frames_bucket_total{bucket="gt_10"} 19090
telemt_pool_swap_total 188
telemt_pool_force_close_total 5565
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 64539
telemt_me_writer_removed_unexpected_total 2742
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6683
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60631
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4816
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58974
telemt_me_writer_teardown_success_total{mode="normal"} 67314
telemt_me_writer_teardown_noop_total 64540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 129720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 131537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 131810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 131844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 131847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 131847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 131850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 131854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 131854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 131854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 131854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 131854
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.205064
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 131854
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2550
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8643014
telemt_user_connections_current{user="hello"} 736
telemt_user_octets_from_client{user="hello"} 194213902129 (180.88 GB)
telemt_user_octets_to_client{user="hello"} 3299647273580 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 353
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 121224.8 (33h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11640930
telemt_connections_bad_total 475786
telemt_connections_current 480
telemt_connections_me_current 480
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4757959
telemt_upstream_connect_attempt_total 57828
telemt_upstream_connect_success_total 57406
telemt_upstream_connect_fail_total 411
telemt_upstream_connect_attempts_per_request{bucket="1"} 57817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26283
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 411
telemt_me_reconnect_attempts_total 48802
telemt_me_reconnect_success_total 1766
telemt_me_reader_eof_total 1436
telemt_me_idle_close_by_peer_total 1435
telemt_me_route_drop_no_conn_total 4081112
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5591813
telemt_me_endpoint_quarantine_total 803
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 926
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31452
telemt_desync_full_logged_total 10715
telemt_desync_suppressed_total 20737
telemt_desync_frames_bucket_total{bucket="1_2"} 6262
telemt_desync_frames_bucket_total{bucket="3_10"} 12404
telemt_desync_frames_bucket_total{bucket="gt_10"} 12786
telemt_pool_swap_total 128
telemt_pool_force_close_total 3805
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 374
telemt_me_draining_writers_reap_progress_total 43643
telemt_me_writer_removed_unexpected_total 1487
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3665
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41508
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3364
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39838
telemt_me_writer_teardown_success_total{mode="normal"} 45173
telemt_me_writer_teardown_noop_total 43650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88823
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.649815
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88823
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 374
telemt_me_refill_failed_total 2733
telemt_me_writer_restored_same_endpoint_total 1568
telemt_me_writer_restored_fallback_total 23
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5584398
telemt_user_connections_current{user="hello"} 480
telemt_user_octets_from_client{user="hello"} 118872348032 (110.71 GB)
telemt_user_octets_to_client{user="hello"} 2161543460818 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 102195.3 (28h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1493862
telemt_connections_bad_total 36613
telemt_connections_current 400
telemt_connections_me_current 400
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29844
telemt_upstream_connect_attempt_total 47778
telemt_upstream_connect_success_total 47627
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 47750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 781
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2165
telemt_me_reconnect_success_total 881
telemt_me_reader_eof_total 861
telemt_me_idle_close_by_peer_total 861
telemt_me_route_drop_no_conn_total 512429
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1326807
telemt_me_endpoint_quarantine_total 826
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 844
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
telemt_me_writers_active_current 45
telemt_desync_total 8545
telemt_desync_full_logged_total 2548
telemt_desync_suppressed_total 5997
telemt_desync_frames_bucket_total{bucket="1_2"} 2250
telemt_desync_frames_bucket_total{bucket="3_10"} 3289
telemt_desync_frames_bucket_total{bucket="gt_10"} 3006
telemt_pool_swap_total 110
telemt_pool_force_close_total 2850
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 159
telemt_me_draining_writers_reap_progress_total 40203
telemt_me_writer_removed_unexpected_total 833
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3145
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37926
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2762
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37353
telemt_me_writer_teardown_success_total{mode="normal"} 41071
telemt_me_writer_teardown_noop_total 40207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81278
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.121319
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81278
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 159
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 748
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 1322654
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 25764806681 (24.00 GB)
telemt_user_octets_to_client{user="hello"} 569346577511 (530.25 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 184393.1 (51h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13274077
telemt_connections_bad_total 1584512
telemt_connections_current 646
telemt_connections_me_current 646
telemt_handshake_timeouts_total 385338
telemt_upstream_connect_attempt_total 71522
telemt_upstream_connect_success_total 71178
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 71386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35834
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2851
telemt_me_reconnect_success_total 1438
telemt_me_reader_eof_total 1421
telemt_me_idle_close_by_peer_total 1421
telemt_me_route_drop_no_conn_total 4478133
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10019463
telemt_me_endpoint_quarantine_total 1275
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1389
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
telemt_me_writers_active_current 49
telemt_desync_total 41854
telemt_desync_full_logged_total 13667
telemt_desync_suppressed_total 28187
telemt_desync_frames_bucket_total{bucket="1_2"} 10062
telemt_desync_frames_bucket_total{bucket="3_10"} 15390
telemt_desync_frames_bucket_total{bucket="gt_10"} 16402
telemt_pool_swap_total 204
telemt_pool_force_close_total 5504
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 671
telemt_me_draining_writers_reap_progress_total 64566
telemt_me_writer_removed_unexpected_total 1361
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5141
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60836
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5330
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59062
telemt_me_writer_teardown_success_total{mode="normal"} 65977
telemt_me_writer_teardown_noop_total 64568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 127944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 129653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 130036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 130412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 130532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 130545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 130545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 130545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 130545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 130545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 130545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 130545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 130545
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.731999
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 130545
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 671
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 1262
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 9986201
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 194416875208 (181.06 GB)
telemt_user_octets_to_client{user="hello"} 4430905278124 (4.03 TB)
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 184389.8 (51h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11562290
telemt_connections_bad_total 1328261
telemt_connections_current 509
telemt_connections_me_current 509
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 308245
telemt_upstream_connect_attempt_total 98209
telemt_upstream_connect_success_total 97339
telemt_upstream_connect_fail_total 662
telemt_upstream_connect_attempts_per_request{bucket="1"} 98001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41438
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 662
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10243
telemt_me_reconnect_success_total 2528
telemt_me_reader_eof_total 2347
telemt_me_idle_close_by_peer_total 2346
telemt_me_seq_mismatch_total 92
telemt_me_route_drop_no_conn_total 5638441
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8924132
telemt_me_endpoint_quarantine_total 1460
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 1391
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 41635
telemt_desync_full_logged_total 13372
telemt_desync_suppressed_total 28263
telemt_desync_frames_bucket_total{bucket="1_2"} 10744
telemt_desync_frames_bucket_total{bucket="3_10"} 15305
telemt_desync_frames_bucket_total{bucket="gt_10"} 15586
telemt_pool_swap_total 194
telemt_pool_force_close_total 5300
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 657
telemt_me_draining_writers_reap_progress_total 64545
telemt_me_writer_removed_unexpected_total 2385
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6504
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60509
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4829
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59245
telemt_me_writer_teardown_success_total{mode="normal"} 67013
telemt_me_writer_teardown_noop_total 64550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 130655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 131194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 131513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 131563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 131563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 131563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 131563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 131563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 131563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 131563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 131563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 131563
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.430422
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 131563
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 657
telemt_me_refill_failed_total 399
telemt_me_writer_restored_same_endpoint_total 2044
telemt_me_writer_restored_fallback_total 127
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 8929479
telemt_user_connections_current{user="hello"} 509
telemt_user_octets_from_client{user="hello"} 157094018785 (146.31 GB)
telemt_user_octets_to_client{user="hello"} 3474234270487 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 47
```
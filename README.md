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

# Server Metrics 2026-03-22 23:44:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 95885.8 (26h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3409545
telemt_connections_bad_total 281099
telemt_connections_current 789
telemt_connections_me_current 789
telemt_handshake_timeouts_total 107217
telemt_upstream_connect_attempt_total 35407
telemt_upstream_connect_success_total 35406
telemt_upstream_connect_attempts_per_request{bucket="1"} 35406
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23012
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1367
telemt_me_reconnect_success_total 575
telemt_me_reader_eof_total 592
telemt_me_idle_close_by_peer_total 592
telemt_me_route_drop_no_conn_total 2971576
telemt_me_route_drop_channel_closed_total 1230
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2836912
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
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 12163
telemt_desync_full_logged_total 3811
telemt_desync_suppressed_total 8352
telemt_desync_frames_bucket_total{bucket="1_2"} 3288
telemt_desync_frames_bucket_total{bucket="3_10"} 4432
telemt_desync_frames_bucket_total{bucket="gt_10"} 4443
telemt_pool_swap_total 106
telemt_pool_force_close_total 3298
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 645
telemt_me_draining_writers_reap_progress_total 32411
telemt_me_writer_removed_unexpected_total 571
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2359
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30270
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3242
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29113
telemt_me_writer_teardown_success_total{mode="normal"} 32629
telemt_me_writer_teardown_noop_total 32422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65051
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 375.304511
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65051
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 645
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 514
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2826169
telemt_user_connections_current{user="hello"} 789
telemt_user_octets_from_client{user="hello"} 40501198920 (37.72 GB)
telemt_user_octets_to_client{user="hello"} 771030754988 (718.08 GB)
telemt_user_unique_ips_current{user="hello"} 369
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 109251.7 (30h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3972274
telemt_connections_bad_total 360983
telemt_connections_current 187
telemt_connections_me_current 187
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100249
telemt_upstream_connect_attempt_total 67601
telemt_upstream_connect_success_total 66782
telemt_upstream_connect_fail_total 726
telemt_upstream_connect_attempts_per_request{bucket="1"} 67508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 726
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9748
telemt_me_reconnect_success_total 3528
telemt_me_reader_eof_total 3533
telemt_me_idle_close_by_peer_total 3533
telemt_me_route_drop_no_conn_total 3638259
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3159708
telemt_me_endpoint_quarantine_total 836
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 849
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
telemt_desync_total 12903
telemt_desync_full_logged_total 7228
telemt_desync_suppressed_total 5675
telemt_desync_frames_bucket_total{bucket="1_2"} 2928
telemt_desync_frames_bucket_total{bucket="3_10"} 5059
telemt_desync_frames_bucket_total{bucket="gt_10"} 4916
telemt_pool_swap_total 101
telemt_pool_force_close_total 2993
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 245
telemt_me_draining_writers_reap_progress_total 44305
telemt_me_writer_removed_unexpected_total 3468
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5987
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41814
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2535
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41312
telemt_me_writer_teardown_success_total{mode="normal"} 47801
telemt_me_writer_teardown_noop_total 44306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92107
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.552237
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92107
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 245
telemt_me_refill_failed_total 238
telemt_me_writer_restored_same_endpoint_total 3170
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 3172192
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 42848222314 (39.91 GB)
telemt_user_octets_to_client{user="hello"} 786236311224 (732.24 GB)
telemt_user_msgs_from_client{user="hello"} 47428
telemt_user_msgs_to_client{user="hello"} 180951
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 184111.5 (51h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16274729
telemt_connections_bad_total 1635300
telemt_connections_current 890
telemt_connections_me_current 890
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396610
telemt_upstream_connect_attempt_total 82072
telemt_upstream_connect_success_total 81971
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 81988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1708
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2942
telemt_me_reconnect_success_total 1538
telemt_me_reader_eof_total 1485
telemt_me_idle_close_by_peer_total 1483
telemt_me_route_drop_no_conn_total 14038148
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12929868
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
telemt_desync_total 53482
telemt_desync_full_logged_total 16975
telemt_desync_suppressed_total 36507
telemt_desync_frames_bucket_total{bucket="1_2"} 11879
telemt_desync_frames_bucket_total{bucket="3_10"} 20845
telemt_desync_frames_bucket_total{bucket="gt_10"} 20758
telemt_pool_swap_total 199
telemt_pool_force_close_total 6600
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1053
telemt_me_draining_writers_reap_progress_total 61700
telemt_me_writer_removed_unexpected_total 1431
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5330
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57074
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6130
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55100
telemt_me_writer_teardown_success_total{mode="normal"} 62404
telemt_me_writer_teardown_noop_total 61753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 124118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 124148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 124149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 124153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 124155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 124157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 124157
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.434554
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 124157
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1053
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 1331
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 12929967
telemt_user_connections_current{user="hello"} 890
telemt_user_octets_from_client{user="hello"} 190747257813 (177.65 GB)
telemt_user_octets_to_client{user="hello"} 3478556137863 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 184113.0 (51h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11817681
telemt_connections_bad_total 1221091
telemt_connections_current 583
telemt_connections_me_current 583
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344286
telemt_upstream_connect_attempt_total 96516
telemt_upstream_connect_success_total 95202
telemt_upstream_connect_fail_total 865
telemt_upstream_connect_attempts_per_request{bucket="1"} 96067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39822
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3798
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 865
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4353
telemt_me_reconnect_success_total 1840
telemt_me_reader_eof_total 1704
telemt_me_idle_close_by_peer_total 1704
telemt_me_route_drop_no_conn_total 4549065
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8779641
telemt_me_endpoint_quarantine_total 1209
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1402
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
telemt_me_draining_writers_reap_progress_total 60031
telemt_me_writer_removed_unexpected_total 1736
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5446
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56175
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5446
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54073
telemt_me_writer_teardown_success_total{mode="normal"} 61621
telemt_me_writer_teardown_noop_total 60056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121677
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.292821
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121677
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1571
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 8717441
telemt_user_connections_current{user="hello"} 583
telemt_user_octets_from_client{user="hello"} 217577268660 (202.63 GB)
telemt_user_octets_to_client{user="hello"} 3945972642819 (3.59 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 184077.1 (51h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11008191
telemt_connections_bad_total 964903
telemt_connections_current 505
telemt_connections_me_current 505
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345259
telemt_upstream_connect_attempt_total 80648
telemt_upstream_connect_success_total 79095
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 79300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38239
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2016
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5687
telemt_me_reconnect_success_total 2332
telemt_me_reader_eof_total 2073
telemt_me_idle_close_by_peer_total 2072
telemt_me_route_drop_no_conn_total 5331359
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8327330
telemt_me_endpoint_quarantine_total 1283
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1358
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
telemt_me_writers_active_current 46
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
telemt_me_draining_writers_reap_progress_total 60249
telemt_me_writer_removed_unexpected_total 2226
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6182
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56222
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5297
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54381
telemt_me_writer_teardown_success_total{mode="normal"} 62404
telemt_me_writer_teardown_noop_total 60320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122724
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.662215
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122724
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 736
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 2023
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8319313
telemt_user_connections_current{user="hello"} 505
telemt_user_octets_from_client{user="hello"} 192481227291 (179.26 GB)
telemt_user_octets_to_client{user="hello"} 3458880014549 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 54357.1 (15h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11162409
telemt_connections_bad_total 667887
telemt_connections_current 999
telemt_connections_me_current 999
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 261980
telemt_upstream_connect_attempt_total 54836
telemt_upstream_connect_success_total 52013
telemt_upstream_connect_fail_total 1899
telemt_upstream_connect_attempts_per_request{bucket="1"} 53912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17605
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6001
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1899
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7442
telemt_me_reconnect_success_total 1140
telemt_me_reader_eof_total 714
telemt_me_idle_close_by_peer_total 713
telemt_me_route_drop_no_conn_total 25276433
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9271364
telemt_me_endpoint_quarantine_total 393
telemt_me_single_endpoint_outage_enter_total 85
telemt_me_single_endpoint_outage_exit_total 85
telemt_me_single_endpoint_outage_reconnect_attempt_total 158
telemt_me_single_endpoint_outage_reconnect_success_total 42
telemt_me_single_endpoint_quarantine_bypass_total 158
telemt_me_single_endpoint_shadow_rotate_total 431
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
telemt_me_writers_active_current 41
telemt_desync_total 16161
telemt_desync_full_logged_total 4366
telemt_desync_suppressed_total 11795
telemt_desync_frames_bucket_total{bucket="1_2"} 3069
telemt_desync_frames_bucket_total{bucket="3_10"} 6550
telemt_desync_frames_bucket_total{bucket="gt_10"} 6542
telemt_pool_swap_total 56
telemt_pool_force_close_total 1890
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 470
telemt_me_draining_writers_reap_progress_total 16591
telemt_me_writer_removed_unexpected_total 1031
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2297
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15265
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1583
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14701
telemt_me_writer_teardown_success_total{mode="normal"} 17562
telemt_me_writer_teardown_noop_total 16610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34172
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.523882
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34172
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 470
telemt_me_refill_failed_total 336
telemt_me_writer_restored_same_endpoint_total 738
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 9296825
telemt_user_connections_current{user="hello"} 999
telemt_user_octets_from_client{user="hello"} 86450861458 (80.51 GB)
telemt_user_octets_to_client{user="hello"} 589981053585 (549.46 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 406
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 184083.7 (51h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10945684
telemt_connections_bad_total 941212
telemt_connections_current 764
telemt_connections_me_current 764
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241618
telemt_upstream_connect_attempt_total 109520
telemt_upstream_connect_success_total 108384
telemt_upstream_connect_fail_total 964
telemt_upstream_connect_attempts_per_request{bucket="1"} 109348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41766
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 964
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72805
telemt_me_reconnect_success_total 3014
telemt_me_reader_eof_total 2706
telemt_me_idle_close_by_peer_total 2704
telemt_me_route_drop_no_conn_total 5253665
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8637565
telemt_me_endpoint_quarantine_total 1222
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 43
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 43
telemt_me_single_endpoint_shadow_rotate_total 1387
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
telemt_desync_total 46083
telemt_desync_full_logged_total 15775
telemt_desync_suppressed_total 30308
telemt_desync_frames_bucket_total{bucket="1_2"} 9351
telemt_desync_frames_bucket_total{bucket="3_10"} 17642
telemt_desync_frames_bucket_total{bucket="gt_10"} 19090
telemt_pool_swap_total 188
telemt_pool_force_close_total 5565
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 64400
telemt_me_writer_removed_unexpected_total 2737
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6677
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60493
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4816
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58835
telemt_me_writer_teardown_success_total{mode="normal"} 67170
telemt_me_writer_teardown_noop_total 64401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 129437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 130835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 131254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 131527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 131561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 131564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 131564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 131567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 131571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 131571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 131571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 131571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 131571
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.204324
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 131571
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2545
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8640617
telemt_user_connections_current{user="hello"} 764
telemt_user_octets_from_client{user="hello"} 194200365957 (180.86 GB)
telemt_user_octets_to_client{user="hello"} 3298822630504 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 120920.0 (33h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11637835
telemt_connections_bad_total 475520
telemt_connections_current 452
telemt_connections_me_current 452
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4757745
telemt_upstream_connect_attempt_total 57670
telemt_upstream_connect_success_total 57248
telemt_upstream_connect_fail_total 411
telemt_upstream_connect_attempts_per_request{bucket="1"} 57659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26205
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 411
telemt_me_reconnect_attempts_total 48802
telemt_me_reconnect_success_total 1766
telemt_me_reader_eof_total 1436
telemt_me_idle_close_by_peer_total 1435
telemt_me_route_drop_no_conn_total 4080663
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5590349
telemt_me_endpoint_quarantine_total 803
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 925
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
telemt_desync_total 31441
telemt_desync_full_logged_total 10711
telemt_desync_suppressed_total 20730
telemt_desync_frames_bucket_total{bucket="1_2"} 6255
telemt_desync_frames_bucket_total{bucket="3_10"} 12401
telemt_desync_frames_bucket_total{bucket="gt_10"} 12785
telemt_pool_swap_total 128
telemt_pool_force_close_total 3805
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 374
telemt_me_draining_writers_reap_progress_total 43487
telemt_me_writer_removed_unexpected_total 1487
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3660
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41357
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3364
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39682
telemt_me_writer_teardown_success_total{mode="normal"} 45017
telemt_me_writer_teardown_noop_total 43494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88511
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.649349
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88511
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 374
telemt_me_refill_failed_total 2733
telemt_me_writer_restored_same_endpoint_total 1568
telemt_me_writer_restored_fallback_total 23
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5582934
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 118863612848 (110.70 GB)
telemt_user_octets_to_client{user="hello"} 2161036416614 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 101890.5 (28h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1492211
telemt_connections_bad_total 36578
telemt_connections_current 431
telemt_connections_me_current 431
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29786
telemt_upstream_connect_attempt_total 47621
telemt_upstream_connect_success_total 47470
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 47593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25044
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 780
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2161
telemt_me_reconnect_success_total 878
telemt_me_reader_eof_total 858
telemt_me_idle_close_by_peer_total 858
telemt_me_route_drop_no_conn_total 511822
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1325296
telemt_me_endpoint_quarantine_total 826
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
telemt_me_writers_active_current 43
telemt_desync_total 8520
telemt_desync_full_logged_total 2542
telemt_desync_suppressed_total 5978
telemt_desync_frames_bucket_total{bucket="1_2"} 2236
telemt_desync_frames_bucket_total{bucket="3_10"} 3281
telemt_desync_frames_bucket_total{bucket="gt_10"} 3003
telemt_pool_swap_total 110
telemt_pool_force_close_total 2850
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 159
telemt_me_draining_writers_reap_progress_total 40077
telemt_me_writer_removed_unexpected_total 830
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3137
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37805
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2762
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37227
telemt_me_writer_teardown_success_total{mode="normal"} 40942
telemt_me_writer_teardown_noop_total 40081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81023
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.119257
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81023
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 159
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 745
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 1321144
telemt_user_connections_current{user="hello"} 431
telemt_user_octets_from_client{user="hello"} 25758296401 (23.99 GB)
telemt_user_octets_to_client{user="hello"} 568914366723 (529.84 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 184088.2 (51h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13266560
telemt_connections_bad_total 1579184
telemt_connections_current 698
telemt_connections_me_current 698
telemt_handshake_timeouts_total 384844
telemt_upstream_connect_attempt_total 71349
telemt_upstream_connect_success_total 71005
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 71213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35732
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2851
telemt_me_reconnect_success_total 1438
telemt_me_reader_eof_total 1421
telemt_me_idle_close_by_peer_total 1421
telemt_me_route_drop_no_conn_total 4477802
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10017879
telemt_me_endpoint_quarantine_total 1275
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1388
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
telemt_me_writers_active_current 48
telemt_desync_total 41852
telemt_desync_full_logged_total 13665
telemt_desync_suppressed_total 28187
telemt_desync_frames_bucket_total{bucket="1_2"} 10062
telemt_desync_frames_bucket_total{bucket="3_10"} 15388
telemt_desync_frames_bucket_total{bucket="gt_10"} 16402
telemt_pool_swap_total 204
telemt_pool_force_close_total 5504
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 671
telemt_me_draining_writers_reap_progress_total 64394
telemt_me_writer_removed_unexpected_total 1361
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5139
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60666
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5330
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58890
telemt_me_writer_teardown_success_total{mode="normal"} 65805
telemt_me_writer_teardown_noop_total 64396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 127600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 129309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 129692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 130068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 130188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 130201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 130201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 130201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 130201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 130201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 130201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 130201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 130201
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.730579
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 130201
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 671
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 1262
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 9984617
telemt_user_connections_current{user="hello"} 698
telemt_user_octets_from_client{user="hello"} 194408220908 (181.06 GB)
telemt_user_octets_to_client{user="hello"} 4430239095352 (4.03 TB)
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 184084.8 (51h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11559438
telemt_connections_bad_total 1327905
telemt_connections_current 534
telemt_connections_me_current 534
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 307957
telemt_upstream_connect_attempt_total 98023
telemt_upstream_connect_success_total 97153
telemt_upstream_connect_fail_total 662
telemt_upstream_connect_attempts_per_request{bucket="1"} 97815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41338
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 662
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10239
telemt_me_reconnect_success_total 2525
telemt_me_reader_eof_total 2344
telemt_me_idle_close_by_peer_total 2343
telemt_me_seq_mismatch_total 92
telemt_me_route_drop_no_conn_total 5638145
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8922094
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
telemt_me_writers_active_current 46
telemt_desync_total 41623
telemt_desync_full_logged_total 13369
telemt_desync_suppressed_total 28254
telemt_desync_frames_bucket_total{bucket="1_2"} 10739
telemt_desync_frames_bucket_total{bucket="3_10"} 15301
telemt_desync_frames_bucket_total{bucket="gt_10"} 15583
telemt_pool_swap_total 194
telemt_pool_force_close_total 5300
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 657
telemt_me_draining_writers_reap_progress_total 64378
telemt_me_writer_removed_unexpected_total 2382
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6499
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60344
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4829
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59078
telemt_me_writer_teardown_success_total{mode="normal"} 66843
telemt_me_writer_teardown_noop_total 64383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 130318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 130857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 131176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 131226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 131226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 131226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 131226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 131226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 131226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 131226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 131226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 131226
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.429080
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 131226
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 657
telemt_me_refill_failed_total 399
telemt_me_writer_restored_same_endpoint_total 2041
telemt_me_writer_restored_fallback_total 127
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 8927441
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 157082258565 (146.29 GB)
telemt_user_octets_to_client{user="hello"} 3473611681707 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 56
```
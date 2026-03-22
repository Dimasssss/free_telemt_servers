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

# Server Metrics 2026-03-22 04:43:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 27429.3 (7h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 448053
telemt_connections_bad_total 30197
telemt_connections_current 1107
telemt_connections_me_current 1107
telemt_handshake_timeouts_total 24859
telemt_upstream_connect_attempt_total 11420
telemt_upstream_connect_success_total 11419
telemt_upstream_connect_attempts_per_request{bucket="1"} 11419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7355
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 306
telemt_me_reconnect_success_total 177
telemt_me_reader_eof_total 173
telemt_me_idle_close_by_peer_total 173
telemt_me_route_drop_no_conn_total 92782
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 369653
telemt_me_endpoint_quarantine_total 220
telemt_me_single_endpoint_shadow_rotate_total 230
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
telemt_me_writers_active_current 44
telemt_desync_total 3306
telemt_desync_full_logged_total 901
telemt_desync_suppressed_total 2405
telemt_desync_frames_bucket_total{bucket="1_2"} 1145
telemt_desync_frames_bucket_total{bucket="3_10"} 1261
telemt_desync_frames_bucket_total{bucket="gt_10"} 900
telemt_pool_swap_total 30
telemt_pool_force_close_total 793
telemt_me_writer_close_signal_drop_total 65
telemt_me_draining_writers_reap_progress_total 10333
telemt_me_writer_removed_unexpected_total 171
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 703
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9793
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 788
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9540
telemt_me_writer_teardown_success_total{mode="normal"} 10496
telemt_me_writer_teardown_noop_total 10334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 20138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 20641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 20752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 20812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 20830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 20830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 20830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 20830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 20830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 20830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 20830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 20830
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.464100
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 20830
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 65
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 160
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 368716
telemt_user_connections_current{user="hello"} 1107
telemt_user_octets_from_client{user="hello"} 5037824372 (4.69 GB)
telemt_user_octets_to_client{user="hello"} 129542993672 (120.65 GB)
telemt_user_unique_ips_current{user="hello"} 467
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 40796.0 (11h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 900362
telemt_connections_bad_total 62717
telemt_connections_current 658
telemt_connections_me_current 658
telemt_handshake_timeouts_total 31630
telemt_upstream_connect_attempt_total 19166
telemt_upstream_connect_success_total 18863
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 19135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10491
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_reconnect_attempts_total 1609
telemt_me_reconnect_success_total 597
telemt_me_reader_eof_total 528
telemt_me_idle_close_by_peer_total 528
telemt_me_route_drop_no_conn_total 361415
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 711177
telemt_me_endpoint_quarantine_total 384
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 333
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
telemt_me_writers_active_current 43
telemt_desync_total 3021
telemt_desync_full_logged_total 1741
telemt_desync_suppressed_total 1280
telemt_desync_frames_bucket_total{bucket="1_2"} 638
telemt_desync_frames_bucket_total{bucket="3_10"} 1161
telemt_desync_frames_bucket_total{bucket="gt_10"} 1222
telemt_pool_swap_total 44
telemt_pool_force_close_total 1178
telemt_me_writer_close_signal_drop_total 85
telemt_me_draining_writers_reap_progress_total 16987
telemt_me_writer_removed_unexpected_total 503
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1426
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16076
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1156
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15809
telemt_me_writer_teardown_success_total{mode="normal"} 17502
telemt_me_writer_teardown_noop_total 16987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34489
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.074942
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34489
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 85
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 448
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 710028
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 11386167544 (10.60 GB)
telemt_user_octets_to_client{user="hello"} 256605560648 (238.98 GB)
telemt_user_unique_ips_current{user="hello"} 436
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 115656.3 (32h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8065495
telemt_connections_bad_total 688328
telemt_connections_current 2461
telemt_connections_me_current 2461
telemt_handshake_timeouts_total 264655
telemt_upstream_connect_attempt_total 43164
telemt_upstream_connect_success_total 43086
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 43094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23394
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1635
telemt_me_reconnect_success_total 851
telemt_me_reader_eof_total 860
telemt_me_idle_close_by_peer_total 860
telemt_me_route_drop_no_conn_total 4591629
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6495724
telemt_me_endpoint_quarantine_total 744
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 868
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 27281
telemt_desync_full_logged_total 9078
telemt_desync_suppressed_total 18203
telemt_desync_frames_bucket_total{bucket="1_2"} 5894
telemt_desync_frames_bucket_total{bucket="3_10"} 10666
telemt_desync_frames_bucket_total{bucket="gt_10"} 10721
telemt_pool_swap_total 125
telemt_pool_force_close_total 4111
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 620
telemt_me_draining_writers_reap_progress_total 39407
telemt_me_writer_removed_unexpected_total 828
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3263
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36501
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3870
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 241
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35296
telemt_me_writer_teardown_success_total{mode="normal"} 39764
telemt_me_writer_teardown_noop_total 39451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79215
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 165.329288
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79215
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 620
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 759
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6487432
telemt_user_connections_current{user="hello"} 2461
telemt_user_octets_from_client{user="hello"} 110038001624 (102.48 GB)
telemt_user_octets_to_client{user="hello"} 2186355623420 (1.99 TB)
telemt_user_unique_ips_current{user="hello"} 1072
telemt_user_unique_ips_recent_window{user="hello"} 332
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 115657.6 (32h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6657584
telemt_connections_bad_total 596797
telemt_connections_current 2499
telemt_connections_me_current 2499
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 220995
telemt_upstream_connect_attempt_total 47105
telemt_upstream_connect_success_total 46707
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 46908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23014
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 558
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2035
telemt_me_reconnect_success_total 913
telemt_me_reader_eof_total 888
telemt_me_idle_close_by_peer_total 888
telemt_me_route_drop_no_conn_total 2303080
telemt_me_route_drop_channel_closed_total 284
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4972912
telemt_me_endpoint_quarantine_total 732
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 894
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 23136
telemt_desync_full_logged_total 7916
telemt_desync_suppressed_total 15220
telemt_desync_frames_bucket_total{bucket="1_2"} 5555
telemt_desync_frames_bucket_total{bucket="3_10"} 8985
telemt_desync_frames_bucket_total{bucket="gt_10"} 8596
telemt_pool_swap_total 126
telemt_pool_force_close_total 3736
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 378
telemt_me_draining_writers_reap_progress_total 37846
telemt_me_writer_removed_unexpected_total 869
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3118
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35538
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3519
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 217
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34110
telemt_me_writer_teardown_success_total{mode="normal"} 38656
telemt_me_writer_teardown_noop_total 37852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76508
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.249150
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76508
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 378
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 795
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 4894534
telemt_user_connections_current{user="hello"} 2499
telemt_user_octets_from_client{user="hello"} 144010338825 (134.12 GB)
telemt_user_octets_to_client{user="hello"} 2334781562119 (2.12 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1098
telemt_user_unique_ips_recent_window{user="hello"} 312
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 115623.0 (32h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6513218
telemt_connections_bad_total 555497
telemt_connections_current 1823
telemt_connections_me_current 1823
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 215552
telemt_upstream_connect_attempt_total 53550
telemt_upstream_connect_success_total 53045
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 53187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24583
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 2361
telemt_me_reconnect_success_total 1033
telemt_me_reader_eof_total 976
telemt_me_idle_close_by_peer_total 976
telemt_me_route_drop_no_conn_total 2259934
telemt_me_route_drop_channel_closed_total 132
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4840981
telemt_me_endpoint_quarantine_total 820
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 861
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
telemt_desync_total 23021
telemt_desync_full_logged_total 7798
telemt_desync_suppressed_total 15223
telemt_desync_frames_bucket_total{bucket="1_2"} 5627
telemt_desync_frames_bucket_total{bucket="3_10"} 8829
telemt_desync_frames_bucket_total{bucket="gt_10"} 8565
telemt_pool_swap_total 124
telemt_pool_force_close_total 3606
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 408
telemt_me_draining_writers_reap_progress_total 38972
telemt_me_writer_removed_unexpected_total 963
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3317
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36637
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3372
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 234
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35366
telemt_me_writer_teardown_success_total{mode="normal"} 39954
telemt_me_writer_teardown_noop_total 38984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78938
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 32.910023
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78938
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 408
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 905
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 4835812
telemt_user_connections_current{user="hello"} 1823
telemt_user_octets_from_client{user="hello"} 136061760575 (126.72 GB)
telemt_user_octets_to_client{user="hello"} 2213357619287 (2.01 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 834
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 115675.4 (32h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20876743
telemt_connections_bad_total 1748711
telemt_connections_current 3414
telemt_connections_me_current 3414
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 633138
telemt_upstream_connect_attempt_total 204044
telemt_upstream_connect_success_total 185735
telemt_upstream_connect_fail_total 16474
telemt_upstream_connect_attempts_per_request{bucket="1"} 202209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44919
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8952
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16474
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65220
telemt_me_reconnect_success_total 2469
telemt_me_reader_eof_total 1556
telemt_me_idle_close_by_peer_total 1555
telemt_me_route_drop_no_conn_total 39654836
telemt_me_route_drop_channel_closed_total 128
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16789556
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 892
telemt_me_single_endpoint_outage_enter_total 144
telemt_me_single_endpoint_outage_exit_total 144
telemt_me_single_endpoint_outage_reconnect_attempt_total 297
telemt_me_single_endpoint_outage_reconnect_success_total 76
telemt_me_single_endpoint_quarantine_bypass_total 297
telemt_me_single_endpoint_shadow_rotate_total 908
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_me_writers_active_current 87
telemt_desync_total 32587
telemt_desync_full_logged_total 9819
telemt_desync_suppressed_total 22768
telemt_desync_frames_bucket_total{bucket="1_2"} 7076
telemt_desync_frames_bucket_total{bucket="3_10"} 14452
telemt_desync_frames_bucket_total{bucket="gt_10"} 11059
telemt_pool_swap_total 119
telemt_pool_force_close_total 3836
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 837
telemt_me_draining_writers_reap_progress_total 36314
telemt_me_writer_removed_unexpected_total 2295
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4908
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33446
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3302
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 534
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32478
telemt_me_writer_teardown_success_total{mode="normal"} 38354
telemt_me_writer_teardown_noop_total 36341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74695
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 217.274574
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74695
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 837
telemt_me_refill_failed_total 3809
telemt_me_writer_restored_same_endpoint_total 1692
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 582
telemt_user_connections_total{user="hello"} 16924251
telemt_user_connections_current{user="hello"} 3414
telemt_user_octets_from_client{user="hello"} 243442068832 (226.72 GB)
telemt_user_octets_to_client{user="hello"} 1293846745667 (1.18 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1397
telemt_user_unique_ips_recent_window{user="hello"} 453
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 115627.9 (32h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6288061
telemt_connections_bad_total 605128
telemt_connections_current 2513
telemt_connections_me_current 2513
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 132776
telemt_upstream_connect_attempt_total 62009
telemt_upstream_connect_success_total 61306
telemt_upstream_connect_fail_total 599
telemt_upstream_connect_attempts_per_request{bucket="1"} 61905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25503
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 599
telemt_me_reconnect_attempts_total 69848
telemt_me_reconnect_success_total 1855
telemt_me_reader_eof_total 1635
telemt_me_idle_close_by_peer_total 1634
telemt_me_route_drop_no_conn_total 2435851
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4880351
telemt_me_endpoint_quarantine_total 785
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 879
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
telemt_desync_total 24340
telemt_desync_full_logged_total 8536
telemt_desync_suppressed_total 15804
telemt_desync_frames_bucket_total{bucket="1_2"} 4775
telemt_desync_frames_bucket_total{bucket="3_10"} 9413
telemt_desync_frames_bucket_total{bucket="gt_10"} 10152
telemt_pool_swap_total 120
telemt_pool_force_close_total 3428
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 408
telemt_me_draining_writers_reap_progress_total 40887
telemt_me_writer_removed_unexpected_total 1671
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4144
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38446
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3027
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37459
telemt_me_writer_teardown_success_total{mode="normal"} 42590
telemt_me_writer_teardown_noop_total 40888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83478
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.852762
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83478
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 408
telemt_me_refill_failed_total 4213
telemt_me_writer_restored_same_endpoint_total 1553
telemt_me_writer_restored_fallback_total 37
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 4872665
telemt_user_connections_current{user="hello"} 2513
telemt_user_octets_from_client{user="hello"} 127606999600 (118.84 GB)
telemt_user_octets_to_client{user="hello"} 2015039241790 (1.83 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1081
telemt_user_unique_ips_recent_window{user="hello"} 314
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 52463.4 (14h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4242556
telemt_connections_bad_total 179315
telemt_connections_current 1793
telemt_connections_me_current 1793
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1687034
telemt_upstream_connect_attempt_total 30885
telemt_upstream_connect_success_total 30681
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 30878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11818
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_reconnect_attempts_total 45981
telemt_me_reconnect_success_total 1017
telemt_me_reader_eof_total 705
telemt_me_idle_close_by_peer_total 705
telemt_me_route_drop_no_conn_total 1064398
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2088453
telemt_me_endpoint_quarantine_total 383
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 409
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 11216
telemt_desync_full_logged_total 3878
telemt_desync_suppressed_total 7338
telemt_desync_frames_bucket_total{bucket="1_2"} 2124
telemt_desync_frames_bucket_total{bucket="3_10"} 4293
telemt_desync_frames_bucket_total{bucket="gt_10"} 4799
telemt_pool_swap_total 57
telemt_pool_force_close_total 1672
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 150
telemt_me_draining_writers_reap_progress_total 19617
telemt_me_writer_removed_unexpected_total 776
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1703
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18719
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1465
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 207
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17945
telemt_me_writer_teardown_success_total{mode="normal"} 20422
telemt_me_writer_teardown_noop_total 19619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40041
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.522847
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40041
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 150
telemt_me_refill_failed_total 2612
telemt_me_writer_restored_same_endpoint_total 910
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2091723
telemt_user_connections_current{user="hello"} 1793
telemt_user_octets_from_client{user="hello"} 56841692616 (52.94 GB)
telemt_user_octets_to_client{user="hello"} 906490513562 (844.24 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 841
telemt_user_unique_ips_recent_window{user="hello"} 288
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 33434.5 (9h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235249
telemt_connections_bad_total 1867
telemt_connections_current 460
telemt_connections_me_current 460
telemt_handshake_timeouts_total 6126
telemt_upstream_connect_attempt_total 16238
telemt_upstream_connect_success_total 16198
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 16235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9276
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 400
telemt_me_reconnect_success_total 222
telemt_me_reader_eof_total 225
telemt_me_idle_close_by_peer_total 225
telemt_me_route_drop_no_conn_total 65476
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 208910
telemt_me_endpoint_quarantine_total 328
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 289
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
telemt_me_writers_active_current 40
telemt_desync_total 1191
telemt_desync_full_logged_total 321
telemt_desync_suppressed_total 870
telemt_desync_frames_bucket_total{bucket="1_2"} 419
telemt_desync_frames_bucket_total{bucket="3_10"} 457
telemt_desync_frames_bucket_total{bucket="gt_10"} 315
telemt_pool_swap_total 37
telemt_pool_force_close_total 803
telemt_me_writer_close_signal_drop_total 29
telemt_me_draining_writers_reap_progress_total 14675
telemt_me_writer_removed_unexpected_total 215
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 935
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13965
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 801
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13872
telemt_me_writer_teardown_success_total{mode="normal"} 14900
telemt_me_writer_teardown_noop_total 14675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29575
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.179831
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29575
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 29
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 194
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 208556
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 3544097552 (3.30 GB)
telemt_user_octets_to_client{user="hello"} 129792271136 (120.88 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 115632.3 (32h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7626990
telemt_connections_bad_total 763814
telemt_connections_current 2393
telemt_connections_me_current 2393
telemt_handshake_timeouts_total 217205
telemt_upstream_connect_attempt_total 45620
telemt_upstream_connect_success_total 45454
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 45583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22912
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_reconnect_attempts_total 1672
telemt_me_reconnect_success_total 891
telemt_me_reader_eof_total 882
telemt_me_idle_close_by_peer_total 882
telemt_me_route_drop_no_conn_total 2172268
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5677107
telemt_me_endpoint_quarantine_total 831
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 888
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
telemt_me_writers_active_current 43
telemt_desync_total 22186
telemt_desync_full_logged_total 7303
telemt_desync_suppressed_total 14883
telemt_desync_frames_bucket_total{bucket="1_2"} 5554
telemt_desync_frames_bucket_total{bucket="3_10"} 8061
telemt_desync_frames_bucket_total{bucket="gt_10"} 8571
telemt_pool_swap_total 128
telemt_pool_force_close_total 3413
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 404
telemt_me_draining_writers_reap_progress_total 41194
telemt_me_writer_removed_unexpected_total 847
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3210
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38856
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3325
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37781
telemt_me_writer_teardown_success_total{mode="normal"} 42066
telemt_me_writer_teardown_noop_total 41196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83262
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.797049
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83262
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 404
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 796
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 5651807
telemt_user_connections_current{user="hello"} 2393
telemt_user_octets_from_client{user="hello"} 112329913700 (104.62 GB)
telemt_user_octets_to_client{user="hello"} 2635240504332 (2.40 TB)
telemt_user_unique_ips_current{user="hello"} 1006
telemt_user_unique_ips_recent_window{user="hello"} 288
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 115628.7 (32h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6609549
telemt_connections_bad_total 647908
telemt_connections_current 2646
telemt_connections_me_current 2646
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 179320
telemt_upstream_connect_attempt_total 61465
telemt_upstream_connect_success_total 61000
telemt_upstream_connect_fail_total 405
telemt_upstream_connect_attempts_per_request{bucket="1"} 61405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24546
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 405
telemt_me_reconnect_attempts_total 5755
telemt_me_reconnect_success_total 1259
telemt_me_reader_eof_total 1131
telemt_me_idle_close_by_peer_total 1131
telemt_me_seq_mismatch_total 52
telemt_me_route_drop_no_conn_total 2226127
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5046529
telemt_me_endpoint_quarantine_total 910
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 886
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
telemt_desync_total 20916
telemt_desync_full_logged_total 6985
telemt_desync_suppressed_total 13931
telemt_desync_frames_bucket_total{bucket="1_2"} 5318
telemt_desync_frames_bucket_total{bucket="3_10"} 7657
telemt_desync_frames_bucket_total{bucket="gt_10"} 7941
telemt_pool_swap_total 126
telemt_pool_force_close_total 3365
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 398
telemt_me_draining_writers_reap_progress_total 39765
telemt_me_writer_removed_unexpected_total 1142
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3770
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37193
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3142
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36400
telemt_me_writer_teardown_success_total{mode="normal"} 40963
telemt_me_writer_teardown_noop_total 39769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80732
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.412761
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80732
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 398
telemt_me_refill_failed_total 259
telemt_me_writer_restored_same_endpoint_total 985
telemt_me_writer_restored_fallback_total 70
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 5049306
telemt_user_connections_current{user="hello"} 2646
telemt_user_octets_from_client{user="hello"} 95200362717 (88.66 GB)
telemt_user_octets_to_client{user="hello"} 2168270001844 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1089
telemt_user_unique_ips_recent_window{user="hello"} 316
```
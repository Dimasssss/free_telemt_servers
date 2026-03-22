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

# Server Metrics 2026-03-22 18:37:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 77474.1 (21h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2832923
telemt_connections_bad_total 179476
telemt_connections_current 1473
telemt_connections_me_current 1473
telemt_handshake_timeouts_total 96066
telemt_upstream_connect_attempt_total 28370
telemt_upstream_connect_success_total 28369
telemt_upstream_connect_attempts_per_request{bucket="1"} 28369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18428
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 68
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1148
telemt_me_reconnect_success_total 482
telemt_me_reader_eof_total 485
telemt_me_idle_close_by_peer_total 485
telemt_me_route_drop_no_conn_total 2322679
telemt_me_route_drop_channel_closed_total 971
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2398359
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 519
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 601
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
telemt_me_writers_active_current 42
telemt_me_writers_warm_current 31
telemt_desync_total 10807
telemt_desync_full_logged_total 3426
telemt_desync_suppressed_total 7381
telemt_desync_frames_bucket_total{bucket="1_2"} 2905
telemt_desync_frames_bucket_total{bucket="3_10"} 4002
telemt_desync_frames_bucket_total{bucket="gt_10"} 3900
telemt_pool_swap_total 85
telemt_pool_force_close_total 2639
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 547
telemt_me_draining_writers_reap_progress_total 25889
telemt_me_writer_removed_unexpected_total 471
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1891
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24225
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2586
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23250
telemt_me_writer_teardown_success_total{mode="normal"} 26116
telemt_me_writer_teardown_noop_total 25899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52015
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 262.607270
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52015
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 547
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 427
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2394436
telemt_user_connections_current{user="hello"} 1473
telemt_user_octets_from_client{user="hello"} 35195409096 (32.78 GB)
telemt_user_octets_to_client{user="hello"} 635766062312 (592.10 GB)
telemt_user_unique_ips_current{user="hello"} 570
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 90839.6 (25h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3753408
telemt_connections_bad_total 337265
telemt_connections_current 1008
telemt_connections_me_current 1008
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 95438
telemt_upstream_connect_attempt_total 55609
telemt_upstream_connect_success_total 54926
telemt_upstream_connect_fail_total 601
telemt_upstream_connect_attempts_per_request{bucket="1"} 55527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23464
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 601
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6360
telemt_me_reconnect_success_total 2334
telemt_me_reader_eof_total 2266
telemt_me_idle_close_by_peer_total 2266
telemt_me_route_drop_no_conn_total 3580316
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2981846
telemt_me_endpoint_quarantine_total 711
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 701
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_me_writers_active_current 42
telemt_desync_total 11848
telemt_desync_full_logged_total 6618
telemt_desync_suppressed_total 5230
telemt_desync_frames_bucket_total{bucket="1_2"} 2727
telemt_desync_frames_bucket_total{bucket="3_10"} 4634
telemt_desync_frames_bucket_total{bucket="gt_10"} 4487
telemt_pool_swap_total 85
telemt_pool_force_close_total 2572
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 214
telemt_me_draining_writers_reap_progress_total 36105
telemt_me_writer_removed_unexpected_total 2217
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4282
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34051
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2183
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33533
telemt_me_writer_teardown_success_total{mode="normal"} 38333
telemt_me_writer_teardown_noop_total 36105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74438
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.331856
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74438
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 214
telemt_me_refill_failed_total 160
telemt_me_writer_restored_same_endpoint_total 2022
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 2992685
telemt_user_connections_current{user="hello"} 1008
telemt_user_octets_from_client{user="hello"} 38678778355 (36.02 GB)
telemt_user_octets_to_client{user="hello"} 694578740398 (646.88 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 607
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 165699.3 (46h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15736100
telemt_connections_bad_total 1510915
telemt_connections_current 2333
telemt_connections_me_current 2333
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 388997
telemt_upstream_connect_attempt_total 74031
telemt_upstream_connect_success_total 73934
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 73951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35285
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1683
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2753
telemt_me_reconnect_success_total 1408
telemt_me_reader_eof_total 1347
telemt_me_idle_close_by_peer_total 1345
telemt_me_route_drop_no_conn_total 13914835
telemt_me_route_drop_channel_closed_total 142
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12541053
telemt_me_endpoint_quarantine_total 1042
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1232
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
telemt_me_writers_warm_current 40
telemt_desync_total 51613
telemt_desync_full_logged_total 16226
telemt_desync_suppressed_total 35387
telemt_desync_frames_bucket_total{bucket="1_2"} 11515
telemt_desync_frames_bucket_total{bucket="3_10"} 20115
telemt_desync_frames_bucket_total{bucket="gt_10"} 19983
telemt_pool_swap_total 178
telemt_pool_force_close_total 6026
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 972
telemt_me_draining_writers_reap_progress_total 54342
telemt_me_writer_removed_unexpected_total 1301
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4755
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50179
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5561
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 465
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48316
telemt_me_writer_teardown_success_total{mode="normal"} 54934
telemt_me_writer_teardown_noop_total 54392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109326
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 305.762422
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109326
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 972
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1212
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 12541805
telemt_user_connections_current{user="hello"} 2333
telemt_user_octets_from_client{user="hello"} 182565423909 (170.03 GB)
telemt_user_octets_to_client{user="hello"} 3289836416663 (2.99 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 939
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 165701.0 (46h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11359302
telemt_connections_bad_total 1121933
telemt_connections_current 1719
telemt_connections_me_current 1719
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 339559
telemt_upstream_connect_attempt_total 86566
telemt_upstream_connect_success_total 85360
telemt_upstream_connect_fail_total 840
telemt_upstream_connect_attempts_per_request{bucket="1"} 86200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35229
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3703
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 840
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4095
telemt_me_reconnect_success_total 1691
telemt_me_reader_eof_total 1559
telemt_me_idle_close_by_peer_total 1559
telemt_me_route_drop_no_conn_total 4446953
telemt_me_route_drop_channel_closed_total 490
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8461998
telemt_me_endpoint_quarantine_total 1052
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1252
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 37615
telemt_desync_full_logged_total 12661
telemt_desync_suppressed_total 24954
telemt_desync_frames_bucket_total{bucket="1_2"} 9263
telemt_desync_frames_bucket_total{bucket="3_10"} 14488
telemt_desync_frames_bucket_total{bucket="gt_10"} 13864
telemt_pool_swap_total 176
telemt_pool_force_close_total 5446
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 690
telemt_me_draining_writers_reap_progress_total 52847
telemt_me_writer_removed_unexpected_total 1598
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4880
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49409
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4945
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 501
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47401
telemt_me_writer_teardown_success_total{mode="normal"} 54289
telemt_me_writer_teardown_noop_total 52870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107159
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 102.805066
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107159
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 690
telemt_me_refill_failed_total 130
telemt_me_writer_restored_same_endpoint_total 1447
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 8400396
telemt_user_connections_current{user="hello"} 1719
telemt_user_octets_from_client{user="hello"} 210254734573 (195.81 GB)
telemt_user_octets_to_client{user="hello"} 3788147454674 (3.45 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 653
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 165665.4 (46h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10689289
telemt_connections_bad_total 920860
telemt_connections_current 1318
telemt_connections_me_current 1318
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 342321
telemt_upstream_connect_attempt_total 71670
telemt_upstream_connect_success_total 70625
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 70809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33700
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1484
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 4890
telemt_me_reconnect_success_total 1964
telemt_me_reader_eof_total 1718
telemt_me_idle_close_by_peer_total 1717
telemt_me_route_drop_no_conn_total 5216164
telemt_me_route_drop_channel_closed_total 371
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8073956
telemt_me_endpoint_quarantine_total 1122
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1215
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_me_writers_warm_current 17
telemt_desync_total 37135
telemt_desync_full_logged_total 12283
telemt_desync_suppressed_total 24852
telemt_desync_frames_bucket_total{bucket="1_2"} 9403
telemt_desync_frames_bucket_total{bucket="3_10"} 14218
telemt_desync_frames_bucket_total{bucket="gt_10"} 13514
telemt_pool_swap_total 173
telemt_pool_force_close_total 5376
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 699
telemt_me_draining_writers_reap_progress_total 53056
telemt_me_writer_removed_unexpected_total 1859
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5323
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49509
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4831
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 545
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47680
telemt_me_writer_teardown_success_total{mode="normal"} 54832
telemt_me_writer_teardown_noop_total 53127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107959
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.517409
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107959
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 699
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 1697
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 8066505
telemt_user_connections_current{user="hello"} 1318
telemt_user_octets_from_client{user="hello"} 186237168701 (173.45 GB)
telemt_user_octets_to_client{user="hello"} 3358223893225 (3.05 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 503
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 35944.6 (9h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10581172
telemt_connections_bad_total 647474
telemt_connections_current 2244
telemt_connections_me_current 2244
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 218332
telemt_upstream_connect_attempt_total 42573
telemt_upstream_connect_success_total 40438
telemt_upstream_connect_fail_total 1489
telemt_upstream_connect_attempts_per_request{bucket="1"} 41927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12406
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5924
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1489
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6326
telemt_me_reconnect_success_total 816
telemt_me_reader_eof_total 519
telemt_me_idle_close_by_peer_total 519
telemt_me_route_drop_no_conn_total 25115711
telemt_me_route_drop_channel_closed_total 53
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8789213
telemt_me_endpoint_quarantine_total 222
telemt_me_single_endpoint_outage_enter_total 61
telemt_me_single_endpoint_outage_exit_total 61
telemt_me_single_endpoint_outage_reconnect_attempt_total 112
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 112
telemt_me_single_endpoint_shadow_rotate_total 281
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
telemt_me_writers_active_current 44
telemt_desync_total 14048
telemt_desync_full_logged_total 3666
telemt_desync_suppressed_total 10382
telemt_desync_frames_bucket_total{bucket="1_2"} 2591
telemt_desync_frames_bucket_total{bucket="3_10"} 5692
telemt_desync_frames_bucket_total{bucket="gt_10"} 5765
telemt_pool_swap_total 35
telemt_pool_force_close_total 1316
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 397
telemt_me_draining_writers_reap_progress_total 10120
telemt_me_writer_removed_unexpected_total 721
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1532
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9267
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1030
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 286
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8804
telemt_me_writer_teardown_success_total{mode="normal"} 10799
telemt_me_writer_teardown_noop_total 10126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 17814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 19243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 19759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 20437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 20768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 20876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 20925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 20925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 20925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 20925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 20925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 20925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 20925
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 44.888875
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 20925
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 397
telemt_me_refill_failed_total 305
telemt_me_writer_restored_same_endpoint_total 545
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 8810778
telemt_user_connections_current{user="hello"} 2244
telemt_user_octets_from_client{user="hello"} 78838589535 (73.42 GB)
telemt_user_octets_to_client{user="hello"} 419487990017 (390.68 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 792
telemt_user_unique_ips_recent_window{user="hello"} 278
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 165671.3 (46h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10536760
telemt_connections_bad_total 888245
telemt_connections_current 1799
telemt_connections_me_current 1799
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 232601
telemt_upstream_connect_attempt_total 100520
telemt_upstream_connect_success_total 99461
telemt_upstream_connect_fail_total 902
telemt_upstream_connect_attempts_per_request{bucket="1"} 100363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36965
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1325
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 902
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72195
telemt_me_reconnect_success_total 2721
telemt_me_reader_eof_total 2413
telemt_me_idle_close_by_peer_total 2411
telemt_me_route_drop_no_conn_total 5146432
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8316466
telemt_me_endpoint_quarantine_total 1098
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1234
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 16
telemt_desync_total 44114
telemt_desync_full_logged_total 15049
telemt_desync_suppressed_total 29065
telemt_desync_frames_bucket_total{bucket="1_2"} 8950
telemt_desync_frames_bucket_total{bucket="3_10"} 16944
telemt_desync_frames_bucket_total{bucket="gt_10"} 18220
telemt_pool_swap_total 169
telemt_pool_force_close_total 5032
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 623
telemt_me_draining_writers_reap_progress_total 56327
telemt_me_writer_removed_unexpected_total 2453
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6000
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52804
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4336
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 696
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51295
telemt_me_writer_teardown_success_total{mode="normal"} 58804
telemt_me_writer_teardown_noop_total 56328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115132
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.848904
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115132
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 623
telemt_me_refill_failed_total 4281
telemt_me_writer_restored_same_endpoint_total 2279
telemt_me_writer_restored_fallback_total 47
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 8320002
telemt_user_connections_current{user="hello"} 1799
telemt_user_octets_from_client{user="hello"} 188834242189 (175.87 GB)
telemt_user_octets_to_client{user="hello"} 3155864351640 (2.87 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 693
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 102507.4 (28h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11062342
telemt_connections_bad_total 427678
telemt_connections_current 1757
telemt_connections_me_current 1757
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4589511
telemt_upstream_connect_attempt_total 48609
telemt_upstream_connect_success_total 48248
telemt_upstream_connect_fail_total 352
telemt_upstream_connect_attempts_per_request{bucket="1"} 48600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21367
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 352
telemt_me_reconnect_attempts_total 48251
telemt_me_reconnect_success_total 1585
telemt_me_reader_eof_total 1242
telemt_me_idle_close_by_peer_total 1241
telemt_me_route_drop_no_conn_total 3995571
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5318511
telemt_me_endpoint_quarantine_total 663
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 772
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 29742
telemt_desync_full_logged_total 10063
telemt_desync_suppressed_total 19679
telemt_desync_frames_bucket_total{bucket="1_2"} 5973
telemt_desync_frames_bucket_total{bucket="3_10"} 11749
telemt_desync_frames_bucket_total{bucket="gt_10"} 12020
telemt_pool_swap_total 108
telemt_pool_force_close_total 3305
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 342
telemt_me_draining_writers_reap_progress_total 35279
telemt_me_writer_removed_unexpected_total 1303
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3142
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33473
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 423
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31974
telemt_me_writer_teardown_success_total{mode="normal"} 36615
telemt_me_writer_teardown_noop_total 35286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71901
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.315343
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71901
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 342
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1409
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5311570
telemt_user_connections_current{user="hello"} 1757
telemt_user_octets_from_client{user="hello"} 114262203100 (106.41 GB)
telemt_user_octets_to_client{user="hello"} 2022907729270 (1.84 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 634
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 83478.5 (23h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1217214
telemt_connections_bad_total 25961
telemt_connections_current 1233
telemt_connections_me_current 1233
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 23765
telemt_upstream_connect_attempt_total 40037
telemt_upstream_connect_success_total 39919
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 40011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 647
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1785
telemt_me_reconnect_success_total 770
telemt_me_reader_eof_total 742
telemt_me_idle_close_by_peer_total 742
telemt_me_route_drop_no_conn_total 423546
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1078312
telemt_me_endpoint_quarantine_total 704
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 687
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
telemt_desync_total 6227
telemt_desync_full_logged_total 1919
telemt_desync_suppressed_total 4308
telemt_desync_frames_bucket_total{bucket="1_2"} 1415
telemt_desync_frames_bucket_total{bucket="3_10"} 2455
telemt_desync_frames_bucket_total{bucket="gt_10"} 2357
telemt_pool_swap_total 89
telemt_pool_force_close_total 2290
telemt_me_writer_close_signal_drop_total 132
telemt_me_draining_writers_reap_progress_total 33270
telemt_me_writer_removed_unexpected_total 716
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2595
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31420
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2207
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30980
telemt_me_writer_teardown_success_total{mode="normal"} 34015
telemt_me_writer_teardown_noop_total 33274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67289
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.066807
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67289
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 132
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 652
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 1074589
telemt_user_connections_current{user="hello"} 1234
telemt_user_octets_from_client{user="hello"} 19728738789 (18.37 GB)
telemt_user_octets_to_client{user="hello"} 458587052279 (427.09 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 421
telemt_user_unique_ips_recent_window{user="hello"} 196
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 165676.6 (46h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12838408
telemt_connections_bad_total 1491973
telemt_connections_current 1995
telemt_connections_me_current 1995
telemt_handshake_timeouts_total 362753
telemt_upstream_connect_attempt_total 62367
telemt_upstream_connect_success_total 62042
telemt_upstream_connect_fail_total 193
telemt_upstream_connect_attempts_per_request{bucket="1"} 62235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31324
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 193
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2435
telemt_me_reconnect_success_total 1296
telemt_me_reader_eof_total 1257
telemt_me_idle_close_by_peer_total 1257
telemt_me_route_drop_no_conn_total 4372493
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9716258
telemt_me_endpoint_quarantine_total 1102
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1235
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 32
telemt_desync_total 39956
telemt_desync_full_logged_total 13033
telemt_desync_suppressed_total 26923
telemt_desync_frames_bucket_total{bucket="1_2"} 9533
telemt_desync_frames_bucket_total{bucket="3_10"} 14757
telemt_desync_frames_bucket_total{bucket="gt_10"} 15666
telemt_pool_swap_total 183
telemt_pool_force_close_total 5048
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 640
telemt_me_draining_writers_reap_progress_total 56088
telemt_me_writer_removed_unexpected_total 1211
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4618
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52717
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4874
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51040
telemt_me_writer_teardown_success_total{mode="normal"} 57335
telemt_me_writer_teardown_noop_total 56090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113425
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.091457
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113425
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 640
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 1134
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 9684225
telemt_user_connections_current{user="hello"} 1995
telemt_user_octets_from_client{user="hello"} 189574832028 (176.56 GB)
telemt_user_octets_to_client{user="hello"} 4270204530492 (3.88 TB)
telemt_user_unique_ips_current{user="hello"} 674
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 165672.5 (46h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11148553
telemt_connections_bad_total 1256829
telemt_connections_current 1621
telemt_connections_me_current 1621
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 291232
telemt_upstream_connect_attempt_total 88441
telemt_upstream_connect_success_total 87659
telemt_upstream_connect_fail_total 595
telemt_upstream_connect_attempts_per_request{bucket="1"} 88254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2056
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 595
telemt_me_reconnect_attempts_total 9516
telemt_me_reconnect_success_total 2227
telemt_me_reader_eof_total 2074
telemt_me_idle_close_by_peer_total 2074
telemt_me_seq_mismatch_total 77
telemt_me_route_drop_no_conn_total 5545314
telemt_me_route_drop_channel_closed_total 351
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8620342
telemt_me_endpoint_quarantine_total 1270
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1235
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 18
telemt_desync_total 39248
telemt_desync_full_logged_total 12691
telemt_desync_suppressed_total 26557
telemt_desync_frames_bucket_total{bucket="1_2"} 9771
telemt_desync_frames_bucket_total{bucket="3_10"} 14600
telemt_desync_frames_bucket_total{bucket="gt_10"} 14877
telemt_pool_swap_total 174
telemt_pool_force_close_total 4863
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 627
telemt_me_draining_writers_reap_progress_total 55694
telemt_me_writer_removed_unexpected_total 2101
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5838
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52029
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 456
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50831
telemt_me_writer_teardown_success_total{mode="normal"} 57867
telemt_me_writer_teardown_noop_total 55699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113566
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.017381
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113566
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 627
telemt_me_refill_failed_total 376
telemt_me_writer_restored_same_endpoint_total 1805
telemt_me_writer_restored_fallback_total 105
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 8626095
telemt_user_connections_current{user="hello"} 1621
telemt_user_octets_from_client{user="hello"} 151907742329 (141.48 GB)
telemt_user_octets_to_client{user="hello"} 3316168627567 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 622
telemt_user_unique_ips_recent_window{user="hello"} 281
```
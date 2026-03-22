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

# Server Metrics 2026-03-22 12:54:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 56858.6 (15h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1722961
telemt_connections_bad_total 79351
telemt_connections_current 1646
telemt_connections_me_current 1646
telemt_handshake_timeouts_total 76078
telemt_upstream_connect_attempt_total 21488
telemt_upstream_connect_success_total 21487
telemt_upstream_connect_attempts_per_request{bucket="1"} 21487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13991
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 893
telemt_me_reconnect_success_total 350
telemt_me_reader_eof_total 354
telemt_me_idle_close_by_peer_total 354
telemt_me_route_drop_no_conn_total 1145250
telemt_me_route_drop_channel_closed_total 534
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1459080
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 398
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 451
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
telemt_me_writers_active_current 44
telemt_desync_total 8511
telemt_desync_full_logged_total 2585
telemt_desync_suppressed_total 5926
telemt_desync_frames_bucket_total{bucket="1_2"} 2389
telemt_desync_frames_bucket_total{bucket="3_10"} 3203
telemt_desync_frames_bucket_total{bucket="gt_10"} 2919
telemt_pool_swap_total 63
telemt_pool_force_close_total 1854
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 296
telemt_me_draining_writers_reap_progress_total 19554
telemt_me_writer_removed_unexpected_total 345
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1391
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18384
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1818
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17700
telemt_me_writer_teardown_success_total{mode="normal"} 19775
telemt_me_writer_teardown_noop_total 19556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39331
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 140.347129
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39331
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 296
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 309
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 1456261
telemt_user_connections_current{user="hello"} 1646
telemt_user_octets_from_client{user="hello"} 23229129280 (21.63 GB)
telemt_user_octets_to_client{user="hello"} 432451461240 (402.75 GB)
telemt_user_unique_ips_current{user="hello"} 652
telemt_user_unique_ips_recent_window{user="hello"} 344
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 70224.9 (19h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2781526
telemt_connections_bad_total 261672
telemt_connections_current 2436
telemt_connections_me_current 2436
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 66036
telemt_upstream_connect_attempt_total 45901
telemt_upstream_connect_success_total 45366
telemt_upstream_connect_fail_total 473
telemt_upstream_connect_attempts_per_request{bucket="1"} 45839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17790
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 473
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3487
telemt_me_reconnect_success_total 1584
telemt_me_reader_eof_total 1466
telemt_me_idle_close_by_peer_total 1466
telemt_me_route_drop_no_conn_total 2458993
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2177912
telemt_me_endpoint_quarantine_total 592
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 548
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
telemt_me_writers_active_current 46
telemt_desync_total 8682
telemt_desync_full_logged_total 4875
telemt_desync_suppressed_total 3807
telemt_desync_frames_bucket_total{bucket="1_2"} 2048
telemt_desync_frames_bucket_total{bucket="3_10"} 3380
telemt_desync_frames_bucket_total{bucket="gt_10"} 3254
telemt_pool_swap_total 69
telemt_pool_force_close_total 1975
telemt_me_writer_close_signal_drop_total 165
telemt_me_draining_writers_reap_progress_total 27931
telemt_me_writer_removed_unexpected_total 1426
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3050
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26307
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1737
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 238
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25956
telemt_me_writer_teardown_success_total{mode="normal"} 29357
telemt_me_writer_teardown_noop_total 27931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57288
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.029654
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57288
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 165
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 1321
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 2189614
telemt_user_connections_current{user="hello"} 2436
telemt_user_octets_from_client{user="hello"} 26921345843 (25.07 GB)
telemt_user_octets_to_client{user="hello"} 526982484298 (490.79 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1410
telemt_user_unique_ips_recent_window{user="hello"} 598
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 145085.7 (40h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13154220
telemt_connections_bad_total 1162857
telemt_connections_current 4814
telemt_connections_me_current 4814
telemt_handshake_timeouts_total 339684
telemt_upstream_connect_attempt_total 52823
telemt_upstream_connect_success_total 52743
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 52751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28629
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2404
telemt_me_reconnect_success_total 1265
telemt_me_reader_eof_total 1207
telemt_me_idle_close_by_peer_total 1206
telemt_me_route_drop_no_conn_total 10877622
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10514719
telemt_me_endpoint_quarantine_total 925
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1082
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 43383
telemt_desync_full_logged_total 13830
telemt_desync_suppressed_total 29553
telemt_desync_frames_bucket_total{bucket="1_2"} 9806
telemt_desync_frames_bucket_total{bucket="3_10"} 16945
telemt_desync_frames_bucket_total{bucket="gt_10"} 16632
telemt_pool_swap_total 156
telemt_pool_force_close_total 5304
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 844
telemt_me_draining_writers_reap_progress_total 48136
telemt_me_writer_removed_unexpected_total 1165
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4198
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44447
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4875
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 429
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42832
telemt_me_writer_teardown_success_total{mode="normal"} 48645
telemt_me_writer_teardown_noop_total 48184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96829
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 238.726411
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96829
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 844
telemt_me_refill_failed_total 63
telemt_me_writer_restored_same_endpoint_total 1090
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 10502909
telemt_user_connections_current{user="hello"} 4814
telemt_user_octets_from_client{user="hello"} 155022240708 (144.38 GB)
telemt_user_octets_to_client{user="hello"} 2898050601804 (2.64 TB)
telemt_user_unique_ips_current{user="hello"} 1866
telemt_user_unique_ips_recent_window{user="hello"} 818
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 145086.4 (40h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9905715
telemt_connections_bad_total 912608
telemt_connections_current 4597
telemt_connections_me_current 4597
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 298327
telemt_upstream_connect_attempt_total 79294
telemt_upstream_connect_success_total 78162
telemt_upstream_connect_fail_total 815
telemt_upstream_connect_attempts_per_request{bucket="1"} 78977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31264
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3674
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 815
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3462
telemt_me_reconnect_success_total 1415
telemt_me_reader_eof_total 1300
telemt_me_idle_close_by_peer_total 1300
telemt_me_route_drop_no_conn_total 3964698
telemt_me_route_drop_channel_closed_total 411
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7389535
telemt_me_endpoint_quarantine_total 907
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 1102
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 33427
telemt_desync_full_logged_total 11265
telemt_desync_suppressed_total 22162
telemt_desync_frames_bucket_total{bucket="1_2"} 8250
telemt_desync_frames_bucket_total{bucket="3_10"} 12857
telemt_desync_frames_bucket_total{bucket="gt_10"} 12320
telemt_pool_swap_total 155
telemt_pool_force_close_total 4732
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 587
telemt_me_draining_writers_reap_progress_total 46489
telemt_me_writer_removed_unexpected_total 1332
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4187
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43502
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4327
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 405
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41757
telemt_me_writer_teardown_success_total{mode="normal"} 47689
telemt_me_writer_teardown_noop_total 46501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94190
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 84.737384
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94190
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 587
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 1212
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 7329681
telemt_user_connections_current{user="hello"} 4597
telemt_user_octets_from_client{user="hello"} 189567223113 (176.55 GB)
telemt_user_octets_to_client{user="hello"} 3328188425606 (3.03 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1835
telemt_user_unique_ips_recent_window{user="hello"} 647
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 145050.3 (40h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9334165
telemt_connections_bad_total 789836
telemt_connections_current 4048
telemt_connections_me_current 4048
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 296414
telemt_upstream_connect_attempt_total 64422
telemt_upstream_connect_success_total 63667
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 63829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29883
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1965
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 306
telemt_me_reconnect_attempts_total 3887
telemt_me_reconnect_success_total 1687
telemt_me_reader_eof_total 1509
telemt_me_idle_close_by_peer_total 1508
telemt_me_route_drop_no_conn_total 4037583
telemt_me_route_drop_channel_closed_total 293
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7032345
telemt_me_endpoint_quarantine_total 999
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1065
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
telemt_desync_total 33203
telemt_desync_full_logged_total 11008
telemt_desync_suppressed_total 22195
telemt_desync_frames_bucket_total{bucket="1_2"} 8444
telemt_desync_frames_bucket_total{bucket="3_10"} 12701
telemt_desync_frames_bucket_total{bucket="gt_10"} 12058
telemt_pool_swap_total 152
telemt_pool_force_close_total 4701
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 611
telemt_me_draining_writers_reap_progress_total 47115
telemt_me_writer_removed_unexpected_total 1589
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4571
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44055
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4210
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 491
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42414
telemt_me_writer_teardown_success_total{mode="normal"} 48626
telemt_me_writer_teardown_noop_total 47182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95808
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3093.992127
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95808
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 611
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1468
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 7023942
telemt_user_connections_current{user="hello"} 4048
telemt_user_octets_from_client{user="hello"} 169243569097 (157.62 GB)
telemt_user_octets_to_client{user="hello"} 3002709633265 (2.73 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1689
telemt_user_unique_ips_recent_window{user="hello"} 588
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 15330.5 (4h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6470814
telemt_connections_bad_total 400116
telemt_connections_current 6499
telemt_connections_me_current 6499
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 102071
telemt_upstream_connect_attempt_total 24541
telemt_upstream_connect_success_total 23439
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 24277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5146
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4634
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_timeout_total 530
telemt_me_reconnect_attempts_total 2349
telemt_me_reconnect_success_total 374
telemt_me_reader_eof_total 241
telemt_me_idle_close_by_peer_total 241
telemt_me_route_drop_no_conn_total 15519079
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5402968
telemt_me_endpoint_quarantine_total 97
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 123
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 6
telemt_desync_total 8142
telemt_desync_full_logged_total 2067
telemt_desync_suppressed_total 6075
telemt_desync_frames_bucket_total{bucket="1_2"} 1457
telemt_desync_frames_bucket_total{bucket="3_10"} 3266
telemt_desync_frames_bucket_total{bucket="gt_10"} 3419
telemt_pool_swap_total 14
telemt_pool_force_close_total 570
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 223
telemt_me_draining_writers_reap_progress_total 3946
telemt_me_writer_removed_unexpected_total 329
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 652
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3580
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 424
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 146
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3376
telemt_me_writer_teardown_success_total{mode="normal"} 4232
telemt_me_writer_teardown_noop_total 3949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8181
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.641107
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8181
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 223
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 253
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 5416270
telemt_user_connections_current{user="hello"} 6499
telemt_user_octets_from_client{user="hello"} 29607632934 (27.57 GB)
telemt_user_octets_to_client{user="hello"} 159266347779 (148.33 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2433
telemt_user_unique_ips_recent_window{user="hello"} 1352
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 145057.3 (40h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9110571
telemt_connections_bad_total 762269
telemt_connections_current 4830
telemt_connections_me_current 4830
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 195376
telemt_upstream_connect_attempt_total 88943
telemt_upstream_connect_success_total 88067
telemt_upstream_connect_fail_total 754
telemt_upstream_connect_attempts_per_request{bucket="1"} 88821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31838
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1251
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 754
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71170
telemt_me_reconnect_success_total 2372
telemt_me_reader_eof_total 2115
telemt_me_idle_close_by_peer_total 2114
telemt_me_route_drop_no_conn_total 4381528
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7198576
telemt_me_endpoint_quarantine_total 973
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1085
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 36844
telemt_desync_full_logged_total 12632
telemt_desync_suppressed_total 24212
telemt_desync_frames_bucket_total{bucket="1_2"} 7501
telemt_desync_frames_bucket_total{bucket="3_10"} 14194
telemt_desync_frames_bucket_total{bucket="gt_10"} 15149
telemt_pool_swap_total 149
telemt_pool_force_close_total 4358
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 527
telemt_me_draining_writers_reap_progress_total 49682
telemt_me_writer_removed_unexpected_total 2143
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5242
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46609
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3761
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 597
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45324
telemt_me_writer_teardown_success_total{mode="normal"} 51851
telemt_me_writer_teardown_noop_total 49683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101534
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.060861
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101534
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 527
telemt_me_refill_failed_total 4247
telemt_me_writer_restored_same_endpoint_total 1991
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 7200709
telemt_user_connections_current{user="hello"} 4830
telemt_user_octets_from_client{user="hello"} 168314341031 (156.75 GB)
telemt_user_octets_to_client{user="hello"} 2765854147673 (2.52 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2007
telemt_user_unique_ips_recent_window{user="hello"} 699
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 81893.4 (22h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8757375
telemt_connections_bad_total 312407
telemt_connections_current 4516
telemt_connections_me_current 4516
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3679470
telemt_upstream_connect_attempt_total 41176
telemt_upstream_connect_success_total 40886
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 41169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_reconnect_attempts_total 47862
telemt_me_reconnect_success_total 1416
telemt_me_reader_eof_total 1085
telemt_me_idle_close_by_peer_total 1085
telemt_me_route_drop_no_conn_total 3043727
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4243576
telemt_me_endpoint_quarantine_total 542
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 616
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 23373
telemt_desync_full_logged_total 7830
telemt_desync_suppressed_total 15543
telemt_desync_frames_bucket_total{bucket="1_2"} 4759
telemt_desync_frames_bucket_total{bucket="3_10"} 9141
telemt_desync_frames_bucket_total{bucket="gt_10"} 9473
telemt_pool_swap_total 85
telemt_pool_force_close_total 2637
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 270
telemt_me_draining_writers_reap_progress_total 28661
telemt_me_writer_removed_unexpected_total 1150
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2587
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27252
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2242
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 395
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26024
telemt_me_writer_teardown_success_total{mode="normal"} 29839
telemt_me_writer_teardown_noop_total 28668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58507
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.842115
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58507
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 270
telemt_me_refill_failed_total 2700
telemt_me_writer_restored_same_endpoint_total 1267
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4239298
telemt_user_connections_current{user="hello"} 4516
telemt_user_octets_from_client{user="hello"} 94612094532 (88.11 GB)
telemt_user_octets_to_client{user="hello"} 1658474713462 (1.51 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1784
telemt_user_unique_ips_recent_window{user="hello"} 625
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 62863.7 (17h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 714403
telemt_connections_bad_total 8458
telemt_connections_current 914
telemt_connections_me_current 914
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 13838
telemt_upstream_connect_attempt_total 32152
telemt_upstream_connect_success_total 32071
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 32138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16929
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 380
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_reconnect_attempts_total 1405
telemt_me_reconnect_success_total 612
telemt_me_reader_eof_total 592
telemt_me_idle_close_by_peer_total 592
telemt_me_route_drop_no_conn_total 239451
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 644972
telemt_me_endpoint_quarantine_total 568
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 525
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 3485
telemt_desync_full_logged_total 1030
telemt_desync_suppressed_total 2455
telemt_desync_frames_bucket_total{bucket="1_2"} 855
telemt_desync_frames_bucket_total{bucket="3_10"} 1389
telemt_desync_frames_bucket_total{bucket="gt_10"} 1241
telemt_pool_swap_total 66
telemt_pool_force_close_total 1624
telemt_me_writer_close_signal_drop_total 96
telemt_me_draining_writers_reap_progress_total 26342
telemt_me_writer_removed_unexpected_total 574
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2003
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24933
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1547
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24718
telemt_me_writer_teardown_success_total{mode="normal"} 26936
telemt_me_writer_teardown_noop_total 26344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53280
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.899596
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53280
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 96
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 531
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 646660
telemt_user_connections_current{user="hello"} 914
telemt_user_octets_from_client{user="hello"} 12395515021 (11.54 GB)
telemt_user_octets_to_client{user="hello"} 310790868551 (289.45 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 359
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 145062.1 (40h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11113971
telemt_connections_bad_total 1289518
telemt_connections_current 5883
telemt_connections_me_current 5883
telemt_handshake_timeouts_total 298547
telemt_upstream_connect_attempt_total 55019
telemt_upstream_connect_success_total 54806
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 54971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27728
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_reconnect_attempts_total 2154
telemt_me_reconnect_success_total 1147
telemt_me_reader_eof_total 1111
telemt_me_idle_close_by_peer_total 1111
telemt_me_route_drop_no_conn_total 3494104
telemt_me_route_drop_channel_closed_total 87
telemt_me_route_drop_queue_full_total 32
telemt_me_route_drop_queue_full_profile_total{profile="high"} 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8350211
telemt_me_endpoint_quarantine_total 1002
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1090
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 34006
telemt_desync_full_logged_total 11147
telemt_desync_suppressed_total 22859
telemt_desync_frames_bucket_total{bucket="1_2"} 8157
telemt_desync_frames_bucket_total{bucket="3_10"} 12579
telemt_desync_frames_bucket_total{bucket="gt_10"} 13270
telemt_pool_swap_total 161
telemt_pool_force_close_total 4384
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 549
telemt_me_draining_writers_reap_progress_total 49554
telemt_me_writer_removed_unexpected_total 1066
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4049
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46607
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4234
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 150
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45170
telemt_me_writer_teardown_success_total{mode="normal"} 50656
telemt_me_writer_teardown_noop_total 49556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100212
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.643658
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100212
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 549
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 1003
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 8321186
telemt_user_connections_current{user="hello"} 5883
telemt_user_octets_from_client{user="hello"} 159632945488 (148.67 GB)
telemt_user_octets_to_client{user="hello"} 3764890599372 (3.42 TB)
telemt_user_unique_ips_current{user="hello"} 2278
telemt_user_unique_ips_recent_window{user="hello"} 710
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 145058.9 (40h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9631820
telemt_connections_bad_total 1082884
telemt_connections_current 4241
telemt_connections_me_current 4241
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 250592
telemt_upstream_connect_attempt_total 80298
telemt_upstream_connect_success_total 79713
telemt_upstream_connect_fail_total 507
telemt_upstream_connect_attempts_per_request{bucket="1"} 80220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32630
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1996
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 507
telemt_me_reconnect_attempts_total 8497
telemt_me_reconnect_success_total 1868
telemt_me_reader_eof_total 1740
telemt_me_idle_close_by_peer_total 1740
telemt_me_seq_mismatch_total 70
telemt_me_route_drop_no_conn_total 4173091
telemt_me_route_drop_channel_closed_total 302
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7407466
telemt_me_endpoint_quarantine_total 1113
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1094
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 33345
telemt_desync_full_logged_total 10906
telemt_desync_suppressed_total 22439
telemt_desync_frames_bucket_total{bucket="1_2"} 8246
telemt_desync_frames_bucket_total{bucket="3_10"} 12427
telemt_desync_frames_bucket_total{bucket="gt_10"} 12672
telemt_pool_swap_total 155
telemt_pool_force_close_total 4256
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 537
telemt_me_draining_writers_reap_progress_total 48647
telemt_me_writer_removed_unexpected_total 1764
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5013
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45464
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3893
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 363
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44391
telemt_me_writer_teardown_success_total{mode="normal"} 50477
telemt_me_writer_teardown_noop_total 48651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99128
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.332654
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99128
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 537
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 1512
telemt_me_writer_restored_fallback_total 94
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 7415037
telemt_user_connections_current{user="hello"} 4241
telemt_user_octets_from_client{user="hello"} 131119843129 (122.11 GB)
telemt_user_octets_to_client{user="hello"} 2953871605171 (2.69 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1797
telemt_user_unique_ips_recent_window{user="hello"} 662
```
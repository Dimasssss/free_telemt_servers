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

# Server Metrics 2026-03-22 09:19:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 43984.6 (12h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1095087
telemt_connections_bad_total 60043
telemt_connections_current 1721
telemt_connections_me_current 1721
telemt_handshake_timeouts_total 49977
telemt_upstream_connect_attempt_total 17273
telemt_upstream_connect_success_total 17272
telemt_upstream_connect_attempts_per_request{bucket="1"} 17272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11209
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 493
telemt_me_reconnect_success_total 265
telemt_me_reader_eof_total 263
telemt_me_idle_close_by_peer_total 263
telemt_me_route_drop_no_conn_total 598162
telemt_me_route_drop_channel_closed_total 225
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 911326
telemt_me_endpoint_quarantine_total 308
telemt_me_single_endpoint_shadow_rotate_total 352
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 6571
telemt_desync_full_logged_total 1884
telemt_desync_suppressed_total 4687
telemt_desync_frames_bucket_total{bucket="1_2"} 1942
telemt_desync_frames_bucket_total{bucket="3_10"} 2473
telemt_desync_frames_bucket_total{bucket="gt_10"} 2156
telemt_pool_swap_total 48
telemt_pool_force_close_total 1362
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 157
telemt_me_draining_writers_reap_progress_total 15684
telemt_me_writer_removed_unexpected_total 260
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1083
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14812
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1334
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14322
telemt_me_writer_teardown_success_total{mode="normal"} 15895
telemt_me_writer_teardown_noop_total 15686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31581
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 59.732885
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31581
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 157
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 243
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 909670
telemt_user_connections_current{user="hello"} 1721
telemt_user_octets_from_client{user="hello"} 14334792084 (13.35 GB)
telemt_user_octets_to_client{user="hello"} 291602548640 (271.58 GB)
telemt_user_unique_ips_current{user="hello"} 626
telemt_user_unique_ips_recent_window{user="hello"} 252
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 57350.8 (15h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1638630
telemt_connections_bad_total 155131
telemt_connections_current 2213
telemt_connections_me_current 2213
telemt_handshake_timeouts_total 44609
telemt_upstream_connect_attempt_total 34259
telemt_upstream_connect_success_total 33816
telemt_upstream_connect_fail_total 389
telemt_upstream_connect_attempts_per_request{bucket="1"} 34205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 389
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2576
telemt_me_reconnect_success_total 1098
telemt_me_reader_eof_total 992
telemt_me_idle_close_by_peer_total 992
telemt_me_route_drop_no_conn_total 848373
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1245968
telemt_me_endpoint_quarantine_total 505
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 454
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
telemt_desync_total 5608
telemt_desync_full_logged_total 3226
telemt_desync_suppressed_total 2382
telemt_desync_frames_bucket_total{bucket="1_2"} 1242
telemt_desync_frames_bucket_total{bucket="3_10"} 2188
telemt_desync_frames_bucket_total{bucket="gt_10"} 2178
telemt_pool_swap_total 59
telemt_pool_force_close_total 1610
telemt_me_writer_close_signal_drop_total 132
telemt_me_draining_writers_reap_progress_total 23251
telemt_me_writer_removed_unexpected_total 960
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2298
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21904
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1486
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21641
telemt_me_writer_teardown_success_total{mode="normal"} 24202
telemt_me_writer_teardown_noop_total 23251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47453
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.168083
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47453
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 132
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 879
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1252117
telemt_user_connections_current{user="hello"} 2213
telemt_user_octets_from_client{user="hello"} 18677155618 (17.39 GB)
telemt_user_octets_to_client{user="hello"} 405767720064 (377.90 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 1326
telemt_user_unique_ips_recent_window{user="hello"} 672
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 132210.9 (36h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10212348
telemt_connections_bad_total 913701
telemt_connections_current 5646
telemt_connections_me_current 5646
telemt_handshake_timeouts_total 297877
telemt_upstream_connect_attempt_total 48612
telemt_upstream_connect_success_total 48532
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 48540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26384
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1973
telemt_me_reconnect_success_total 1028
telemt_me_reader_eof_total 1025
telemt_me_idle_close_by_peer_total 1024
telemt_me_route_drop_no_conn_total 6159476
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8031188
telemt_me_endpoint_quarantine_total 840
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 989
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
telemt_desync_total 34553
telemt_desync_full_logged_total 11308
telemt_desync_suppressed_total 23245
telemt_desync_frames_bucket_total{bucket="1_2"} 7607
telemt_desync_frames_bucket_total{bucket="3_10"} 13447
telemt_desync_frames_bucket_total{bucket="gt_10"} 13499
telemt_pool_swap_total 142
telemt_pool_force_close_total 4746
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 728
telemt_me_draining_writers_reap_progress_total 44360
telemt_me_writer_removed_unexpected_total 985
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3743
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41059
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4428
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 318
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39614
telemt_me_writer_teardown_success_total{mode="normal"} 44802
telemt_me_writer_teardown_noop_total 44404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89206
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 192.924133
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89206
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 728
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 911
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 8021145
telemt_user_connections_current{user="hello"} 5646
telemt_user_octets_from_client{user="hello"} 129903937708 (120.98 GB)
telemt_user_octets_to_client{user="hello"} 2605826652020 (2.37 TB)
telemt_user_unique_ips_current{user="hello"} 2107
telemt_user_unique_ips_recent_window{user="hello"} 909
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 132212.1 (36h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8240254
telemt_connections_bad_total 738700
telemt_connections_current 3980
telemt_connections_me_current 3980
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 261964
telemt_upstream_connect_attempt_total 54590
telemt_upstream_connect_success_total 54100
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 54346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26472
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2937
telemt_me_reconnect_success_total 1113
telemt_me_reader_eof_total 1026
telemt_me_idle_close_by_peer_total 1026
telemt_me_route_drop_no_conn_total 2856933
telemt_me_route_drop_channel_closed_total 330
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6102916
telemt_me_endpoint_quarantine_total 837
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 1017
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 28089
telemt_desync_full_logged_total 9528
telemt_desync_suppressed_total 18561
telemt_desync_frames_bucket_total{bucket="1_2"} 6796
telemt_desync_frames_bucket_total{bucket="3_10"} 10873
telemt_desync_frames_bucket_total{bucket="gt_10"} 10420
telemt_pool_swap_total 144
telemt_pool_force_close_total 4337
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 470
telemt_me_draining_writers_reap_progress_total 42540
telemt_me_writer_removed_unexpected_total 1044
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3637
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39840
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4075
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 262
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38203
telemt_me_writer_teardown_success_total{mode="normal"} 43477
telemt_me_writer_teardown_noop_total 42546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86023
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 61.938054
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86023
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 470
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 938
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 6025233
telemt_user_connections_current{user="hello"} 3980
telemt_user_octets_from_client{user="hello"} 164027170091 (152.76 GB)
telemt_user_octets_to_client{user="hello"} 2862799865726 (2.60 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1462
telemt_user_unique_ips_recent_window{user="hello"} 582
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 132177.4 (36h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7895486
telemt_connections_bad_total 659997
telemt_connections_current 4749
telemt_connections_me_current 4749
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 260842
telemt_upstream_connect_attempt_total 59308
telemt_upstream_connect_success_total 58623
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 58770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27612
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 3049
telemt_me_reconnect_success_total 1391
telemt_me_reader_eof_total 1286
telemt_me_idle_close_by_peer_total 1286
telemt_me_route_drop_no_conn_total 3184900
telemt_me_route_drop_channel_closed_total 204
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5886068
telemt_me_endpoint_quarantine_total 915
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 971
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 50
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
telemt_me_writers_active_current 127
telemt_desync_total 27635
telemt_desync_full_logged_total 9411
telemt_desync_suppressed_total 18224
telemt_desync_frames_bucket_total{bucket="1_2"} 6687
telemt_desync_frames_bucket_total{bucket="3_10"} 10610
telemt_desync_frames_bucket_total{bucket="gt_10"} 10338
telemt_pool_swap_total 139
telemt_pool_force_close_total 4147
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 486
telemt_me_draining_writers_reap_progress_total 43553
telemt_me_writer_removed_unexpected_total 1306
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4018
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40826
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3834
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39406
telemt_me_writer_teardown_success_total{mode="normal"} 44844
telemt_me_writer_teardown_noop_total 43565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88409
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.080966
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88409
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 486
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 1228
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 5878924
telemt_user_connections_current{user="hello"} 4749
telemt_user_octets_from_client{user="hello"} 150876703799 (140.51 GB)
telemt_user_octets_to_client{user="hello"} 2609176229351 (2.37 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 2008
telemt_user_unique_ips_recent_window{user="hello"} 589
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 2456.3 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 975962
telemt_connections_bad_total 81761
telemt_connections_current 5564
telemt_connections_me_current 5564
telemt_handshake_timeouts_total 12194
telemt_upstream_connect_attempt_total 7635
telemt_upstream_connect_success_total 7244
telemt_upstream_connect_fail_total 332
telemt_upstream_connect_attempts_per_request{bucket="1"} 7576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1101
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2660
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 332
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 302
telemt_me_reconnect_success_total 101
telemt_me_reader_eof_total 54
telemt_me_idle_close_by_peer_total 54
telemt_me_route_drop_no_conn_total 2051824
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 797663
telemt_me_endpoint_quarantine_total 15
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 43
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 1319
telemt_desync_full_logged_total 343
telemt_desync_suppressed_total 976
telemt_desync_frames_bucket_total{bucket="1_2"} 262
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 537
telemt_pool_swap_total 1
telemt_pool_force_close_total 62
telemt_me_writer_close_signal_drop_total 40
telemt_me_draining_writers_reap_progress_total 663
telemt_me_writer_removed_unexpected_total 98
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 142
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 619
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 26
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 601
telemt_me_writer_teardown_success_total{mode="normal"} 761
telemt_me_writer_teardown_noop_total 663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1424
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.785900
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1424
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 40
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 58
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 803835
telemt_user_connections_current{user="hello"} 5564
telemt_user_octets_from_client{user="hello"} 5300998458 (4.94 GB)
telemt_user_octets_to_client{user="hello"} 24927867987 (23.22 GB)
telemt_user_msgs_from_client{user="hello"} 6014
telemt_user_msgs_to_client{user="hello"} 4995
telemt_user_unique_ips_current{user="hello"} 1984
telemt_user_unique_ips_recent_window{user="hello"} 1253
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 132183.0 (36h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7530231
telemt_connections_bad_total 674861
telemt_connections_current 5247
telemt_connections_me_current 5247
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 154304
telemt_upstream_connect_attempt_total 75459
telemt_upstream_connect_success_total 74639
telemt_upstream_connect_fail_total 702
telemt_upstream_connect_attempts_per_request{bucket="1"} 75341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28668
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 443
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 702
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70433
telemt_me_reconnect_success_total 2073
telemt_me_reader_eof_total 1818
telemt_me_idle_close_by_peer_total 1817
telemt_me_route_drop_no_conn_total 3006941
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5920693
telemt_me_endpoint_quarantine_total 885
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 997
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_me_writers_active_current 92
telemt_desync_total 29976
telemt_desync_full_logged_total 10383
telemt_desync_suppressed_total 19593
telemt_desync_frames_bucket_total{bucket="1_2"} 6007
telemt_desync_frames_bucket_total{bucket="3_10"} 11521
telemt_desync_frames_bucket_total{bucket="gt_10"} 12448
telemt_pool_swap_total 137
telemt_pool_force_close_total 3932
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 466
telemt_me_draining_writers_reap_progress_total 45793
telemt_me_writer_removed_unexpected_total 1848
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4661
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43006
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3490
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 442
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41861
telemt_me_writer_teardown_success_total{mode="normal"} 47667
telemt_me_writer_teardown_noop_total 45794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93461
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.380412
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93461
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 466
telemt_me_refill_failed_total 4229
telemt_me_writer_restored_same_endpoint_total 1721
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 5918798
telemt_user_connections_current{user="hello"} 5247
telemt_user_octets_from_client{user="hello"} 148632537847 (138.42 GB)
telemt_user_octets_to_client{user="hello"} 2429736806463 (2.21 TB)
telemt_user_msgs_from_client{user="hello"} 115484
telemt_user_msgs_to_client{user="hello"} 517108
telemt_user_unique_ips_current{user="hello"} 2075
telemt_user_unique_ips_recent_window{user="hello"} 632
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 69019.0 (19h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6133973
telemt_connections_bad_total 239267
telemt_connections_current 3670
telemt_connections_me_current 3670
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2461810
telemt_upstream_connect_attempt_total 36879
telemt_upstream_connect_success_total 36622
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 36872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14949
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_reconnect_attempts_total 47466
telemt_me_reconnect_success_total 1243
telemt_me_reader_eof_total 908
telemt_me_idle_close_by_peer_total 908
telemt_me_route_drop_no_conn_total 1577897
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3060142
telemt_me_endpoint_quarantine_total 477
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 53
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 53
telemt_me_single_endpoint_shadow_rotate_total 526
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 16758
telemt_desync_full_logged_total 5659
telemt_desync_suppressed_total 11099
telemt_desync_frames_bucket_total{bucket="1_2"} 3306
telemt_desync_frames_bucket_total{bucket="3_10"} 6427
telemt_desync_frames_bucket_total{bucket="gt_10"} 7025
telemt_pool_swap_total 73
telemt_pool_force_close_total 2213
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 211
telemt_me_draining_writers_reap_progress_total 24901
telemt_me_writer_removed_unexpected_total 979
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2177
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23725
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1903
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 310
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22688
telemt_me_writer_teardown_success_total{mode="normal"} 25902
telemt_me_writer_teardown_noop_total 24907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50809
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.715745
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50809
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 211
telemt_me_refill_failed_total 2688
telemt_me_writer_restored_same_endpoint_total 1110
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3060925
telemt_user_connections_current{user="hello"} 3670
telemt_user_octets_from_client{user="hello"} 76603221316 (71.34 GB)
telemt_user_octets_to_client{user="hello"} 1320910720426 (1.20 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1502
telemt_user_unique_ips_recent_window{user="hello"} 591
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 49989.6 (13h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 463407
telemt_connections_bad_total 3575
telemt_connections_current 903
telemt_connections_me_current 903
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 8830
telemt_upstream_connect_attempt_total 26512
telemt_upstream_connect_success_total 26449
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 26507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13784
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 263
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1115
telemt_me_reconnect_success_total 439
telemt_me_reader_eof_total 439
telemt_me_idle_close_by_peer_total 439
telemt_me_route_drop_no_conn_total 150515
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 418299
telemt_me_endpoint_quarantine_total 463
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 429
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
telemt_me_writers_active_current 84
telemt_desync_total 1957
telemt_desync_full_logged_total 570
telemt_desync_suppressed_total 1387
telemt_desync_frames_bucket_total{bucket="1_2"} 565
telemt_desync_frames_bucket_total{bucket="3_10"} 761
telemt_desync_frames_bucket_total{bucket="gt_10"} 631
telemt_pool_swap_total 53
telemt_pool_force_close_total 1222
telemt_me_writer_close_signal_drop_total 47
telemt_me_draining_writers_reap_progress_total 21315
telemt_me_writer_removed_unexpected_total 422
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1543
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20211
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1194
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20093
telemt_me_writer_teardown_success_total{mode="normal"} 21754
telemt_me_writer_teardown_noop_total 21315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43069
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.978425
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43069
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 47
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 388
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 420428
telemt_user_connections_current{user="hello"} 903
telemt_user_octets_from_client{user="hello"} 8356716889 (7.78 GB)
telemt_user_octets_to_client{user="hello"} 210461849371 (196.01 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 132187.4 (36h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9271778
telemt_connections_bad_total 1076419
telemt_connections_current 5337
telemt_connections_me_current 5337
telemt_handshake_timeouts_total 253865
telemt_upstream_connect_attempt_total 51169
telemt_upstream_connect_success_total 50974
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 51125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25718
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_reconnect_attempts_total 1914
telemt_me_reconnect_success_total 1044
telemt_me_reader_eof_total 1015
telemt_me_idle_close_by_peer_total 1015
telemt_me_route_drop_no_conn_total 2621225
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6873763
telemt_me_endpoint_quarantine_total 937
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1004
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 27754
telemt_desync_full_logged_total 9097
telemt_desync_suppressed_total 18657
telemt_desync_frames_bucket_total{bucket="1_2"} 6860
telemt_desync_frames_bucket_total{bucket="3_10"} 10134
telemt_desync_frames_bucket_total{bucket="gt_10"} 10760
telemt_pool_swap_total 146
telemt_pool_force_close_total 3930
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 478
telemt_me_draining_writers_reap_progress_total 46165
telemt_me_writer_removed_unexpected_total 976
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3698
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43473
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3828
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 102
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42235
telemt_me_writer_teardown_success_total{mode="normal"} 47171
telemt_me_writer_teardown_noop_total 46167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93338
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.759204
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93338
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 478
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 916
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 6846523
telemt_user_connections_current{user="hello"} 5337
telemt_user_octets_from_client{user="hello"} 132897909200 (123.77 GB)
telemt_user_octets_to_client{user="hello"} 3211782412552 (2.92 TB)
telemt_user_unique_ips_current{user="hello"} 2021
telemt_user_unique_ips_recent_window{user="hello"} 722
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 132184.1 (36h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8064623
telemt_connections_bad_total 897870
telemt_connections_current 4204
telemt_connections_me_current 4204
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 212414
telemt_upstream_connect_attempt_total 75584
telemt_upstream_connect_success_total 75051
telemt_upstream_connect_fail_total 464
telemt_upstream_connect_attempts_per_request{bucket="1"} 75515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30191
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1965
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 464
telemt_me_reconnect_attempts_total 6478
telemt_me_reconnect_success_total 1491
telemt_me_reader_eof_total 1334
telemt_me_idle_close_by_peer_total 1334
telemt_me_seq_mismatch_total 62
telemt_me_route_drop_no_conn_total 2819162
telemt_me_route_drop_channel_closed_total 240
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6139620
telemt_me_endpoint_quarantine_total 1033
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1001
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
telemt_me_writers_active_current 43
telemt_desync_total 26650
telemt_desync_full_logged_total 8850
telemt_desync_suppressed_total 17800
telemt_desync_frames_bucket_total{bucket="1_2"} 6564
telemt_desync_frames_bucket_total{bucket="3_10"} 9793
telemt_desync_frames_bucket_total{bucket="gt_10"} 10293
telemt_pool_swap_total 143
telemt_pool_force_close_total 3853
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 475
telemt_me_draining_writers_reap_progress_total 44772
telemt_me_writer_removed_unexpected_total 1350
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4333
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41851
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3576
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 277
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40919
telemt_me_writer_teardown_success_total{mode="normal"} 46184
telemt_me_writer_teardown_noop_total 44776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90960
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.289309
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90960
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 475
telemt_me_refill_failed_total 287
telemt_me_writer_restored_same_endpoint_total 1164
telemt_me_writer_restored_fallback_total 86
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 112
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 6148403
telemt_user_connections_current{user="hello"} 4204
telemt_user_octets_from_client{user="hello"} 112642212885 (104.91 GB)
telemt_user_octets_to_client{user="hello"} 2627564336715 (2.39 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1670
telemt_user_unique_ips_recent_window{user="hello"} 604
```
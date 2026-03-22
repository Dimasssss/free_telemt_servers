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

# Server Metrics 2026-03-22 12:28:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 55329.8 (15h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1655448
telemt_connections_bad_total 77039
telemt_connections_current 1641
telemt_connections_me_current 1641
telemt_handshake_timeouts_total 73735
telemt_upstream_connect_attempt_total 21037
telemt_upstream_connect_success_total 21036
telemt_upstream_connect_attempts_per_request{bucket="1"} 21036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13713
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 794
telemt_me_reconnect_success_total 342
telemt_me_reader_eof_total 339
telemt_me_idle_close_by_peer_total 339
telemt_me_route_drop_no_conn_total 1106589
telemt_me_route_drop_channel_closed_total 501
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1401264
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 392
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 441
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
telemt_me_writers_active_current 43
telemt_desync_total 8314
telemt_desync_full_logged_total 2505
telemt_desync_suppressed_total 5809
telemt_desync_frames_bucket_total{bucket="1_2"} 2347
telemt_desync_frames_bucket_total{bucket="3_10"} 3139
telemt_desync_frames_bucket_total{bucket="gt_10"} 2828
telemt_pool_swap_total 61
telemt_pool_force_close_total 1825
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 279
telemt_me_draining_writers_reap_progress_total 19191
telemt_me_writer_removed_unexpected_total 334
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1357
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18040
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1790
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17366
telemt_me_writer_teardown_success_total{mode="normal"} 19397
telemt_me_writer_teardown_noop_total 19193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38590
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 136.660863
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38590
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 279
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 303
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 1398518
telemt_user_connections_current{user="hello"} 1641
telemt_user_octets_from_client{user="hello"} 21806445560 (20.31 GB)
telemt_user_octets_to_client{user="hello"} 414582021528 (386.11 GB)
telemt_user_unique_ips_current{user="hello"} 643
telemt_user_unique_ips_recent_window{user="hello"} 261
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 68696.2 (19h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2676422
telemt_connections_bad_total 244282
telemt_connections_current 1424
telemt_connections_me_current 1424
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 61834
telemt_upstream_connect_attempt_total 45367
telemt_upstream_connect_success_total 44839
telemt_upstream_connect_fail_total 467
telemt_upstream_connect_attempts_per_request{bucket="1"} 45306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17503
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 467
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3460
telemt_me_reconnect_success_total 1564
telemt_me_reader_eof_total 1450
telemt_me_idle_close_by_peer_total 1450
telemt_me_route_drop_no_conn_total 2347627
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2099684
telemt_me_endpoint_quarantine_total 582
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 538
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
telemt_me_writers_active_current 45
telemt_desync_total 8313
telemt_desync_full_logged_total 4684
telemt_desync_suppressed_total 3629
telemt_desync_frames_bucket_total{bucket="1_2"} 1941
telemt_desync_frames_bucket_total{bucket="3_10"} 3242
telemt_desync_frames_bucket_total{bucket="gt_10"} 3130
telemt_pool_swap_total 68
telemt_pool_force_close_total 1946
telemt_me_writer_close_signal_drop_total 161
telemt_me_draining_writers_reap_progress_total 27467
telemt_me_writer_removed_unexpected_total 1410
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3018
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25859
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1708
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 238
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25521
telemt_me_writer_teardown_success_total{mode="normal"} 28877
telemt_me_writer_teardown_noop_total 27467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56344
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.422948
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56344
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 161
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 1307
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 2111424
telemt_user_connections_current{user="hello"} 1424
telemt_user_octets_from_client{user="hello"} 26144831559 (24.35 GB)
telemt_user_octets_to_client{user="hello"} 515413113670 (480.02 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 889
telemt_user_unique_ips_recent_window{user="hello"} 510
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 143556.0 (39h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12876646
telemt_connections_bad_total 1133855
telemt_connections_current 4829
telemt_connections_me_current 4829
telemt_handshake_timeouts_total 333817
telemt_upstream_connect_attempt_total 52321
telemt_upstream_connect_success_total 52241
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 52249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28378
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2374
telemt_me_reconnect_success_total 1223
telemt_me_reader_eof_total 1186
telemt_me_idle_close_by_peer_total 1185
telemt_me_route_drop_no_conn_total 10548437
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10287036
telemt_me_endpoint_quarantine_total 914
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1068
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
telemt_me_writers_active_current 44
telemt_desync_total 42308
telemt_desync_full_logged_total 13512
telemt_desync_suppressed_total 28796
telemt_desync_frames_bucket_total{bucket="1_2"} 9564
telemt_desync_frames_bucket_total{bucket="3_10"} 16503
telemt_desync_frames_bucket_total{bucket="gt_10"} 16241
telemt_pool_swap_total 154
telemt_pool_force_close_total 5263
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 834
telemt_me_draining_writers_reap_progress_total 47713
telemt_me_writer_removed_unexpected_total 1145
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4148
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44066
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4848
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 415
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42450
telemt_me_writer_teardown_success_total{mode="normal"} 48214
telemt_me_writer_teardown_noop_total 47761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95975
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 228.813750
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95975
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 834
telemt_me_refill_failed_total 63
telemt_me_writer_restored_same_endpoint_total 1060
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 10275458
telemt_user_connections_current{user="hello"} 4829
telemt_user_octets_from_client{user="hello"} 152326234748 (141.86 GB)
telemt_user_octets_to_client{user="hello"} 2860610139024 (2.60 TB)
telemt_user_unique_ips_current{user="hello"} 1883
telemt_user_unique_ips_recent_window{user="hello"} 806
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 143557.3 (39h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9731678
telemt_connections_bad_total 888795
telemt_connections_current 4956
telemt_connections_me_current 4956
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 293470
telemt_upstream_connect_attempt_total 78628
telemt_upstream_connect_success_total 77500
telemt_upstream_connect_fail_total 814
telemt_upstream_connect_attempts_per_request{bucket="1"} 78314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30906
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3671
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 814
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3336
telemt_me_reconnect_success_total 1360
telemt_me_reader_eof_total 1246
telemt_me_idle_close_by_peer_total 1246
telemt_me_route_drop_no_conn_total 3901723
telemt_me_route_drop_channel_closed_total 400
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7257967
telemt_me_endpoint_quarantine_total 904
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1096
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
telemt_me_writers_active_current 45
telemt_desync_total 32753
telemt_desync_full_logged_total 11071
telemt_desync_suppressed_total 21682
telemt_desync_frames_bucket_total{bucket="1_2"} 8078
telemt_desync_frames_bucket_total{bucket="3_10"} 12615
telemt_desync_frames_bucket_total{bucket="gt_10"} 12060
telemt_pool_swap_total 154
telemt_pool_force_close_total 4706
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 570
telemt_me_draining_writers_reap_progress_total 45951
telemt_me_writer_removed_unexpected_total 1277
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4102
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42994
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4327
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 379
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41245
telemt_me_writer_teardown_success_total{mode="normal"} 47096
telemt_me_writer_teardown_noop_total 45962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93058
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 83.032628
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93058
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 570
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 1161
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 7198427
telemt_user_connections_current{user="hello"} 4956
telemt_user_octets_from_client{user="hello"} 185932696377 (173.16 GB)
telemt_user_octets_to_client{user="hello"} 3268479290142 (2.97 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1861
telemt_user_unique_ips_recent_window{user="hello"} 602
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 143522.0 (39h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9169530
telemt_connections_bad_total 769628
telemt_connections_current 3393
telemt_connections_me_current 3393
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 292055
telemt_upstream_connect_attempt_total 63958
telemt_upstream_connect_success_total 63203
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 63365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29655
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1964
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 306
telemt_me_reconnect_attempts_total 3883
telemt_me_reconnect_success_total 1683
telemt_me_reader_eof_total 1504
telemt_me_idle_close_by_peer_total 1503
telemt_me_route_drop_no_conn_total 3986665
telemt_me_route_drop_channel_closed_total 281
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6905318
telemt_me_endpoint_quarantine_total 987
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1053
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
telemt_me_writers_active_current 48
telemt_desync_total 32441
telemt_desync_full_logged_total 10831
telemt_desync_suppressed_total 21610
telemt_desync_frames_bucket_total{bucket="1_2"} 8180
telemt_desync_frames_bucket_total{bucket="3_10"} 12450
telemt_desync_frames_bucket_total{bucket="gt_10"} 11811
telemt_pool_swap_total 150
telemt_pool_force_close_total 4668
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 603
telemt_me_draining_writers_reap_progress_total 46718
telemt_me_writer_removed_unexpected_total 1585
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4540
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43684
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4184
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 484
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42050
telemt_me_writer_teardown_success_total{mode="normal"} 48224
telemt_me_writer_teardown_noop_total 46784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95008
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3092.037135
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95008
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 603
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1464
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 6897257
telemt_user_connections_current{user="hello"} 3393
telemt_user_octets_from_client{user="hello"} 167084655621 (155.61 GB)
telemt_user_octets_to_client{user="hello"} 2949276387733 (2.68 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1393
telemt_user_unique_ips_recent_window{user="hello"} 564
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 13801.1 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5844668
telemt_connections_bad_total 349523
telemt_connections_current 6424
telemt_connections_me_current 6424
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 93357
telemt_upstream_connect_attempt_total 24127
telemt_upstream_connect_success_total 23052
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 23890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4921
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4627
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_timeout_total 521
telemt_me_reconnect_attempts_total 2299
telemt_me_reconnect_success_total 361
telemt_me_reader_eof_total 232
telemt_me_idle_close_by_peer_total 232
telemt_me_route_drop_no_conn_total 13736441
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 24
telemt_me_route_drop_queue_full_profile_total{profile="high"} 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4891714
telemt_me_endpoint_quarantine_total 92
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 115
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
telemt_desync_total 7392
telemt_desync_full_logged_total 1888
telemt_desync_suppressed_total 5504
telemt_desync_frames_bucket_total{bucket="1_2"} 1353
telemt_desync_frames_bucket_total{bucket="3_10"} 2956
telemt_desync_frames_bucket_total{bucket="gt_10"} 3083
telemt_pool_swap_total 13
telemt_pool_force_close_total 540
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 211
telemt_me_draining_writers_reap_progress_total 3610
telemt_me_writer_removed_unexpected_total 320
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 620
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3267
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 395
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 145
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3070
telemt_me_writer_teardown_success_total{mode="normal"} 3887
telemt_me_writer_teardown_noop_total 3613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 7439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 7499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 7500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 7500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 7500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 7500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 7500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 7500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 7500
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.174672
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 7500
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 211
telemt_me_refill_failed_total 107
telemt_me_writer_restored_same_endpoint_total 246
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 4905126
telemt_user_connections_current{user="hello"} 6424
telemt_user_octets_from_client{user="hello"} 27004672902 (25.15 GB)
telemt_user_octets_to_client{user="hello"} 143270738403 (133.43 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2367
telemt_user_unique_ips_recent_window{user="hello"} 1343
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 143527.6 (39h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8929489
telemt_connections_bad_total 755645
telemt_connections_current 4753
telemt_connections_me_current 4753
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 190229
telemt_upstream_connect_attempt_total 88494
telemt_upstream_connect_success_total 87620
telemt_upstream_connect_fail_total 752
telemt_upstream_connect_attempts_per_request{bucket="1"} 88372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31599
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1248
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 752
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71131
telemt_me_reconnect_success_total 2366
telemt_me_reader_eof_total 2107
telemt_me_idle_close_by_peer_total 2106
telemt_me_route_drop_no_conn_total 4182726
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7054347
telemt_me_endpoint_quarantine_total 959
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1073
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
telemt_desync_total 36013
telemt_desync_full_logged_total 12394
telemt_desync_suppressed_total 23619
telemt_desync_frames_bucket_total{bucket="1_2"} 7355
telemt_desync_frames_bucket_total{bucket="3_10"} 13834
telemt_desync_frames_bucket_total{bucket="gt_10"} 14824
telemt_pool_swap_total 147
telemt_pool_force_close_total 4326
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 523
telemt_me_draining_writers_reap_progress_total 49319
telemt_me_writer_removed_unexpected_total 2135
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5201
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46279
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3733
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 593
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44993
telemt_me_writer_teardown_success_total{mode="normal"} 51480
telemt_me_writer_teardown_noop_total 49320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100800
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.043287
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100800
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 523
telemt_me_refill_failed_total 4245
telemt_me_writer_restored_same_endpoint_total 1985
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 7056904
telemt_user_connections_current{user="hello"} 4753
telemt_user_octets_from_client{user="hello"} 166390426547 (154.96 GB)
telemt_user_octets_to_client{user="hello"} 2725365752429 (2.48 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1901
telemt_user_unique_ips_recent_window{user="hello"} 650
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 80363.8 (22h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8491556
telemt_connections_bad_total 298743
telemt_connections_current 4236
telemt_connections_me_current 4236
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3562632
telemt_upstream_connect_attempt_total 40752
telemt_upstream_connect_success_total 40462
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 40745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17019
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_reconnect_attempts_total 47847
telemt_me_reconnect_success_total 1401
telemt_me_reader_eof_total 1071
telemt_me_idle_close_by_peer_total 1071
telemt_me_route_drop_no_conn_total 2925842
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4126636
telemt_me_endpoint_quarantine_total 539
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 608
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 22705
telemt_desync_full_logged_total 7588
telemt_desync_suppressed_total 15117
telemt_desync_frames_bucket_total{bucket="1_2"} 4659
telemt_desync_frames_bucket_total{bucket="3_10"} 8837
telemt_desync_frames_bucket_total{bucket="gt_10"} 9209
telemt_pool_swap_total 84
telemt_pool_force_close_total 2608
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 266
telemt_me_draining_writers_reap_progress_total 28284
telemt_me_writer_removed_unexpected_total 1136
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2553
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26895
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2213
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 395
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25676
telemt_me_writer_teardown_success_total{mode="normal"} 29448
telemt_me_writer_teardown_noop_total 28291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57739
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.829495
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57739
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 266
telemt_me_refill_failed_total 2700
telemt_me_writer_restored_same_endpoint_total 1253
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4122999
telemt_user_connections_current{user="hello"} 4236
telemt_user_octets_from_client{user="hello"} 92702472608 (86.34 GB)
telemt_user_octets_to_client{user="hello"} 1616853881318 (1.47 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1694
telemt_user_unique_ips_recent_window{user="hello"} 647
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 61334.7 (17h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 684494
telemt_connections_bad_total 7704
telemt_connections_current 1122
telemt_connections_me_current 1122
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 13423
telemt_upstream_connect_attempt_total 31551
telemt_upstream_connect_success_total 31472
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 31539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_reconnect_attempts_total 1394
telemt_me_reconnect_success_total 603
telemt_me_reader_eof_total 583
telemt_me_idle_close_by_peer_total 583
telemt_me_route_drop_no_conn_total 228905
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 617967
telemt_me_endpoint_quarantine_total 563
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 512
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
telemt_me_writers_active_current 43
telemt_desync_total 3395
telemt_desync_full_logged_total 998
telemt_desync_suppressed_total 2397
telemt_desync_frames_bucket_total{bucket="1_2"} 843
telemt_desync_frames_bucket_total{bucket="3_10"} 1349
telemt_desync_frames_bucket_total{bucket="gt_10"} 1203
telemt_pool_swap_total 65
telemt_pool_force_close_total 1569
telemt_me_writer_close_signal_drop_total 87
telemt_me_draining_writers_reap_progress_total 25788
telemt_me_writer_removed_unexpected_total 565
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1960
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24412
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1492
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24219
telemt_me_writer_teardown_success_total{mode="normal"} 26372
telemt_me_writer_teardown_noop_total 25790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52162
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.791951
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52162
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 87
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 524
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 619731
telemt_user_connections_current{user="hello"} 1122
telemt_user_octets_from_client{user="hello"} 11934544953 (11.11 GB)
telemt_user_octets_to_client{user="hello"} 300149613555 (279.54 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 374
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 143532.4 (39h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10876915
telemt_connections_bad_total 1257823
telemt_connections_current 5465
telemt_connections_me_current 5465
telemt_handshake_timeouts_total 291629
telemt_upstream_connect_attempt_total 54582
telemt_upstream_connect_success_total 54369
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 54534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27504
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_reconnect_attempts_total 2143
telemt_me_reconnect_success_total 1136
telemt_me_reader_eof_total 1099
telemt_me_idle_close_by_peer_total 1099
telemt_me_route_drop_no_conn_total 3366544
telemt_me_route_drop_channel_closed_total 84
telemt_me_route_drop_queue_full_total 32
telemt_me_route_drop_queue_full_profile_total{profile="high"} 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8162935
telemt_me_endpoint_quarantine_total 996
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1081
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
telemt_desync_total 33251
telemt_desync_full_logged_total 10924
telemt_desync_suppressed_total 22327
telemt_desync_frames_bucket_total{bucket="1_2"} 8007
telemt_desync_frames_bucket_total{bucket="3_10"} 12280
telemt_desync_frames_bucket_total{bucket="gt_10"} 12964
telemt_pool_swap_total 159
telemt_pool_force_close_total 4349
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 542
telemt_me_draining_writers_reap_progress_total 49181
telemt_me_writer_removed_unexpected_total 1055
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4010
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46261
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4205
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 144
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44832
telemt_me_writer_teardown_success_total{mode="normal"} 50271
telemt_me_writer_teardown_noop_total 49183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99454
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.464423
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99454
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 542
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 992
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 8134058
telemt_user_connections_current{user="hello"} 5465
telemt_user_octets_from_client{user="hello"} 155838203136 (145.14 GB)
telemt_user_octets_to_client{user="hello"} 3699903263928 (3.37 TB)
telemt_user_unique_ips_current{user="hello"} 1807
telemt_user_unique_ips_recent_window{user="hello"} 855
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 143529.1 (39h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9468258
telemt_connections_bad_total 1067181
telemt_connections_current 5442
telemt_connections_me_current 5442
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 245613
telemt_upstream_connect_attempt_total 79634
telemt_upstream_connect_success_total 79053
telemt_upstream_connect_fail_total 505
telemt_upstream_connect_attempts_per_request{bucket="1"} 79558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32266
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1991
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 505
telemt_me_reconnect_attempts_total 8364
telemt_me_reconnect_success_total 1821
telemt_me_reader_eof_total 1690
telemt_me_idle_close_by_peer_total 1690
telemt_me_seq_mismatch_total 69
telemt_me_route_drop_no_conn_total 3997258
telemt_me_route_drop_channel_closed_total 300
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7272362
telemt_me_endpoint_quarantine_total 1096
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1083
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_active_current 128
telemt_desync_total 32558
telemt_desync_full_logged_total 10654
telemt_desync_suppressed_total 21904
telemt_desync_frames_bucket_total{bucket="1_2"} 8062
telemt_desync_frames_bucket_total{bucket="3_10"} 12117
telemt_desync_frames_bucket_total{bucket="gt_10"} 12379
telemt_pool_swap_total 153
telemt_pool_force_close_total 4179
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 531
telemt_me_draining_writers_reap_progress_total 48031
telemt_me_writer_removed_unexpected_total 1714
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4916
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44894
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3866
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43852
telemt_me_writer_teardown_success_total{mode="normal"} 49810
telemt_me_writer_teardown_noop_total 48035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97845
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.226297
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97845
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 531
telemt_me_refill_failed_total 337
telemt_me_writer_restored_same_endpoint_total 1469
telemt_me_writer_restored_fallback_total 93
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 7280238
telemt_user_connections_current{user="hello"} 5442
telemt_user_octets_from_client{user="hello"} 128725149297 (119.88 GB)
telemt_user_octets_to_client{user="hello"} 2918634171211 (2.65 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 2250
telemt_user_unique_ips_recent_window{user="hello"} 646
```
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

# Server Metrics 2026-03-22 03:06:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 21606.0 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319181
telemt_connections_bad_total 21498
telemt_connections_current 927
telemt_connections_me_current 927
telemt_handshake_timeouts_total 18336
telemt_upstream_connect_attempt_total 9037
telemt_upstream_connect_success_total 9036
telemt_upstream_connect_attempts_per_request{bucket="1"} 9036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5789
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 268
telemt_me_reconnect_success_total 143
telemt_me_reader_eof_total 138
telemt_me_idle_close_by_peer_total 138
telemt_me_route_drop_no_conn_total 60645
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 262557
telemt_me_endpoint_quarantine_total 174
telemt_me_single_endpoint_shadow_rotate_total 180
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 2300
telemt_desync_full_logged_total 627
telemt_desync_suppressed_total 1673
telemt_desync_frames_bucket_total{bucket="1_2"} 772
telemt_desync_frames_bucket_total{bucket="3_10"} 855
telemt_desync_frames_bucket_total{bucket="gt_10"} 673
telemt_pool_swap_total 23
telemt_pool_force_close_total 604
telemt_me_writer_close_signal_drop_total 40
telemt_me_draining_writers_reap_progress_total 8148
telemt_me_writer_removed_unexpected_total 138
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 546
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7730
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 599
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7544
telemt_me_writer_teardown_success_total{mode="normal"} 8276
telemt_me_writer_teardown_noop_total 8149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16425
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.933526
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16425
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 40
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 129
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 262043
telemt_user_connections_current{user="hello"} 927
telemt_user_octets_from_client{user="hello"} 3018624176 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 94927252136 (88.41 GB)
telemt_user_unique_ips_current{user="hello"} 406
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 34972.0 (9h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 809365
telemt_connections_bad_total 51674
telemt_connections_current 794
telemt_connections_me_current 794
telemt_handshake_timeouts_total 29830
telemt_upstream_connect_attempt_total 16289
telemt_upstream_connect_success_total 16036
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 16266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8946
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_reconnect_attempts_total 1367
telemt_me_reconnect_success_total 504
telemt_me_reader_eof_total 444
telemt_me_idle_close_by_peer_total 444
telemt_me_route_drop_no_conn_total 343734
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 639308
telemt_me_endpoint_quarantine_total 331
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 282
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 2764
telemt_desync_full_logged_total 1588
telemt_desync_suppressed_total 1176
telemt_desync_frames_bucket_total{bucket="1_2"} 587
telemt_desync_frames_bucket_total{bucket="3_10"} 1057
telemt_desync_frames_bucket_total{bucket="gt_10"} 1120
telemt_pool_swap_total 37
telemt_pool_force_close_total 1004
telemt_me_writer_close_signal_drop_total 72
telemt_me_draining_writers_reap_progress_total 14444
telemt_me_writer_removed_unexpected_total 421
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1211
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13664
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 982
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13440
telemt_me_writer_teardown_success_total{mode="normal"} 14875
telemt_me_writer_teardown_noop_total 14444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29319
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.764703
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29319
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 72
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 371
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 638386
telemt_user_connections_current{user="hello"} 794
telemt_user_octets_from_client{user="hello"} 10340318336 (9.63 GB)
telemt_user_octets_to_client{user="hello"} 226899504816 (211.32 GB)
telemt_user_unique_ips_current{user="hello"} 526
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 109831.9 (30h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7793371
telemt_connections_bad_total 635991
telemt_connections_current 2051
telemt_connections_me_current 2051
telemt_handshake_timeouts_total 256089
telemt_upstream_connect_attempt_total 40806
telemt_upstream_connect_success_total 40731
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 40738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22125
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1583
telemt_me_reconnect_success_total 821
telemt_me_reader_eof_total 830
telemt_me_idle_close_by_peer_total 830
telemt_me_route_drop_no_conn_total 4543151
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6303360
telemt_me_endpoint_quarantine_total 702
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 821
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 6
telemt_desync_total 26539
telemt_desync_full_logged_total 8790
telemt_desync_suppressed_total 17749
telemt_desync_frames_bucket_total{bucket="1_2"} 5725
telemt_desync_frames_bucket_total{bucket="3_10"} 10365
telemt_desync_frames_bucket_total{bucket="gt_10"} 10449
telemt_pool_swap_total 118
telemt_pool_force_close_total 3912
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 605
telemt_me_draining_writers_reap_progress_total 37239
telemt_me_writer_removed_unexpected_total 799
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3101
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34471
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3673
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33327
telemt_me_writer_teardown_success_total{mode="normal"} 37572
telemt_me_writer_teardown_noop_total 37283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74855
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 160.778350
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74855
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 605
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 731
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 6295458
telemt_user_connections_current{user="hello"} 2051
telemt_user_octets_from_client{user="hello"} 107282953516 (99.92 GB)
telemt_user_octets_to_client{user="hello"} 2097648994652 (1.91 TB)
telemt_user_unique_ips_current{user="hello"} 1054
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 109833.3 (30h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6440878
telemt_connections_bad_total 589225
telemt_connections_current 1829
telemt_connections_me_current 1829
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 213619
telemt_upstream_connect_attempt_total 44847
telemt_upstream_connect_success_total 44456
telemt_upstream_connect_fail_total 193
telemt_upstream_connect_attempts_per_request{bucket="1"} 44649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21816
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 193
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1950
telemt_me_reconnect_success_total 881
telemt_me_reader_eof_total 852
telemt_me_idle_close_by_peer_total 852
telemt_me_route_drop_no_conn_total 2263823
telemt_me_route_drop_channel_closed_total 264
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4808265
telemt_me_endpoint_quarantine_total 688
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 844
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_me_writers_warm_current 7
telemt_desync_total 22697
telemt_desync_full_logged_total 7736
telemt_desync_suppressed_total 14961
telemt_desync_frames_bucket_total{bucket="1_2"} 5464
telemt_desync_frames_bucket_total{bucket="3_10"} 8818
telemt_desync_frames_bucket_total{bucket="gt_10"} 8415
telemt_pool_swap_total 119
telemt_pool_force_close_total 3544
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 363
telemt_me_draining_writers_reap_progress_total 35773
telemt_me_writer_removed_unexpected_total 837
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2974
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33573
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3331
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32229
telemt_me_writer_teardown_success_total{mode="normal"} 36547
telemt_me_writer_teardown_noop_total 35779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72326
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.325034
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72326
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 363
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 771
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 4730398
telemt_user_connections_current{user="hello"} 1829
telemt_user_octets_from_client{user="hello"} 140752337121 (131.09 GB)
telemt_user_octets_to_client{user="hello"} 2237018749083 (2.03 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 889
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 109797.9 (30h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6317425
telemt_connections_bad_total 549242
telemt_connections_current 1577
telemt_connections_me_current 1577
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 204658
telemt_upstream_connect_attempt_total 50932
telemt_upstream_connect_success_total 50558
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 50694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23230
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1076
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2076
telemt_me_reconnect_success_total 918
telemt_me_reader_eof_total 865
telemt_me_idle_close_by_peer_total 865
telemt_me_route_drop_no_conn_total 2157072
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4695619
telemt_me_endpoint_quarantine_total 769
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 818
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
telemt_me_writers_active_current 45
telemt_desync_total 22614
telemt_desync_full_logged_total 7612
telemt_desync_suppressed_total 15002
telemt_desync_frames_bucket_total{bucket="1_2"} 5524
telemt_desync_frames_bucket_total{bucket="3_10"} 8662
telemt_desync_frames_bucket_total{bucket="gt_10"} 8428
telemt_pool_swap_total 118
telemt_pool_force_close_total 3426
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 386
telemt_me_draining_writers_reap_progress_total 36861
telemt_me_writer_removed_unexpected_total 835
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3050
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34662
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33435
telemt_me_writer_teardown_success_total{mode="normal"} 37712
telemt_me_writer_teardown_noop_total 36873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74585
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.070111
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74585
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 386
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 796
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 4691140
telemt_user_connections_current{user="hello"} 1577
telemt_user_octets_from_client{user="hello"} 134139595671 (124.93 GB)
telemt_user_octets_to_client{user="hello"} 2150648138447 (1.96 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 756
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 109836.9 (30h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20485901
telemt_connections_bad_total 1644118
telemt_connections_current 2426
telemt_connections_me_current 2426
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 612387
telemt_upstream_connect_attempt_total 199816
telemt_upstream_connect_success_total 181709
telemt_upstream_connect_fail_total 16340
telemt_upstream_connect_attempts_per_request{bucket="1"} 198049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43075
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8930
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16340
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64948
telemt_me_reconnect_success_total 2339
telemt_me_reader_eof_total 1469
telemt_me_idle_close_by_peer_total 1468
telemt_me_route_drop_no_conn_total 39521159
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16541478
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 859
telemt_me_single_endpoint_outage_enter_total 135
telemt_me_single_endpoint_outage_exit_total 135
telemt_me_single_endpoint_outage_reconnect_attempt_total 285
telemt_me_single_endpoint_outage_reconnect_success_total 70
telemt_me_single_endpoint_quarantine_bypass_total 285
telemt_me_single_endpoint_shadow_rotate_total 859
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 64
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
telemt_me_writers_warm_current 10
telemt_desync_total 32033
telemt_desync_full_logged_total 9626
telemt_desync_suppressed_total 22407
telemt_desync_frames_bucket_total{bucket="1_2"} 6939
telemt_desync_frames_bucket_total{bucket="3_10"} 14222
telemt_desync_frames_bucket_total{bucket="gt_10"} 10872
telemt_pool_swap_total 113
telemt_pool_force_close_total 3656
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 798
telemt_me_draining_writers_reap_progress_total 34450
telemt_me_writer_removed_unexpected_total 2167
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4635
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31723
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3132
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 524
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30794
telemt_me_writer_teardown_success_total{mode="normal"} 36358
telemt_me_writer_teardown_noop_total 34477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70835
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 215.172555
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70835
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 798
telemt_me_refill_failed_total 3804
telemt_me_writer_restored_same_endpoint_total 1604
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 542
telemt_user_connections_total{user="hello"} 16674628
telemt_user_connections_current{user="hello"} 2426
telemt_user_octets_from_client{user="hello"} 223623833744 (208.27 GB)
telemt_user_octets_to_client{user="hello"} 1216181285189 (1.11 TB)
telemt_user_msgs_from_client{user="hello"} 395497
telemt_user_msgs_to_client{user="hello"} 785476
telemt_user_unique_ips_current{user="hello"} 1149
telemt_user_unique_ips_recent_window{user="hello"} 267
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 109804.2 (30h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6065558
telemt_connections_bad_total 572852
telemt_connections_current 1766
telemt_connections_me_current 1766
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 127488
telemt_upstream_connect_attempt_total 59616
telemt_upstream_connect_success_total 58927
telemt_upstream_connect_fail_total 588
telemt_upstream_connect_attempts_per_request{bucket="1"} 59515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24195
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 352
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 588
telemt_me_reconnect_attempts_total 69677
telemt_me_reconnect_success_total 1808
telemt_me_reader_eof_total 1587
telemt_me_idle_close_by_peer_total 1586
telemt_me_route_drop_no_conn_total 2394945
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4726113
telemt_me_endpoint_quarantine_total 742
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 830
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
telemt_me_writers_active_current 47
telemt_desync_total 23472
telemt_desync_full_logged_total 8278
telemt_desync_suppressed_total 15194
telemt_desync_frames_bucket_total{bucket="1_2"} 4486
telemt_desync_frames_bucket_total{bucket="3_10"} 9090
telemt_desync_frames_bucket_total{bucket="gt_10"} 9896
telemt_pool_swap_total 113
telemt_pool_force_close_total 3246
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 396
telemt_me_draining_writers_reap_progress_total 38730
telemt_me_writer_removed_unexpected_total 1625
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3969
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36417
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2845
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35484
telemt_me_writer_teardown_success_total{mode="normal"} 40386
telemt_me_writer_teardown_noop_total 38731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79117
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.131370
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79117
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 396
telemt_me_refill_failed_total 4206
telemt_me_writer_restored_same_endpoint_total 1517
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 4718884
telemt_user_connections_current{user="hello"} 1766
telemt_user_octets_from_client{user="hello"} 125082957660 (116.49 GB)
telemt_user_octets_to_client{user="hello"} 1924180146546 (1.75 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 873
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 46640.0 (12h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3984254
telemt_connections_bad_total 151008
telemt_connections_current 1395
telemt_connections_me_current 1395
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1620343
telemt_upstream_connect_attempt_total 28244
telemt_upstream_connect_success_total 28065
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 28237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_reconnect_attempts_total 45833
telemt_me_reconnect_success_total 978
telemt_me_reader_eof_total 662
telemt_me_idle_close_by_peer_total 662
telemt_me_route_drop_no_conn_total 1026840
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1950813
telemt_me_endpoint_quarantine_total 344
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 358
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
telemt_me_writers_active_current 47
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10545
telemt_desync_full_logged_total 3641
telemt_desync_suppressed_total 6904
telemt_desync_frames_bucket_total{bucket="1_2"} 1907
telemt_desync_frames_bucket_total{bucket="3_10"} 4042
telemt_desync_frames_bucket_total{bucket="gt_10"} 4596
telemt_pool_swap_total 50
telemt_pool_force_close_total 1509
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 137
telemt_me_draining_writers_reap_progress_total 17217
telemt_me_writer_removed_unexpected_total 735
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1556
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16423
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1303
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15708
telemt_me_writer_teardown_success_total{mode="normal"} 17979
telemt_me_writer_teardown_noop_total 17219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35198
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.490675
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35198
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 137
telemt_me_refill_failed_total 2606
telemt_me_writer_restored_same_endpoint_total 877
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1954386
telemt_user_connections_current{user="hello"} 1395
telemt_user_octets_from_client{user="hello"} 54567851404 (50.82 GB)
telemt_user_octets_to_client{user="hello"} 828950407770 (772.02 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 736
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 27611.0 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202593
telemt_connections_bad_total 1742
telemt_connections_current 350
telemt_connections_me_current 350
telemt_handshake_timeouts_total 5564
telemt_upstream_connect_attempt_total 13316
telemt_upstream_connect_success_total 13284
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 13314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 292
telemt_me_reconnect_success_total 170
telemt_me_reader_eof_total 175
telemt_me_idle_close_by_peer_total 175
telemt_me_route_drop_no_conn_total 55855
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 178717
telemt_me_endpoint_quarantine_total 271
telemt_me_single_endpoint_shadow_rotate_total 241
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1033
telemt_desync_full_logged_total 262
telemt_desync_suppressed_total 771
telemt_desync_frames_bucket_total{bucket="1_2"} 391
telemt_desync_frames_bucket_total{bucket="3_10"} 384
telemt_desync_frames_bucket_total{bucket="gt_10"} 258
telemt_pool_swap_total 30
telemt_pool_force_close_total 669
telemt_me_writer_close_signal_drop_total 23
telemt_me_draining_writers_reap_progress_total 12041
telemt_me_writer_removed_unexpected_total 168
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 764
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11452
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 667
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11372
telemt_me_writer_teardown_success_total{mode="normal"} 12216
telemt_me_writer_teardown_noop_total 12041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24257
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.038396
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24257
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 23
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 154
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 178399
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 3200484648 (2.98 GB)
telemt_user_octets_to_client{user="hello"} 111056992060 (103.43 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 109808.5 (30h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7384609
telemt_connections_bad_total 744076
telemt_connections_current 1884
telemt_connections_me_current 1884
telemt_handshake_timeouts_total 210160
telemt_upstream_connect_attempt_total 43083
telemt_upstream_connect_success_total 42926
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 43046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21625
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_reconnect_attempts_total 1589
telemt_me_reconnect_success_total 854
telemt_me_reader_eof_total 837
telemt_me_idle_close_by_peer_total 837
telemt_me_route_drop_no_conn_total 2133004
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5511381
telemt_me_endpoint_quarantine_total 769
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 846
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 21649
telemt_desync_full_logged_total 7089
telemt_desync_suppressed_total 14560
telemt_desync_frames_bucket_total{bucket="1_2"} 5443
telemt_desync_frames_bucket_total{bucket="3_10"} 7835
telemt_desync_frames_bucket_total{bucket="gt_10"} 8371
telemt_pool_swap_total 121
telemt_pool_force_close_total 3236
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 390
telemt_me_draining_writers_reap_progress_total 38866
telemt_me_writer_removed_unexpected_total 808
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3039
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36654
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3148
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35630
telemt_me_writer_teardown_success_total{mode="normal"} 39693
telemt_me_writer_teardown_noop_total 38868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78561
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.674723
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78561
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 390
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 764
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 5486384
telemt_user_connections_current{user="hello"} 1884
telemt_user_octets_from_client{user="hello"} 110002543612 (102.45 GB)
telemt_user_octets_to_client{user="hello"} 2556466732272 (2.33 TB)
telemt_user_unique_ips_current{user="hello"} 809
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 109805.2 (30h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6377540
telemt_connections_bad_total 630324
telemt_connections_current 1742
telemt_connections_me_current 1742
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 174013
telemt_upstream_connect_attempt_total 58873
telemt_upstream_connect_success_total 58433
telemt_upstream_connect_fail_total 381
telemt_upstream_connect_attempts_per_request{bucket="1"} 58814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23295
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 381
telemt_me_reconnect_attempts_total 5585
telemt_me_reconnect_success_total 1185
telemt_me_reader_eof_total 1071
telemt_me_idle_close_by_peer_total 1071
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 2186141
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4879304
telemt_me_endpoint_quarantine_total 864
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 840
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
telemt_desync_total 20229
telemt_desync_full_logged_total 6738
telemt_desync_suppressed_total 13491
telemt_desync_frames_bucket_total{bucket="1_2"} 5181
telemt_desync_frames_bucket_total{bucket="3_10"} 7377
telemt_desync_frames_bucket_total{bucket="gt_10"} 7671
telemt_pool_swap_total 119
telemt_pool_force_close_total 3195
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 382
telemt_me_draining_writers_reap_progress_total 37411
telemt_me_writer_removed_unexpected_total 1081
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3568
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34977
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2972
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34216
telemt_me_writer_teardown_success_total{mode="normal"} 38545
telemt_me_writer_teardown_noop_total 37415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75960
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.093724
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75960
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 382
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 927
telemt_me_writer_restored_fallback_total 64
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4882292
telemt_user_connections_current{user="hello"} 1742
telemt_user_octets_from_client{user="hello"} 92261387293 (85.93 GB)
telemt_user_octets_to_client{user="hello"} 2086098985988 (1.90 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 807
telemt_user_unique_ips_recent_window{user="hello"} 198
```
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

# Server Metrics 2026-03-22 02:10:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 18230.2 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262467
telemt_connections_bad_total 18363
telemt_connections_current 740
telemt_connections_me_current 740
telemt_handshake_timeouts_total 15123
telemt_upstream_connect_attempt_total 7623
telemt_upstream_connect_success_total 7622
telemt_upstream_connect_attempts_per_request{bucket="1"} 7622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4824
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 247
telemt_me_reconnect_success_total 121
telemt_me_reader_eof_total 119
telemt_me_idle_close_by_peer_total 119
telemt_me_route_drop_no_conn_total 48131
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214838
telemt_me_endpoint_quarantine_total 154
telemt_me_single_endpoint_shadow_rotate_total 157
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 1906
telemt_desync_full_logged_total 522
telemt_desync_suppressed_total 1384
telemt_desync_frames_bucket_total{bucket="1_2"} 603
telemt_desync_frames_bucket_total{bucket="3_10"} 699
telemt_desync_frames_bucket_total{bucket="gt_10"} 604
telemt_pool_swap_total 20
telemt_pool_force_close_total 520
telemt_me_writer_close_signal_drop_total 35
telemt_me_draining_writers_reap_progress_total 6851
telemt_me_writer_removed_unexpected_total 119
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 484
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6476
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 515
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6331
telemt_me_writer_teardown_success_total{mode="normal"} 6960
telemt_me_writer_teardown_noop_total 6852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13812
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.265011
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13812
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 35
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 110
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 214444
telemt_user_connections_current{user="hello"} 740
telemt_user_octets_from_client{user="hello"} 2327057176 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 75566593872 (70.38 GB)
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 31596.1 (8h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 763463
telemt_connections_bad_total 43837
telemt_connections_current 771
telemt_connections_me_current 771
telemt_handshake_timeouts_total 28271
telemt_upstream_connect_attempt_total 14586
telemt_upstream_connect_success_total 14349
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 14565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8003
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_reconnect_attempts_total 1228
telemt_me_reconnect_success_total 460
telemt_me_reader_eof_total 403
telemt_me_idle_close_by_peer_total 403
telemt_me_route_drop_no_conn_total 338062
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 608848
telemt_me_endpoint_quarantine_total 298
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 17
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 17
telemt_me_single_endpoint_shadow_rotate_total 254
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
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
telemt_me_writers_active_current 51
telemt_me_writers_warm_current 29
telemt_desync_total 2654
telemt_desync_full_logged_total 1518
telemt_desync_suppressed_total 1136
telemt_desync_frames_bucket_total{bucket="1_2"} 562
telemt_desync_frames_bucket_total{bucket="3_10"} 1007
telemt_desync_frames_bucket_total{bucket="gt_10"} 1085
telemt_pool_swap_total 33
telemt_pool_force_close_total 909
telemt_me_writer_close_signal_drop_total 64
telemt_me_draining_writers_reap_progress_total 12876
telemt_me_writer_removed_unexpected_total 384
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1086
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12180
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 887
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11967
telemt_me_writer_teardown_success_total{mode="normal"} 13266
telemt_me_writer_teardown_noop_total 12876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26142
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.537865
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26142
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 64
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 339
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 607957
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 9995087296 (9.31 GB)
telemt_user_octets_to_client{user="hello"} 217003938112 (202.10 GB)
telemt_user_unique_ips_current{user="hello"} 517
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 106456.1 (29h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7681913
telemt_connections_bad_total 623024
telemt_connections_current 1312
telemt_connections_me_current 1312
telemt_handshake_timeouts_total 252189
telemt_upstream_connect_attempt_total 39335
telemt_upstream_connect_success_total 39261
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 39268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21287
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1558
telemt_me_reconnect_success_total 798
telemt_me_reader_eof_total 807
telemt_me_idle_close_by_peer_total 807
telemt_me_route_drop_no_conn_total 4528785
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6227278
telemt_me_endpoint_quarantine_total 686
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 795
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
telemt_desync_total 26322
telemt_desync_full_logged_total 8708
telemt_desync_suppressed_total 17614
telemt_desync_frames_bucket_total{bucket="1_2"} 5674
telemt_desync_frames_bucket_total{bucket="3_10"} 10273
telemt_desync_frames_bucket_total{bucket="gt_10"} 10375
telemt_pool_swap_total 115
telemt_pool_force_close_total 3833
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 600
telemt_me_draining_writers_reap_progress_total 35901
telemt_me_writer_removed_unexpected_total 776
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3000
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33221
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3594
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32068
telemt_me_writer_teardown_success_total{mode="normal"} 36221
telemt_me_writer_teardown_noop_total 35945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72166
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 157.467719
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72166
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 600
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 709
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 6219458
telemt_user_connections_current{user="hello"} 1312
telemt_user_octets_from_client{user="hello"} 105922497376 (98.65 GB)
telemt_user_octets_to_client{user="hello"} 2064521518592 (1.88 TB)
telemt_user_unique_ips_current{user="hello"} 628
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 106457.5 (29h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6336040
telemt_connections_bad_total 585319
telemt_connections_current 1374
telemt_connections_me_current 1374
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 209610
telemt_upstream_connect_attempt_total 43353
telemt_upstream_connect_success_total 42965
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 43155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21027
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1934
telemt_me_reconnect_success_total 865
telemt_me_reader_eof_total 836
telemt_me_idle_close_by_peer_total 836
telemt_me_route_drop_no_conn_total 2250526
telemt_me_route_drop_channel_closed_total 257
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4743189
telemt_me_endpoint_quarantine_total 664
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 818
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
telemt_me_writers_active_current 44
telemt_desync_total 22482
telemt_desync_full_logged_total 7641
telemt_desync_suppressed_total 14841
telemt_desync_frames_bucket_total{bucket="1_2"} 5416
telemt_desync_frames_bucket_total{bucket="3_10"} 8724
telemt_desync_frames_bucket_total{bucket="gt_10"} 8342
telemt_pool_swap_total 116
telemt_pool_force_close_total 3471
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 358
telemt_me_draining_writers_reap_progress_total 34413
telemt_me_writer_removed_unexpected_total 821
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2909
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32262
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3258
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30942
telemt_me_writer_teardown_success_total{mode="normal"} 35171
telemt_me_writer_teardown_noop_total 34419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69590
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.264101
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69590
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 358
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 756
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 4665387
telemt_user_connections_current{user="hello"} 1374
telemt_user_octets_from_client{user="hello"} 139859890221 (130.25 GB)
telemt_user_octets_to_client{user="hello"} 2197897234655 (2.00 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 660
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 106422.1 (29h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6222100
telemt_connections_bad_total 546149
telemt_connections_current 1407
telemt_connections_me_current 1407
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 200915
telemt_upstream_connect_attempt_total 49610
telemt_upstream_connect_success_total 49252
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 49388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22391
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 448
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1965
telemt_me_reconnect_success_total 891
telemt_me_reader_eof_total 835
telemt_me_idle_close_by_peer_total 835
telemt_me_route_drop_no_conn_total 2143695
telemt_me_route_drop_channel_closed_total 119
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4636513
telemt_me_endpoint_quarantine_total 743
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 795
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
telemt_desync_total 22345
telemt_desync_full_logged_total 7502
telemt_desync_suppressed_total 14843
telemt_desync_frames_bucket_total{bucket="1_2"} 5455
telemt_desync_frames_bucket_total{bucket="3_10"} 8560
telemt_desync_frames_bucket_total{bucket="gt_10"} 8330
telemt_pool_swap_total 115
telemt_pool_force_close_total 3344
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 383
telemt_me_draining_writers_reap_progress_total 35705
telemt_me_writer_removed_unexpected_total 807
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2962
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33564
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3129
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32361
telemt_me_writer_teardown_success_total{mode="normal"} 36526
telemt_me_writer_teardown_noop_total 35717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72243
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 26.547379
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72243
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 383
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 774
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4632165
telemt_user_connections_current{user="hello"} 1407
telemt_user_octets_from_client{user="hello"} 133300640715 (124.15 GB)
telemt_user_octets_to_client{user="hello"} 2115868258031 (1.92 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 590
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 106476.4 (29h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20324645
telemt_connections_bad_total 1592500
telemt_connections_current 1967
telemt_connections_me_current 1967
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 599946
telemt_upstream_connect_attempt_total 194710
telemt_upstream_connect_success_total 176749
telemt_upstream_connect_fail_total 16227
telemt_upstream_connect_attempts_per_request{bucket="1"} 192976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42025
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8912
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16227
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64839
telemt_me_reconnect_success_total 2300
telemt_me_reader_eof_total 1436
telemt_me_idle_close_by_peer_total 1435
telemt_me_route_drop_no_conn_total 39496889
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16452545
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 837
telemt_me_single_endpoint_outage_enter_total 134
telemt_me_single_endpoint_outage_exit_total 134
telemt_me_single_endpoint_outage_reconnect_attempt_total 284
telemt_me_single_endpoint_outage_reconnect_success_total 69
telemt_me_single_endpoint_quarantine_bypass_total 284
telemt_me_single_endpoint_shadow_rotate_total 833
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 62
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
telemt_desync_total 31872
telemt_desync_full_logged_total 9543
telemt_desync_suppressed_total 22329
telemt_desync_frames_bucket_total{bucket="1_2"} 6904
telemt_desync_frames_bucket_total{bucket="3_10"} 14147
telemt_desync_frames_bucket_total{bucket="gt_10"} 10821
telemt_pool_swap_total 110
telemt_pool_force_close_total 3601
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 792
telemt_me_draining_writers_reap_progress_total 33288
telemt_me_writer_removed_unexpected_total 2136
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4507
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30656
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3078
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 523
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29687
telemt_me_writer_teardown_success_total{mode="normal"} 35163
telemt_me_writer_teardown_noop_total 33314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68477
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 214.656795
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68477
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 792
telemt_me_refill_failed_total 3801
telemt_me_writer_restored_same_endpoint_total 1577
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 538
telemt_user_connections_total{user="hello"} 16582065
telemt_user_connections_current{user="hello"} 1967
telemt_user_octets_from_client{user="hello"} 212720448782 (198.11 GB)
telemt_user_octets_to_client{user="hello"} 1183275949103 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 373576
telemt_user_msgs_to_client{user="hello"} 663916
telemt_user_unique_ips_current{user="hello"} 912
telemt_user_unique_ips_recent_window{user="hello"} 265
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 106428.2 (29h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5979064
telemt_connections_bad_total 559146
telemt_connections_current 1034
telemt_connections_me_current 1034
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 124976
telemt_upstream_connect_attempt_total 58105
telemt_upstream_connect_success_total 57428
telemt_upstream_connect_fail_total 580
telemt_upstream_connect_attempts_per_request{bucket="1"} 58008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23427
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 580
telemt_me_reconnect_attempts_total 69636
telemt_me_reconnect_success_total 1775
telemt_me_reader_eof_total 1553
telemt_me_idle_close_by_peer_total 1552
telemt_me_route_drop_no_conn_total 2382865
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4667043
telemt_me_endpoint_quarantine_total 720
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 803
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
telemt_me_writers_active_current 44
telemt_desync_total 23278
telemt_desync_full_logged_total 8193
telemt_desync_suppressed_total 15085
telemt_desync_frames_bucket_total{bucket="1_2"} 4425
telemt_desync_frames_bucket_total{bucket="3_10"} 9010
telemt_desync_frames_bucket_total{bucket="gt_10"} 9843
telemt_pool_swap_total 110
telemt_pool_force_close_total 3179
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 392
telemt_me_draining_writers_reap_progress_total 37392
telemt_me_writer_removed_unexpected_total 1592
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3868
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35146
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2778
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34213
telemt_me_writer_teardown_success_total{mode="normal"} 39014
telemt_me_writer_teardown_noop_total 37393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76407
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.113480
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76407
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 392
telemt_me_refill_failed_total 4206
telemt_me_writer_restored_same_endpoint_total 1487
telemt_me_writer_restored_fallback_total 33
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 4659918
telemt_user_connections_current{user="hello"} 1034
telemt_user_octets_from_client{user="hello"} 124017390588 (115.50 GB)
telemt_user_octets_to_client{user="hello"} 1902353830478 (1.73 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 471
telemt_user_unique_ips_recent_window{user="hello"} 340
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 43264.1 (12h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3865823
telemt_connections_bad_total 140160
telemt_connections_current 1473
telemt_connections_me_current 1473
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1579198
telemt_upstream_connect_attempt_total 26518
telemt_upstream_connect_success_total 26345
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 26511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9468
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_reconnect_attempts_total 45800
telemt_me_reconnect_success_total 948
telemt_me_reader_eof_total 628
telemt_me_idle_close_by_peer_total 628
telemt_me_route_drop_no_conn_total 1016560
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1895268
telemt_me_endpoint_quarantine_total 320
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 329
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 20
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10366
telemt_desync_full_logged_total 3572
telemt_desync_suppressed_total 6794
telemt_desync_frames_bucket_total{bucket="1_2"} 1846
telemt_desync_frames_bucket_total{bucket="3_10"} 3976
telemt_desync_frames_bucket_total{bucket="gt_10"} 4544
telemt_pool_swap_total 46
telemt_pool_force_close_total 1429
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 132
telemt_me_draining_writers_reap_progress_total 15632
telemt_me_writer_removed_unexpected_total 704
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1473
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14887
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1223
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14203
telemt_me_writer_teardown_success_total{mode="normal"} 16360
telemt_me_writer_teardown_noop_total 15634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31994
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.346279
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31994
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 132
telemt_me_refill_failed_total 2606
telemt_me_writer_restored_same_endpoint_total 849
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1898931
telemt_user_connections_current{user="hello"} 1473
telemt_user_octets_from_client{user="hello"} 53663638448 (49.98 GB)
telemt_user_octets_to_client{user="hello"} 810263016630 (754.62 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 813
telemt_user_unique_ips_recent_window{user="hello"} 258
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 24235.2 (6h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189136
telemt_connections_bad_total 1625
telemt_connections_current 333
telemt_connections_me_current 333
telemt_handshake_timeouts_total 5229
telemt_upstream_connect_attempt_total 11573
telemt_upstream_connect_success_total 11545
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 11571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6582
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 235
telemt_me_reconnect_success_total 149
telemt_me_reader_eof_total 151
telemt_me_idle_close_by_peer_total 151
telemt_me_route_drop_no_conn_total 51596
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166646
telemt_me_endpoint_quarantine_total 239
telemt_me_single_endpoint_shadow_rotate_total 212
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 1008
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 754
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 250
telemt_pool_swap_total 26
telemt_pool_force_close_total 582
telemt_me_writer_close_signal_drop_total 22
telemt_me_draining_writers_reap_progress_total 10436
telemt_me_writer_removed_unexpected_total 146
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 678
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9909
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 580
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9854
telemt_me_writer_teardown_success_total{mode="normal"} 10587
telemt_me_writer_teardown_noop_total 10436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 20828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 21013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 21023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 21023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 21023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 21023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 21023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 21023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 21023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 21023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 21023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 21023
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.958351
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 21023
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 22
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 136
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 166337
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 3047071156 (2.84 GB)
telemt_user_octets_to_client{user="hello"} 100449674548 (93.55 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 106432.6 (29h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7268704
telemt_connections_bad_total 738585
telemt_connections_current 1577
telemt_connections_me_current 1577
telemt_handshake_timeouts_total 206831
telemt_upstream_connect_attempt_total 41625
telemt_upstream_connect_success_total 41469
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 41588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20855
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_reconnect_attempts_total 1574
telemt_me_reconnect_success_total 840
telemt_me_reader_eof_total 823
telemt_me_idle_close_by_peer_total 823
telemt_me_route_drop_no_conn_total 2120532
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5447033
telemt_me_endpoint_quarantine_total 741
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 819
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
telemt_me_writers_active_current 43
telemt_desync_total 21399
telemt_desync_full_logged_total 7018
telemt_desync_suppressed_total 14381
telemt_desync_frames_bucket_total{bucket="1_2"} 5384
telemt_desync_frames_bucket_total{bucket="3_10"} 7745
telemt_desync_frames_bucket_total{bucket="gt_10"} 8270
telemt_pool_swap_total 118
telemt_pool_force_close_total 3169
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 386
telemt_me_draining_writers_reap_progress_total 37527
telemt_me_writer_removed_unexpected_total 794
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2968
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35372
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3081
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34358
telemt_me_writer_teardown_success_total{mode="normal"} 38340
telemt_me_writer_teardown_noop_total 37529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75869
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.633240
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75869
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 386
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 750
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 5422053
telemt_user_connections_current{user="hello"} 1577
telemt_user_octets_from_client{user="hello"} 109040085900 (101.55 GB)
telemt_user_octets_to_client{user="hello"} 2527236979568 (2.30 TB)
telemt_user_unique_ips_current{user="hello"} 682
telemt_user_unique_ips_recent_window{user="hello"} 347
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 106429.3 (29h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6269289
telemt_connections_bad_total 619302
telemt_connections_current 1231
telemt_connections_me_current 1231
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 172051
telemt_upstream_connect_attempt_total 57368
telemt_upstream_connect_success_total 56939
telemt_upstream_connect_fail_total 370
telemt_upstream_connect_attempts_per_request{bucket="1"} 57309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22567
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 370
telemt_me_reconnect_attempts_total 5552
telemt_me_reconnect_success_total 1154
telemt_me_reader_eof_total 1037
telemt_me_idle_close_by_peer_total 1037
telemt_me_seq_mismatch_total 47
telemt_me_route_drop_no_conn_total 2173728
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4813919
telemt_me_endpoint_quarantine_total 846
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 815
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
telemt_me_writers_active_current 44
telemt_desync_total 20015
telemt_desync_full_logged_total 6655
telemt_desync_suppressed_total 13360
telemt_desync_frames_bucket_total{bucket="1_2"} 5107
telemt_desync_frames_bucket_total{bucket="3_10"} 7294
telemt_desync_frames_bucket_total{bucket="gt_10"} 7614
telemt_pool_swap_total 116
telemt_pool_force_close_total 3128
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 379
telemt_me_draining_writers_reap_progress_total 36053
telemt_me_writer_removed_unexpected_total 1050
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3489
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33663
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2905
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32925
telemt_me_writer_teardown_success_total{mode="normal"} 37152
telemt_me_writer_teardown_noop_total 36057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73209
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.070451
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73209
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 379
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 900
telemt_me_writer_restored_fallback_total 60
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4816990
telemt_user_connections_current{user="hello"} 1231
telemt_user_octets_from_client{user="hello"} 90517175505 (84.30 GB)
telemt_user_octets_to_client{user="hello"} 2058326801744 (1.87 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 566
telemt_user_unique_ips_recent_window{user="hello"} 375
```
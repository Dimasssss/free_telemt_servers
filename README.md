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

# Server Metrics 2026-03-22 20:46:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 85177.2 (23h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3147029
telemt_connections_bad_total 220903
telemt_connections_current 981
telemt_connections_me_current 981
telemt_handshake_timeouts_total 100394
telemt_upstream_connect_attempt_total 31192
telemt_upstream_connect_success_total 31191
telemt_upstream_connect_attempts_per_request{bucket="1"} 31191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20338
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 85
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1274
telemt_me_reconnect_success_total 522
telemt_me_reader_eof_total 531
telemt_me_idle_close_by_peer_total 531
telemt_me_route_drop_no_conn_total 2808839
telemt_me_route_drop_channel_closed_total 1118
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2657647
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 576
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 660
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
telemt_me_writers_active_current 47
telemt_desync_total 11483
telemt_desync_full_logged_total 3601
telemt_desync_suppressed_total 7882
telemt_desync_frames_bucket_total{bucket="1_2"} 3096
telemt_desync_frames_bucket_total{bucket="3_10"} 4213
telemt_desync_frames_bucket_total{bucket="gt_10"} 4174
telemt_pool_swap_total 94
telemt_pool_force_close_total 2936
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 601
telemt_me_draining_writers_reap_progress_total 28525
telemt_me_writer_removed_unexpected_total 516
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2081
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26664
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 54
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25589
telemt_me_writer_teardown_success_total{mode="normal"} 28745
telemt_me_writer_teardown_noop_total 28536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57281
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 329.041633
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57281
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 601
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 463
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 2648689
telemt_user_connections_current{user="hello"} 981
telemt_user_octets_from_client{user="hello"} 38748091436 (36.09 GB)
telemt_user_octets_to_client{user="hello"} 706725827336 (658.19 GB)
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 98543.6 (27h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3872101
telemt_connections_bad_total 342160
telemt_connections_current 513
telemt_connections_me_current 513
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 98502
telemt_upstream_connect_attempt_total 59421
telemt_upstream_connect_success_total 58693
telemt_upstream_connect_fail_total 642
telemt_upstream_connect_attempts_per_request{bucket="1"} 59335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 642
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6848
telemt_me_reconnect_success_total 2674
telemt_me_reader_eof_total 2623
telemt_me_idle_close_by_peer_total 2623
telemt_me_route_drop_no_conn_total 3616994
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3086606
telemt_me_endpoint_quarantine_total 752
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 758
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
telemt_desync_total 12443
telemt_desync_full_logged_total 6965
telemt_desync_suppressed_total 5478
telemt_desync_frames_bucket_total{bucket="1_2"} 2829
telemt_desync_frames_bucket_total{bucket="3_10"} 4876
telemt_desync_frames_bucket_total{bucket="gt_10"} 4738
telemt_pool_swap_total 92
telemt_pool_force_close_total 2802
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 234
telemt_me_draining_writers_reap_progress_total 39293
telemt_me_writer_removed_unexpected_total 2566
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4809
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37070
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2375
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36491
telemt_me_writer_teardown_success_total{mode="normal"} 41879
telemt_me_writer_teardown_noop_total 39294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81173
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.349619
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81173
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 234
telemt_me_refill_failed_total 166
telemt_me_writer_restored_same_endpoint_total 2357
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 3097333
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 40678295579 (37.88 GB)
telemt_user_octets_to_client{user="hello"} 749095792342 (697.65 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 173403.3 (48h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16030403
telemt_connections_bad_total 1554018
telemt_connections_current 1405
telemt_connections_me_current 1405
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 393878
telemt_upstream_connect_attempt_total 76900
telemt_upstream_connect_success_total 76800
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 76817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36912
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1690
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2817
telemt_me_reconnect_success_total 1454
telemt_me_reader_eof_total 1398
telemt_me_idle_close_by_peer_total 1396
telemt_me_route_drop_no_conn_total 13998389
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12775461
telemt_me_endpoint_quarantine_total 1097
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1292
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 52740
telemt_desync_full_logged_total 16621
telemt_desync_suppressed_total 36119
telemt_desync_frames_bucket_total{bucket="1_2"} 11741
telemt_desync_frames_bucket_total{bucket="3_10"} 20535
telemt_desync_frames_bucket_total{bucket="gt_10"} 20464
telemt_pool_swap_total 187
telemt_pool_force_close_total 6303
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1020
telemt_me_draining_writers_reap_progress_total 56998
telemt_me_writer_removed_unexpected_total 1349
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4986
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52639
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5833
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50695
telemt_me_writer_teardown_success_total{mode="normal"} 57625
telemt_me_writer_teardown_noop_total 57049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114674
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 313.764200
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114674
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1020
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1254
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 12775859
telemt_user_connections_current{user="hello"} 1405
telemt_user_octets_from_client{user="hello"} 187181413813 (174.33 GB)
telemt_user_octets_to_client{user="hello"} 3411086632699 (3.10 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 645
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 173404.8 (48h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11610533
telemt_connections_bad_total 1167401
telemt_connections_current 1015
telemt_connections_me_current 1015
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343328
telemt_upstream_connect_attempt_total 91378
telemt_upstream_connect_success_total 90091
telemt_upstream_connect_fail_total 857
telemt_upstream_connect_attempts_per_request{bucket="1"} 90948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36937
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3777
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 857
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4261
telemt_me_reconnect_success_total 1771
telemt_me_reader_eof_total 1628
telemt_me_idle_close_by_peer_total 1628
telemt_me_route_drop_no_conn_total 4515338
telemt_me_route_drop_channel_closed_total 496
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8647586
telemt_me_endpoint_quarantine_total 1101
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1314
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
telemt_me_writers_active_current 45
telemt_desync_total 38307
telemt_desync_full_logged_total 12884
telemt_desync_suppressed_total 25423
telemt_desync_frames_bucket_total{bucket="1_2"} 9449
telemt_desync_frames_bucket_total{bucket="3_10"} 14736
telemt_desync_frames_bucket_total{bucket="gt_10"} 14122
telemt_pool_swap_total 184
telemt_pool_force_close_total 5673
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 704
telemt_me_draining_writers_reap_progress_total 55365
telemt_me_writer_removed_unexpected_total 1667
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5143
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51736
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5161
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49692
telemt_me_writer_teardown_success_total{mode="normal"} 56879
telemt_me_writer_teardown_noop_total 55390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112269
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.767201
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112269
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 704
telemt_me_refill_failed_total 134
telemt_me_writer_restored_same_endpoint_total 1504
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 8587561
telemt_user_connections_current{user="hello"} 1015
telemt_user_octets_from_client{user="hello"} 215842522408 (201.02 GB)
telemt_user_octets_to_client{user="hello"} 3881737256991 (3.53 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 387
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 173371.8 (48h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10876960
telemt_connections_bad_total 942573
telemt_connections_current 1214
telemt_connections_me_current 1214
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344343
telemt_upstream_connect_attempt_total 74855
telemt_upstream_connect_success_total 73603
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 73794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35262
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1698
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2247
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1411
telemt_me_reconnect_attempts_total 5191
telemt_me_reconnect_success_total 2130
telemt_me_reader_eof_total 1869
telemt_me_idle_close_by_peer_total 1868
telemt_me_route_drop_no_conn_total 5292009
telemt_me_route_drop_channel_closed_total 379
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8229494
telemt_me_endpoint_quarantine_total 1176
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1269
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 65
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
telemt_me_writers_active_current 90
telemt_desync_total 37712
telemt_desync_full_logged_total 12489
telemt_desync_suppressed_total 25223
telemt_desync_frames_bucket_total{bucket="1_2"} 9533
telemt_desync_frames_bucket_total{bucket="3_10"} 14413
telemt_desync_frames_bucket_total{bucket="gt_10"} 13766
telemt_pool_swap_total 181
telemt_pool_force_close_total 5609
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 716
telemt_me_draining_writers_reap_progress_total 55502
telemt_me_writer_removed_unexpected_total 2014
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5671
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51767
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5058
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 551
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49893
telemt_me_writer_teardown_success_total{mode="normal"} 57438
telemt_me_writer_teardown_noop_total 55573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113011
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.042088
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113011
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 716
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 1838
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 8221606
telemt_user_connections_current{user="hello"} 1212
telemt_user_octets_from_client{user="hello"} 191521980749 (178.37 GB)
telemt_user_octets_to_client{user="hello"} 3420751617437 (3.11 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 514
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 43648.9 (12h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10912758
telemt_connections_bad_total 661180
telemt_connections_current 1394
telemt_connections_me_current 1394
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 239257
telemt_upstream_connect_attempt_total 49231
telemt_upstream_connect_success_total 46735
telemt_upstream_connect_fail_total 1726
telemt_upstream_connect_attempts_per_request{bucket="1"} 48461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15142
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5982
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1726
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6875
telemt_me_reconnect_success_total 989
telemt_me_reader_eof_total 601
telemt_me_idle_close_by_peer_total 601
telemt_me_route_drop_no_conn_total 25225543
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9062688
telemt_me_endpoint_quarantine_total 299
telemt_me_single_endpoint_outage_enter_total 75
telemt_me_single_endpoint_outage_exit_total 75
telemt_me_single_endpoint_outage_reconnect_attempt_total 134
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 134
telemt_me_single_endpoint_shadow_rotate_total 349
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
telemt_me_writers_active_current 43
telemt_desync_total 14947
telemt_desync_full_logged_total 3960
telemt_desync_suppressed_total 10987
telemt_desync_frames_bucket_total{bucket="1_2"} 2816
telemt_desync_frames_bucket_total{bucket="3_10"} 6064
telemt_desync_frames_bucket_total{bucket="gt_10"} 6067
telemt_pool_swap_total 44
telemt_pool_force_close_total 1587
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 445
telemt_me_draining_writers_reap_progress_total 12573
telemt_me_writer_removed_unexpected_total 884
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1902
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11507
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1285
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 302
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10986
telemt_me_writer_teardown_success_total{mode="normal"} 13409
telemt_me_writer_teardown_noop_total 12592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26001
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 51.957388
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26001
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 445
telemt_me_refill_failed_total 320
telemt_me_writer_restored_same_endpoint_total 644
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 9087463
telemt_user_connections_current{user="hello"} 1394
telemt_user_octets_from_client{user="hello"} 84027761036 (78.26 GB)
telemt_user_octets_to_client{user="hello"} 520618917722 (484.86 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 571
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 173375.5 (48h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10769477
telemt_connections_bad_total 909282
telemt_connections_current 1299
telemt_connections_me_current 1299
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 237250
telemt_upstream_connect_attempt_total 104014
telemt_upstream_connect_success_total 102923
telemt_upstream_connect_fail_total 930
telemt_upstream_connect_attempts_per_request{bucket="1"} 103853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38856
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1345
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 930
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72440
telemt_me_reconnect_success_total 2845
telemt_me_reader_eof_total 2538
telemt_me_idle_close_by_peer_total 2536
telemt_me_route_drop_no_conn_total 5215444
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8509158
telemt_me_endpoint_quarantine_total 1144
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1297
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 45360
telemt_desync_full_logged_total 15471
telemt_desync_suppressed_total 29889
telemt_desync_frames_bucket_total{bucket="1_2"} 9199
telemt_desync_frames_bucket_total{bucket="3_10"} 17379
telemt_desync_frames_bucket_total{bucket="gt_10"} 18782
telemt_pool_swap_total 177
telemt_pool_force_close_total 5287
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 643
telemt_me_draining_writers_reap_progress_total 59441
telemt_me_writer_removed_unexpected_total 2575
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6295
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55748
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4557
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 730
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54154
telemt_me_writer_teardown_success_total{mode="normal"} 62043
telemt_me_writer_teardown_noop_total 59442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121485
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.066036
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121485
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 643
telemt_me_refill_failed_total 4287
telemt_me_writer_restored_same_endpoint_total 2394
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 8512367
telemt_user_connections_current{user="hello"} 1299
telemt_user_octets_from_client{user="hello"} 192409524353 (179.20 GB)
telemt_user_octets_to_client{user="hello"} 3240446163416 (2.95 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 565
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 110211.6 (30h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11375042
telemt_connections_bad_total 455624
telemt_connections_current 990
telemt_connections_me_current 990
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4667582
telemt_upstream_connect_attempt_total 52152
telemt_upstream_connect_success_total 51761
telemt_upstream_connect_fail_total 381
telemt_upstream_connect_attempts_per_request{bucket="1"} 52142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23269
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 381
telemt_me_reconnect_attempts_total 48596
telemt_me_reconnect_success_total 1686
telemt_me_reader_eof_total 1344
telemt_me_idle_close_by_peer_total 1343
telemt_me_route_drop_no_conn_total 4050818
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5483833
telemt_me_endpoint_quarantine_total 713
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 833
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30838
telemt_desync_full_logged_total 10473
telemt_desync_suppressed_total 20365
telemt_desync_frames_bucket_total{bucket="1_2"} 6131
telemt_desync_frames_bucket_total{bucket="3_10"} 12200
telemt_desync_frames_bucket_total{bucket="gt_10"} 12507
telemt_pool_swap_total 116
telemt_pool_force_close_total 3534
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 356
telemt_me_draining_writers_reap_progress_total 38457
telemt_me_writer_removed_unexpected_total 1404
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3378
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36517
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3093
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34923
telemt_me_writer_teardown_success_total{mode="normal"} 39895
telemt_me_writer_teardown_noop_total 38464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78359
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.531883
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78359
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 356
telemt_me_refill_failed_total 2726
telemt_me_writer_restored_same_endpoint_total 1498
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5476595
telemt_user_connections_current{user="hello"} 990
telemt_user_octets_from_client{user="hello"} 117643395836 (109.56 GB)
telemt_user_octets_to_client{user="hello"} 2100578796778 (1.91 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 91182.6 (25h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1382401
telemt_connections_bad_total 33750
telemt_connections_current 873
telemt_connections_me_current 873
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 25675
telemt_upstream_connect_attempt_total 42977
telemt_upstream_connect_success_total 42845
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 42950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22774
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 738
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2036
telemt_me_reconnect_success_total 824
telemt_me_reader_eof_total 805
telemt_me_idle_close_by_peer_total 805
telemt_me_route_drop_no_conn_total 482817
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1226257
telemt_me_endpoint_quarantine_total 753
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 751
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
telemt_desync_total 7487
telemt_desync_full_logged_total 2313
telemt_desync_suppressed_total 5174
telemt_desync_frames_bucket_total{bucket="1_2"} 1677
telemt_desync_frames_bucket_total{bucket="3_10"} 2903
telemt_desync_frames_bucket_total{bucket="gt_10"} 2907
telemt_pool_swap_total 98
telemt_pool_force_close_total 2549
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 147
telemt_me_draining_writers_reap_progress_total 35838
telemt_me_writer_removed_unexpected_total 776
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2834
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33812
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2462
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33289
telemt_me_writer_teardown_success_total{mode="normal"} 36646
telemt_me_writer_teardown_noop_total 35842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72488
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.554181
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72488
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 147
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 698
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1222282
telemt_user_connections_current{user="hello"} 873
telemt_user_octets_from_client{user="hello"} 23738028041 (22.11 GB)
telemt_user_octets_to_client{user="hello"} 517889374547 (482.32 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 173379.9 (48h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13091440
telemt_connections_bad_total 1536118
telemt_connections_current 1391
telemt_connections_me_current 1391
telemt_handshake_timeouts_total 375348
telemt_upstream_connect_attempt_total 65696
telemt_upstream_connect_success_total 65364
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 65561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32883
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2575
telemt_me_reconnect_success_total 1352
telemt_me_reader_eof_total 1319
telemt_me_idle_close_by_peer_total 1319
telemt_me_route_drop_no_conn_total 4432440
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9904191
telemt_me_endpoint_quarantine_total 1168
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1300
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
telemt_me_writers_active_current 45
telemt_desync_total 41124
telemt_desync_full_logged_total 13403
telemt_desync_suppressed_total 27721
telemt_desync_frames_bucket_total{bucket="1_2"} 9842
telemt_desync_frames_bucket_total{bucket="3_10"} 15171
telemt_desync_frames_bucket_total{bucket="gt_10"} 16111
telemt_pool_swap_total 192
telemt_pool_force_close_total 5272
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 654
telemt_me_draining_writers_reap_progress_total 59197
telemt_me_writer_removed_unexpected_total 1269
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4821
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55685
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5098
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53925
telemt_me_writer_teardown_success_total{mode="normal"} 60506
telemt_me_writer_teardown_noop_total 59199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 119705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119705
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.524149
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119705
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 654
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1183
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 9871810
telemt_user_connections_current{user="hello"} 1391
telemt_user_octets_from_client{user="hello"} 192753114760 (179.52 GB)
telemt_user_octets_to_client{user="hello"} 4365581150756 (3.97 TB)
telemt_user_unique_ips_current{user="hello"} 508
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 173376.6 (48h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11388095
telemt_connections_bad_total 1289189
telemt_connections_current 1207
telemt_connections_me_current 1207
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 299833
telemt_upstream_connect_attempt_total 92139
telemt_upstream_connect_success_total 91308
telemt_upstream_connect_fail_total 624
telemt_upstream_connect_attempts_per_request{bucket="1"} 91932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38415
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 624
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9917
telemt_me_reconnect_success_total 2381
telemt_me_reader_eof_total 2225
telemt_me_idle_close_by_peer_total 2224
telemt_me_seq_mismatch_total 79
telemt_me_route_drop_no_conn_total 5609519
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8807910
telemt_me_endpoint_quarantine_total 1328
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 1299
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 40328
telemt_desync_full_logged_total 13028
telemt_desync_suppressed_total 27300
telemt_desync_frames_bucket_total{bucket="1_2"} 10071
telemt_desync_frames_bucket_total{bucket="3_10"} 14970
telemt_desync_frames_bucket_total{bucket="gt_10"} 15287
telemt_pool_swap_total 182
telemt_pool_force_close_total 5069
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 640
telemt_me_draining_writers_reap_progress_total 58976
telemt_me_writer_removed_unexpected_total 2257
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6163
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55146
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4598
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53907
telemt_me_writer_teardown_success_total{mode="normal"} 61309
telemt_me_writer_teardown_noop_total 58981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 120290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120290
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.231400
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120290
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 640
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 1939
telemt_me_writer_restored_fallback_total 109
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 8813413
telemt_user_connections_current{user="hello"} 1207
telemt_user_octets_from_client{user="hello"} 155956026625 (145.25 GB)
telemt_user_octets_to_client{user="hello"} 3416600928159 (3.11 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 453
telemt_user_unique_ips_recent_window{user="hello"} 134
```
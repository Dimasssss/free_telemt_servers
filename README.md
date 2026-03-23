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

# Server Metrics 2026-03-23 00:50:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 99852.5 (27h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3491684
telemt_connections_bad_total 304759
telemt_connections_current 872
telemt_connections_me_current 872
telemt_handshake_timeouts_total 109147
telemt_upstream_connect_attempt_total 37012
telemt_upstream_connect_success_total 37011
telemt_upstream_connect_attempts_per_request{bucket="1"} 37011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24041
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1387
telemt_me_reconnect_success_total 594
telemt_me_reader_eof_total 609
telemt_me_idle_close_by_peer_total 609
telemt_me_route_drop_no_conn_total 2980813
telemt_me_route_drop_channel_closed_total 1231
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2886318
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 697
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 776
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
telemt_me_writers_active_current 46
telemt_desync_total 12394
telemt_desync_full_logged_total 3884
telemt_desync_suppressed_total 8510
telemt_desync_frames_bucket_total{bucket="1_2"} 3347
telemt_desync_frames_bucket_total{bucket="3_10"} 4506
telemt_desync_frames_bucket_total{bucket="gt_10"} 4541
telemt_pool_swap_total 110
telemt_pool_force_close_total 3403
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 651
telemt_me_draining_writers_reap_progress_total 33884
telemt_me_writer_removed_unexpected_total 588
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2448
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31671
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3347
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30481
telemt_me_writer_teardown_success_total{mode="normal"} 34119
telemt_me_writer_teardown_noop_total 33895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68014
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 376.145008
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68014
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 651
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 531
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2875436
telemt_user_connections_current{user="hello"} 872
telemt_user_octets_from_client{user="hello"} 40993555476 (38.18 GB)
telemt_user_octets_to_client{user="hello"} 787236168420 (733.17 GB)
telemt_user_unique_ips_current{user="hello"} 421
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 113218.5 (31h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3993627
telemt_connections_bad_total 366355
telemt_connections_current 345
telemt_connections_me_current 345
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100581
telemt_upstream_connect_attempt_total 70305
telemt_upstream_connect_success_total 69468
telemt_upstream_connect_fail_total 744
telemt_upstream_connect_attempts_per_request{bucket="1"} 70212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 744
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9940
telemt_me_reconnect_success_total 3589
telemt_me_reader_eof_total 3586
telemt_me_idle_close_by_peer_total 3586
telemt_me_route_drop_no_conn_total 3640421
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3174655
telemt_me_endpoint_quarantine_total 886
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 44
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 44
telemt_me_single_endpoint_shadow_rotate_total 882
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
telemt_desync_total 12947
telemt_desync_full_logged_total 7258
telemt_desync_suppressed_total 5689
telemt_desync_frames_bucket_total{bucket="1_2"} 2939
telemt_desync_frames_bucket_total{bucket="3_10"} 5075
telemt_desync_frames_bucket_total{bucket="gt_10"} 4933
telemt_pool_swap_total 105
telemt_pool_force_close_total 3052
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 252
telemt_me_draining_writers_reap_progress_total 46445
telemt_me_writer_removed_unexpected_total 3518
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6136
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43858
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2594
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43393
telemt_me_writer_teardown_success_total{mode="normal"} 49994
telemt_me_writer_teardown_noop_total 46446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96440
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.590970
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96440
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 252
telemt_me_refill_failed_total 244
telemt_me_writer_restored_same_endpoint_total 3212
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 3187492
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 43049857895 (40.09 GB)
telemt_user_octets_to_client{user="hello"} 790525847943 (736.23 GB)
telemt_user_msgs_from_client{user="hello"} 48526
telemt_user_msgs_to_client{user="hello"} 183196
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 188078.4 (52h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16319084
telemt_connections_bad_total 1644185
telemt_connections_current 1001
telemt_connections_me_current 1001
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 397080
telemt_upstream_connect_attempt_total 84127
telemt_upstream_connect_success_total 84023
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 84040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41068
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1715
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2988
telemt_me_reconnect_success_total 1566
telemt_me_reader_eof_total 1513
telemt_me_idle_close_by_peer_total 1511
telemt_me_route_drop_no_conn_total 14043843
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12963575
telemt_me_endpoint_quarantine_total 1234
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1413
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 53762
telemt_desync_full_logged_total 17065
telemt_desync_suppressed_total 36697
telemt_desync_frames_bucket_total{bucket="1_2"} 11981
telemt_desync_frames_bucket_total{bucket="3_10"} 20972
telemt_desync_frames_bucket_total{bucket="gt_10"} 20809
telemt_pool_swap_total 203
telemt_pool_force_close_total 6681
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1058
telemt_me_draining_writers_reap_progress_total 63610
telemt_me_writer_removed_unexpected_total 1457
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5443
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58899
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56929
telemt_me_writer_teardown_success_total{mode="normal"} 64342
telemt_me_writer_teardown_noop_total 63663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 124677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 127997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128005
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.599737
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128005
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1058
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1354
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 12963619
telemt_user_connections_current{user="hello"} 1001
telemt_user_octets_from_client{user="hello"} 191045787569 (177.93 GB)
telemt_user_octets_to_client{user="hello"} 3487013472847 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 496
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 188079.7 (52h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11866386
telemt_connections_bad_total 1232352
telemt_connections_current 491
telemt_connections_me_current 491
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344546
telemt_upstream_connect_attempt_total 98517
telemt_upstream_connect_success_total 97195
telemt_upstream_connect_fail_total 869
telemt_upstream_connect_attempts_per_request{bucket="1"} 98064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40940
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3800
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 869
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4408
telemt_me_reconnect_success_total 1874
telemt_me_reader_eof_total 1740
telemt_me_idle_close_by_peer_total 1740
telemt_me_route_drop_no_conn_total 4553972
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8809362
telemt_me_endpoint_quarantine_total 1244
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1432
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_me_writers_active_current 43
telemt_desync_total 38753
telemt_desync_full_logged_total 13049
telemt_desync_suppressed_total 25704
telemt_desync_frames_bucket_total{bucket="1_2"} 9602
telemt_desync_frames_bucket_total{bucket="3_10"} 14886
telemt_desync_frames_bucket_total{bucket="gt_10"} 14265
telemt_pool_swap_total 200
telemt_pool_force_close_total 6042
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 708
telemt_me_draining_writers_reap_progress_total 61848
telemt_me_writer_removed_unexpected_total 1770
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5537
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57937
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5530
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55806
telemt_me_writer_teardown_success_total{mode="normal"} 63474
telemt_me_writer_teardown_noop_total 61873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 121824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 124163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 124922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 125262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125347
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.401835
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125347
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 708
telemt_me_refill_failed_total 136
telemt_me_writer_restored_same_endpoint_total 1602
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 8747126
telemt_user_connections_current{user="hello"} 491
telemt_user_octets_from_client{user="hello"} 217736332500 (202.78 GB)
telemt_user_octets_to_client{user="hello"} 3960219082807 (3.60 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 188043.7 (52h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11045845
telemt_connections_bad_total 972929
telemt_connections_current 551
telemt_connections_me_current 551
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345535
telemt_upstream_connect_attempt_total 82809
telemt_upstream_connect_success_total 81250
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 81455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39421
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5738
telemt_me_reconnect_success_total 2362
telemt_me_reader_eof_total 2107
telemt_me_idle_close_by_peer_total 2106
telemt_me_route_drop_no_conn_total 5335878
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8350104
telemt_me_endpoint_quarantine_total 1321
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1389
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
telemt_me_writers_active_current 43
telemt_desync_total 38071
telemt_desync_full_logged_total 12623
telemt_desync_suppressed_total 25448
telemt_desync_frames_bucket_total{bucket="1_2"} 9613
telemt_desync_frames_bucket_total{bucket="3_10"} 14561
telemt_desync_frames_bucket_total{bucket="gt_10"} 13897
telemt_pool_swap_total 196
telemt_pool_force_close_total 5939
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 739
telemt_me_draining_writers_reap_progress_total 62233
telemt_me_writer_removed_unexpected_total 2257
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6292
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58130
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5368
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56294
telemt_me_writer_teardown_success_total{mode="normal"} 64422
telemt_me_writer_teardown_noop_total 62304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 126639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 126672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 126675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 126726
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.776945
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 126726
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 739
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2052
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8342072
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 192698707803 (179.46 GB)
telemt_user_octets_to_client{user="hello"} 3468439890617 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 58323.9 (16h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11225384
telemt_connections_bad_total 668637
telemt_connections_current 848
telemt_connections_me_current 848
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 269897
telemt_upstream_connect_attempt_total 56647
telemt_upstream_connect_success_total 53754
telemt_upstream_connect_fail_total 1911
telemt_upstream_connect_attempts_per_request{bucket="1"} 55665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18523
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6006
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1911
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7510
telemt_me_reconnect_success_total 1186
telemt_me_reader_eof_total 757
telemt_me_idle_close_by_peer_total 756
telemt_me_route_drop_no_conn_total 25288236
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9318042
telemt_me_endpoint_quarantine_total 437
telemt_me_single_endpoint_outage_enter_total 86
telemt_me_single_endpoint_outage_exit_total 86
telemt_me_single_endpoint_outage_reconnect_attempt_total 159
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 159
telemt_me_single_endpoint_shadow_rotate_total 461
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 16301
telemt_desync_full_logged_total 4439
telemt_desync_suppressed_total 11862
telemt_desync_frames_bucket_total{bucket="1_2"} 3090
telemt_desync_frames_bucket_total{bucket="3_10"} 6632
telemt_desync_frames_bucket_total{bucket="gt_10"} 6579
telemt_pool_swap_total 60
telemt_pool_force_close_total 1986
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 478
telemt_me_draining_writers_reap_progress_total 18163
telemt_me_writer_removed_unexpected_total 1072
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2434
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16743
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1679
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16177
telemt_me_writer_teardown_success_total{mode="normal"} 19177
telemt_me_writer_teardown_noop_total 18182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37359
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.679638
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37359
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 478
telemt_me_refill_failed_total 337
telemt_me_writer_restored_same_endpoint_total 774
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 9343371
telemt_user_connections_current{user="hello"} 848
telemt_user_octets_from_client{user="hello"} 87191691542 (81.20 GB)
telemt_user_octets_to_client{user="hello"} 603805341661 (562.34 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 381
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 188050.3 (52h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10981763
telemt_connections_bad_total 944487
telemt_connections_current 725
telemt_connections_me_current 725
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241950
telemt_upstream_connect_attempt_total 111724
telemt_upstream_connect_success_total 110573
telemt_upstream_connect_fail_total 978
telemt_upstream_connect_attempts_per_request{bucket="1"} 111551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42981
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1359
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 978
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72875
telemt_me_reconnect_success_total 3069
telemt_me_reader_eof_total 2756
telemt_me_idle_close_by_peer_total 2754
telemt_me_route_drop_no_conn_total 5260915
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8668260
telemt_me_endpoint_quarantine_total 1266
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1418
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 46208
telemt_desync_full_logged_total 15817
telemt_desync_suppressed_total 30391
telemt_desync_frames_bucket_total{bucket="1_2"} 9390
telemt_desync_frames_bucket_total{bucket="3_10"} 17686
telemt_desync_frames_bucket_total{bucket="gt_10"} 19132
telemt_pool_swap_total 192
telemt_pool_force_close_total 5644
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 662
telemt_me_draining_writers_reap_progress_total 66408
telemt_me_writer_removed_unexpected_total 2785
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6809
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62419
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4895
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60764
telemt_me_writer_teardown_success_total{mode="normal"} 69228
telemt_me_writer_teardown_noop_total 66409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 135627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 135637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 135637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135637
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.246663
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135637
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 662
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2590
telemt_me_writer_restored_fallback_total 51
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8671272
telemt_user_connections_current{user="hello"} 725
telemt_user_octets_from_client{user="hello"} 194540153777 (181.18 GB)
telemt_user_octets_to_client{user="hello"} 3312733464772 (3.01 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 124886.6 (34h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11685549
telemt_connections_bad_total 482155
telemt_connections_current 535
telemt_connections_me_current 535
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4760111
telemt_upstream_connect_attempt_total 59975
telemt_upstream_connect_success_total 59539
telemt_upstream_connect_fail_total 425
telemt_upstream_connect_attempts_per_request{bucket="1"} 59964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 425
telemt_me_reconnect_attempts_total 48899
telemt_me_reconnect_success_total 1808
telemt_me_reader_eof_total 1479
telemt_me_idle_close_by_peer_total 1478
telemt_me_route_drop_no_conn_total 4086232
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5613509
telemt_me_endpoint_quarantine_total 841
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 957
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31546
telemt_desync_full_logged_total 10755
telemt_desync_suppressed_total 20791
telemt_desync_frames_bucket_total{bucket="1_2"} 6275
telemt_desync_frames_bucket_total{bucket="3_10"} 12444
telemt_desync_frames_bucket_total{bucket="gt_10"} 12827
telemt_pool_swap_total 132
telemt_pool_force_close_total 3876
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 45581
telemt_me_writer_removed_unexpected_total 1530
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3762
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43392
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3435
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41705
telemt_me_writer_teardown_success_total{mode="normal"} 47154
telemt_me_writer_teardown_noop_total 45588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92742
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.685367
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92742
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 2736
telemt_me_writer_restored_same_endpoint_total 1604
telemt_me_writer_restored_fallback_total 26
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5606044
telemt_user_connections_current{user="hello"} 535
telemt_user_octets_from_client{user="hello"} 119045651508 (110.87 GB)
telemt_user_octets_to_client{user="hello"} 2168671098670 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 105857.6 (29h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1515910
telemt_connections_bad_total 36714
telemt_connections_current 407
telemt_connections_me_current 407
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 30497
telemt_upstream_connect_attempt_total 49793
telemt_upstream_connect_success_total 49637
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 49765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 787
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2237
telemt_me_reconnect_success_total 903
telemt_me_reader_eof_total 890
telemt_me_idle_close_by_peer_total 890
telemt_me_route_drop_no_conn_total 516603
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1347149
telemt_me_endpoint_quarantine_total 871
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 875
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
telemt_me_writers_active_current 46
telemt_desync_total 8876
telemt_desync_full_logged_total 2607
telemt_desync_suppressed_total 6269
telemt_desync_frames_bucket_total{bucket="1_2"} 2456
telemt_desync_frames_bucket_total{bucket="3_10"} 3400
telemt_desync_frames_bucket_total{bucket="gt_10"} 3020
telemt_pool_swap_total 114
telemt_pool_force_close_total 2926
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 165
telemt_me_draining_writers_reap_progress_total 42072
telemt_me_writer_removed_unexpected_total 858
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3232
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39737
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2838
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39146
telemt_me_writer_teardown_success_total{mode="normal"} 42969
telemt_me_writer_teardown_noop_total 42076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85045
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.242063
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85045
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 165
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 768
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1342961
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 25893908973 (24.12 GB)
telemt_user_octets_to_client{user="hello"} 573984435447 (534.56 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 188055.0 (52h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13317042
telemt_connections_bad_total 1600711
telemt_connections_current 554
telemt_connections_me_current 554
telemt_handshake_timeouts_total 388553
telemt_upstream_connect_attempt_total 73709
telemt_upstream_connect_success_total 73361
telemt_upstream_connect_fail_total 212
telemt_upstream_connect_attempts_per_request{bucket="1"} 73573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36995
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 212
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2944
telemt_me_reconnect_success_total 1480
telemt_me_reader_eof_total 1464
telemt_me_idle_close_by_peer_total 1464
telemt_me_route_drop_no_conn_total 4481831
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10041595
telemt_me_endpoint_quarantine_total 1328
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1420
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_active_current 45
telemt_desync_total 42050
telemt_desync_full_logged_total 13735
telemt_desync_suppressed_total 28315
telemt_desync_frames_bucket_total{bucket="1_2"} 10168
telemt_desync_frames_bucket_total{bucket="3_10"} 15453
telemt_desync_frames_bucket_total{bucket="gt_10"} 16429
telemt_pool_swap_total 208
telemt_pool_force_close_total 5568
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 66583
telemt_me_writer_removed_unexpected_total 1402
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5266
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62771
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5394
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61015
telemt_me_writer_teardown_success_total{mode="normal"} 68037
telemt_me_writer_teardown_noop_total 66585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 134489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 134622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 134622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 134622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 134622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 134622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 134622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 134622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 134622
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.767200
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 134622
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1298
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 10008313
telemt_user_connections_current{user="hello"} 554
telemt_user_octets_from_client{user="hello"} 194729190436 (181.36 GB)
telemt_user_octets_to_client{user="hello"} 4437497240504 (4.04 TB)
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 188051.4 (52h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11627753
telemt_connections_bad_total 1354764
telemt_connections_current 529
telemt_connections_me_current 529
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 311093
telemt_upstream_connect_attempt_total 101216
telemt_upstream_connect_success_total 100328
telemt_upstream_connect_fail_total 680
telemt_upstream_connect_attempts_per_request{bucket="1"} 101008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42602
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 680
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10463
telemt_me_reconnect_success_total 2572
telemt_me_reader_eof_total 2383
telemt_me_idle_close_by_peer_total 2382
telemt_me_seq_mismatch_total 97
telemt_me_route_drop_no_conn_total 5649042
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8951594
telemt_me_endpoint_quarantine_total 1515
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 52
telemt_me_single_endpoint_outage_exit_total 52
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 1422
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_me_writers_active_current 43
telemt_desync_total 41749
telemt_desync_full_logged_total 13442
telemt_desync_suppressed_total 28307
telemt_desync_frames_bucket_total{bucket="1_2"} 10766
telemt_desync_frames_bucket_total{bucket="3_10"} 15358
telemt_desync_frames_bucket_total{bucket="gt_10"} 15625
telemt_pool_swap_total 198
telemt_pool_force_close_total 5343
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 663
telemt_me_draining_writers_reap_progress_total 66653
telemt_me_writer_removed_unexpected_total 2426
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6620
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62542
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4872
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61310
telemt_me_writer_teardown_success_total{mode="normal"} 69162
telemt_me_writer_teardown_noop_total 66658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 135820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 135820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 135820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135820
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.458197
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135820
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 663
telemt_me_refill_failed_total 408
telemt_me_writer_restored_same_endpoint_total 2068
telemt_me_writer_restored_fallback_total 132
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 8956199
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 157325111888 (146.52 GB)
telemt_user_octets_to_client{user="hello"} 3487675864082 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 52
```
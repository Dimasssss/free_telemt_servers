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

# Server Metrics 2026-03-22 19:24:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 80261.2 (22h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2989600
telemt_connections_bad_total 196571
telemt_connections_current 1220
telemt_connections_me_current 1220
telemt_handshake_timeouts_total 97755
telemt_upstream_connect_attempt_total 29385
telemt_upstream_connect_success_total 29384
telemt_upstream_connect_attempts_per_request{bucket="1"} 29384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19082
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 70
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1180
telemt_me_reconnect_success_total 495
telemt_me_reader_eof_total 500
telemt_me_idle_close_by_peer_total 500
telemt_me_route_drop_no_conn_total 2672726
telemt_me_route_drop_channel_closed_total 1062
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2534434
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 542
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 622
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
telemt_desync_total 10965
telemt_desync_full_logged_total 3489
telemt_desync_suppressed_total 7476
telemt_desync_frames_bucket_total{bucket="1_2"} 2945
telemt_desync_frames_bucket_total{bucket="3_10"} 4072
telemt_desync_frames_bucket_total{bucket="gt_10"} 3948
telemt_pool_swap_total 89
telemt_pool_force_close_total 2736
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 575
telemt_me_draining_writers_reap_progress_total 26848
telemt_me_writer_removed_unexpected_total 484
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1953
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25116
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2683
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24112
telemt_me_writer_teardown_success_total{mode="normal"} 27069
telemt_me_writer_teardown_noop_total 26858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53927
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 297.542975
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53927
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 575
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 437
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 2527052
telemt_user_connections_current{user="hello"} 1220
telemt_user_octets_from_client{user="hello"} 37020266640 (34.48 GB)
telemt_user_octets_to_client{user="hello"} 661016772564 (615.62 GB)
telemt_user_unique_ips_current{user="hello"} 507
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 93627.1 (26h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3804044
telemt_connections_bad_total 339666
telemt_connections_current 1235
telemt_connections_me_current 1235
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 97097
telemt_upstream_connect_attempt_total 56738
telemt_upstream_connect_success_total 56046
telemt_upstream_connect_fail_total 609
telemt_upstream_connect_attempts_per_request{bucket="1"} 56655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 609
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6395
telemt_me_reconnect_success_total 2351
telemt_me_reader_eof_total 2285
telemt_me_idle_close_by_peer_total 2285
telemt_me_route_drop_no_conn_total 3595982
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3025746
telemt_me_endpoint_quarantine_total 728
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 721
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
telemt_me_writers_active_current 44
telemt_desync_total 12078
telemt_desync_full_logged_total 6758
telemt_desync_suppressed_total 5320
telemt_desync_frames_bucket_total{bucket="1_2"} 2776
telemt_desync_frames_bucket_total{bucket="3_10"} 4722
telemt_desync_frames_bucket_total{bucket="gt_10"} 4580
telemt_pool_swap_total 88
telemt_pool_force_close_total 2657
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 225
telemt_me_draining_writers_reap_progress_total 37115
telemt_me_writer_removed_unexpected_total 2235
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4361
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35001
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2268
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34458
telemt_me_writer_teardown_success_total{mode="normal"} 39362
telemt_me_writer_teardown_noop_total 37115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76477
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.957833
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76477
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 225
telemt_me_refill_failed_total 161
telemt_me_writer_restored_same_endpoint_total 2038
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 3036545
telemt_user_connections_current{user="hello"} 1235
telemt_user_octets_from_client{user="hello"} 39342474059 (36.64 GB)
telemt_user_octets_to_client{user="hello"} 714260888234 (665.21 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 704
telemt_user_unique_ips_recent_window{user="hello"} 314
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 168487.1 (46h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15858513
telemt_connections_bad_total 1528532
telemt_connections_current 1789
telemt_connections_me_current 1789
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 391081
telemt_upstream_connect_attempt_total 75085
telemt_upstream_connect_success_total 74988
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 75005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35883
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1685
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2774
telemt_me_reconnect_success_total 1430
telemt_me_reader_eof_total 1371
telemt_me_idle_close_by_peer_total 1369
telemt_me_route_drop_no_conn_total 13949863
telemt_me_route_drop_channel_closed_total 143
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12638514
telemt_me_endpoint_quarantine_total 1064
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1254
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
telemt_me_writers_active_current 43
telemt_desync_total 52110
telemt_desync_full_logged_total 16387
telemt_desync_suppressed_total 35723
telemt_desync_frames_bucket_total{bucket="1_2"} 11617
telemt_desync_frames_bucket_total{bucket="3_10"} 20297
telemt_desync_frames_bucket_total{bucket="gt_10"} 20196
telemt_pool_swap_total 182
telemt_pool_force_close_total 6145
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 999
telemt_me_draining_writers_reap_progress_total 55328
telemt_me_writer_removed_unexpected_total 1323
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4859
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51085
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5677
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 468
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49183
telemt_me_writer_teardown_success_total{mode="normal"} 55944
telemt_me_writer_teardown_noop_total 55379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111323
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 310.801103
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111323
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 999
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1232
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 12639074
telemt_user_connections_current{user="hello"} 1789
telemt_user_octets_from_client{user="hello"} 184540230109 (171.87 GB)
telemt_user_octets_to_client{user="hello"} 3340574025727 (3.04 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 670
telemt_user_unique_ips_recent_window{user="hello"} 652
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 168488.4 (46h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11451227
telemt_connections_bad_total 1134459
telemt_connections_current 1517
telemt_connections_me_current 1517
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 340389
telemt_upstream_connect_attempt_total 87572
telemt_upstream_connect_success_total 86344
telemt_upstream_connect_fail_total 843
telemt_upstream_connect_attempts_per_request{bucket="1"} 87187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35772
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3708
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 843
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4128
telemt_me_reconnect_success_total 1709
telemt_me_reader_eof_total 1578
telemt_me_idle_close_by_peer_total 1578
telemt_me_route_drop_no_conn_total 4473710
telemt_me_route_drop_channel_closed_total 491
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8535582
telemt_me_endpoint_quarantine_total 1064
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1276
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 37803
telemt_desync_full_logged_total 12743
telemt_desync_suppressed_total 25060
telemt_desync_frames_bucket_total{bucket="1_2"} 9329
telemt_desync_frames_bucket_total{bucket="3_10"} 14562
telemt_desync_frames_bucket_total{bucket="gt_10"} 13912
telemt_pool_swap_total 179
telemt_pool_force_close_total 5554
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 701
telemt_me_draining_writers_reap_progress_total 53771
telemt_me_writer_removed_unexpected_total 1616
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4975
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50258
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5051
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 503
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48217
telemt_me_writer_teardown_success_total{mode="normal"} 55233
telemt_me_writer_teardown_noop_total 53796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109029
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.640213
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109029
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 701
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1462
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 8473835
telemt_user_connections_current{user="hello"} 1517
telemt_user_octets_from_client{user="hello"} 212859633161 (198.24 GB)
telemt_user_octets_to_client{user="hello"} 3820626393342 (3.47 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 546
telemt_user_unique_ips_recent_window{user="hello"} 473
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 168452.4 (46h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10766828
telemt_connections_bad_total 927918
telemt_connections_current 1257
telemt_connections_me_current 1257
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 343219
telemt_upstream_connect_attempt_total 72639
telemt_upstream_connect_success_total 71551
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 71736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34193
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1557
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 4937
telemt_me_reconnect_success_total 1995
telemt_me_reader_eof_total 1742
telemt_me_idle_close_by_peer_total 1741
telemt_me_route_drop_no_conn_total 5245319
telemt_me_route_drop_channel_closed_total 374
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8140032
telemt_me_endpoint_quarantine_total 1152
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1235
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 60
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
telemt_desync_total 37355
telemt_desync_full_logged_total 12359
telemt_desync_suppressed_total 24996
telemt_desync_frames_bucket_total{bucket="1_2"} 9448
telemt_desync_frames_bucket_total{bucket="3_10"} 14296
telemt_desync_frames_bucket_total{bucket="gt_10"} 13611
telemt_pool_swap_total 177
telemt_pool_force_close_total 5471
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 707
telemt_me_draining_writers_reap_progress_total 53863
telemt_me_writer_removed_unexpected_total 1884
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5404
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50260
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4920
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 551
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48392
telemt_me_writer_teardown_success_total{mode="normal"} 55664
telemt_me_writer_teardown_noop_total 53934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109598
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.731989
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109598
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 707
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 1718
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 8132380
telemt_user_connections_current{user="hello"} 1257
telemt_user_octets_from_client{user="hello"} 189005886941 (176.03 GB)
telemt_user_octets_to_client{user="hello"} 3385127958257 (3.08 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 462
telemt_user_unique_ips_recent_window{user="hello"} 305
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 38732.6 (10h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10717542
telemt_connections_bad_total 653918
telemt_connections_current 1976
telemt_connections_me_current 1976
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 227256
telemt_upstream_connect_attempt_total 44347
telemt_upstream_connect_success_total 42117
telemt_upstream_connect_fail_total 1541
telemt_upstream_connect_attempts_per_request{bucket="1"} 43658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13167
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5955
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1541
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6463
telemt_me_reconnect_success_total 866
telemt_me_reader_eof_total 538
telemt_me_idle_close_by_peer_total 538
telemt_me_route_drop_no_conn_total 25162922
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8900761
telemt_me_endpoint_quarantine_total 239
telemt_me_single_endpoint_outage_enter_total 63
telemt_me_single_endpoint_outage_exit_total 63
telemt_me_single_endpoint_outage_reconnect_attempt_total 114
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 114
telemt_me_single_endpoint_shadow_rotate_total 301
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_writers_warm_current 9
telemt_desync_total 14351
telemt_desync_full_logged_total 3755
telemt_desync_suppressed_total 10596
telemt_desync_frames_bucket_total{bucket="1_2"} 2661
telemt_desync_frames_bucket_total{bucket="3_10"} 5824
telemt_desync_frames_bucket_total{bucket="gt_10"} 5866
telemt_pool_swap_total 38
telemt_pool_force_close_total 1411
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 421
telemt_me_draining_writers_reap_progress_total 10912
telemt_me_writer_removed_unexpected_total 782
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1654
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9993
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1119
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 292
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9501
telemt_me_writer_teardown_success_total{mode="normal"} 11647
telemt_me_writer_teardown_noop_total 10931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 21309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 22061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22578
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.635365
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22578
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 421
telemt_me_refill_failed_total 310
telemt_me_writer_restored_same_endpoint_total 576
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 8922990
telemt_user_connections_current{user="hello"} 1976
telemt_user_octets_from_client{user="hello"} 81496675699 (75.90 GB)
telemt_user_octets_to_client{user="hello"} 457702860035 (426.27 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 756
telemt_user_unique_ips_recent_window{user="hello"} 299
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 168458.8 (46h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10631107
telemt_connections_bad_total 895707
telemt_connections_current 1393
telemt_connections_me_current 1393
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 233701
telemt_upstream_connect_attempt_total 102019
telemt_upstream_connect_success_total 100940
telemt_upstream_connect_fail_total 920
telemt_upstream_connect_attempts_per_request{bucket="1"} 101860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37760
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 920
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72288
telemt_me_reconnect_success_total 2799
telemt_me_reader_eof_total 2488
telemt_me_idle_close_by_peer_total 2486
telemt_me_route_drop_no_conn_total 5176607
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8396639
telemt_me_endpoint_quarantine_total 1118
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1256
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
telemt_me_writers_active_current 43
telemt_desync_total 44643
telemt_desync_full_logged_total 15201
telemt_desync_suppressed_total 29442
telemt_desync_frames_bucket_total{bucket="1_2"} 9046
telemt_desync_frames_bucket_total{bucket="3_10"} 17121
telemt_desync_frames_bucket_total{bucket="gt_10"} 18476
telemt_pool_swap_total 172
telemt_pool_force_close_total 5118
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 630
telemt_me_draining_writers_reap_progress_total 57658
telemt_me_writer_removed_unexpected_total 2526
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6154
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54056
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4393
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 725
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52540
telemt_me_writer_teardown_success_total{mode="normal"} 60210
telemt_me_writer_teardown_noop_total 57659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117869
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.956960
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117869
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 630
telemt_me_refill_failed_total 4281
telemt_me_writer_restored_same_endpoint_total 2351
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 8400044
telemt_user_connections_current{user="hello"} 1393
telemt_user_octets_from_client{user="hello"} 190918511945 (177.81 GB)
telemt_user_octets_to_client{user="hello"} 3190196027860 (2.90 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 547
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 105294.9 (29h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11185925
telemt_connections_bad_total 439355
telemt_connections_current 1606
telemt_connections_me_current 1606
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4618470
telemt_upstream_connect_attempt_total 50024
telemt_upstream_connect_success_total 49651
telemt_upstream_connect_fail_total 364
telemt_upstream_connect_attempts_per_request{bucket="1"} 50015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 364
telemt_me_reconnect_attempts_total 48453
telemt_me_reconnect_success_total 1652
telemt_me_reader_eof_total 1307
telemt_me_idle_close_by_peer_total 1306
telemt_me_route_drop_no_conn_total 4019157
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5385123
telemt_me_endpoint_quarantine_total 683
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 792
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30195
telemt_desync_full_logged_total 10209
telemt_desync_suppressed_total 19986
telemt_desync_frames_bucket_total{bucket="1_2"} 6049
telemt_desync_frames_bucket_total{bucket="3_10"} 11937
telemt_desync_frames_bucket_total{bucket="gt_10"} 12209
telemt_pool_swap_total 110
telemt_pool_force_close_total 3376
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 345
telemt_me_draining_writers_reap_progress_total 36535
telemt_me_writer_removed_unexpected_total 1368
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3257
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34679
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2936
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 440
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33159
telemt_me_writer_teardown_success_total{mode="normal"} 37936
telemt_me_writer_teardown_noop_total 36542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74478
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.372717
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74478
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 345
telemt_me_refill_failed_total 2720
telemt_me_writer_restored_same_endpoint_total 1468
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5378069
telemt_user_connections_current{user="hello"} 1606
telemt_user_octets_from_client{user="hello"} 116127699168 (108.15 GB)
telemt_user_octets_to_client{user="hello"} 2057821065578 (1.87 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 651
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 86266.1 (23h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1284860
telemt_connections_bad_total 28663
telemt_connections_current 1175
telemt_connections_me_current 1175
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 24473
telemt_upstream_connect_attempt_total 41060
telemt_upstream_connect_success_total 40937
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 41033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 690
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1889
telemt_me_reconnect_success_total 796
telemt_me_reader_eof_total 772
telemt_me_idle_close_by_peer_total 772
telemt_me_route_drop_no_conn_total 448294
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1138903
telemt_me_endpoint_quarantine_total 722
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 709
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
telemt_desync_total 6685
telemt_desync_full_logged_total 2063
telemt_desync_suppressed_total 4622
telemt_desync_frames_bucket_total{bucket="1_2"} 1499
telemt_desync_frames_bucket_total{bucket="3_10"} 2643
telemt_desync_frames_bucket_total{bucket="gt_10"} 2543
telemt_pool_swap_total 92
telemt_pool_force_close_total 2380
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 141
telemt_me_draining_writers_reap_progress_total 34139
telemt_me_writer_removed_unexpected_total 745
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2684
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32230
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2295
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31759
telemt_me_writer_teardown_success_total{mode="normal"} 34914
telemt_me_writer_teardown_noop_total 34143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69057
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.271159
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69057
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 141
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 674
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 1135087
telemt_user_connections_current{user="hello"} 1175
telemt_user_octets_from_client{user="hello"} 21669982921 (20.18 GB)
telemt_user_octets_to_client{user="hello"} 481774181303 (448.69 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 415
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 168463.5 (46h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12948030
telemt_connections_bad_total 1513036
telemt_connections_current 1728
telemt_connections_me_current 1728
telemt_handshake_timeouts_total 369615
telemt_upstream_connect_attempt_total 63505
telemt_upstream_connect_success_total 63174
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 63370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31860
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2512
telemt_me_reconnect_success_total 1306
telemt_me_reader_eof_total 1271
telemt_me_idle_close_by_peer_total 1271
telemt_me_route_drop_no_conn_total 4399798
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9795155
telemt_me_endpoint_quarantine_total 1128
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1258
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
telemt_me_writers_active_current 41
telemt_desync_total 40383
telemt_desync_full_logged_total 13165
telemt_desync_suppressed_total 27218
telemt_desync_frames_bucket_total{bucket="1_2"} 9654
telemt_desync_frames_bucket_total{bucket="3_10"} 14896
telemt_desync_frames_bucket_total{bucket="gt_10"} 15833
telemt_pool_swap_total 187
telemt_pool_force_close_total 5123
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 644
telemt_me_draining_writers_reap_progress_total 57196
telemt_me_writer_removed_unexpected_total 1223
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4690
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53767
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4949
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52073
telemt_me_writer_teardown_success_total{mode="normal"} 58457
telemt_me_writer_teardown_noop_total 57198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115655
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.138893
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115655
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 644
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 1141
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 9762999
telemt_user_connections_current{user="hello"} 1728
telemt_user_octets_from_client{user="hello"} 191283646800 (178.15 GB)
telemt_user_octets_to_client{user="hello"} 4313120813812 (3.92 TB)
telemt_user_unique_ips_current{user="hello"} 641
telemt_user_unique_ips_recent_window{user="hello"} 201
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 168459.9 (46h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11255992
telemt_connections_bad_total 1275092
telemt_connections_current 1501
telemt_connections_me_current 1501
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 296082
telemt_upstream_connect_attempt_total 89935
telemt_upstream_connect_success_total 89119
telemt_upstream_connect_fail_total 610
telemt_upstream_connect_attempts_per_request{bucket="1"} 89729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37348
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 610
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9726
telemt_me_reconnect_success_total 2325
telemt_me_reader_eof_total 2172
telemt_me_idle_close_by_peer_total 2171
telemt_me_seq_mismatch_total 78
telemt_me_route_drop_no_conn_total 5577590
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8698641
telemt_me_endpoint_quarantine_total 1293
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1259
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
telemt_me_writers_active_current 41
telemt_desync_total 39696
telemt_desync_full_logged_total 12827
telemt_desync_suppressed_total 26869
telemt_desync_frames_bucket_total{bucket="1_2"} 9904
telemt_desync_frames_bucket_total{bucket="3_10"} 14758
telemt_desync_frames_bucket_total{bucket="gt_10"} 15034
telemt_pool_swap_total 177
telemt_pool_force_close_total 4922
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 634
telemt_me_draining_writers_reap_progress_total 56952
telemt_me_writer_removed_unexpected_total 2206
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6019
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53212
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4451
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52030
telemt_me_writer_teardown_success_total{mode="normal"} 59231
telemt_me_writer_teardown_noop_total 56957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116188
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.109031
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116188
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 634
telemt_me_refill_failed_total 382
telemt_me_writer_restored_same_endpoint_total 1899
telemt_me_writer_restored_fallback_total 106
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 8704286
telemt_user_connections_current{user="hello"} 1501
telemt_user_octets_from_client{user="hello"} 154115167885 (143.53 GB)
telemt_user_octets_to_client{user="hello"} 3354043966543 (3.05 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 570
telemt_user_unique_ips_recent_window{user="hello"} 197
```
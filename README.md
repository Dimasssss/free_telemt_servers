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

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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
- Оплачен до: 25 марта
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
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
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

# Server Metrics 2026-03-21 12:04:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 55712.8 (15h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1766169
telemt_connections_bad_total 88175
telemt_connections_current 2688
telemt_connections_me_current 2688
telemt_handshake_timeouts_total 68318
telemt_upstream_connect_attempt_total 21700
telemt_upstream_connect_success_total 21592
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 21662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13859
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 1099
telemt_me_reconnect_success_total 490
telemt_me_reader_eof_total 474
telemt_me_idle_close_by_peer_total 474
telemt_me_route_drop_no_conn_total 1191936
telemt_me_route_drop_channel_closed_total 424
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1374764
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 390
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 440
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 5398
telemt_desync_full_logged_total 1908
telemt_desync_suppressed_total 3490
telemt_desync_frames_bucket_total{bucket="1_2"} 1153
telemt_desync_frames_bucket_total{bucket="3_10"} 2083
telemt_desync_frames_bucket_total{bucket="gt_10"} 2162
telemt_pool_swap_total 60
telemt_pool_force_close_total 1757
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 329
telemt_me_draining_writers_reap_progress_total 19392
telemt_me_writer_removed_unexpected_total 455
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1593
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18111
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1693
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 64
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17635
telemt_me_writer_teardown_success_total{mode="normal"} 19704
telemt_me_writer_teardown_noop_total 19396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39100
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 140.277152
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39100
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 329
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 428
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1373792
telemt_user_connections_current{user="hello"} 2688
telemt_user_octets_from_client{user="hello"} 19214337175 (17.89 GB)
telemt_user_octets_to_client{user="hello"} 362655940295 (337.75 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 682
telemt_user_unique_ips_recent_window{user="hello"} 482
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 1358.2 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81220
telemt_connections_bad_total 6437
telemt_connections_current 2408
telemt_connections_me_current 2408
telemt_handshake_timeouts_total 2630
telemt_upstream_connect_attempt_total 540
telemt_upstream_connect_success_total 524
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 34
telemt_me_reconnect_success_total 16
telemt_me_reader_eof_total 10
telemt_me_idle_close_by_peer_total 10
telemt_me_route_drop_no_conn_total 37760
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66369
telemt_me_endpoint_quarantine_total 17
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 15
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
telemt_me_writers_active_current 43
telemt_desync_total 262
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 127
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 1
telemt_pool_force_close_total 31
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 401
telemt_me_writer_removed_unexpected_total 10
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 376
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 370
telemt_me_writer_teardown_success_total{mode="normal"} 411
telemt_me_writer_teardown_noop_total 401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 812
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.122044
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 812
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_writer_restored_same_endpoint_total 10
telemt_user_connections_total{user="hello"} 66347
telemt_user_connections_current{user="hello"} 2408
telemt_user_octets_from_client{user="hello"} 1076304572 (1.00 GB)
telemt_user_octets_to_client{user="hello"} 17811180584 (16.59 GB)
telemt_user_unique_ips_current{user="hello"} 1201
telemt_user_unique_ips_recent_window{user="hello"} 597
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 55710.8 (15h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3337435
telemt_connections_bad_total 361553
telemt_connections_current 5054
telemt_connections_me_current 5054
telemt_handshake_timeouts_total 122544
telemt_upstream_connect_attempt_total 21033
telemt_upstream_connect_success_total 21020
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 21021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 730
telemt_me_reconnect_success_total 391
telemt_me_reader_eof_total 404
telemt_me_idle_close_by_peer_total 404
telemt_me_route_drop_no_conn_total 1439608
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2660261
telemt_me_endpoint_quarantine_total 361
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 427
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
telemt_desync_total 11643
telemt_desync_full_logged_total 3932
telemt_desync_suppressed_total 7711
telemt_desync_frames_bucket_total{bucket="1_2"} 2469
telemt_desync_frames_bucket_total{bucket="3_10"} 4526
telemt_desync_frames_bucket_total{bucket="gt_10"} 4648
telemt_pool_swap_total 60
telemt_pool_force_close_total 1857
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 260
telemt_me_draining_writers_reap_progress_total 19159
telemt_me_writer_removed_unexpected_total 381
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1570
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17810
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 14
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1757
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 100
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17302
telemt_me_writer_teardown_success_total{mode="normal"} 19380
telemt_me_writer_teardown_noop_total 19173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38553
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.111668
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38553
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 260
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 347
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 2656603
telemt_user_connections_current{user="hello"} 5054
telemt_user_octets_from_client{user="hello"} 43615000360 (40.62 GB)
telemt_user_octets_to_client{user="hello"} 963950768572 (897.75 GB)
telemt_user_unique_ips_current{user="hello"} 1878
telemt_user_unique_ips_recent_window{user="hello"} 687
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 55715.1 (15h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2783223
telemt_connections_bad_total 309651
telemt_connections_current 3385
telemt_connections_me_current 3385
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 113437
telemt_upstream_connect_attempt_total 25947
telemt_upstream_connect_success_total 25683
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 25814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11753
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 458
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1079
telemt_me_reconnect_success_total 506
telemt_me_reader_eof_total 468
telemt_me_idle_close_by_peer_total 468
telemt_me_route_drop_no_conn_total 856221
telemt_me_route_drop_channel_closed_total 70
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1970781
telemt_me_endpoint_quarantine_total 371
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 427
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
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
telemt_desync_total 8996
telemt_desync_full_logged_total 3081
telemt_desync_suppressed_total 5915
telemt_desync_frames_bucket_total{bucket="1_2"} 2257
telemt_desync_frames_bucket_total{bucket="3_10"} 3516
telemt_desync_frames_bucket_total{bucket="gt_10"} 3223
telemt_pool_swap_total 60
telemt_pool_force_close_total 1672
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 139
telemt_me_draining_writers_reap_progress_total 18835
telemt_me_writer_removed_unexpected_total 458
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1581
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17730
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1561
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 111
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17163
telemt_me_writer_teardown_success_total{mode="normal"} 19311
telemt_me_writer_teardown_noop_total 18836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38147
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.869831
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38147
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 139
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 425
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1972133
telemt_user_connections_current{user="hello"} 3385
telemt_user_octets_from_client{user="hello"} 37214570013 (34.66 GB)
telemt_user_octets_to_client{user="hello"} 939919463599 (875.37 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1197
telemt_user_unique_ips_recent_window{user="hello"} 634
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 55676.1 (15h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2701864
telemt_connections_bad_total 303738
telemt_connections_current 4148
telemt_connections_me_current 4148
telemt_handshake_timeouts_total 80280
telemt_upstream_connect_attempt_total 22556
telemt_upstream_connect_success_total 22473
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12223
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 837
telemt_me_reconnect_success_total 581
telemt_me_reader_eof_total 523
telemt_me_idle_close_by_peer_total 523
telemt_me_route_drop_no_conn_total 808383
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1956486
telemt_me_endpoint_quarantine_total 416
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 421
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_me_writers_active_current 83
telemt_desync_total 9082
telemt_desync_full_logged_total 3057
telemt_desync_suppressed_total 6025
telemt_desync_frames_bucket_total{bucket="1_2"} 2412
telemt_desync_frames_bucket_total{bucket="3_10"} 3451
telemt_desync_frames_bucket_total{bucket="gt_10"} 3219
telemt_pool_swap_total 58
telemt_pool_force_close_total 1617
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 175
telemt_me_draining_writers_reap_progress_total 20084
telemt_me_writer_removed_unexpected_total 502
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1648
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18971
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1496
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 121
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18467
telemt_me_writer_teardown_success_total{mode="normal"} 20619
telemt_me_writer_teardown_noop_total 20087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40706
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.011222
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40706
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 175
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 507
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1953603
telemt_user_connections_current{user="hello"} 4148
telemt_user_octets_from_client{user="hello"} 43857319300 (40.85 GB)
telemt_user_octets_to_client{user="hello"} 946430611748 (881.43 GB)
telemt_user_unique_ips_current{user="hello"} 1623
telemt_user_unique_ips_recent_window{user="hello"} 551
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 55715.4 (15h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8787366
telemt_connections_bad_total 592405
telemt_connections_current 5388
telemt_connections_me_current 5388
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 303792
telemt_upstream_connect_attempt_total 88296
telemt_upstream_connect_success_total 83147
telemt_upstream_connect_fail_total 4321
telemt_upstream_connect_attempts_per_request{bucket="1"} 87468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4321
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3402
telemt_me_reconnect_success_total 1147
telemt_me_reader_eof_total 804
telemt_me_idle_close_by_peer_total 803
telemt_me_route_drop_no_conn_total 15621579
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7269659
telemt_me_endpoint_quarantine_total 434
telemt_me_single_endpoint_outage_enter_total 66
telemt_me_single_endpoint_outage_exit_total 66
telemt_me_single_endpoint_outage_reconnect_attempt_total 151
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 151
telemt_me_single_endpoint_shadow_rotate_total 441
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
telemt_me_writers_active_current 43
telemt_desync_total 13823
telemt_desync_full_logged_total 4444
telemt_desync_suppressed_total 9379
telemt_desync_frames_bucket_total{bucket="1_2"} 2972
telemt_desync_frames_bucket_total{bucket="3_10"} 6113
telemt_desync_frames_bucket_total{bucket="gt_10"} 4738
telemt_pool_swap_total 56
telemt_pool_force_close_total 1755
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 367
telemt_me_draining_writers_reap_progress_total 18374
telemt_me_writer_removed_unexpected_total 1114
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2388
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16996
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1503
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 252
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16619
telemt_me_writer_teardown_success_total{mode="normal"} 19384
telemt_me_writer_teardown_noop_total 18383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37767
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.034714
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37767
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 367
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 792
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 7327728
telemt_user_connections_current{user="hello"} 5388
telemt_user_octets_from_client{user="hello"} 58850042233 (54.81 GB)
telemt_user_octets_to_client{user="hello"} 665607007212 (619.89 GB)
telemt_user_msgs_from_client{user="hello"} 173886
telemt_user_msgs_to_client{user="hello"} 472410
telemt_user_unique_ips_current{user="hello"} 1925
telemt_user_unique_ips_recent_window{user="hello"} 1138
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 55683.1 (15h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2748688
telemt_connections_bad_total 335773
telemt_connections_current 4213
telemt_connections_me_current 4213
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 60586
telemt_upstream_connect_attempt_total 23904
telemt_upstream_connect_success_total 23641
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 23879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12229
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_reconnect_attempts_total 2346
telemt_me_reconnect_success_total 772
telemt_me_reader_eof_total 767
telemt_me_idle_close_by_peer_total 767
telemt_me_route_drop_no_conn_total 953513
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2071572
telemt_me_endpoint_quarantine_total 348
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 426
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
telemt_desync_total 9553
telemt_desync_full_logged_total 3387
telemt_desync_suppressed_total 6166
telemt_desync_frames_bucket_total{bucket="1_2"} 1879
telemt_desync_frames_bucket_total{bucket="3_10"} 3824
telemt_desync_frames_bucket_total{bucket="gt_10"} 3850
telemt_pool_swap_total 57
telemt_pool_force_close_total 1578
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 137
telemt_me_draining_writers_reap_progress_total 19907
telemt_me_writer_removed_unexpected_total 741
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1866
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18808
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1421
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 157
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18329
telemt_me_writer_teardown_success_total{mode="normal"} 20674
telemt_me_writer_teardown_noop_total 19907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40581
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.210149
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40581
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 137
telemt_me_refill_failed_total 86
telemt_me_writer_restored_same_endpoint_total 648
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 2056670
telemt_user_connections_current{user="hello"} 4213
telemt_user_octets_from_client{user="hello"} 38040531104 (35.43 GB)
telemt_user_octets_to_client{user="hello"} 912264542778 (849.61 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1658
telemt_user_unique_ips_recent_window{user="hello"} 642
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 55677.7 (15h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4053235
telemt_connections_bad_total 210697
telemt_connections_current 3042
telemt_connections_me_current 3042
telemt_handshake_timeouts_total 1750131
telemt_upstream_connect_attempt_total 22409
telemt_upstream_connect_success_total 22375
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 22378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 287
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 804
telemt_me_reconnect_success_total 401
telemt_me_reader_eof_total 402
telemt_me_idle_close_by_peer_total 402
telemt_me_route_drop_no_conn_total 875601
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1843950
telemt_me_endpoint_quarantine_total 423
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 438
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_desync_total 8967
telemt_desync_full_logged_total 3193
telemt_desync_suppressed_total 5774
telemt_desync_frames_bucket_total{bucket="1_2"} 1660
telemt_desync_frames_bucket_total{bucket="3_10"} 3582
telemt_desync_frames_bucket_total{bucket="gt_10"} 3725
telemt_pool_swap_total 60
telemt_pool_force_close_total 1523
telemt_me_writer_close_signal_drop_total 127
telemt_me_draining_writers_reap_progress_total 20054
telemt_me_writer_removed_unexpected_total 388
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1349
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19116
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1471
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 52
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18531
telemt_me_writer_teardown_success_total{mode="normal"} 20465
telemt_me_writer_teardown_noop_total 20054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40519
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.114789
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40519
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 127
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 352
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 1837637
telemt_user_connections_current{user="hello"} 3042
telemt_user_octets_from_client{user="hello"} 33729159156 (31.41 GB)
telemt_user_octets_to_client{user="hello"} 879662581428 (819.25 GB)
telemt_user_unique_ips_current{user="hello"} 1265
telemt_user_unique_ips_recent_window{user="hello"} 749
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 53668.7 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 849064
telemt_connections_bad_total 62205
telemt_connections_current 745
telemt_connections_me_current 745
telemt_handshake_timeouts_total 308977
telemt_upstream_connect_attempt_total 25700
telemt_upstream_connect_success_total 25698
telemt_upstream_connect_attempts_per_request{bucket="1"} 25698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14997
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1093
telemt_me_reconnect_success_total 424
telemt_me_reader_eof_total 420
telemt_me_idle_close_by_peer_total 420
telemt_me_route_drop_no_conn_total 181482
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 414451
telemt_me_endpoint_quarantine_total 494
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 457
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
telemt_me_writers_active_current 44
telemt_desync_total 2894
telemt_desync_full_logged_total 1096
telemt_desync_suppressed_total 1798
telemt_desync_frames_bucket_total{bucket="1_2"} 474
telemt_desync_frames_bucket_total{bucket="3_10"} 1042
telemt_desync_frames_bucket_total{bucket="gt_10"} 1378
telemt_pool_swap_total 59
telemt_pool_force_close_total 1317
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 88
telemt_me_draining_writers_reap_progress_total 23019
telemt_me_writer_removed_unexpected_total 399
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1677
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21747
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1314
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21702
telemt_me_writer_teardown_success_total{mode="normal"} 23424
telemt_me_writer_teardown_noop_total 23019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46443
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.671188
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46443
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 88
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 344
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 414315
telemt_user_connections_current{user="hello"} 745
telemt_user_octets_from_client{user="hello"} 6604559291 (6.15 GB)
telemt_user_octets_to_client{user="hello"} 158706770245 (147.81 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 55687.3 (15h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2896844
telemt_connections_bad_total 269043
telemt_connections_current 4479
telemt_connections_me_current 4479
telemt_handshake_timeouts_total 79745
telemt_upstream_connect_attempt_total 23264
telemt_upstream_connect_success_total 23166
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 23233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11599
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_reconnect_attempts_total 955
telemt_me_reconnect_success_total 532
telemt_me_reader_eof_total 496
telemt_me_idle_close_by_peer_total 496
telemt_me_route_drop_no_conn_total 775726
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2296155
telemt_me_endpoint_quarantine_total 429
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 434
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
telemt_me_writers_active_current 45
telemt_desync_total 9214
telemt_desync_full_logged_total 3042
telemt_desync_suppressed_total 6172
telemt_desync_frames_bucket_total{bucket="1_2"} 2193
telemt_desync_frames_bucket_total{bucket="3_10"} 3431
telemt_desync_frames_bucket_total{bucket="gt_10"} 3590
telemt_pool_swap_total 61
telemt_pool_force_close_total 1535
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 163
telemt_me_draining_writers_reap_progress_total 20896
telemt_me_writer_removed_unexpected_total 487
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1611
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19789
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1508
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19361
telemt_me_writer_teardown_success_total{mode="normal"} 21400
telemt_me_writer_teardown_noop_total 20896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42296
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.589285
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42296
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 163
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 474
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 2289461
telemt_user_connections_current{user="hello"} 4479
telemt_user_octets_from_client{user="hello"} 48228551396 (44.92 GB)
telemt_user_octets_to_client{user="hello"} 1069974985448 (996.49 GB)
telemt_user_unique_ips_current{user="hello"} 1612
telemt_user_unique_ips_recent_window{user="hello"} 646
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 55684.4 (15h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2655454
telemt_connections_bad_total 216775
telemt_connections_current 3829
telemt_connections_me_current 3829
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 73368
telemt_upstream_connect_attempt_total 39410
telemt_upstream_connect_success_total 39164
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 39367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13208
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 585
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_reconnect_attempts_total 3256
telemt_me_reconnect_success_total 680
telemt_me_reader_eof_total 594
telemt_me_idle_close_by_peer_total 594
telemt_me_seq_mismatch_total 28
telemt_me_route_drop_no_conn_total 783938
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2131663
telemt_me_endpoint_quarantine_total 480
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 431
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_desync_total 8042
telemt_desync_full_logged_total 2761
telemt_desync_suppressed_total 5281
telemt_desync_frames_bucket_total{bucket="1_2"} 2095
telemt_desync_frames_bucket_total{bucket="3_10"} 2991
telemt_desync_frames_bucket_total{bucket="gt_10"} 2956
telemt_pool_swap_total 60
telemt_pool_force_close_total 1488
telemt_me_writer_close_signal_drop_total 138
telemt_me_draining_writers_reap_progress_total 20063
telemt_me_writer_removed_unexpected_total 606
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1875
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18822
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1396
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 92
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18575
telemt_me_writer_teardown_success_total{mode="normal"} 20697
telemt_me_writer_teardown_noop_total 20064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40761
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.334456
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40761
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 138
telemt_me_refill_failed_total 146
telemt_me_writer_restored_same_endpoint_total 516
telemt_me_writer_restored_fallback_total 37
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 2142230
telemt_user_connections_current{user="hello"} 3829
telemt_user_octets_from_client{user="hello"} 38985647401 (36.31 GB)
telemt_user_octets_to_client{user="hello"} 941335611732 (876.69 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1466
telemt_user_unique_ips_recent_window{user="hello"} 575
```
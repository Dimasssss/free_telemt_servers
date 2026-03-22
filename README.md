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

# Server Metrics 2026-03-22 07:27:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 37263.6 (10h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 780204
telemt_connections_bad_total 49411
telemt_connections_current 1409
telemt_connections_me_current 1409
telemt_handshake_timeouts_total 37010
telemt_upstream_connect_attempt_total 15125
telemt_upstream_connect_success_total 15124
telemt_upstream_connect_attempts_per_request{bucket="1"} 15124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9830
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 423
telemt_me_reconnect_success_total 236
telemt_me_reader_eof_total 233
telemt_me_idle_close_by_peer_total 233
telemt_me_route_drop_no_conn_total 304427
telemt_me_route_drop_channel_closed_total 113
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 646626
telemt_me_endpoint_quarantine_total 269
telemt_me_single_endpoint_shadow_rotate_total 306
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 5184
telemt_desync_full_logged_total 1469
telemt_desync_suppressed_total 3715
telemt_desync_frames_bucket_total{bucket="1_2"} 1659
telemt_desync_frames_bucket_total{bucket="3_10"} 1953
telemt_desync_frames_bucket_total{bucket="gt_10"} 1572
telemt_pool_swap_total 41
telemt_pool_force_close_total 1120
telemt_me_writer_close_signal_drop_total 115
telemt_me_draining_writers_reap_progress_total 13725
telemt_me_writer_removed_unexpected_total 230
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 953
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12977
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1103
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12605
telemt_me_writer_teardown_success_total{mode="normal"} 13930
telemt_me_writer_teardown_noop_total 13726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27656
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 32.212134
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27656
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 115
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 645416
telemt_user_connections_current{user="hello"} 1409
telemt_user_octets_from_client{user="hello"} 8834598336 (8.23 GB)
telemt_user_octets_to_client{user="hello"} 220463815460 (205.32 GB)
telemt_user_unique_ips_current{user="hello"} 552
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 50629.9 (14h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1258490
telemt_connections_bad_total 122290
telemt_connections_current 932
telemt_connections_me_current 932
telemt_handshake_timeouts_total 39242
telemt_upstream_connect_attempt_total 26614
telemt_upstream_connect_success_total 26217
telemt_upstream_connect_fail_total 346
telemt_upstream_connect_attempts_per_request{bucket="1"} 26563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 346
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 1980
telemt_me_reconnect_success_total 809
telemt_me_reader_eof_total 699
telemt_me_idle_close_by_peer_total 699
telemt_me_route_drop_no_conn_total 477953
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 948789
telemt_me_endpoint_quarantine_total 469
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 405
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
telemt_me_writers_active_current 48
telemt_desync_total 4106
telemt_desync_full_logged_total 2395
telemt_desync_suppressed_total 1711
telemt_desync_frames_bucket_total{bucket="1_2"} 871
telemt_desync_frames_bucket_total{bucket="3_10"} 1591
telemt_desync_frames_bucket_total{bucket="gt_10"} 1644
telemt_pool_swap_total 54
telemt_pool_force_close_total 1450
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 20763
telemt_me_writer_removed_unexpected_total 672
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1860
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19561
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1379
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 71
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19313
telemt_me_writer_teardown_success_total{mode="normal"} 21421
telemt_me_writer_teardown_noop_total 20763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42184
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.380872
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42184
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 615
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 950483
telemt_user_connections_current{user="hello"} 932
telemt_user_octets_from_client{user="hello"} 15073401458 (14.04 GB)
telemt_user_octets_to_client{user="hello"} 347085901471 (323.25 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 592
telemt_user_unique_ips_recent_window{user="hello"} 464
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 125489.7 (34h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9064013
telemt_connections_bad_total 833617
telemt_connections_current 4244
telemt_connections_me_current 4244
telemt_handshake_timeouts_total 282332
telemt_upstream_connect_attempt_total 46363
telemt_upstream_connect_success_total 46284
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 46292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25177
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1797
telemt_me_reconnect_success_total 923
telemt_me_reader_eof_total 925
telemt_me_idle_close_by_peer_total 925
telemt_me_route_drop_no_conn_total 4893899
telemt_me_route_drop_channel_closed_total 74
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7133492
telemt_me_endpoint_quarantine_total 791
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 942
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
telemt_me_writers_active_current 49
telemt_desync_total 31029
telemt_desync_full_logged_total 10252
telemt_desync_suppressed_total 20777
telemt_desync_frames_bucket_total{bucket="1_2"} 6730
telemt_desync_frames_bucket_total{bucket="3_10"} 12056
telemt_desync_frames_bucket_total{bucket="gt_10"} 12243
telemt_pool_swap_total 136
telemt_pool_force_close_total 4487
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 677
telemt_me_draining_writers_reap_progress_total 42315
telemt_me_writer_removed_unexpected_total 889
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3518
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39176
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4217
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 270
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37828
telemt_me_writer_teardown_success_total{mode="normal"} 42694
telemt_me_writer_teardown_noop_total 42359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85053
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 179.950835
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85053
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 677
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 821
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 7124108
telemt_user_connections_current{user="hello"} 4244
telemt_user_octets_from_client{user="hello"} 120115607928 (111.87 GB)
telemt_user_octets_to_client{user="hello"} 2436509903640 (2.22 TB)
telemt_user_unique_ips_current{user="hello"} 1741
telemt_user_unique_ips_recent_window{user="hello"} 652
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 125491.2 (34h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7465961
telemt_connections_bad_total 657971
telemt_connections_current 4100
telemt_connections_me_current 4100
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 244388
telemt_upstream_connect_attempt_total 50375
telemt_upstream_connect_success_total 49969
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 50178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24741
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 562
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2632
telemt_me_reconnect_success_total 991
telemt_me_reader_eof_total 958
telemt_me_idle_close_by_peer_total 958
telemt_me_route_drop_no_conn_total 2505752
telemt_me_route_drop_channel_closed_total 304
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5534558
telemt_me_endpoint_quarantine_total 794
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 965
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
telemt_desync_total 25455
telemt_desync_full_logged_total 8734
telemt_desync_suppressed_total 16721
telemt_desync_frames_bucket_total{bucket="1_2"} 6081
telemt_desync_frames_bucket_total{bucket="3_10"} 9886
telemt_desync_frames_bucket_total{bucket="gt_10"} 9488
telemt_pool_swap_total 137
telemt_pool_force_close_total 4105
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 430
telemt_me_draining_writers_reap_progress_total 40793
telemt_me_writer_removed_unexpected_total 934
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3388
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38258
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3867
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 238
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36688
telemt_me_writer_teardown_success_total{mode="normal"} 41646
telemt_me_writer_teardown_noop_total 40799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82445
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.432756
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82445
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 430
telemt_me_refill_failed_total 92
telemt_me_writer_restored_same_endpoint_total 867
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 5455478
telemt_user_connections_current{user="hello"} 4100
telemt_user_octets_from_client{user="hello"} 154721518157 (144.10 GB)
telemt_user_octets_to_client{user="hello"} 2638866056255 (2.40 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1547
telemt_user_unique_ips_recent_window{user="hello"} 540
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 125455.1 (34h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7217948
telemt_connections_bad_total 594182
telemt_connections_current 3394
telemt_connections_me_current 3394
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 240466
telemt_upstream_connect_attempt_total 56988
telemt_upstream_connect_success_total 56322
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 56469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26363
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 885
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2732
telemt_me_reconnect_success_total 1186
telemt_me_reader_eof_total 1094
telemt_me_idle_close_by_peer_total 1094
telemt_me_route_drop_no_conn_total 2912038
telemt_me_route_drop_channel_closed_total 172
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5390350
telemt_me_endpoint_quarantine_total 884
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 930
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_me_writers_active_current 49
telemt_desync_total 25156
telemt_desync_full_logged_total 8580
telemt_desync_suppressed_total 16576
telemt_desync_frames_bucket_total{bucket="1_2"} 6103
telemt_desync_frames_bucket_total{bucket="3_10"} 9650
telemt_desync_frames_bucket_total{bucket="gt_10"} 9403
telemt_pool_swap_total 134
telemt_pool_force_close_total 3955
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 455
telemt_me_draining_writers_reap_progress_total 41738
telemt_me_writer_removed_unexpected_total 1104
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3702
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39144
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3662
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 293
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37783
telemt_me_writer_teardown_success_total{mode="normal"} 42846
telemt_me_writer_teardown_noop_total 41750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84596
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 43.680394
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84596
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 455
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1027
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 5383991
telemt_user_connections_current{user="hello"} 3394
telemt_user_octets_from_client{user="hello"} 142884245795 (133.07 GB)
telemt_user_octets_to_client{user="hello"} 2400542277483 (2.18 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1435
telemt_user_unique_ips_recent_window{user="hello"} 495
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 125494.4 (34h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23104313
telemt_connections_bad_total 1928014
telemt_connections_current 4654
telemt_connections_me_current 4654
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 680500
telemt_upstream_connect_attempt_total 240589
telemt_upstream_connect_success_total 220857
telemt_upstream_connect_fail_total 17755
telemt_upstream_connect_attempts_per_request{bucket="1"} 238612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52078
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17755
telemt_me_keepalive_timeout_total 400
telemt_me_reconnect_attempts_total 66501
telemt_me_reconnect_success_total 2677
telemt_me_reader_eof_total 1662
telemt_me_idle_close_by_peer_total 1660
telemt_me_route_drop_no_conn_total 44128542
telemt_me_route_drop_channel_closed_total 139
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18618775
telemt_me_writer_pick_total{mode="p2c",result="full"} 227
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_writer_pick_blocking_fallback_total 222
telemt_me_endpoint_quarantine_total 981
telemt_me_single_endpoint_outage_enter_total 164
telemt_me_single_endpoint_outage_exit_total 164
telemt_me_single_endpoint_outage_reconnect_attempt_total 335
telemt_me_single_endpoint_outage_reconnect_success_total 86
telemt_me_single_endpoint_quarantine_bypass_total 335
telemt_me_single_endpoint_shadow_rotate_total 987
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 71
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
telemt_me_writers_active_current 37
telemt_desync_total 36022
telemt_desync_full_logged_total 10759
telemt_desync_suppressed_total 25263
telemt_desync_frames_bucket_total{bucket="1_2"} 7992
telemt_desync_frames_bucket_total{bucket="3_10"} 15960
telemt_desync_frames_bucket_total{bucket="gt_10"} 12070
telemt_pool_swap_total 130
telemt_pool_force_close_total 4122
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 954
telemt_me_draining_writers_reap_progress_total 39202
telemt_me_writer_removed_unexpected_total 2485
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5335
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36083
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3534
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 588
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35080
telemt_me_writer_teardown_success_total{mode="normal"} 41418
telemt_me_writer_teardown_noop_total 39234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80652
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 281.659980
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80652
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 954
telemt_me_refill_failed_total 3863
telemt_me_writer_restored_same_endpoint_total 1812
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14757
telemt_me_writer_removed_unexpected_minus_restored_total 651
telemt_user_connections_total{user="hello"} 18784610
telemt_user_connections_current{user="hello"} 4654
telemt_user_octets_from_client{user="hello"} 272978266331 (254.23 GB)
telemt_user_octets_to_client{user="hello"} 1407210822163 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 503035
telemt_user_msgs_to_client{user="hello"} 1007896
telemt_user_unique_ips_current{user="hello"} 1754
telemt_user_unique_ips_recent_window{user="hello"} 994
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 125462.1 (34h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6888835
telemt_connections_bad_total 633208
telemt_connections_current 3798
telemt_connections_me_current 3798
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 142674
telemt_upstream_connect_attempt_total 65393
telemt_upstream_connect_success_total 64648
telemt_upstream_connect_fail_total 639
telemt_upstream_connect_attempts_per_request{bucket="1"} 65287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27287
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 639
telemt_me_reconnect_attempts_total 70048
telemt_me_reconnect_success_total 1927
telemt_me_reader_eof_total 1704
telemt_me_idle_close_by_peer_total 1703
telemt_me_route_drop_no_conn_total 2644225
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5391474
telemt_me_endpoint_quarantine_total 838
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 954
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_desync_total 27116
telemt_desync_full_logged_total 9447
telemt_desync_suppressed_total 17669
telemt_desync_frames_bucket_total{bucket="1_2"} 5425
telemt_desync_frames_bucket_total{bucket="3_10"} 10411
telemt_desync_frames_bucket_total{bucket="gt_10"} 11280
telemt_pool_swap_total 131
telemt_pool_force_close_total 3766
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 444
telemt_me_draining_writers_reap_progress_total 43928
telemt_me_writer_removed_unexpected_total 1735
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4401
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41299
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3348
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 418
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40162
telemt_me_writer_teardown_success_total{mode="normal"} 45700
telemt_me_writer_teardown_noop_total 43929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89629
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.040970
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89629
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 444
telemt_me_refill_failed_total 4219
telemt_me_writer_restored_same_endpoint_total 1609
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 5382588
telemt_user_connections_current{user="hello"} 3798
telemt_user_octets_from_client{user="hello"} 137289755244 (127.86 GB)
telemt_user_octets_to_client{user="hello"} 2251579249922 (2.05 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1527
telemt_user_unique_ips_recent_window{user="hello"} 564
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 62298.0 (17h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5152361
telemt_connections_bad_total 208965
telemt_connections_current 3534
telemt_connections_me_current 3534
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2043235
telemt_upstream_connect_attempt_total 34314
telemt_upstream_connect_success_total 34075
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 34307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_reconnect_attempts_total 46241
telemt_me_reconnect_success_total 1082
telemt_me_reader_eof_total 772
telemt_me_idle_close_by_peer_total 772
telemt_me_route_drop_no_conn_total 1264104
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2568098
telemt_me_endpoint_quarantine_total 437
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 481
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 13651
telemt_desync_full_logged_total 4711
telemt_desync_suppressed_total 8940
telemt_desync_frames_bucket_total{bucket="1_2"} 2710
telemt_desync_frames_bucket_total{bucket="3_10"} 5223
telemt_desync_frames_bucket_total{bucket="gt_10"} 5718
telemt_pool_swap_total 68
telemt_pool_force_close_total 1974
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 180
telemt_me_draining_writers_reap_progress_total 22643
telemt_me_writer_removed_unexpected_total 842
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1911
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21596
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1744
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 230
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20669
telemt_me_writer_teardown_success_total{mode="normal"} 23507
telemt_me_writer_teardown_noop_total 22645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46152
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.991597
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46152
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 180
telemt_me_refill_failed_total 2623
telemt_me_writer_restored_same_endpoint_total 963
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2569727
telemt_user_connections_current{user="hello"} 3534
telemt_user_octets_from_client{user="hello"} 65313524104 (60.83 GB)
telemt_user_octets_to_client{user="hello"} 1141748509326 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1435
telemt_user_unique_ips_recent_window{user="hello"} 507
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 43268.8 (12h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 338657
telemt_connections_bad_total 2407
telemt_connections_current 699
telemt_connections_me_current 699
telemt_handshake_timeouts_total 7558
telemt_upstream_connect_attempt_total 20692
telemt_upstream_connect_success_total 20638
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 20688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_reconnect_attempts_total 900
telemt_me_reconnect_success_total 304
telemt_me_reader_eof_total 300
telemt_me_idle_close_by_peer_total 300
telemt_me_route_drop_no_conn_total 104289
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 307280
telemt_me_endpoint_quarantine_total 405
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 372
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_me_writers_warm_current 26
telemt_desync_total 1467
telemt_desync_full_logged_total 415
telemt_desync_suppressed_total 1052
telemt_desync_frames_bucket_total{bucket="1_2"} 472
telemt_desync_frames_bucket_total{bucket="3_10"} 566
telemt_desync_frames_bucket_total{bucket="gt_10"} 429
telemt_pool_swap_total 47
telemt_pool_force_close_total 1059
telemt_me_writer_close_signal_drop_total 39
telemt_me_draining_writers_reap_progress_total 18679
telemt_me_writer_removed_unexpected_total 287
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1222
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17757
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1057
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17620
telemt_me_writer_teardown_success_total{mode="normal"} 18979
telemt_me_writer_teardown_noop_total 18679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37658
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.489448
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37658
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 39
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 258
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 306747
telemt_user_connections_current{user="hello"} 699
telemt_user_octets_from_client{user="hello"} 5002285520 (4.66 GB)
telemt_user_octets_to_client{user="hello"} 172326819956 (160.49 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 125466.3 (34h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8425565
telemt_connections_bad_total 910109
telemt_connections_current 4174
telemt_connections_me_current 4174
telemt_handshake_timeouts_total 237453
telemt_upstream_connect_attempt_total 49191
telemt_upstream_connect_success_total 49010
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 49152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24679
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_reconnect_attempts_total 1832
telemt_me_reconnect_success_total 995
telemt_me_reader_eof_total 972
telemt_me_idle_close_by_peer_total 972
telemt_me_route_drop_no_conn_total 2362911
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6257242
telemt_me_endpoint_quarantine_total 894
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 958
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
telemt_desync_total 24921
telemt_desync_full_logged_total 8184
telemt_desync_suppressed_total 16737
telemt_desync_frames_bucket_total{bucket="1_2"} 6176
telemt_desync_frames_bucket_total{bucket="3_10"} 9082
telemt_desync_frames_bucket_total{bucket="gt_10"} 9663
telemt_pool_swap_total 139
telemt_pool_force_close_total 3716
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 442
telemt_me_draining_writers_reap_progress_total 44389
telemt_me_writer_removed_unexpected_total 934
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3510
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41841
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3623
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 93
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40673
telemt_me_writer_teardown_success_total{mode="normal"} 45351
telemt_me_writer_teardown_noop_total 44391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89742
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.492757
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89742
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 442
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 879
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 6231010
telemt_user_connections_current{user="hello"} 4174
telemt_user_octets_from_client{user="hello"} 123243319128 (114.78 GB)
telemt_user_octets_to_client{user="hello"} 2924435194796 (2.66 TB)
telemt_user_unique_ips_current{user="hello"} 1591
telemt_user_unique_ips_recent_window{user="hello"} 588
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 125463.1 (34h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7352021
telemt_connections_bad_total 786082
telemt_connections_current 4052
telemt_connections_me_current 4052
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 196384
telemt_upstream_connect_attempt_total 65163
telemt_upstream_connect_success_total 64666
telemt_upstream_connect_fail_total 434
telemt_upstream_connect_attempts_per_request{bucket="1"} 65100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26384
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 624
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 434
telemt_me_reconnect_attempts_total 6022
telemt_me_reconnect_success_total 1389
telemt_me_reader_eof_total 1252
telemt_me_idle_close_by_peer_total 1252
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2447973
telemt_me_route_drop_channel_closed_total 202
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5596975
telemt_me_endpoint_quarantine_total 987
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 956
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
telemt_me_writers_active_current 44
telemt_desync_total 23943
telemt_desync_full_logged_total 7953
telemt_desync_suppressed_total 15990
telemt_desync_frames_bucket_total{bucket="1_2"} 5921
telemt_desync_frames_bucket_total{bucket="3_10"} 8783
telemt_desync_frames_bucket_total{bucket="gt_10"} 9239
telemt_pool_swap_total 136
telemt_pool_force_close_total 3662
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 443
telemt_me_draining_writers_reap_progress_total 43012
telemt_me_writer_removed_unexpected_total 1267
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4095
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40245
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3406
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 256
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39350
telemt_me_writer_teardown_success_total{mode="normal"} 44340
telemt_me_writer_teardown_noop_total 43016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87356
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.565310
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87356
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 443
telemt_me_refill_failed_total 267
telemt_me_writer_restored_same_endpoint_total 1087
telemt_me_writer_restored_fallback_total 81
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 5598581
telemt_user_connections_current{user="hello"} 4052
telemt_user_octets_from_client{user="hello"} 103592932609 (96.48 GB)
telemt_user_octets_to_client{user="hello"} 2434520133488 (2.21 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1592
telemt_user_unique_ips_recent_window{user="hello"} 546
```
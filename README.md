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

# Server Metrics 2026-03-21 09:10:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 45297.0 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1247215
telemt_connections_bad_total 61322
telemt_connections_current 1792
telemt_connections_me_current 1792
telemt_handshake_timeouts_total 51856
telemt_upstream_connect_attempt_total 17855
telemt_upstream_connect_success_total 17774
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 17831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11344
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 757
telemt_me_reconnect_success_total 315
telemt_me_reader_eof_total 321
telemt_me_idle_close_by_peer_total 321
telemt_me_route_drop_no_conn_total 700962
telemt_me_route_drop_channel_closed_total 187
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 940263
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 323
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 367
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
telemt_me_writers_active_current 43
telemt_desync_total 4013
telemt_desync_full_logged_total 1376
telemt_desync_suppressed_total 2637
telemt_desync_frames_bucket_total{bucket="1_2"} 849
telemt_desync_frames_bucket_total{bucket="3_10"} 1568
telemt_desync_frames_bucket_total{bucket="gt_10"} 1596
telemt_pool_swap_total 50
telemt_pool_force_close_total 1399
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 194
telemt_me_draining_writers_reap_progress_total 16004
telemt_me_writer_removed_unexpected_total 301
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1248
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14960
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1378
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14605
telemt_me_writer_teardown_success_total{mode="normal"} 16208
telemt_me_writer_teardown_noop_total 16005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32213
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 75.758993
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32213
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 194
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 275
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 939501
telemt_user_connections_current{user="hello"} 1792
telemt_user_octets_from_client{user="hello"} 13345086527 (12.43 GB)
telemt_user_octets_to_client{user="hello"} 257195229079 (239.53 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 567
telemt_user_unique_ips_recent_window{user="hello"} 267
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 45298.1 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3055255
telemt_connections_bad_total 334688
telemt_connections_current 4865
telemt_connections_me_current 4865
telemt_handshake_timeouts_total 88350
telemt_upstream_connect_attempt_total 16435
telemt_upstream_connect_success_total 16359
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 16411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_reconnect_attempts_total 979
telemt_me_reconnect_success_total 373
telemt_me_reader_eof_total 367
telemt_me_idle_close_by_peer_total 366
telemt_me_route_drop_no_conn_total 1146875
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2013397
telemt_me_endpoint_quarantine_total 294
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 353
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
telemt_me_writers_active_current 47
telemt_desync_total 8819
telemt_desync_full_logged_total 2972
telemt_desync_suppressed_total 5847
telemt_desync_frames_bucket_total{bucket="1_2"} 1815
telemt_desync_frames_bucket_total{bucket="3_10"} 3452
telemt_desync_frames_bucket_total{bucket="gt_10"} 3552
telemt_pool_swap_total 49
telemt_pool_force_close_total 1478
telemt_me_writer_close_signal_drop_total 174
telemt_me_draining_writers_reap_progress_total 14690
telemt_me_writer_removed_unexpected_total 344
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1359
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13671
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1394
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 84
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13212
telemt_me_writer_teardown_success_total{mode="normal"} 15030
telemt_me_writer_teardown_noop_total 14690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29720
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.191639
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29720
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 174
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 299
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2009309
telemt_user_connections_current{user="hello"} 4865
telemt_user_octets_from_client{user="hello"} 28757433048 (26.78 GB)
telemt_user_octets_to_client{user="hello"} 729943362740 (679.81 GB)
telemt_user_unique_ips_current{user="hello"} 1698
telemt_user_unique_ips_recent_window{user="hello"} 711
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 45294.6 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2207366
telemt_connections_bad_total 270188
telemt_connections_current 4001
telemt_connections_me_current 4001
telemt_handshake_timeouts_total 81575
telemt_upstream_connect_attempt_total 17848
telemt_upstream_connect_success_total 17838
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 604
telemt_me_reconnect_success_total 337
telemt_me_reader_eof_total 350
telemt_me_idle_close_by_peer_total 350
telemt_me_route_drop_no_conn_total 746732
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1710512
telemt_me_endpoint_quarantine_total 305
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 357
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
telemt_me_writers_active_current 45
telemt_desync_total 7267
telemt_desync_full_logged_total 2548
telemt_desync_suppressed_total 4719
telemt_desync_frames_bucket_total{bucket="1_2"} 1577
telemt_desync_frames_bucket_total{bucket="3_10"} 2826
telemt_desync_frames_bucket_total{bucket="gt_10"} 2864
telemt_pool_swap_total 49
telemt_pool_force_close_total 1446
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 183
telemt_me_draining_writers_reap_progress_total 16236
telemt_me_writer_removed_unexpected_total 330
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1329
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15134
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1370
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14790
telemt_me_writer_teardown_success_total{mode="normal"} 16463
telemt_me_writer_teardown_noop_total 16246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32709
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 32.453050
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32709
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 183
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 300
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 1707636
telemt_user_connections_current{user="hello"} 4001
telemt_user_octets_from_client{user="hello"} 25328115184 (23.59 GB)
telemt_user_octets_to_client{user="hello"} 684402132072 (637.40 GB)
telemt_user_unique_ips_current{user="hello"} 1424
telemt_user_unique_ips_recent_window{user="hello"} 630
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 45296.0 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1856981
telemt_connections_bad_total 224595
telemt_connections_current 3528
telemt_connections_me_current 3528
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 77415
telemt_upstream_connect_attempt_total 22760
telemt_upstream_connect_success_total 22528
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 22652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10107
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 381
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 926
telemt_me_reconnect_success_total 426
telemt_me_reader_eof_total 392
telemt_me_idle_close_by_peer_total 392
telemt_me_route_drop_no_conn_total 527209
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1280595
telemt_me_endpoint_quarantine_total 323
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 360
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
telemt_desync_total 6018
telemt_desync_full_logged_total 2068
telemt_desync_suppressed_total 3950
telemt_desync_frames_bucket_total{bucket="1_2"} 1479
telemt_desync_frames_bucket_total{bucket="3_10"} 2406
telemt_desync_frames_bucket_total{bucket="gt_10"} 2133
telemt_pool_swap_total 49
telemt_pool_force_close_total 1331
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 86
telemt_me_draining_writers_reap_progress_total 16117
telemt_me_writer_removed_unexpected_total 385
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1291
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15225
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1252
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 79
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14786
telemt_me_writer_teardown_success_total{mode="normal"} 16516
telemt_me_writer_teardown_noop_total 16118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32634
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.750780
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32634
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 86
telemt_me_refill_failed_total 26
telemt_me_writer_restored_same_endpoint_total 358
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1282750
telemt_user_connections_current{user="hello"} 3528
telemt_user_octets_from_client{user="hello"} 25648313361 (23.89 GB)
telemt_user_octets_to_client{user="hello"} 618584142195 (576.10 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1249
telemt_user_unique_ips_recent_window{user="hello"} 530
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 45260.3 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1771927
telemt_connections_bad_total 211763
telemt_connections_current 3202
telemt_connections_me_current 3202
telemt_handshake_timeouts_total 55078
telemt_upstream_connect_attempt_total 18744
telemt_upstream_connect_success_total 18725
telemt_upstream_connect_attempts_per_request{bucket="1"} 18725
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10315
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 474
telemt_me_reconnect_success_total 362
telemt_me_reader_eof_total 347
telemt_me_idle_close_by_peer_total 347
telemt_me_route_drop_no_conn_total 489283
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1280654
telemt_me_endpoint_quarantine_total 355
telemt_me_single_endpoint_shadow_rotate_total 351
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
telemt_me_writers_active_current 43
telemt_desync_total 5983
telemt_desync_full_logged_total 2099
telemt_desync_suppressed_total 3884
telemt_desync_frames_bucket_total{bucket="1_2"} 1563
telemt_desync_frames_bucket_total{bucket="3_10"} 2314
telemt_desync_frames_bucket_total{bucket="gt_10"} 2106
telemt_pool_swap_total 49
telemt_pool_force_close_total 1292
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 110
telemt_me_draining_writers_reap_progress_total 16906
telemt_me_writer_removed_unexpected_total 321
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1229
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16027
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1236
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15614
telemt_me_writer_teardown_success_total{mode="normal"} 17256
telemt_me_writer_teardown_noop_total 16909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34165
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.697577
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34165
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 110
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 318
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 1278390
telemt_user_connections_current{user="hello"} 3202
telemt_user_octets_from_client{user="hello"} 30965060596 (28.84 GB)
telemt_user_octets_to_client{user="hello"} 644146955712 (599.91 GB)
telemt_user_unique_ips_current{user="hello"} 1206
telemt_user_unique_ips_recent_window{user="hello"} 482
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 45299.9 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5053564
telemt_connections_bad_total 272421
telemt_connections_current 5745
telemt_connections_me_current 5745
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 215389
telemt_upstream_connect_attempt_total 44566
telemt_upstream_connect_success_total 42563
telemt_upstream_connect_fail_total 1377
telemt_upstream_connect_attempts_per_request{bucket="1"} 43940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11808
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1282
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1377
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 2468
telemt_me_reconnect_success_total 874
telemt_me_reader_eof_total 612
telemt_me_idle_close_by_peer_total 611
telemt_me_route_drop_no_conn_total 7956469
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4248902
telemt_me_endpoint_quarantine_total 354
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 356
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
telemt_me_writers_active_current 127
telemt_desync_total 8946
telemt_desync_full_logged_total 2992
telemt_desync_suppressed_total 5954
telemt_desync_frames_bucket_total{bucket="1_2"} 1966
telemt_desync_frames_bucket_total{bucket="3_10"} 3856
telemt_desync_frames_bucket_total{bucket="gt_10"} 3124
telemt_pool_swap_total 46
telemt_pool_force_close_total 1353
telemt_me_writer_close_signal_drop_total 241
telemt_me_draining_writers_reap_progress_total 15309
telemt_me_writer_removed_unexpected_total 837
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1873
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14229
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1228
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 125
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13956
telemt_me_writer_teardown_success_total{mode="normal"} 16102
telemt_me_writer_teardown_noop_total 15315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31417
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 31.806767
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31417
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 241
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 605
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 4270946
telemt_user_connections_current{user="hello"} 5745
telemt_user_octets_from_client{user="hello"} 44298220302 (41.26 GB)
telemt_user_octets_to_client{user="hello"} 550690603162 (512.87 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1917
telemt_user_unique_ips_recent_window{user="hello"} 1063
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 45267.0 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1835280
telemt_connections_bad_total 236755
telemt_connections_current 3526
telemt_connections_me_current 3526
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 35273
telemt_upstream_connect_attempt_total 20277
telemt_upstream_connect_success_total 20075
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 20258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10267
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_reconnect_attempts_total 1877
telemt_me_reconnect_success_total 581
telemt_me_reader_eof_total 587
telemt_me_idle_close_by_peer_total 587
telemt_me_route_drop_no_conn_total 526646
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1367566
telemt_me_endpoint_quarantine_total 284
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 359
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
telemt_me_writers_active_current 48
telemt_desync_total 6187
telemt_desync_full_logged_total 2254
telemt_desync_suppressed_total 3933
telemt_desync_frames_bucket_total{bucket="1_2"} 1215
telemt_desync_frames_bucket_total{bucket="3_10"} 2507
telemt_desync_frames_bucket_total{bucket="gt_10"} 2465
telemt_pool_swap_total 48
telemt_pool_force_close_total 1248
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 86
telemt_me_draining_writers_reap_progress_total 16775
telemt_me_writer_removed_unexpected_total 564
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1482
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15880
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1170
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15527
telemt_me_writer_teardown_success_total{mode="normal"} 17362
telemt_me_writer_teardown_noop_total 16775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34137
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.522849
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34137
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 86
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 484
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 1364333
telemt_user_connections_current{user="hello"} 3526
telemt_user_octets_from_client{user="hello"} 24687464176 (22.99 GB)
telemt_user_octets_to_client{user="hello"} 633041614606 (589.57 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1253
telemt_user_unique_ips_recent_window{user="hello"} 570
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 45261.5 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2482150
telemt_connections_bad_total 147323
telemt_connections_current 3365
telemt_connections_me_current 3365
telemt_handshake_timeouts_total 975313
telemt_upstream_connect_attempt_total 19065
telemt_upstream_connect_success_total 19031
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 19034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 280
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 508
telemt_me_reconnect_success_total 289
telemt_me_reader_eof_total 290
telemt_me_idle_close_by_peer_total 290
telemt_me_route_drop_no_conn_total 465436
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1207553
telemt_me_endpoint_quarantine_total 358
telemt_me_single_endpoint_shadow_rotate_total 361
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
telemt_desync_total 5974
telemt_desync_full_logged_total 2116
telemt_desync_suppressed_total 3858
telemt_desync_frames_bucket_total{bucket="1_2"} 1049
telemt_desync_frames_bucket_total{bucket="3_10"} 2398
telemt_desync_frames_bucket_total{bucket="gt_10"} 2527
telemt_pool_swap_total 50
telemt_pool_force_close_total 1212
telemt_me_writer_close_signal_drop_total 89
telemt_me_draining_writers_reap_progress_total 17088
telemt_me_writer_removed_unexpected_total 280
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1071
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16316
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1195
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15876
telemt_me_writer_teardown_success_total{mode="normal"} 17387
telemt_me_writer_teardown_noop_total 17088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34475
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.824927
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34475
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 89
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 256
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1203436
telemt_user_connections_current{user="hello"} 3365
telemt_user_octets_from_client{user="hello"} 21171189820 (19.72 GB)
telemt_user_octets_to_client{user="hello"} 601748832052 (560.42 GB)
telemt_user_unique_ips_current{user="hello"} 1253
telemt_user_unique_ips_recent_window{user="hello"} 547
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 43252.6 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 529057
telemt_connections_bad_total 19480
telemt_connections_current 622
telemt_connections_me_current 622
telemt_handshake_timeouts_total 188787
telemt_upstream_connect_attempt_total 21298
telemt_upstream_connect_success_total 21296
telemt_upstream_connect_attempts_per_request{bucket="1"} 21296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12356
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 850
telemt_me_reconnect_success_total 352
telemt_me_reader_eof_total 347
telemt_me_idle_close_by_peer_total 347
telemt_me_route_drop_no_conn_total 113967
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 281417
telemt_me_endpoint_quarantine_total 418
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 368
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 19
telemt_desync_total 1759
telemt_desync_full_logged_total 717
telemt_desync_suppressed_total 1042
telemt_desync_frames_bucket_total{bucket="1_2"} 349
telemt_desync_frames_bucket_total{bucket="3_10"} 711
telemt_desync_frames_bucket_total{bucket="gt_10"} 699
telemt_pool_swap_total 47
telemt_pool_force_close_total 1008
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 61
telemt_me_draining_writers_reap_progress_total 18977
telemt_me_writer_removed_unexpected_total 329
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1361
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17948
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1006
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17969
telemt_me_writer_teardown_success_total{mode="normal"} 19309
telemt_me_writer_teardown_noop_total 18977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38286
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.555494
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38286
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 61
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 288
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 281588
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 3988017807 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 111657602021 (103.99 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 45271.1 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1884011
telemt_connections_bad_total 165239
telemt_connections_current 3594
telemt_connections_me_current 3594
telemt_handshake_timeouts_total 47787
telemt_upstream_connect_attempt_total 19745
telemt_upstream_connect_success_total 19658
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 19715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9781
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 733
telemt_me_reconnect_success_total 424
telemt_me_reader_eof_total 392
telemt_me_idle_close_by_peer_total 392
telemt_me_route_drop_no_conn_total 456475
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1485524
telemt_me_endpoint_quarantine_total 359
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 361
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
telemt_me_writers_active_current 46
telemt_desync_total 5934
telemt_desync_full_logged_total 1993
telemt_desync_suppressed_total 3941
telemt_desync_frames_bucket_total{bucket="1_2"} 1456
telemt_desync_frames_bucket_total{bucket="3_10"} 2238
telemt_desync_frames_bucket_total{bucket="gt_10"} 2240
telemt_pool_swap_total 50
telemt_pool_force_close_total 1226
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 113
telemt_me_draining_writers_reap_progress_total 17789
telemt_me_writer_removed_unexpected_total 391
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1310
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16879
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1203
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16563
telemt_me_writer_teardown_success_total{mode="normal"} 18189
telemt_me_writer_teardown_noop_total 17789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35978
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.350151
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35978
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 113
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 380
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1480131
telemt_user_connections_current{user="hello"} 3594
telemt_user_octets_from_client{user="hello"} 33680459244 (31.37 GB)
telemt_user_octets_to_client{user="hello"} 689759666268 (642.39 GB)
telemt_user_unique_ips_current{user="hello"} 1236
telemt_user_unique_ips_recent_window{user="hello"} 622
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 45268.1 (12h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1789713
telemt_connections_bad_total 146414
telemt_connections_current 4527
telemt_connections_me_current 4527
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 44639
telemt_upstream_connect_attempt_total 28242
telemt_upstream_connect_success_total 28036
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 28201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10216
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_reconnect_attempts_total 2885
telemt_me_reconnect_success_total 591
telemt_me_reader_eof_total 513
telemt_me_idle_close_by_peer_total 513
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 470797
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1431921
telemt_me_endpoint_quarantine_total 410
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 358
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
telemt_me_writers_active_current 90
telemt_desync_total 5594
telemt_desync_full_logged_total 1853
telemt_desync_suppressed_total 3741
telemt_desync_frames_bucket_total{bucket="1_2"} 1545
telemt_desync_frames_bucket_total{bucket="3_10"} 2056
telemt_desync_frames_bucket_total{bucket="gt_10"} 1993
telemt_pool_swap_total 49
telemt_pool_force_close_total 1177
telemt_me_writer_close_signal_drop_total 99
telemt_me_draining_writers_reap_progress_total 16871
telemt_me_writer_removed_unexpected_total 522
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1556
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15862
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1124
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15694
telemt_me_writer_teardown_success_total{mode="normal"} 17418
telemt_me_writer_teardown_noop_total 16872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34290
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.975624
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34290
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 99
telemt_me_refill_failed_total 130
telemt_me_writer_restored_same_endpoint_total 456
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 1435947
telemt_user_connections_current{user="hello"} 4527
telemt_user_octets_from_client{user="hello"} 22383973955 (20.85 GB)
telemt_user_octets_to_client{user="hello"} 638695764415 (594.83 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1607
telemt_user_unique_ips_recent_window{user="hello"} 538
```
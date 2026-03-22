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

# Server Metrics 2026-03-22 21:57:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 89470.2 (24h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3269415
telemt_connections_bad_total 240659
telemt_connections_current 810
telemt_connections_me_current 810
telemt_handshake_timeouts_total 103836
telemt_upstream_connect_attempt_total 32840
telemt_upstream_connect_success_total 32839
telemt_upstream_connect_attempts_per_request{bucket="1"} 32839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21406
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 423
telemt_me_reconnect_attempts_total 1317
telemt_me_reconnect_success_total 546
telemt_me_reader_eof_total 559
telemt_me_idle_close_by_peer_total 559
telemt_me_route_drop_no_conn_total 2883819
telemt_me_route_drop_channel_closed_total 1221
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2753797
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 607
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 697
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
telemt_me_writers_active_current 43
telemt_desync_total 11847
telemt_desync_full_logged_total 3714
telemt_desync_suppressed_total 8133
telemt_desync_frames_bucket_total{bucket="1_2"} 3211
telemt_desync_frames_bucket_total{bucket="3_10"} 4333
telemt_desync_frames_bucket_total{bucket="gt_10"} 4303
telemt_pool_swap_total 99
telemt_pool_force_close_total 3096
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 626
telemt_me_draining_writers_reap_progress_total 30049
telemt_me_writer_removed_unexpected_total 542
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2181
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28076
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3041
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26953
telemt_me_writer_teardown_success_total{mode="normal"} 30257
telemt_me_writer_teardown_noop_total 30060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60317
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 369.639886
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60317
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 626
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 486
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 2743235
telemt_user_connections_current{user="hello"} 810
telemt_user_octets_from_client{user="hello"} 39482583012 (36.77 GB)
telemt_user_octets_to_client{user="hello"} 740679773504 (689.81 GB)
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 281
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 102836.7 (28h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3926386
telemt_connections_bad_total 352846
telemt_connections_current 807
telemt_connections_me_current 807
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99574
telemt_upstream_connect_attempt_total 61808
telemt_upstream_connect_success_total 61054
telemt_upstream_connect_fail_total 668
telemt_upstream_connect_attempts_per_request{bucket="1"} 61722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 668
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 7359
telemt_me_reconnect_success_total 2808
telemt_me_reader_eof_total 2766
telemt_me_idle_close_by_peer_total 2766
telemt_me_route_drop_no_conn_total 3629963
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3125755
telemt_me_endpoint_quarantine_total 770
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 793
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
telemt_me_writers_active_current 128
telemt_desync_total 12698
telemt_desync_full_logged_total 7118
telemt_desync_suppressed_total 5580
telemt_desync_frames_bucket_total{bucket="1_2"} 2866
telemt_desync_frames_bucket_total{bucket="3_10"} 4986
telemt_desync_frames_bucket_total{bucket="gt_10"} 4846
telemt_pool_swap_total 95
telemt_pool_force_close_total 2879
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 238
telemt_me_draining_writers_reap_progress_total 41288
telemt_me_writer_removed_unexpected_total 2706
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5039
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38978
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2452
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38409
telemt_me_writer_teardown_success_total{mode="normal"} 44017
telemt_me_writer_teardown_noop_total 41289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85306
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.401284
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85306
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 238
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 2482
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 198
telemt_user_connections_total{user="hello"} 3136418
telemt_user_connections_current{user="hello"} 807
telemt_user_octets_from_client{user="hello"} 41905350083 (39.03 GB)
telemt_user_octets_to_client{user="hello"} 771735273330 (718.73 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 476
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 177696.3 (49h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16141498
telemt_connections_bad_total 1579263
telemt_connections_current 974
telemt_connections_me_current 974
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 395609
telemt_upstream_connect_attempt_total 78843
telemt_upstream_connect_success_total 78743
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 78760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37984
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1697
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2856
telemt_me_reconnect_success_total 1488
telemt_me_reader_eof_total 1434
telemt_me_idle_close_by_peer_total 1432
telemt_me_route_drop_no_conn_total 14021938
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12856309
telemt_me_endpoint_quarantine_total 1142
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1329
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 53117
telemt_desync_full_logged_total 16802
telemt_desync_suppressed_total 36315
telemt_desync_frames_bucket_total{bucket="1_2"} 11803
telemt_desync_frames_bucket_total{bucket="3_10"} 20685
telemt_desync_frames_bucket_total{bucket="gt_10"} 20629
telemt_pool_swap_total 192
telemt_pool_force_close_total 6440
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1042
telemt_me_draining_writers_reap_progress_total 58749
telemt_me_writer_removed_unexpected_total 1383
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5133
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54269
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5970
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52309
telemt_me_writer_teardown_success_total{mode="normal"} 59402
telemt_me_writer_teardown_noop_total 58802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118204
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 316.200531
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118204
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1042
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1286
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 12856594
telemt_user_connections_current{user="hello"} 974
telemt_user_octets_from_client{user="hello"} 189558645969 (176.54 GB)
telemt_user_octets_to_client{user="hello"} 3449345901375 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 428
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 177698.1 (49h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11712423
telemt_connections_bad_total 1194215
telemt_connections_current 856
telemt_connections_me_current 856
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343636
telemt_upstream_connect_attempt_total 93312
telemt_upstream_connect_success_total 92004
telemt_upstream_connect_fail_total 861
telemt_upstream_connect_attempts_per_request{bucket="1"} 92865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37968
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3792
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 861
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4309
telemt_me_reconnect_success_total 1801
telemt_me_reader_eof_total 1662
telemt_me_idle_close_by_peer_total 1662
telemt_me_route_drop_no_conn_total 4536438
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8717295
telemt_me_endpoint_quarantine_total 1138
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1351
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_me_writers_active_current 48
telemt_desync_total 38504
telemt_desync_full_logged_total 12952
telemt_desync_suppressed_total 25552
telemt_desync_frames_bucket_total{bucket="1_2"} 9508
telemt_desync_frames_bucket_total{bucket="3_10"} 14802
telemt_desync_frames_bucket_total{bucket="gt_10"} 14194
telemt_pool_swap_total 189
telemt_pool_force_close_total 5812
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 57083
telemt_me_writer_removed_unexpected_total 1697
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5268
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53363
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5300
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51271
telemt_me_writer_teardown_success_total{mode="normal"} 58631
telemt_me_writer_teardown_noop_total 57108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115739
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.235137
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115739
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1533
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8655164
telemt_user_connections_current{user="hello"} 856
telemt_user_octets_from_client{user="hello"} 216882129380 (201.99 GB)
telemt_user_octets_to_client{user="hello"} 3921106290339 (3.57 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 354
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 177664.3 (49h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10937318
telemt_connections_bad_total 950629
telemt_connections_current 721
telemt_connections_me_current 721
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344760
telemt_upstream_connect_attempt_total 77082
telemt_upstream_connect_success_total 75617
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 75821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36330
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1879
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2309
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5447
telemt_me_reconnect_success_total 2248
telemt_me_reader_eof_total 1985
telemt_me_idle_close_by_peer_total 1984
telemt_me_route_drop_no_conn_total 5318397
telemt_me_route_drop_channel_closed_total 382
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8277612
telemt_me_endpoint_quarantine_total 1219
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1304
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 67
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
telemt_me_writers_active_current 83
telemt_desync_total 37848
telemt_desync_full_logged_total 12541
telemt_desync_suppressed_total 25307
telemt_desync_frames_bucket_total{bucket="1_2"} 9564
telemt_desync_frames_bucket_total{bucket="3_10"} 14475
telemt_desync_frames_bucket_total{bucket="gt_10"} 13809
telemt_pool_swap_total 185
telemt_pool_force_close_total 5722
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 726
telemt_me_draining_writers_reap_progress_total 57160
telemt_me_writer_removed_unexpected_total 2141
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5920
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53307
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5157
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 565
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51438
telemt_me_writer_teardown_success_total{mode="normal"} 59227
telemt_me_writer_teardown_noop_total 57231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116458
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.264012
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116458
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 726
telemt_me_refill_failed_total 169
telemt_me_writer_restored_same_endpoint_total 1948
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 8269619
telemt_user_connections_current{user="hello"} 721
telemt_user_octets_from_client{user="hello"} 191926885001 (178.75 GB)
telemt_user_octets_to_client{user="hello"} 3440457618753 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 47942.0 (13h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11037204
telemt_connections_bad_total 666898
telemt_connections_current 1135
telemt_connections_me_current 1135
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 248783
telemt_upstream_connect_attempt_total 50985
telemt_upstream_connect_success_total 48436
telemt_upstream_connect_fail_total 1737
telemt_upstream_connect_attempts_per_request{bucket="1"} 50173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16075
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5987
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1737
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7048
telemt_me_reconnect_success_total 1037
telemt_me_reader_eof_total 649
telemt_me_idle_close_by_peer_total 648
telemt_me_route_drop_no_conn_total 25254744
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9166798
telemt_me_endpoint_quarantine_total 335
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 379
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
telemt_me_writers_active_current 44
telemt_desync_total 15697
telemt_desync_full_logged_total 4157
telemt_desync_suppressed_total 11540
telemt_desync_frames_bucket_total{bucket="1_2"} 3005
telemt_desync_frames_bucket_total{bucket="3_10"} 6345
telemt_desync_frames_bucket_total{bucket="gt_10"} 6347
telemt_pool_swap_total 49
telemt_pool_force_close_total 1711
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 452
telemt_me_draining_writers_reap_progress_total 14120
telemt_me_writer_removed_unexpected_total 926
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2047
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12957
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1405
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 306
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12409
telemt_me_writer_teardown_success_total{mode="normal"} 15004
telemt_me_writer_teardown_noop_total 14139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29143
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.297708
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29143
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 452
telemt_me_refill_failed_total 327
telemt_me_writer_restored_same_endpoint_total 677
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 9191496
telemt_user_connections_current{user="hello"} 1135
telemt_user_octets_from_client{user="hello"} 85377747644 (79.51 GB)
telemt_user_octets_to_client{user="hello"} 557070534186 (518.81 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 439
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 177668.5 (49h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10853846
telemt_connections_bad_total 915002
telemt_connections_current 786
telemt_connections_me_current 786
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 238900
telemt_upstream_connect_attempt_total 106175
telemt_upstream_connect_success_total 105066
telemt_upstream_connect_fail_total 941
telemt_upstream_connect_attempts_per_request{bucket="1"} 106007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39962
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 941
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72603
telemt_me_reconnect_success_total 2935
telemt_me_reader_eof_total 2633
telemt_me_idle_close_by_peer_total 2631
telemt_me_route_drop_no_conn_total 5237350
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8577995
telemt_me_endpoint_quarantine_total 1171
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1333
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
telemt_me_writers_active_current 47
telemt_desync_total 45782
telemt_desync_full_logged_total 15654
telemt_desync_suppressed_total 30128
telemt_desync_frames_bucket_total{bucket="1_2"} 9283
telemt_desync_frames_bucket_total{bucket="3_10"} 17519
telemt_desync_frames_bucket_total{bucket="gt_10"} 18980
telemt_pool_swap_total 181
telemt_pool_force_close_total 5415
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 651
telemt_me_draining_writers_reap_progress_total 61385
telemt_me_writer_removed_unexpected_total 2666
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6476
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57606
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4666
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55970
telemt_me_writer_teardown_success_total{mode="normal"} 64082
telemt_me_writer_teardown_noop_total 61386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 125151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 125458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 125461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125468
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.156012
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125468
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 651
telemt_me_refill_failed_total 4291
telemt_me_writer_restored_same_endpoint_total 2481
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 8581079
telemt_user_connections_current{user="hello"} 786
telemt_user_octets_from_client{user="hello"} 193617210225 (180.32 GB)
telemt_user_octets_to_client{user="hello"} 3274999709372 (2.98 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 378
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 114504.7 (31h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11500270
telemt_connections_bad_total 459680
telemt_connections_current 877
telemt_connections_me_current 877
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4714869
telemt_upstream_connect_attempt_total 54162
telemt_upstream_connect_success_total 53758
telemt_upstream_connect_fail_total 393
telemt_upstream_connect_attempts_per_request{bucket="1"} 54151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 205
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 393
telemt_me_reconnect_attempts_total 48674
telemt_me_reconnect_success_total 1714
telemt_me_reader_eof_total 1378
telemt_me_idle_close_by_peer_total 1377
telemt_me_route_drop_no_conn_total 4068275
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5538556
telemt_me_endpoint_quarantine_total 747
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 868
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31118
telemt_desync_full_logged_total 10599
telemt_desync_suppressed_total 20519
telemt_desync_frames_bucket_total{bucket="1_2"} 6177
telemt_desync_frames_bucket_total{bucket="3_10"} 12289
telemt_desync_frames_bucket_total{bucket="gt_10"} 12652
telemt_pool_swap_total 121
telemt_pool_force_close_total 3641
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 364
telemt_me_draining_writers_reap_progress_total 40238
telemt_me_writer_removed_unexpected_total 1432
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3483
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38227
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3200
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36597
telemt_me_writer_teardown_success_total{mode="normal"} 41710
telemt_me_writer_teardown_noop_total 40245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81955
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.626364
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81955
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 364
telemt_me_refill_failed_total 2729
telemt_me_writer_restored_same_endpoint_total 1519
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5531218
telemt_user_connections_current{user="hello"} 877
telemt_user_octets_from_client{user="hello"} 118315580444 (110.19 GB)
telemt_user_octets_to_client{user="hello"} 2125573525294 (1.93 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 414
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 95475.8 (26h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1440802
telemt_connections_bad_total 35546
telemt_connections_current 650
telemt_connections_me_current 650
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 28158
telemt_upstream_connect_attempt_total 44680
telemt_upstream_connect_success_total 44541
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 44652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23746
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 759
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2058
telemt_me_reconnect_success_total 842
telemt_me_reader_eof_total 825
telemt_me_idle_close_by_peer_total 825
telemt_me_route_drop_no_conn_total 499114
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1278423
telemt_me_endpoint_quarantine_total 765
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 783
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
telemt_me_writers_warm_current 25
telemt_desync_total 7992
telemt_desync_full_logged_total 2429
telemt_desync_suppressed_total 5563
telemt_desync_frames_bucket_total{bucket="1_2"} 1950
telemt_desync_frames_bucket_total{bucket="3_10"} 3089
telemt_desync_frames_bucket_total{bucket="gt_10"} 2953
telemt_pool_swap_total 102
telemt_pool_force_close_total 2658
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 37365
telemt_me_writer_removed_unexpected_total 794
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2939
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35254
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2570
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34707
telemt_me_writer_teardown_success_total{mode="normal"} 38193
telemt_me_writer_teardown_noop_total 37369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75562
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.899895
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75562
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 715
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 1274366
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 25093509741 (23.37 GB)
telemt_user_octets_to_client{user="hello"} 540720697395 (503.59 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 177673.1 (49h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13187177
telemt_connections_bad_total 1563253
telemt_connections_current 1039
telemt_connections_me_current 1039
telemt_handshake_timeouts_total 379055
telemt_upstream_connect_attempt_total 67846
telemt_upstream_connect_success_total 67509
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 67710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33943
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2644
telemt_me_reconnect_success_total 1383
telemt_me_reader_eof_total 1351
telemt_me_idle_close_by_peer_total 1351
telemt_me_route_drop_no_conn_total 4465819
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9967048
telemt_me_endpoint_quarantine_total 1213
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1333
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 41637
telemt_desync_full_logged_total 13581
telemt_desync_suppressed_total 28056
telemt_desync_frames_bucket_total{bucket="1_2"} 10010
telemt_desync_frames_bucket_total{bucket="3_10"} 15321
telemt_desync_frames_bucket_total{bucket="gt_10"} 16306
telemt_pool_swap_total 197
telemt_pool_force_close_total 5380
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 660
telemt_me_draining_writers_reap_progress_total 61195
telemt_me_writer_removed_unexpected_total 1300
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4955
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57581
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5206
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55815
telemt_me_writer_teardown_success_total{mode="normal"} 62536
telemt_me_writer_teardown_noop_total 61197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 121169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 123224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 123600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123733
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.575531
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123733
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 660
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 1210
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 9933867
telemt_user_connections_current{user="hello"} 1039
telemt_user_octets_from_client{user="hello"} 193924251304 (180.61 GB)
telemt_user_octets_to_client{user="hello"} 4398288913200 (4.00 TB)
telemt_user_unique_ips_current{user="hello"} 384
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 177669.6 (49h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11475818
telemt_connections_bad_total 1307115
telemt_connections_current 805
telemt_connections_me_current 805
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 302946
telemt_upstream_connect_attempt_total 94353
telemt_upstream_connect_success_total 93506
telemt_upstream_connect_fail_total 640
telemt_upstream_connect_attempts_per_request{bucket="1"} 94146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39508
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2066
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 640
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10086
telemt_me_reconnect_success_total 2437
telemt_me_reader_eof_total 2274
telemt_me_idle_close_by_peer_total 2273
telemt_me_seq_mismatch_total 85
telemt_me_route_drop_no_conn_total 5625697
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8867133
telemt_me_endpoint_quarantine_total 1375
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 1336
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
telemt_desync_total 41187
telemt_desync_full_logged_total 13212
telemt_desync_suppressed_total 27975
telemt_desync_frames_bucket_total{bucket="1_2"} 10567
telemt_desync_frames_bucket_total{bucket="3_10"} 15161
telemt_desync_frames_bucket_total{bucket="gt_10"} 15459
telemt_pool_swap_total 187
telemt_pool_force_close_total 5172
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 649
telemt_me_draining_writers_reap_progress_total 60995
telemt_me_writer_removed_unexpected_total 2309
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6293
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57090
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4701
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55823
telemt_me_writer_teardown_success_total{mode="normal"} 63383
telemt_me_writer_teardown_noop_total 61000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 121715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 124333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 124383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 124383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 124383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 124383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 124383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 124383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 124383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 124383
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.303420
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 124383
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 649
telemt_me_refill_failed_total 395
telemt_me_writer_restored_same_endpoint_total 1976
telemt_me_writer_restored_fallback_total 117
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 8872580
telemt_user_connections_current{user="hello"} 805
telemt_user_octets_from_client{user="hello"} 156623503721 (145.87 GB)
telemt_user_octets_to_client{user="hello"} 3452851787015 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 342
telemt_user_unique_ips_recent_window{user="hello"} 85
```
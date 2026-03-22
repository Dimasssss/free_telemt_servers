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

# Server Metrics 2026-03-22 22:18:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 90696.9 (25h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3302396
telemt_connections_bad_total 249954
telemt_connections_current 822
telemt_connections_me_current 822
telemt_handshake_timeouts_total 104759
telemt_upstream_connect_attempt_total 33333
telemt_upstream_connect_success_total 33332
telemt_upstream_connect_attempts_per_request{bucket="1"} 33332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21738
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1321
telemt_me_reconnect_success_total 550
telemt_me_reader_eof_total 565
telemt_me_idle_close_by_peer_total 565
telemt_me_route_drop_no_conn_total 2959167
telemt_me_route_drop_channel_closed_total 1227
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2774440
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 619
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 705
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
telemt_me_writers_active_current 44
telemt_desync_total 11910
telemt_desync_full_logged_total 3731
telemt_desync_suppressed_total 8179
telemt_desync_frames_bucket_total{bucket="1_2"} 3221
telemt_desync_frames_bucket_total{bucket="3_10"} 4352
telemt_desync_frames_bucket_total{bucket="gt_10"} 4337
telemt_pool_swap_total 100
telemt_pool_force_close_total 3120
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 628
telemt_me_draining_writers_reap_progress_total 30498
telemt_me_writer_removed_unexpected_total 546
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2203
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28508
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3065
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27378
telemt_me_writer_teardown_success_total{mode="normal"} 30711
telemt_me_writer_teardown_noop_total 30509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61220
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 373.483902
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61220
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 628
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 490
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 2763826
telemt_user_connections_current{user="hello"} 822
telemt_user_octets_from_client{user="hello"} 39670097592 (36.95 GB)
telemt_user_octets_to_client{user="hello"} 746614417404 (695.34 GB)
telemt_user_unique_ips_current{user="hello"} 365
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 104063.2 (28h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3937914
telemt_connections_bad_total 355733
telemt_connections_current 845
telemt_connections_me_current 845
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99641
telemt_upstream_connect_attempt_total 62766
telemt_upstream_connect_success_total 62001
telemt_upstream_connect_fail_total 679
telemt_upstream_connect_attempts_per_request{bucket="1"} 62680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27541
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 679
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9170
telemt_me_reconnect_success_total 3289
telemt_me_reader_eof_total 3300
telemt_me_idle_close_by_peer_total 3300
telemt_me_route_drop_no_conn_total 3632976
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3133913
telemt_me_endpoint_quarantine_total 771
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 804
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
telemt_desync_total 12753
telemt_desync_full_logged_total 7144
telemt_desync_suppressed_total 5609
telemt_desync_frames_bucket_total{bucket="1_2"} 2877
telemt_desync_frames_bucket_total{bucket="3_10"} 5005
telemt_desync_frames_bucket_total{bucket="gt_10"} 4871
telemt_pool_swap_total 95
telemt_pool_force_close_total 2879
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 238
telemt_me_draining_writers_reap_progress_total 41694
telemt_me_writer_removed_unexpected_total 3239
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5589
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39368
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2452
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38815
telemt_me_writer_teardown_success_total{mode="normal"} 44957
telemt_me_writer_teardown_noop_total 41695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86652
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.425097
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86652
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 238
telemt_me_refill_failed_total 223
telemt_me_writer_restored_same_endpoint_total 2963
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 3144575
telemt_user_connections_current{user="hello"} 845
telemt_user_octets_from_client{user="hello"} 42354256551 (39.45 GB)
telemt_user_octets_to_client{user="hello"} 774877922146 (721.66 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 178923.0 (49h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16175802
telemt_connections_bad_total 1595105
telemt_connections_current 944
telemt_connections_me_current 944
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 395931
telemt_upstream_connect_attempt_total 79402
telemt_upstream_connect_success_total 79302
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 79319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38304
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1700
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2888
telemt_me_reconnect_success_total 1500
telemt_me_reader_eof_total 1446
telemt_me_idle_close_by_peer_total 1444
telemt_me_route_drop_no_conn_total 14026226
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12873638
telemt_me_endpoint_quarantine_total 1154
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1337
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
telemt_me_writers_active_current 46
telemt_desync_total 53196
telemt_desync_full_logged_total 16849
telemt_desync_suppressed_total 36347
telemt_desync_frames_bucket_total{bucket="1_2"} 11819
telemt_desync_frames_bucket_total{bucket="3_10"} 20719
telemt_desync_frames_bucket_total{bucket="gt_10"} 20658
telemt_pool_swap_total 193
telemt_pool_force_close_total 6464
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1043
telemt_me_draining_writers_reap_progress_total 59247
telemt_me_writer_removed_unexpected_total 1395
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5161
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54751
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5994
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52783
telemt_me_writer_teardown_success_total{mode="normal"} 59912
telemt_me_writer_teardown_noop_total 59300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119212
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 316.841698
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119212
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1043
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 1297
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 12873899
telemt_user_connections_current{user="hello"} 944
telemt_user_octets_from_client{user="hello"} 189769807525 (176.74 GB)
telemt_user_octets_to_client{user="hello"} 3456628454187 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 178924.4 (49h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11738692
telemt_connections_bad_total 1202096
telemt_connections_current 822
telemt_connections_me_current 822
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343698
telemt_upstream_connect_attempt_total 93868
telemt_upstream_connect_success_total 92559
telemt_upstream_connect_fail_total 862
telemt_upstream_connect_attempts_per_request{bucket="1"} 93421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38295
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3794
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 862
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4318
telemt_me_reconnect_success_total 1809
telemt_me_reader_eof_total 1670
telemt_me_idle_close_by_peer_total 1670
telemt_me_route_drop_no_conn_total 4540530
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8732586
telemt_me_endpoint_quarantine_total 1149
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1358
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
telemt_me_writers_active_current 46
telemt_desync_total 38577
telemt_desync_full_logged_total 12976
telemt_desync_suppressed_total 25601
telemt_desync_frames_bucket_total{bucket="1_2"} 9529
telemt_desync_frames_bucket_total{bucket="3_10"} 14830
telemt_desync_frames_bucket_total{bucket="gt_10"} 14218
telemt_pool_swap_total 190
telemt_pool_force_close_total 5833
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 57587
telemt_me_writer_removed_unexpected_total 1705
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5291
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53852
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5321
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51754
telemt_me_writer_teardown_success_total{mode="normal"} 59143
telemt_me_writer_teardown_noop_total 57612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116755
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.246351
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116755
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1541
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8670431
telemt_user_connections_current{user="hello"} 822
telemt_user_octets_from_client{user="hello"} 217017579792 (202.11 GB)
telemt_user_octets_to_client{user="hello"} 3928838056459 (3.57 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 178888.6 (49h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10952300
telemt_connections_bad_total 953007
telemt_connections_current 555
telemt_connections_me_current 555
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344890
telemt_upstream_connect_attempt_total 77929
telemt_upstream_connect_success_total 76421
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 76625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36807
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1926
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2324
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5532
telemt_me_reconnect_success_total 2283
telemt_me_reader_eof_total 2019
telemt_me_idle_close_by_peer_total 2018
telemt_me_route_drop_no_conn_total 5322462
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8289055
telemt_me_endpoint_quarantine_total 1232
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1314
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_me_writers_active_current 44
telemt_desync_total 37860
telemt_desync_full_logged_total 12548
telemt_desync_suppressed_total 25312
telemt_desync_frames_bucket_total{bucket="1_2"} 9565
telemt_desync_frames_bucket_total{bucket="3_10"} 14480
telemt_desync_frames_bucket_total{bucket="gt_10"} 13815
telemt_pool_swap_total 186
telemt_pool_force_close_total 5755
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 728
telemt_me_draining_writers_reap_progress_total 57901
telemt_me_writer_removed_unexpected_total 2174
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5994
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54008
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5184
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52146
telemt_me_writer_teardown_success_total{mode="normal"} 60002
telemt_me_writer_teardown_noop_total 57972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117974
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.511810
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117974
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 728
telemt_me_refill_failed_total 172
telemt_me_writer_restored_same_endpoint_total 1977
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 8281047
telemt_user_connections_current{user="hello"} 555
telemt_user_octets_from_client{user="hello"} 192007049009 (178.82 GB)
telemt_user_octets_to_client{user="hello"} 3443920990445 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 49168.5 (13h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11066872
telemt_connections_bad_total 666991
telemt_connections_current 1313
telemt_connections_me_current 1313
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 251443
telemt_upstream_connect_attempt_total 51413
telemt_upstream_connect_success_total 48845
telemt_upstream_connect_fail_total 1740
telemt_upstream_connect_attempts_per_request{bucket="1"} 50585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16306
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5987
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1740
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7056
telemt_me_reconnect_success_total 1045
telemt_me_reader_eof_total 658
telemt_me_idle_close_by_peer_total 657
telemt_me_route_drop_no_conn_total 25261159
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9192287
telemt_me_endpoint_quarantine_total 339
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 389
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
telemt_me_writers_active_current 44
telemt_desync_total 15771
telemt_desync_full_logged_total 4187
telemt_desync_suppressed_total 11584
telemt_desync_frames_bucket_total{bucket="1_2"} 3014
telemt_desync_frames_bucket_total{bucket="3_10"} 6373
telemt_desync_frames_bucket_total{bucket="gt_10"} 6384
telemt_pool_swap_total 50
telemt_pool_force_close_total 1749
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 456
telemt_me_draining_writers_reap_progress_total 14498
telemt_me_writer_removed_unexpected_total 934
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2071
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13312
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1442
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12749
telemt_me_writer_teardown_success_total{mode="normal"} 15383
telemt_me_writer_teardown_noop_total 14517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29900
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.616342
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29900
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 456
telemt_me_refill_failed_total 327
telemt_me_writer_restored_same_endpoint_total 685
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 9216968
telemt_user_connections_current{user="hello"} 1313
telemt_user_octets_from_client{user="hello"} 85737031772 (79.85 GB)
telemt_user_octets_to_client{user="hello"} 564935247886 (526.14 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 498
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 178895.2 (49h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10877579
telemt_connections_bad_total 924493
telemt_connections_current 981
telemt_connections_me_current 981
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 239124
telemt_upstream_connect_attempt_total 106748
telemt_upstream_connect_success_total 105637
telemt_upstream_connect_fail_total 942
telemt_upstream_connect_attempts_per_request{bucket="1"} 106579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40262
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 942
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72640
telemt_me_reconnect_success_total 2952
telemt_me_reader_eof_total 2649
telemt_me_idle_close_by_peer_total 2647
telemt_me_route_drop_no_conn_total 5241392
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8591125
telemt_me_endpoint_quarantine_total 1177
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1341
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_desync_total 45821
telemt_desync_full_logged_total 15674
telemt_desync_suppressed_total 30147
telemt_desync_frames_bucket_total{bucket="1_2"} 9296
telemt_desync_frames_bucket_total{bucket="3_10"} 17532
telemt_desync_frames_bucket_total{bucket="gt_10"} 18993
telemt_pool_swap_total 182
telemt_pool_force_close_total 5437
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 652
telemt_me_draining_writers_reap_progress_total 61895
telemt_me_writer_removed_unexpected_total 2682
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6511
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58097
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4688
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56458
telemt_me_writer_teardown_success_total{mode="normal"} 64608
telemt_me_writer_teardown_noop_total 61896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 125768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 126460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 126504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 126504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 126504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 126504
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.175092
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 126504
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 652
telemt_me_refill_failed_total 4292
telemt_me_writer_restored_same_endpoint_total 2495
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 8594203
telemt_user_connections_current{user="hello"} 981
telemt_user_octets_from_client{user="hello"} 193770686705 (180.46 GB)
telemt_user_octets_to_client{user="hello"} 3281424506356 (2.98 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 115731.4 (32h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11535170
telemt_connections_bad_total 460108
telemt_connections_current 715
telemt_connections_me_current 715
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4731133
telemt_upstream_connect_attempt_total 54790
telemt_upstream_connect_success_total 54384
telemt_upstream_connect_fail_total 395
telemt_upstream_connect_attempts_per_request{bucket="1"} 54779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24652
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 395
telemt_me_reconnect_attempts_total 48687
telemt_me_reconnect_success_total 1726
telemt_me_reader_eof_total 1390
telemt_me_idle_close_by_peer_total 1389
telemt_me_route_drop_no_conn_total 4071875
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5550572
telemt_me_endpoint_quarantine_total 751
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 879
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31199
telemt_desync_full_logged_total 10632
telemt_desync_suppressed_total 20567
telemt_desync_frames_bucket_total{bucket="1_2"} 6194
telemt_desync_frames_bucket_total{bucket="3_10"} 12314
telemt_desync_frames_bucket_total{bucket="gt_10"} 12691
telemt_pool_swap_total 122
telemt_pool_force_close_total 3684
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 367
telemt_me_draining_writers_reap_progress_total 40816
telemt_me_writer_removed_unexpected_total 1444
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3512
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38788
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3243
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37132
telemt_me_writer_teardown_success_total{mode="normal"} 42300
telemt_me_writer_teardown_noop_total 40823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83123
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.631002
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83123
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 367
telemt_me_refill_failed_total 2729
telemt_me_writer_restored_same_endpoint_total 1531
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5543199
telemt_user_connections_current{user="hello"} 715
telemt_user_octets_from_client{user="hello"} 118439306064 (110.31 GB)
telemt_user_octets_to_client{user="hello"} 2132352788854 (1.94 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 336
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 96702.5 (26h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1454226
telemt_connections_bad_total 36378
telemt_connections_current 651
telemt_connections_me_current 651
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 28951
telemt_upstream_connect_attempt_total 45256
telemt_upstream_connect_success_total 45115
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 45228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 763
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2066
telemt_me_reconnect_success_total 851
telemt_me_reader_eof_total 832
telemt_me_idle_close_by_peer_total 832
telemt_me_route_drop_no_conn_total 502462
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1290043
telemt_me_endpoint_quarantine_total 783
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 797
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
telemt_desync_total 8098
telemt_desync_full_logged_total 2452
telemt_desync_suppressed_total 5646
telemt_desync_frames_bucket_total{bucket="1_2"} 2001
telemt_desync_frames_bucket_total{bucket="3_10"} 3126
telemt_desync_frames_bucket_total{bucket="gt_10"} 2971
telemt_pool_swap_total 104
telemt_pool_force_close_total 2714
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 149
telemt_me_draining_writers_reap_progress_total 37920
telemt_me_writer_removed_unexpected_total 801
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2976
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35779
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2626
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35206
telemt_me_writer_teardown_success_total{mode="normal"} 38755
telemt_me_writer_teardown_noop_total 37924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76679
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.966968
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76679
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 149
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 721
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 1285959
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 25250794765 (23.52 GB)
telemt_user_octets_to_client{user="hello"} 546997023351 (509.43 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 178899.6 (49h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13203580
telemt_connections_bad_total 1566178
telemt_connections_current 984
telemt_connections_me_current 984
telemt_handshake_timeouts_total 379144
telemt_upstream_connect_attempt_total 68407
telemt_upstream_connect_success_total 68069
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 68271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34236
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2674
telemt_me_reconnect_success_total 1396
telemt_me_reader_eof_total 1365
telemt_me_idle_close_by_peer_total 1365
telemt_me_route_drop_no_conn_total 4469712
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9980192
telemt_me_endpoint_quarantine_total 1222
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1342
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
telemt_me_writers_active_current 46
telemt_desync_total 41693
telemt_desync_full_logged_total 13605
telemt_desync_suppressed_total 28088
telemt_desync_frames_bucket_total{bucket="1_2"} 10015
telemt_desync_frames_bucket_total{bucket="3_10"} 15347
telemt_desync_frames_bucket_total{bucket="gt_10"} 16331
telemt_pool_swap_total 198
telemt_pool_force_close_total 5402
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 661
telemt_me_draining_writers_reap_progress_total 61690
telemt_me_writer_removed_unexpected_total 1313
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4985
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58060
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5228
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56288
telemt_me_writer_teardown_success_total{mode="normal"} 63045
telemt_me_writer_teardown_noop_total 61692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 124604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 124724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 124737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 124737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 124737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 124737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 124737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 124737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 124737
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.586299
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 124737
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 661
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 1222
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 9946988
telemt_user_connections_current{user="hello"} 984
telemt_user_octets_from_client{user="hello"} 194075980940 (180.75 GB)
telemt_user_octets_to_client{user="hello"} 4408034791504 (4.01 TB)
telemt_user_unique_ips_current{user="hello"} 366
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 178896.3 (49h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11495306
telemt_connections_bad_total 1310247
telemt_connections_current 752
telemt_connections_me_current 752
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 304460
telemt_upstream_connect_attempt_total 94909
telemt_upstream_connect_success_total 94061
telemt_upstream_connect_fail_total 641
telemt_upstream_connect_attempts_per_request{bucket="1"} 94702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 641
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10095
telemt_me_reconnect_success_total 2446
telemt_me_reader_eof_total 2283
telemt_me_idle_close_by_peer_total 2282
telemt_me_seq_mismatch_total 85
telemt_me_route_drop_no_conn_total 5629313
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8881119
telemt_me_endpoint_quarantine_total 1384
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 1344
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
telemt_me_writers_active_current 44
telemt_desync_total 41303
telemt_desync_full_logged_total 13255
telemt_desync_suppressed_total 28048
telemt_desync_frames_bucket_total{bucket="1_2"} 10603
telemt_desync_frames_bucket_total{bucket="3_10"} 15202
telemt_desync_frames_bucket_total{bucket="gt_10"} 15498
telemt_pool_swap_total 188
telemt_pool_force_close_total 5197
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 650
telemt_me_draining_writers_reap_progress_total 61493
telemt_me_writer_removed_unexpected_total 2317
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6324
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57566
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4726
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56296
telemt_me_writer_teardown_success_total{mode="normal"} 63890
telemt_me_writer_teardown_noop_total 61498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 125019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 125388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 125388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125388
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.315024
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125388
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 650
telemt_me_refill_failed_total 395
telemt_me_writer_restored_same_endpoint_total 1984
telemt_me_writer_restored_fallback_total 117
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 8886537
telemt_user_connections_current{user="hello"} 752
telemt_user_octets_from_client{user="hello"} 156758872709 (145.99 GB)
telemt_user_octets_to_client{user="hello"} 3459139138927 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 342
telemt_user_unique_ips_recent_window{user="hello"} 91
```
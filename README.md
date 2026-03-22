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

# Server Metrics 2026-03-22 19:39:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 81177.8 (22h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3018871
telemt_connections_bad_total 202894
telemt_connections_current 1170
telemt_connections_me_current 1170
telemt_handshake_timeouts_total 97930
telemt_upstream_connect_attempt_total 29761
telemt_upstream_connect_success_total 29760
telemt_upstream_connect_attempts_per_request{bucket="1"} 29760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19336
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 75
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1187
telemt_me_reconnect_success_total 501
telemt_me_reader_eof_total 506
telemt_me_idle_close_by_peer_total 506
telemt_me_route_drop_no_conn_total 2687049
telemt_me_route_drop_channel_closed_total 1072
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2556261
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 552
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 630
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
telemt_me_writers_active_current 47
telemt_desync_total 11003
telemt_desync_full_logged_total 3498
telemt_desync_suppressed_total 7505
telemt_desync_frames_bucket_total{bucket="1_2"} 2950
telemt_desync_frames_bucket_total{bucket="3_10"} 4085
telemt_desync_frames_bucket_total{bucket="gt_10"} 3968
telemt_pool_swap_total 90
telemt_pool_force_close_total 2762
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 580
telemt_me_draining_writers_reap_progress_total 27174
telemt_me_writer_removed_unexpected_total 490
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1979
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25419
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2709
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24412
telemt_me_writer_teardown_success_total{mode="normal"} 27398
telemt_me_writer_teardown_noop_total 27184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54582
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 301.967746
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54582
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 580
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 443
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 2548589
telemt_user_connections_current{user="hello"} 1170
telemt_user_octets_from_client{user="hello"} 37243621136 (34.69 GB)
telemt_user_octets_to_client{user="hello"} 668479328180 (622.57 GB)
telemt_user_unique_ips_current{user="hello"} 489
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 94543.8 (26h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3817771
telemt_connections_bad_total 339983
telemt_connections_current 1379
telemt_connections_me_current 1379
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 97405
telemt_upstream_connect_attempt_total 57322
telemt_upstream_connect_success_total 56619
telemt_upstream_connect_fail_total 620
telemt_upstream_connect_attempts_per_request{bucket="1"} 57239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 620
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6491
telemt_me_reconnect_success_total 2398
telemt_me_reader_eof_total 2336
telemt_me_idle_close_by_peer_total 2336
telemt_me_route_drop_no_conn_total 3600736
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3038124
telemt_me_endpoint_quarantine_total 729
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 727
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_me_writers_warm_current 7
telemt_desync_total 12142
telemt_desync_full_logged_total 6788
telemt_desync_suppressed_total 5354
telemt_desync_frames_bucket_total{bucket="1_2"} 2784
telemt_desync_frames_bucket_total{bucket="3_10"} 4759
telemt_desync_frames_bucket_total{bucket="gt_10"} 4599
telemt_pool_swap_total 88
telemt_pool_force_close_total 2657
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 225
telemt_me_draining_writers_reap_progress_total 37564
telemt_me_writer_removed_unexpected_total 2286
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4426
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35436
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2268
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34907
telemt_me_writer_teardown_success_total{mode="normal"} 39862
telemt_me_writer_teardown_noop_total 37564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77426
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.967276
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77426
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 225
telemt_me_refill_failed_total 164
telemt_me_writer_restored_same_endpoint_total 2085
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 3048927
telemt_user_connections_current{user="hello"} 1379
telemt_user_octets_from_client{user="hello"} 39526236963 (36.81 GB)
telemt_user_octets_to_client{user="hello"} 720193835726 (670.73 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 758
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 169403.9 (47h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15894892
telemt_connections_bad_total 1533954
telemt_connections_current 1638
telemt_connections_me_current 1638
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 392196
telemt_upstream_connect_attempt_total 75455
telemt_upstream_connect_success_total 75357
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 75374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36085
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1686
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2800
telemt_me_reconnect_success_total 1439
telemt_me_reader_eof_total 1381
telemt_me_idle_close_by_peer_total 1379
telemt_me_route_drop_no_conn_total 13960603
telemt_me_route_drop_channel_closed_total 143
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12666985
telemt_me_endpoint_quarantine_total 1071
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1262
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 52225
telemt_desync_full_logged_total 16431
telemt_desync_suppressed_total 35794
telemt_desync_frames_bucket_total{bucket="1_2"} 11643
telemt_desync_frames_bucket_total{bucket="3_10"} 20343
telemt_desync_frames_bucket_total{bucket="gt_10"} 20239
telemt_pool_swap_total 183
telemt_pool_force_close_total 6191
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1005
telemt_me_draining_writers_reap_progress_total 55678
telemt_me_writer_removed_unexpected_total 1333
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4888
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51400
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5723
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 468
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49487
telemt_me_writer_teardown_success_total{mode="normal"} 56288
telemt_me_writer_teardown_noop_total 55729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112017
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 312.721070
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112017
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1005
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1241
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 12667507
telemt_user_connections_current{user="hello"} 1638
telemt_user_octets_from_client{user="hello"} 184973961189 (172.27 GB)
telemt_user_octets_to_client{user="hello"} 3358928959435 (3.05 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 621
telemt_user_unique_ips_recent_window{user="hello"} 608
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 169405.0 (47h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11490182
telemt_connections_bad_total 1143893
telemt_connections_current 1091
telemt_connections_me_current 1091
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 342109
telemt_upstream_connect_attempt_total 87902
telemt_upstream_connect_success_total 86672
telemt_upstream_connect_fail_total 845
telemt_upstream_connect_attempts_per_request{bucket="1"} 87517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35940
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3708
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 845
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4137
telemt_me_reconnect_success_total 1718
telemt_me_reader_eof_total 1587
telemt_me_idle_close_by_peer_total 1587
telemt_me_route_drop_no_conn_total 4481955
telemt_me_route_drop_channel_closed_total 491
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8561310
telemt_me_endpoint_quarantine_total 1071
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1284
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
telemt_me_writers_active_current 43
telemt_desync_total 37936
telemt_desync_full_logged_total 12781
telemt_desync_suppressed_total 25155
telemt_desync_frames_bucket_total{bucket="1_2"} 9353
telemt_desync_frames_bucket_total{bucket="3_10"} 14613
telemt_desync_frames_bucket_total{bucket="gt_10"} 13970
telemt_pool_swap_total 180
telemt_pool_force_close_total 5580
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 702
telemt_me_draining_writers_reap_progress_total 54067
telemt_me_writer_removed_unexpected_total 1625
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5005
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50533
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5077
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 503
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48487
telemt_me_writer_teardown_success_total{mode="normal"} 55538
telemt_me_writer_teardown_noop_total 54092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109630
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.648610
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109630
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 702
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1469
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 8499523
telemt_user_connections_current{user="hello"} 1091
telemt_user_octets_from_client{user="hello"} 213210909317 (198.57 GB)
telemt_user_octets_to_client{user="hello"} 3836174483954 (3.49 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 415
telemt_user_unique_ips_recent_window{user="hello"} 414
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 169373.3 (47h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10788401
telemt_connections_bad_total 931663
telemt_connections_current 1433
telemt_connections_me_current 1433
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 343674
telemt_upstream_connect_attempt_total 73008
telemt_upstream_connect_success_total 71904
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 72089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34376
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1581
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 4961
telemt_me_reconnect_success_total 2004
telemt_me_reader_eof_total 1750
telemt_me_idle_close_by_peer_total 1749
telemt_me_route_drop_no_conn_total 5252452
telemt_me_route_drop_channel_closed_total 374
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8156637
telemt_me_endpoint_quarantine_total 1156
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1242
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
telemt_me_writers_active_current 43
telemt_desync_total 37403
telemt_desync_full_logged_total 12377
telemt_desync_suppressed_total 25026
telemt_desync_frames_bucket_total{bucket="1_2"} 9464
telemt_desync_frames_bucket_total{bucket="3_10"} 14306
telemt_desync_frames_bucket_total{bucket="gt_10"} 13633
telemt_pool_swap_total 178
telemt_pool_force_close_total 5501
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 709
telemt_me_draining_writers_reap_progress_total 54177
telemt_me_writer_removed_unexpected_total 1891
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5432
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50555
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4950
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 551
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48676
telemt_me_writer_teardown_success_total{mode="normal"} 55987
telemt_me_writer_teardown_noop_total 54248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110235
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.775044
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110235
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 709
telemt_me_refill_failed_total 157
telemt_me_writer_restored_same_endpoint_total 1724
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 8148970
telemt_user_connections_current{user="hello"} 1433
telemt_user_octets_from_client{user="hello"} 189229249817 (176.23 GB)
telemt_user_octets_to_client{user="hello"} 3392154929693 (3.09 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 550
telemt_user_unique_ips_recent_window{user="hello"} 302
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 39649.2 (11h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10761183
telemt_connections_bad_total 656603
telemt_connections_current 2033
telemt_connections_me_current 2033
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 230562
telemt_upstream_connect_attempt_total 44657
telemt_upstream_connect_success_total 42415
telemt_upstream_connect_fail_total 1543
telemt_upstream_connect_attempts_per_request{bucket="1"} 43958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13340
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5958
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1543
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6470
telemt_me_reconnect_success_total 873
telemt_me_reader_eof_total 545
telemt_me_idle_close_by_peer_total 545
telemt_me_route_drop_no_conn_total 25176859
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8935662
telemt_me_endpoint_quarantine_total 241
telemt_me_single_endpoint_outage_enter_total 63
telemt_me_single_endpoint_outage_exit_total 63
telemt_me_single_endpoint_outage_reconnect_attempt_total 114
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 114
telemt_me_single_endpoint_shadow_rotate_total 307
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 11
telemt_desync_total 14497
telemt_desync_full_logged_total 3807
telemt_desync_suppressed_total 10690
telemt_desync_frames_bucket_total{bucket="1_2"} 2689
telemt_desync_frames_bucket_total{bucket="3_10"} 5882
telemt_desync_frames_bucket_total{bucket="gt_10"} 5926
telemt_pool_swap_total 39
telemt_pool_force_close_total 1442
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 425
telemt_me_draining_writers_reap_progress_total 11169
telemt_me_writer_removed_unexpected_total 789
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1683
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10228
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1150
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 292
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9727
telemt_me_writer_teardown_success_total{mode="normal"} 11911
telemt_me_writer_teardown_noop_total 11188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 21235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 21821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 22582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 23043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 23099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 23099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 23099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 23099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 23099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 23099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 23099
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.046811
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 23099
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 425
telemt_me_refill_failed_total 310
telemt_me_writer_restored_same_endpoint_total 583
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 8957849
telemt_user_connections_current{user="hello"} 2033
telemt_user_octets_from_client{user="hello"} 81809504691 (76.19 GB)
telemt_user_octets_to_client{user="hello"} 471403812331 (439.03 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 759
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 169375.8 (47h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10659321
telemt_connections_bad_total 897830
telemt_connections_current 1561
telemt_connections_me_current 1561
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 234123
telemt_upstream_connect_attempt_total 102365
telemt_upstream_connect_success_total 101283
telemt_upstream_connect_fail_total 923
telemt_upstream_connect_attempts_per_request{bucket="1"} 102206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37972
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 923
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72364
telemt_me_reconnect_success_total 2805
telemt_me_reader_eof_total 2496
telemt_me_idle_close_by_peer_total 2494
telemt_me_route_drop_no_conn_total 5185171
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8420777
telemt_me_endpoint_quarantine_total 1121
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1264
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
telemt_me_writers_active_current 45
telemt_desync_total 44800
telemt_desync_full_logged_total 15253
telemt_desync_suppressed_total 29547
telemt_desync_frames_bucket_total{bucket="1_2"} 9082
telemt_desync_frames_bucket_total{bucket="3_10"} 17172
telemt_desync_frames_bucket_total{bucket="gt_10"} 18546
telemt_pool_swap_total 173
telemt_pool_force_close_total 5137
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 631
telemt_me_draining_writers_reap_progress_total 57961
telemt_me_writer_removed_unexpected_total 2534
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6178
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54343
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4412
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 725
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52824
telemt_me_writer_teardown_success_total{mode="normal"} 60521
telemt_me_writer_teardown_noop_total 57962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118483
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.968756
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118483
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 631
telemt_me_refill_failed_total 4285
telemt_me_writer_restored_same_endpoint_total 2355
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 8424156
telemt_user_connections_current{user="hello"} 1561
telemt_user_octets_from_client{user="hello"} 191242993673 (178.11 GB)
telemt_user_octets_to_client{user="hello"} 3199004986804 (2.91 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 663
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 106212.0 (29h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11234228
telemt_connections_bad_total 445743
telemt_connections_current 1368
telemt_connections_me_current 1368
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4635103
telemt_upstream_connect_attempt_total 50422
telemt_upstream_connect_success_total 50045
telemt_upstream_connect_fail_total 368
telemt_upstream_connect_attempts_per_request{bucket="1"} 50413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 368
telemt_me_reconnect_attempts_total 48467
telemt_me_reconnect_success_total 1666
telemt_me_reader_eof_total 1322
telemt_me_idle_close_by_peer_total 1321
telemt_me_route_drop_no_conn_total 4026570
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5405194
telemt_me_endpoint_quarantine_total 687
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 798
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30331
telemt_desync_full_logged_total 10254
telemt_desync_suppressed_total 20077
telemt_desync_frames_bucket_total{bucket="1_2"} 6063
telemt_desync_frames_bucket_total{bucket="3_10"} 11983
telemt_desync_frames_bucket_total{bucket="gt_10"} 12285
telemt_pool_swap_total 111
telemt_pool_force_close_total 3403
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 345
telemt_me_draining_writers_reap_progress_total 36880
telemt_me_writer_removed_unexpected_total 1382
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3282
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35014
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2963
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 440
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33477
telemt_me_writer_teardown_success_total{mode="normal"} 38296
telemt_me_writer_teardown_noop_total 36887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75183
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.450385
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75183
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 345
telemt_me_refill_failed_total 2720
telemt_me_writer_restored_same_endpoint_total 1482
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5398119
telemt_user_connections_current{user="hello"} 1368
telemt_user_octets_from_client{user="hello"} 116712758488 (108.70 GB)
telemt_user_octets_to_client{user="hello"} 2066792073298 (1.88 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 504
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 87183.8 (24h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1304433
telemt_connections_bad_total 29175
telemt_connections_current 1150
telemt_connections_me_current 1150
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 24666
telemt_upstream_connect_attempt_total 41412
telemt_upstream_connect_success_total 41288
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 41385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21969
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 699
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1896
telemt_me_reconnect_success_total 802
telemt_me_reader_eof_total 778
telemt_me_idle_close_by_peer_total 778
telemt_me_route_drop_no_conn_total 454866
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1156957
telemt_me_endpoint_quarantine_total 725
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 716
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
telemt_me_writers_active_current 45
telemt_desync_total 6870
telemt_desync_full_logged_total 2110
telemt_desync_suppressed_total 4760
telemt_desync_frames_bucket_total{bucket="1_2"} 1531
telemt_desync_frames_bucket_total{bucket="3_10"} 2717
telemt_desync_frames_bucket_total{bucket="gt_10"} 2622
telemt_pool_swap_total 93
telemt_pool_force_close_total 2408
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 141
telemt_me_draining_writers_reap_progress_total 34448
telemt_me_writer_removed_unexpected_total 751
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2715
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32514
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2323
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32040
telemt_me_writer_teardown_success_total{mode="normal"} 35229
telemt_me_writer_teardown_noop_total 34452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69681
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.286495
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69681
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 141
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 680
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 1153112
telemt_user_connections_current{user="hello"} 1150
telemt_user_octets_from_client{user="hello"} 21984441333 (20.47 GB)
telemt_user_octets_to_client{user="hello"} 488558537275 (455.01 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 396
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 169380.3 (47h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12974980
telemt_connections_bad_total 1514458
telemt_connections_current 1577
telemt_connections_me_current 1577
telemt_handshake_timeouts_total 371686
telemt_upstream_connect_attempt_total 63878
telemt_upstream_connect_success_total 63546
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 63743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32031
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2518
telemt_me_reconnect_success_total 1311
telemt_me_reader_eof_total 1276
telemt_me_idle_close_by_peer_total 1276
telemt_me_route_drop_no_conn_total 4408966
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9817863
telemt_me_endpoint_quarantine_total 1136
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1265
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 40581
telemt_desync_full_logged_total 13231
telemt_desync_suppressed_total 27350
telemt_desync_frames_bucket_total{bucket="1_2"} 9696
telemt_desync_frames_bucket_total{bucket="3_10"} 14969
telemt_desync_frames_bucket_total{bucket="gt_10"} 15916
telemt_pool_swap_total 188
telemt_pool_force_close_total 5148
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 645
telemt_me_draining_writers_reap_progress_total 57528
telemt_me_writer_removed_unexpected_total 1228
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4713
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54081
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4974
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52380
telemt_me_writer_teardown_success_total{mode="normal"} 58794
telemt_me_writer_teardown_noop_total 57530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116324
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.204310
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116324
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 645
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 1146
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 9785627
telemt_user_connections_current{user="hello"} 1577
telemt_user_octets_from_client{user="hello"} 191607826868 (178.45 GB)
telemt_user_octets_to_client{user="hello"} 4323330231144 (3.93 TB)
telemt_user_unique_ips_current{user="hello"} 584
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 169377.0 (47h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11281339
telemt_connections_bad_total 1278162
telemt_connections_current 1307
telemt_connections_me_current 1307
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 296416
telemt_upstream_connect_attempt_total 90348
telemt_upstream_connect_success_total 89529
telemt_upstream_connect_fail_total 613
telemt_upstream_connect_attempts_per_request{bucket="1"} 90142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37578
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 613
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9734
telemt_me_reconnect_success_total 2334
telemt_me_reader_eof_total 2179
telemt_me_idle_close_by_peer_total 2178
telemt_me_seq_mismatch_total 78
telemt_me_route_drop_no_conn_total 5583299
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8719560
telemt_me_endpoint_quarantine_total 1299
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1268
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
telemt_me_writers_active_current 44
telemt_desync_total 39788
telemt_desync_full_logged_total 12856
telemt_desync_suppressed_total 26932
telemt_desync_frames_bucket_total{bucket="1_2"} 9922
telemt_desync_frames_bucket_total{bucket="3_10"} 14802
telemt_desync_frames_bucket_total{bucket="gt_10"} 15064
telemt_pool_swap_total 178
telemt_pool_force_close_total 4948
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 635
telemt_me_draining_writers_reap_progress_total 57334
telemt_me_writer_removed_unexpected_total 2213
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6048
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53572
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4477
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52386
telemt_me_writer_teardown_success_total{mode="normal"} 59620
telemt_me_writer_teardown_noop_total 57339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116959
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.118537
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116959
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 635
telemt_me_refill_failed_total 382
telemt_me_writer_restored_same_endpoint_total 1904
telemt_me_writer_restored_fallback_total 108
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 8725183
telemt_user_connections_current{user="hello"} 1307
telemt_user_octets_from_client{user="hello"} 154316316869 (143.72 GB)
telemt_user_octets_to_client{user="hello"} 3365728380303 (3.06 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 523
telemt_user_unique_ips_recent_window{user="hello"} 182
```
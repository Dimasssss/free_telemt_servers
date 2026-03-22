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

# Server Metrics 2026-03-22 23:08:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 93749.6 (26h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3364757
telemt_connections_bad_total 268958
telemt_connections_current 900
telemt_connections_me_current 900
telemt_handshake_timeouts_total 106586
telemt_upstream_connect_attempt_total 34505
telemt_upstream_connect_success_total 34504
telemt_upstream_connect_attempts_per_request{bucket="1"} 34504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22476
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1356
telemt_me_reconnect_success_total 564
telemt_me_reader_eof_total 580
telemt_me_idle_close_by_peer_total 580
telemt_me_route_drop_no_conn_total 2966657
telemt_me_route_drop_channel_closed_total 1230
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2811045
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 642
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 729
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
telemt_desync_total 12001
telemt_desync_full_logged_total 3762
telemt_desync_suppressed_total 8239
telemt_desync_frames_bucket_total{bucket="1_2"} 3236
telemt_desync_frames_bucket_total{bucket="3_10"} 4381
telemt_desync_frames_bucket_total{bucket="gt_10"} 4384
telemt_pool_swap_total 104
telemt_pool_force_close_total 3200
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 635
telemt_me_draining_writers_reap_progress_total 31557
telemt_me_writer_removed_unexpected_total 560
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2304
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29481
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3144
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28357
telemt_me_writer_teardown_success_total{mode="normal"} 31785
telemt_me_writer_teardown_noop_total 31568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63353
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 373.844367
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63353
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 635
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 503
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2800342
telemt_user_connections_current{user="hello"} 900
telemt_user_octets_from_client{user="hello"} 40042339632 (37.29 GB)
telemt_user_octets_to_client{user="hello"} 761373755440 (709.08 GB)
telemt_user_unique_ips_current{user="hello"} 372
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 107115.9 (29h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3961450
telemt_connections_bad_total 360621
telemt_connections_current 410
telemt_connections_me_current 410
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100019
telemt_upstream_connect_attempt_total 65388
telemt_upstream_connect_success_total 64591
telemt_upstream_connect_fail_total 705
telemt_upstream_connect_attempts_per_request{bucket="1"} 65296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 705
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9491
telemt_me_reconnect_success_total 3482
telemt_me_reader_eof_total 3493
telemt_me_idle_close_by_peer_total 3493
telemt_me_route_drop_no_conn_total 3636706
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3150638
telemt_me_endpoint_quarantine_total 803
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 828
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
telemt_me_writers_active_current 47
telemt_desync_total 12859
telemt_desync_full_logged_total 7203
telemt_desync_suppressed_total 5656
telemt_desync_frames_bucket_total{bucket="1_2"} 2911
telemt_desync_frames_bucket_total{bucket="3_10"} 5044
telemt_desync_frames_bucket_total{bucket="gt_10"} 4904
telemt_pool_swap_total 98
telemt_pool_force_close_total 2959
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 243
telemt_me_draining_writers_reap_progress_total 43107
telemt_me_writer_removed_unexpected_total 3429
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5877
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40686
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2501
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40148
telemt_me_writer_teardown_success_total{mode="normal"} 46563
telemt_me_writer_teardown_noop_total 43108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89671
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.529615
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89671
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 243
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 3142
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 3162243
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 42777729293 (39.84 GB)
telemt_user_octets_to_client{user="hello"} 781588897372 (727.91 GB)
telemt_user_msgs_from_client{user="hello"} 45221
telemt_user_msgs_to_client{user="hello"} 178309
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 181975.9 (50h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16242895
telemt_connections_bad_total 1624639
telemt_connections_current 1051
telemt_connections_me_current 1051
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396444
telemt_upstream_connect_attempt_total 80982
telemt_upstream_connect_success_total 80882
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 80899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39262
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1704
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2918
telemt_me_reconnect_success_total 1515
telemt_me_reader_eof_total 1461
telemt_me_idle_close_by_peer_total 1459
telemt_me_route_drop_no_conn_total 14034205
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12909462
telemt_me_endpoint_quarantine_total 1180
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1361
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 53360
telemt_desync_full_logged_total 16924
telemt_desync_suppressed_total 36436
telemt_desync_frames_bucket_total{bucket="1_2"} 11861
telemt_desync_frames_bucket_total{bucket="3_10"} 20781
telemt_desync_frames_bucket_total{bucket="gt_10"} 20718
telemt_pool_swap_total 197
telemt_pool_force_close_total 6531
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1048
telemt_me_draining_writers_reap_progress_total 60687
telemt_me_writer_removed_unexpected_total 1409
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5257
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56110
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6061
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54156
telemt_me_writer_teardown_success_total{mode="normal"} 61367
telemt_me_writer_teardown_noop_total 60740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122107
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.390364
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122107
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1048
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 1309
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 12909681
telemt_user_connections_current{user="hello"} 1051
telemt_user_octets_from_client{user="hello"} 190469809925 (177.39 GB)
telemt_user_octets_to_client{user="hello"} 3469493241131 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 503
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 181977.1 (50h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11789490
telemt_connections_bad_total 1214970
telemt_connections_current 652
telemt_connections_me_current 652
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344083
telemt_upstream_connect_attempt_total 95427
telemt_upstream_connect_success_total 94114
telemt_upstream_connect_fail_total 865
telemt_upstream_connect_attempts_per_request{bucket="1"} 94979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39187
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3797
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 865
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4336
telemt_me_reconnect_success_total 1826
telemt_me_reader_eof_total 1688
telemt_me_idle_close_by_peer_total 1688
telemt_me_route_drop_no_conn_total 4546401
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8762638
telemt_me_endpoint_quarantine_total 1190
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1382
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_desync_total 38627
telemt_desync_full_logged_total 12999
telemt_desync_suppressed_total 25628
telemt_desync_frames_bucket_total{bucket="1_2"} 9551
telemt_desync_frames_bucket_total{bucket="3_10"} 14844
telemt_desync_frames_bucket_total{bucket="gt_10"} 14232
telemt_pool_swap_total 194
telemt_pool_force_close_total 5899
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 59019
telemt_me_writer_removed_unexpected_total 1722
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5384
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55209
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5387
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53120
telemt_me_writer_teardown_success_total{mode="normal"} 60593
telemt_me_writer_teardown_noop_total 59044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 119552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119637
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.275507
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119637
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1557
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 8700458
telemt_user_connections_current{user="hello"} 652
telemt_user_octets_from_client{user="hello"} 217418169344 (202.49 GB)
telemt_user_octets_to_client{user="hello"} 3941770801623 (3.59 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 181941.1 (50h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10985800
telemt_connections_bad_total 959668
telemt_connections_current 489
telemt_connections_me_current 489
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345089
telemt_upstream_connect_attempt_total 79479
telemt_upstream_connect_success_total 77927
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 78132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37569
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2009
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5655
telemt_me_reconnect_success_total 2303
telemt_me_reader_eof_total 2043
telemt_me_idle_close_by_peer_total 2042
telemt_me_route_drop_no_conn_total 5328696
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8312939
telemt_me_endpoint_quarantine_total 1268
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1338
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_desync_total 37898
telemt_desync_full_logged_total 12567
telemt_desync_suppressed_total 25331
telemt_desync_frames_bucket_total{bucket="1_2"} 9570
telemt_desync_frames_bucket_total{bucket="3_10"} 14495
telemt_desync_frames_bucket_total{bucket="gt_10"} 13833
telemt_pool_swap_total 190
telemt_pool_force_close_total 5809
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 736
telemt_me_draining_writers_reap_progress_total 59185
telemt_me_writer_removed_unexpected_total 2197
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6096
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55214
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5238
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53376
telemt_me_writer_teardown_success_total{mode="normal"} 61310
telemt_me_writer_teardown_noop_total 59256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 120427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120566
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.644835
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120566
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 736
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 1994
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8304941
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 192283618763 (179.08 GB)
telemt_user_octets_to_client{user="hello"} 3455167027413 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 52221.4 (14h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11128306
telemt_connections_bad_total 667591
telemt_connections_current 1067
telemt_connections_me_current 1067
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 257698
telemt_upstream_connect_attempt_total 53821
telemt_upstream_connect_success_total 51032
telemt_upstream_connect_fail_total 1891
telemt_upstream_connect_attempts_per_request{bucket="1"} 52923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17081
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5999
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1891
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7338
telemt_me_reconnect_success_total 1123
telemt_me_reader_eof_total 694
telemt_me_idle_close_by_peer_total 693
telemt_me_route_drop_no_conn_total 25271126
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9243071
telemt_me_endpoint_quarantine_total 366
telemt_me_single_endpoint_outage_enter_total 84
telemt_me_single_endpoint_outage_exit_total 84
telemt_me_single_endpoint_outage_reconnect_attempt_total 157
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 157
telemt_me_single_endpoint_shadow_rotate_total 413
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_me_writers_warm_current 3
telemt_desync_total 15975
telemt_desync_full_logged_total 4280
telemt_desync_suppressed_total 11695
telemt_desync_frames_bucket_total{bucket="1_2"} 3052
telemt_desync_frames_bucket_total{bucket="3_10"} 6452
telemt_desync_frames_bucket_total{bucket="gt_10"} 6471
telemt_pool_swap_total 53
telemt_pool_force_close_total 1815
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 464
telemt_me_draining_writers_reap_progress_total 15660
telemt_me_writer_removed_unexpected_total 1012
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2229
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14395
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1508
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13845
telemt_me_writer_teardown_success_total{mode="normal"} 16624
telemt_me_writer_teardown_noop_total 15679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32303
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.946327
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32303
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 464
telemt_me_refill_failed_total 331
telemt_me_writer_restored_same_endpoint_total 724
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 9268574
telemt_user_connections_current{user="hello"} 1067
telemt_user_octets_from_client{user="hello"} 86250112090 (80.33 GB)
telemt_user_octets_to_client{user="hello"} 580762844309 (540.88 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 181948.0 (50h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10918392
telemt_connections_bad_total 933086
telemt_connections_current 745
telemt_connections_me_current 745
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 240680
telemt_upstream_connect_attempt_total 108309
telemt_upstream_connect_success_total 107182
telemt_upstream_connect_fail_total 955
telemt_upstream_connect_attempts_per_request{bucket="1"} 108137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41098
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 955
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72779
telemt_me_reconnect_success_total 2992
telemt_me_reader_eof_total 2684
telemt_me_idle_close_by_peer_total 2682
telemt_me_route_drop_no_conn_total 5249335
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8620072
telemt_me_endpoint_quarantine_total 1213
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 43
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 43
telemt_me_single_endpoint_shadow_rotate_total 1365
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 46005
telemt_desync_full_logged_total 15744
telemt_desync_suppressed_total 30261
telemt_desync_frames_bucket_total{bucket="1_2"} 9331
telemt_desync_frames_bucket_total{bucket="3_10"} 17607
telemt_desync_frames_bucket_total{bucket="gt_10"} 19067
telemt_pool_swap_total 186
telemt_pool_force_close_total 5503
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 656
telemt_me_draining_writers_reap_progress_total 63287
telemt_me_writer_removed_unexpected_total 2715
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6612
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59423
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4754
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57784
telemt_me_writer_teardown_success_total{mode="normal"} 66035
telemt_me_writer_teardown_noop_total 63288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 127189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 128587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 129006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 129279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 129313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 129316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 129316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 129319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 129323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 129323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 129323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 129323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 129323
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.191058
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 129323
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 656
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2523
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8623137
telemt_user_connections_current{user="hello"} 745
telemt_user_octets_from_client{user="hello"} 194011644861 (180.69 GB)
telemt_user_octets_to_client{user="hello"} 3292926953980 (2.99 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 352
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 118784.1 (32h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11593555
telemt_connections_bad_total 464095
telemt_connections_current 631
telemt_connections_me_current 631
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4748468
telemt_upstream_connect_attempt_total 56416
telemt_upstream_connect_success_total 56000
telemt_upstream_connect_fail_total 405
telemt_upstream_connect_attempts_per_request{bucket="1"} 56405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 405
telemt_me_reconnect_attempts_total 48733
telemt_me_reconnect_success_total 1749
telemt_me_reader_eof_total 1414
telemt_me_idle_close_by_peer_total 1413
telemt_me_route_drop_no_conn_total 4077737
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5575153
telemt_me_endpoint_quarantine_total 775
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 902
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
telemt_me_writers_active_current 47
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31332
telemt_desync_full_logged_total 10671
telemt_desync_suppressed_total 20661
telemt_desync_frames_bucket_total{bucket="1_2"} 6221
telemt_desync_frames_bucket_total{bucket="3_10"} 12362
telemt_desync_frames_bucket_total{bucket="gt_10"} 12749
telemt_pool_swap_total 125
telemt_pool_force_close_total 3746
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 370
telemt_me_draining_writers_reap_progress_total 42320
telemt_me_writer_removed_unexpected_total 1467
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3588
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40240
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3305
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38574
telemt_me_writer_teardown_success_total{mode="normal"} 43828
telemt_me_writer_teardown_noop_total 42327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86155
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.641240
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86155
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 370
telemt_me_refill_failed_total 2730
telemt_me_writer_restored_same_endpoint_total 1553
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5567762
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 118728035360 (110.57 GB)
telemt_user_octets_to_client{user="hello"} 2152571548454 (1.96 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 99754.7 (27h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1477770
telemt_connections_bad_total 36408
telemt_connections_current 496
telemt_connections_me_current 496
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29442
telemt_upstream_connect_attempt_total 46622
telemt_upstream_connect_success_total 46475
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 46594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 776
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2137
telemt_me_reconnect_success_total 873
telemt_me_reader_eof_total 853
telemt_me_idle_close_by_peer_total 853
telemt_me_route_drop_no_conn_total 509119
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1311953
telemt_me_endpoint_quarantine_total 805
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 821
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
telemt_me_writers_active_current 43
telemt_desync_total 8316
telemt_desync_full_logged_total 2504
telemt_desync_suppressed_total 5812
telemt_desync_frames_bucket_total{bucket="1_2"} 2111
telemt_desync_frames_bucket_total{bucket="3_10"} 3217
telemt_desync_frames_bucket_total{bucket="gt_10"} 2988
telemt_pool_swap_total 107
telemt_pool_force_close_total 2783
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 154
telemt_me_draining_writers_reap_progress_total 39135
telemt_me_writer_removed_unexpected_total 825
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3072
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36923
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2695
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36352
telemt_me_writer_teardown_success_total{mode="normal"} 39995
telemt_me_writer_teardown_noop_total 39139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79134
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.035616
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79134
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 154
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 741
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 1307829
telemt_user_connections_current{user="hello"} 496
telemt_user_octets_from_client{user="hello"} 25617865885 (23.86 GB)
telemt_user_octets_to_client{user="hello"} 559278951311 (520.87 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 181952.4 (50h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13236066
telemt_connections_bad_total 1572196
telemt_connections_current 801
telemt_connections_me_current 801
telemt_handshake_timeouts_total 381230
telemt_upstream_connect_attempt_total 70087
telemt_upstream_connect_success_total 69746
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 69951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35085
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2786
telemt_me_reconnect_success_total 1410
telemt_me_reader_eof_total 1389
telemt_me_idle_close_by_peer_total 1389
telemt_me_route_drop_no_conn_total 4475222
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10003604
telemt_me_endpoint_quarantine_total 1261
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1369
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
telemt_me_writers_active_current 42
telemt_desync_total 41791
telemt_desync_full_logged_total 13643
telemt_desync_suppressed_total 28148
telemt_desync_frames_bucket_total{bucket="1_2"} 10039
telemt_desync_frames_bucket_total{bucket="3_10"} 15377
telemt_desync_frames_bucket_total{bucket="gt_10"} 16375
telemt_pool_swap_total 202
telemt_pool_force_close_total 5456
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 667
telemt_me_draining_writers_reap_progress_total 63252
telemt_me_writer_removed_unexpected_total 1333
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5064
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59567
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5282
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57796
telemt_me_writer_teardown_success_total{mode="normal"} 64631
telemt_me_writer_teardown_noop_total 63254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 127376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 127752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 127885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 127885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 127885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 127885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 127885
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.629405
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 127885
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 667
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1236
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 9970363
telemt_user_connections_current{user="hello"} 801
telemt_user_octets_from_client{user="hello"} 194278139960 (180.94 GB)
telemt_user_octets_to_client{user="hello"} 4420794545000 (4.02 TB)
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 181949.1 (50h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11534189
telemt_connections_bad_total 1320181
telemt_connections_current 567
telemt_connections_me_current 567
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 306708
telemt_upstream_connect_attempt_total 96656
telemt_upstream_connect_success_total 95796
telemt_upstream_connect_fail_total 652
telemt_upstream_connect_attempts_per_request{bucket="1"} 96448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40653
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 652
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10140
telemt_me_reconnect_success_total 2479
telemt_me_reader_eof_total 2308
telemt_me_idle_close_by_peer_total 2307
telemt_me_seq_mismatch_total 88
telemt_me_route_drop_no_conn_total 5635684
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8906624
telemt_me_endpoint_quarantine_total 1428
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 1369
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
telemt_me_writers_active_current 43
telemt_desync_total 41514
telemt_desync_full_logged_total 13330
telemt_desync_suppressed_total 28184
telemt_desync_frames_bucket_total{bucket="1_2"} 10695
telemt_desync_frames_bucket_total{bucket="3_10"} 15268
telemt_desync_frames_bucket_total{bucket="gt_10"} 15551
telemt_pool_swap_total 192
telemt_pool_force_close_total 5250
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 654
telemt_me_draining_writers_reap_progress_total 63110
telemt_me_writer_removed_unexpected_total 2345
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6423
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59112
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4779
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57860
telemt_me_writer_teardown_success_total{mode="normal"} 65535
telemt_me_writer_teardown_noop_total 63115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 128281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 128650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 128650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 128650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 128650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 128650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128650
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.360208
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128650
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 654
telemt_me_refill_failed_total 396
telemt_me_writer_restored_same_endpoint_total 2005
telemt_me_writer_restored_fallback_total 122
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 8912003
telemt_user_connections_current{user="hello"} 567
telemt_user_octets_from_client{user="hello"} 156978152481 (146.20 GB)
telemt_user_octets_to_client{user="hello"} 3468789911947 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 53
```
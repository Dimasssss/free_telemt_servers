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

# Server Metrics 2026-03-23 00:30:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 98631.4 (27h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3465585
telemt_connections_bad_total 298625
telemt_connections_current 849
telemt_connections_me_current 849
telemt_handshake_timeouts_total 108342
telemt_upstream_connect_attempt_total 36549
telemt_upstream_connect_success_total 36548
telemt_upstream_connect_attempts_per_request{bucket="1"} 36548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1384
telemt_me_reconnect_success_total 590
telemt_me_reader_eof_total 606
telemt_me_idle_close_by_peer_total 606
telemt_me_route_drop_no_conn_total 2977799
telemt_me_route_drop_channel_closed_total 1231
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2869969
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 682
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 768
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
telemt_me_writers_active_current 44
telemt_desync_total 12352
telemt_desync_full_logged_total 3865
telemt_desync_suppressed_total 8487
telemt_desync_frames_bucket_total{bucket="1_2"} 3336
telemt_desync_frames_bucket_total{bucket="3_10"} 4493
telemt_desync_frames_bucket_total{bucket="gt_10"} 4523
telemt_pool_swap_total 109
telemt_pool_force_close_total 3375
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 650
telemt_me_draining_writers_reap_progress_total 33460
telemt_me_writer_removed_unexpected_total 585
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2433
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31259
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3319
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30085
telemt_me_writer_teardown_success_total{mode="normal"} 33692
telemt_me_writer_teardown_noop_total 33471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67163
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 376.106636
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67163
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 650
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 528
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2859156
telemt_user_connections_current{user="hello"} 849
telemt_user_octets_from_client{user="hello"} 40876085660 (38.07 GB)
telemt_user_octets_to_client{user="hello"} 783475066612 (729.67 GB)
telemt_user_unique_ips_current{user="hello"} 417
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 111997.6 (31h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3987045
telemt_connections_bad_total 364729
telemt_connections_current 130
telemt_connections_me_current 130
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100422
telemt_upstream_connect_attempt_total 69591
telemt_upstream_connect_success_total 68756
telemt_upstream_connect_fail_total 742
telemt_upstream_connect_attempts_per_request{bucket="1"} 69498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30138
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 742
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9911
telemt_me_reconnect_success_total 3577
telemt_me_reader_eof_total 3574
telemt_me_idle_close_by_peer_total 3574
telemt_me_route_drop_no_conn_total 3639812
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3169990
telemt_me_endpoint_quarantine_total 877
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 44
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 44
telemt_me_single_endpoint_shadow_rotate_total 873
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
telemt_me_writers_active_current 45
telemt_desync_total 12932
telemt_desync_full_logged_total 7249
telemt_desync_suppressed_total 5683
telemt_desync_frames_bucket_total{bucket="1_2"} 2936
telemt_desync_frames_bucket_total{bucket="3_10"} 5069
telemt_desync_frames_bucket_total{bucket="gt_10"} 4927
telemt_pool_swap_total 104
telemt_pool_force_close_total 3031
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 252
telemt_me_draining_writers_reap_progress_total 45768
telemt_me_writer_removed_unexpected_total 3506
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6096
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43209
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2573
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42737
telemt_me_writer_teardown_success_total{mode="normal"} 49305
telemt_me_writer_teardown_noop_total 45769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95074
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.579474
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95074
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 252
telemt_me_refill_failed_total 243
telemt_me_writer_restored_same_endpoint_total 3203
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 3182828
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 42940656443 (39.99 GB)
telemt_user_octets_to_client{user="hello"} 789280644983 (735.07 GB)
telemt_user_msgs_from_client{user="hello"} 48526
telemt_user_msgs_to_client{user="hello"} 183196
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 186857.5 (51h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16307679
telemt_connections_bad_total 1643408
telemt_connections_current 787
telemt_connections_me_current 787
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396961
telemt_upstream_connect_attempt_total 83508
telemt_upstream_connect_success_total 83404
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 83421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40709
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1714
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2976
telemt_me_reconnect_success_total 1555
telemt_me_reader_eof_total 1502
telemt_me_idle_close_by_peer_total 1500
telemt_me_route_drop_no_conn_total 14041971
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12953424
telemt_me_endpoint_quarantine_total 1227
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1404
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 53668
telemt_desync_full_logged_total 17028
telemt_desync_suppressed_total 36640
telemt_desync_frames_bucket_total{bucket="1_2"} 11950
telemt_desync_frames_bucket_total{bucket="3_10"} 20930
telemt_desync_frames_bucket_total{bucket="gt_10"} 20788
telemt_pool_swap_total 202
telemt_pool_force_close_total 6661
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1057
telemt_me_draining_writers_reap_progress_total 63056
telemt_me_writer_removed_unexpected_total 1447
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5408
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58369
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6191
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56395
telemt_me_writer_teardown_success_total{mode="normal"} 63777
telemt_me_writer_teardown_noop_total 63109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 123558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 125225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 126882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 126884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 126886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 126886
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.575907
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 126886
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1057
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1344
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 12953482
telemt_user_connections_current{user="hello"} 787
telemt_user_octets_from_client{user="hello"} 190945849589 (177.83 GB)
telemt_user_octets_to_client{user="hello"} 3483801093299 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 403
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 186858.9 (51h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11849375
telemt_connections_bad_total 1227777
telemt_connections_current 589
telemt_connections_me_current 589
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344466
telemt_upstream_connect_attempt_total 97858
telemt_upstream_connect_success_total 96539
telemt_upstream_connect_fail_total 866
telemt_upstream_connect_attempts_per_request{bucket="1"} 97405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40571
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3800
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 866
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4390
telemt_me_reconnect_success_total 1859
telemt_me_reader_eof_total 1724
telemt_me_idle_close_by_peer_total 1724
telemt_me_route_drop_no_conn_total 4552454
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8800114
telemt_me_endpoint_quarantine_total 1233
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1424
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
telemt_me_writers_active_current 45
telemt_desync_total 38700
telemt_desync_full_logged_total 13026
telemt_desync_suppressed_total 25674
telemt_desync_frames_bucket_total{bucket="1_2"} 9588
telemt_desync_frames_bucket_total{bucket="3_10"} 14863
telemt_desync_frames_bucket_total{bucket="gt_10"} 14249
telemt_pool_swap_total 199
telemt_pool_force_close_total 6022
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 708
telemt_me_draining_writers_reap_progress_total 61264
telemt_me_writer_removed_unexpected_total 1755
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5506
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57368
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5510
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55242
telemt_me_writer_teardown_success_total{mode="normal"} 62874
telemt_me_writer_teardown_noop_total 61289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 124153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 124155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 124161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 124163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 124163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 124163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 124163
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.392744
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 124163
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 708
telemt_me_refill_failed_total 136
telemt_me_writer_restored_same_endpoint_total 1587
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 8737882
telemt_user_connections_current{user="hello"} 589
telemt_user_octets_from_client{user="hello"} 217688282268 (202.74 GB)
telemt_user_octets_to_client{user="hello"} 3956849018727 (3.60 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 186823.2 (51h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11036411
telemt_connections_bad_total 971834
telemt_connections_current 448
telemt_connections_me_current 448
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345472
telemt_upstream_connect_attempt_total 82160
telemt_upstream_connect_success_total 80602
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 80807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39054
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5714
telemt_me_reconnect_success_total 2355
telemt_me_reader_eof_total 2099
telemt_me_idle_close_by_peer_total 2098
telemt_me_route_drop_no_conn_total 5334393
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8343279
telemt_me_endpoint_quarantine_total 1308
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1380
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
telemt_me_writers_active_current 49
telemt_desync_total 38059
telemt_desync_full_logged_total 12619
telemt_desync_suppressed_total 25440
telemt_desync_frames_bucket_total{bucket="1_2"} 9611
telemt_desync_frames_bucket_total{bucket="3_10"} 14556
telemt_desync_frames_bucket_total{bucket="gt_10"} 13892
telemt_pool_swap_total 195
telemt_pool_force_close_total 5922
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 738
telemt_me_draining_writers_reap_progress_total 61619
telemt_me_writer_removed_unexpected_total 2249
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6266
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57534
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5351
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55697
telemt_me_writer_teardown_success_total{mode="normal"} 63800
telemt_me_writer_teardown_noop_total 61690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 123335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 124408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 125009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 125223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125490
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.686958
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125490
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 738
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 2045
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8335249
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 192589019043 (179.36 GB)
telemt_user_octets_to_client{user="hello"} 3464934354125 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 57103.0 (15h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11208049
telemt_connections_bad_total 668597
telemt_connections_current 950
telemt_connections_me_current 950
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 267370
telemt_upstream_connect_attempt_total 56097
telemt_upstream_connect_success_total 53228
telemt_upstream_connect_fail_total 1907
telemt_upstream_connect_attempts_per_request{bucket="1"} 55135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18250
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6005
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1907
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7479
telemt_me_reconnect_success_total 1177
telemt_me_reader_eof_total 750
telemt_me_idle_close_by_peer_total 749
telemt_me_route_drop_no_conn_total 25286043
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9304353
telemt_me_endpoint_quarantine_total 426
telemt_me_single_endpoint_outage_enter_total 85
telemt_me_single_endpoint_outage_exit_total 85
telemt_me_single_endpoint_outage_reconnect_attempt_total 158
telemt_me_single_endpoint_outage_reconnect_success_total 42
telemt_me_single_endpoint_quarantine_bypass_total 158
telemt_me_single_endpoint_shadow_rotate_total 452
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
telemt_desync_total 16271
telemt_desync_full_logged_total 4420
telemt_desync_suppressed_total 11851
telemt_desync_frames_bucket_total{bucket="1_2"} 3086
telemt_desync_frames_bucket_total{bucket="3_10"} 6617
telemt_desync_frames_bucket_total{bucket="gt_10"} 6568
telemt_pool_swap_total 59
telemt_pool_force_close_total 1961
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 475
telemt_me_draining_writers_reap_progress_total 17665
telemt_me_writer_removed_unexpected_total 1065
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2402
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16270
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1654
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15704
telemt_me_writer_teardown_success_total{mode="normal"} 18672
telemt_me_writer_teardown_noop_total 17684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36356
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.613911
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36356
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 475
telemt_me_refill_failed_total 336
telemt_me_writer_restored_same_endpoint_total 768
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 9329686
telemt_user_connections_current{user="hello"} 950
telemt_user_octets_from_client{user="hello"} 86867875714 (80.90 GB)
telemt_user_octets_to_client{user="hello"} 600817266293 (559.55 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 404
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 186829.6 (51h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10969594
telemt_connections_bad_total 942559
telemt_connections_current 718
telemt_connections_me_current 718
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241847
telemt_upstream_connect_attempt_total 111086
telemt_upstream_connect_success_total 109940
telemt_upstream_connect_fail_total 973
telemt_upstream_connect_attempts_per_request{bucket="1"} 110913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42604
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 973
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72864
telemt_me_reconnect_success_total 3059
telemt_me_reader_eof_total 2747
telemt_me_idle_close_by_peer_total 2745
telemt_me_route_drop_no_conn_total 5257891
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8658713
telemt_me_endpoint_quarantine_total 1254
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1410
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
telemt_me_writers_active_current 47
telemt_desync_total 46174
telemt_desync_full_logged_total 15806
telemt_desync_suppressed_total 30368
telemt_desync_frames_bucket_total{bucket="1_2"} 9380
telemt_desync_frames_bucket_total{bucket="3_10"} 17675
telemt_desync_frames_bucket_total{bucket="gt_10"} 19119
telemt_pool_swap_total 191
telemt_pool_force_close_total 5627
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 65810
telemt_me_writer_removed_unexpected_total 2776
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6775
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61846
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4878
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60183
telemt_me_writer_teardown_success_total{mode="normal"} 68621
telemt_me_writer_teardown_noop_total 65811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 134388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 134425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 134425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 134428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 134432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 134432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 134432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 134432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 134432
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.228160
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 134432
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2583
telemt_me_writer_restored_fallback_total 49
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8661745
telemt_user_connections_current{user="hello"} 718
telemt_user_octets_from_client{user="hello"} 194441972905 (181.09 GB)
telemt_user_octets_to_client{user="hello"} 3307719363512 (3.01 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 340
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 123665.9 (34h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11667834
telemt_connections_bad_total 476756
telemt_connections_current 536
telemt_connections_me_current 536
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4759946
telemt_upstream_connect_attempt_total 59312
telemt_upstream_connect_success_total 58880
telemt_upstream_connect_fail_total 421
telemt_upstream_connect_attempts_per_request{bucket="1"} 59301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27044
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 421
telemt_me_reconnect_attempts_total 48865
telemt_me_reconnect_success_total 1796
telemt_me_reader_eof_total 1467
telemt_me_idle_close_by_peer_total 1466
telemt_me_route_drop_no_conn_total 4084241
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5606236
telemt_me_endpoint_quarantine_total 836
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 947
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
telemt_desync_total 31501
telemt_desync_full_logged_total 10734
telemt_desync_suppressed_total 20767
telemt_desync_frames_bucket_total{bucket="1_2"} 6271
telemt_desync_frames_bucket_total{bucket="3_10"} 12423
telemt_desync_frames_bucket_total{bucket="gt_10"} 12807
telemt_pool_swap_total 131
telemt_pool_force_close_total 3857
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 44995
telemt_me_writer_removed_unexpected_total 1518
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3733
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42823
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3416
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41138
telemt_me_writer_teardown_success_total{mode="normal"} 46556
telemt_me_writer_teardown_noop_total 45002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91558
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.681332
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91558
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 2735
telemt_me_writer_restored_same_endpoint_total 1593
telemt_me_writer_restored_fallback_total 26
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5598801
telemt_user_connections_current{user="hello"} 536
telemt_user_octets_from_client{user="hello"} 118976102680 (110.81 GB)
telemt_user_octets_to_client{user="hello"} 2166167485438 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 104636.5 (29h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1508773
telemt_connections_bad_total 36692
telemt_connections_current 387
telemt_connections_me_current 387
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 30251
telemt_upstream_connect_attempt_total 49071
telemt_upstream_connect_success_total 48915
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 49043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 785
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2207
telemt_me_reconnect_success_total 891
telemt_me_reader_eof_total 875
telemt_me_idle_close_by_peer_total 875
telemt_me_route_drop_no_conn_total 515697
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1340655
telemt_me_endpoint_quarantine_total 854
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 862
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 8768
telemt_desync_full_logged_total 2586
telemt_desync_suppressed_total 6182
telemt_desync_frames_bucket_total{bucket="1_2"} 2397
telemt_desync_frames_bucket_total{bucket="3_10"} 3361
telemt_desync_frames_bucket_total{bucket="gt_10"} 3010
telemt_pool_swap_total 113
telemt_pool_force_close_total 2910
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 163
telemt_me_draining_writers_reap_progress_total 41418
telemt_me_writer_removed_unexpected_total 845
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3201
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39099
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2822
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38508
telemt_me_writer_teardown_success_total{mode="normal"} 42300
telemt_me_writer_teardown_noop_total 41422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83722
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.223131
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83722
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 163
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 756
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1336469
telemt_user_connections_current{user="hello"} 387
telemt_user_octets_from_client{user="hello"} 25854517989 (24.08 GB)
telemt_user_octets_to_client{user="hello"} 572356566855 (533.05 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 186834.1 (51h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13308201
telemt_connections_bad_total 1600248
telemt_connections_current 650
telemt_connections_me_current 650
telemt_handshake_timeouts_total 388190
telemt_upstream_connect_attempt_total 72997
telemt_upstream_connect_success_total 72650
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 72861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2922
telemt_me_reconnect_success_total 1457
telemt_me_reader_eof_total 1443
telemt_me_idle_close_by_peer_total 1443
telemt_me_route_drop_no_conn_total 4480579
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10033918
telemt_me_endpoint_quarantine_total 1311
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1410
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
telemt_desync_total 42003
telemt_desync_full_logged_total 13713
telemt_desync_suppressed_total 28290
telemt_desync_frames_bucket_total{bucket="1_2"} 10149
telemt_desync_frames_bucket_total{bucket="3_10"} 15437
telemt_desync_frames_bucket_total{bucket="gt_10"} 16417
telemt_pool_swap_total 207
telemt_pool_force_close_total 5550
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 65950
telemt_me_writer_removed_unexpected_total 1381
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5221
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62162
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5376
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60400
telemt_me_writer_teardown_success_total{mode="normal"} 67383
telemt_me_writer_teardown_noop_total 65952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 133322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 133335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 133335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 133335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 133335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 133335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 133335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 133335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 133335
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.748985
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 133335
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1277
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 10000638
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 194561275832 (181.20 GB)
telemt_user_octets_to_client{user="hello"} 4434872696396 (4.03 TB)
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 186830.8 (51h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11613604
telemt_connections_bad_total 1349823
telemt_connections_current 584
telemt_connections_me_current 584
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 310641
telemt_upstream_connect_attempt_total 99747
telemt_upstream_connect_success_total 98866
telemt_upstream_connect_fail_total 673
telemt_upstream_connect_attempts_per_request{bucket="1"} 99539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42250
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 673
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10358
telemt_me_reconnect_success_total 2551
telemt_me_reader_eof_total 2367
telemt_me_idle_close_by_peer_total 2366
telemt_me_seq_mismatch_total 95
telemt_me_route_drop_no_conn_total 5648032
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8944134
telemt_me_endpoint_quarantine_total 1497
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 1414
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 41723
telemt_desync_full_logged_total 13427
telemt_desync_suppressed_total 28296
telemt_desync_frames_bucket_total{bucket="1_2"} 10756
telemt_desync_frames_bucket_total{bucket="3_10"} 15343
telemt_desync_frames_bucket_total{bucket="gt_10"} 15624
telemt_pool_swap_total 197
telemt_pool_force_close_total 5343
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 662
telemt_me_draining_writers_reap_progress_total 65995
telemt_me_writer_removed_unexpected_total 2408
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6581
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61905
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4872
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60652
telemt_me_writer_teardown_success_total{mode="normal"} 68486
telemt_me_writer_teardown_noop_total 66000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 134436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 134486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 134486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 134486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 134486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 134486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 134486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 134486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 134486
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.449977
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 134486
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 662
telemt_me_refill_failed_total 404
telemt_me_writer_restored_same_endpoint_total 2059
telemt_me_writer_restored_fallback_total 130
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 8947979
telemt_user_connections_current{user="hello"} 584
telemt_user_octets_from_client{user="hello"} 157208217349 (146.41 GB)
telemt_user_octets_to_client{user="hello"} 3483591380851 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 62
```
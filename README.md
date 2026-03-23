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

# Server Metrics 2026-03-23 04:19:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 112366.6 (31h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3828411
telemt_connections_bad_total 375804
telemt_connections_current 1394
telemt_connections_me_current 1394
telemt_handshake_timeouts_total 127633
telemt_upstream_connect_attempt_total 41860
telemt_upstream_connect_success_total 41859
telemt_upstream_connect_attempts_per_request{bucket="1"} 41859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27194
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 93
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1453
telemt_me_reconnect_success_total 651
telemt_me_reader_eof_total 667
telemt_me_idle_close_by_peer_total 667
telemt_me_route_drop_no_conn_total 3033012
telemt_me_route_drop_channel_closed_total 1241
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3117934
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 795
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 877
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
telemt_me_writers_active_current 48
telemt_desync_total 13369
telemt_desync_full_logged_total 4259
telemt_desync_suppressed_total 9110
telemt_desync_frames_bucket_total{bucket="1_2"} 3519
telemt_desync_frames_bucket_total{bucket="3_10"} 4910
telemt_desync_frames_bucket_total{bucket="gt_10"} 4940
telemt_pool_swap_total 124
telemt_pool_force_close_total 3770
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 685
telemt_me_draining_writers_reap_progress_total 38335
telemt_me_writer_removed_unexpected_total 644
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2735
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35892
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3714
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34565
telemt_me_writer_teardown_success_total{mode="normal"} 38627
telemt_me_writer_teardown_noop_total 38346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76973
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 382.972412
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76973
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 685
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 584
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 3106570
telemt_user_connections_current{user="hello"} 1394
telemt_user_octets_from_client{user="hello"} 43802220696 (40.79 GB)
telemt_user_octets_to_client{user="hello"} 846280296652 (788.16 GB)
telemt_user_unique_ips_current{user="hello"} 538
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 125732.5 (34h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4087407
telemt_connections_bad_total 381124
telemt_connections_current 674
telemt_connections_me_current 674
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 103170
telemt_upstream_connect_attempt_total 78739
telemt_upstream_connect_success_total 77804
telemt_upstream_connect_fail_total 828
telemt_upstream_connect_attempts_per_request{bucket="1"} 78632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 828
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10653
telemt_me_reconnect_success_total 3790
telemt_me_reader_eof_total 3771
telemt_me_idle_close_by_peer_total 3771
telemt_me_route_drop_no_conn_total 3655202
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3244740
telemt_me_endpoint_quarantine_total 1016
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 51
telemt_me_single_endpoint_outage_exit_total 51
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 990
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
telemt_me_writers_active_current 47
telemt_desync_total 13292
telemt_desync_full_logged_total 7479
telemt_desync_suppressed_total 5813
telemt_desync_frames_bucket_total{bucket="1_2"} 3024
telemt_desync_frames_bucket_total{bucket="3_10"} 5221
telemt_desync_frames_bucket_total{bucket="gt_10"} 5047
telemt_pool_swap_total 119
telemt_pool_force_close_total 3292
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 258
telemt_me_draining_writers_reap_progress_total 52455
telemt_me_writer_removed_unexpected_total 3694
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6659
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49530
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2834
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49163
telemt_me_writer_teardown_success_total{mode="normal"} 56189
telemt_me_writer_teardown_noop_total 52456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108645
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.756225
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108645
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 258
telemt_me_refill_failed_total 270
telemt_me_writer_restored_same_endpoint_total 3356
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 307
telemt_user_connections_total{user="hello"} 3259212
telemt_user_connections_current{user="hello"} 674
telemt_user_octets_from_client{user="hello"} 43788310635 (40.78 GB)
telemt_user_octets_to_client{user="hello"} 815086309401 (759.11 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 374
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 200592.5 (55h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16530315
telemt_connections_bad_total 1676217
telemt_connections_current 1511
telemt_connections_me_current 1511
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 402589
telemt_upstream_connect_attempt_total 90344
telemt_upstream_connect_success_total 90237
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 90254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44506
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1730
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3116
telemt_me_reconnect_success_total 1657
telemt_me_reader_eof_total 1612
telemt_me_idle_close_by_peer_total 1610
telemt_me_route_drop_no_conn_total 14081611
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13126428
telemt_me_endpoint_quarantine_total 1352
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1515
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
telemt_me_writers_active_current 45
telemt_desync_total 54619
telemt_desync_full_logged_total 17410
telemt_desync_suppressed_total 37209
telemt_desync_frames_bucket_total{bucket="1_2"} 12187
telemt_desync_frames_bucket_total{bucket="3_10"} 21367
telemt_desync_frames_bucket_total{bucket="gt_10"} 21065
telemt_pool_swap_total 217
telemt_pool_force_close_total 6994
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1081
telemt_me_draining_writers_reap_progress_total 69317
telemt_me_writer_removed_unexpected_total 1548
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5806
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64342
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6524
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62323
telemt_me_writer_teardown_success_total{mode="normal"} 70148
telemt_me_writer_teardown_noop_total 69370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139518
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.249100
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139518
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1081
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 1439
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 13126393
telemt_user_connections_current{user="hello"} 1511
telemt_user_octets_from_client{user="hello"} 198860171441 (185.20 GB)
telemt_user_octets_to_client{user="hello"} 3553652436603 (3.23 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 634
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 200593.8 (55h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12069637
telemt_connections_bad_total 1276608
telemt_connections_current 878
telemt_connections_me_current 878
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 347612
telemt_upstream_connect_attempt_total 104586
telemt_upstream_connect_success_total 103237
telemt_upstream_connect_fail_total 890
telemt_upstream_connect_attempts_per_request{bucket="1"} 104127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44376
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3805
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 890
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4571
telemt_me_reconnect_success_total 1966
telemt_me_reader_eof_total 1833
telemt_me_idle_close_by_peer_total 1833
telemt_me_route_drop_no_conn_total 4581009
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8930642
telemt_me_endpoint_quarantine_total 1367
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1537
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
telemt_me_writers_active_current 46
telemt_desync_total 39273
telemt_desync_full_logged_total 13227
telemt_desync_suppressed_total 26046
telemt_desync_frames_bucket_total{bucket="1_2"} 9732
telemt_desync_frames_bucket_total{bucket="3_10"} 15096
telemt_desync_frames_bucket_total{bucket="gt_10"} 14445
telemt_pool_swap_total 214
telemt_pool_force_close_total 6338
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 717
telemt_me_draining_writers_reap_progress_total 67366
telemt_me_writer_removed_unexpected_total 1860
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5898
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63187
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5826
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61028
telemt_me_writer_teardown_success_total{mode="normal"} 69085
telemt_me_writer_teardown_noop_total 67391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 129705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136476
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.590754
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136476
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 717
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 1683
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 8868309
telemt_user_connections_current{user="hello"} 878
telemt_user_octets_from_client{user="hello"} 218794220912 (203.77 GB)
telemt_user_octets_to_client{user="hello"} 4001132784131 (3.64 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 367
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 200558.6 (55h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11210693
telemt_connections_bad_total 1011089
telemt_connections_current 877
telemt_connections_me_current 877
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 348945
telemt_upstream_connect_attempt_total 89096
telemt_upstream_connect_success_total 87525
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 87730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42964
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2060
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5850
telemt_me_reconnect_success_total 2456
telemt_me_reader_eof_total 2202
telemt_me_idle_close_by_peer_total 2201
telemt_me_route_drop_no_conn_total 5358991
telemt_me_route_drop_channel_closed_total 384
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8446589
telemt_me_endpoint_quarantine_total 1415
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1495
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 70
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
telemt_desync_total 38488
telemt_desync_full_logged_total 12770
telemt_desync_suppressed_total 25718
telemt_desync_frames_bucket_total{bucket="1_2"} 9717
telemt_desync_frames_bucket_total{bucket="3_10"} 14743
telemt_desync_frames_bucket_total{bucket="gt_10"} 14028
telemt_pool_swap_total 210
telemt_pool_force_close_total 6232
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 755
telemt_me_draining_writers_reap_progress_total 67959
telemt_me_writer_removed_unexpected_total 2348
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6655
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63588
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5661
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61727
telemt_me_writer_teardown_success_total{mode="normal"} 70243
telemt_me_writer_teardown_noop_total 68030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138273
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.911765
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138273
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 755
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 2138
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 8438479
telemt_user_connections_current{user="hello"} 877
telemt_user_octets_from_client{user="hello"} 193505744299 (180.22 GB)
telemt_user_octets_to_client{user="hello"} 3506133436961 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 379
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 70838.3 (19h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11486197
telemt_connections_bad_total 674644
telemt_connections_current 1552
telemt_connections_me_current 1552
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 300804
telemt_upstream_connect_attempt_total 64324
telemt_upstream_connect_success_total 60923
telemt_upstream_connect_fail_total 2204
telemt_upstream_connect_attempts_per_request{bucket="1"} 63127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21995
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2204
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8245
telemt_me_reconnect_success_total 1443
telemt_me_reader_eof_total 926
telemt_me_idle_close_by_peer_total 925
telemt_me_route_drop_no_conn_total 25332868
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9519755
telemt_me_endpoint_quarantine_total 547
telemt_me_single_endpoint_outage_enter_total 102
telemt_me_single_endpoint_outage_exit_total 102
telemt_me_single_endpoint_outage_reconnect_attempt_total 200
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 200
telemt_me_single_endpoint_shadow_rotate_total 569
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 16944
telemt_desync_full_logged_total 4677
telemt_desync_suppressed_total 12267
telemt_desync_frames_bucket_total{bucket="1_2"} 3266
telemt_desync_frames_bucket_total{bucket="3_10"} 6912
telemt_desync_frames_bucket_total{bucket="gt_10"} 6766
telemt_pool_swap_total 73
telemt_pool_force_close_total 2286
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 511
telemt_me_draining_writers_reap_progress_total 23388
telemt_me_writer_removed_unexpected_total 1320
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3021
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21638
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1964
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21102
telemt_me_writer_teardown_success_total{mode="normal"} 24659
telemt_me_writer_teardown_noop_total 23407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48066
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.600505
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48066
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 511
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 934
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 9546199
telemt_user_connections_current{user="hello"} 1552
telemt_user_octets_from_client{user="hello"} 89473321234 (83.33 GB)
telemt_user_octets_to_client{user="hello"} 672753753789 (626.55 GB)
telemt_user_msgs_from_client{user="hello"} 69581
telemt_user_msgs_to_client{user="hello"} 60103
telemt_user_unique_ips_current{user="hello"} 600
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 200564.5 (55h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11174729
telemt_connections_bad_total 986122
telemt_connections_current 1094
telemt_connections_me_current 1094
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 246274
telemt_upstream_connect_attempt_total 117953
telemt_upstream_connect_success_total 116729
telemt_upstream_connect_fail_total 1048
telemt_upstream_connect_attempts_per_request{bucket="1"} 117777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46483
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1048
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73418
telemt_me_reconnect_success_total 3220
telemt_me_reader_eof_total 2912
telemt_me_idle_close_by_peer_total 2909
telemt_me_route_drop_no_conn_total 5293251
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8798057
telemt_me_endpoint_quarantine_total 1363
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1524
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 46889
telemt_desync_full_logged_total 16099
telemt_desync_suppressed_total 30790
telemt_desync_frames_bucket_total{bucket="1_2"} 9517
telemt_desync_frames_bucket_total{bucket="3_10"} 17976
telemt_desync_frames_bucket_total{bucket="gt_10"} 19396
telemt_pool_swap_total 206
telemt_pool_force_close_total 5958
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 677
telemt_me_draining_writers_reap_progress_total 71982
telemt_me_writer_removed_unexpected_total 2931
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7199
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67759
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5209
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66024
telemt_me_writer_teardown_success_total{mode="normal"} 74958
telemt_me_writer_teardown_noop_total 71983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 144786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 146205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 146624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 146897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 146931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 146934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 146934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 146937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 146941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 146941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 146941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 146941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 146941
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.338015
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 146941
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 677
telemt_me_refill_failed_total 4318
telemt_me_writer_restored_same_endpoint_total 2712
telemt_me_writer_restored_fallback_total 54
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7369
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 8800864
telemt_user_connections_current{user="hello"} 1094
telemt_user_octets_from_client{user="hello"} 197562319677 (183.99 GB)
telemt_user_octets_to_client{user="hello"} 3366914333200 (3.06 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 464
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 137400.9 (38h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11913971
telemt_connections_bad_total 490330
telemt_connections_current 904
telemt_connections_me_current 904
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4810283
telemt_upstream_connect_attempt_total 66850
telemt_upstream_connect_success_total 66373
telemt_upstream_connect_fail_total 464
telemt_upstream_connect_attempts_per_request{bucket="1"} 66837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 464
telemt_me_reconnect_attempts_total 49239
telemt_me_reconnect_success_total 1938
telemt_me_reader_eof_total 1620
telemt_me_idle_close_by_peer_total 1619
telemt_me_route_drop_no_conn_total 4119591
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5727260
telemt_me_endpoint_quarantine_total 950
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1060
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32206
telemt_desync_full_logged_total 11006
telemt_desync_suppressed_total 21200
telemt_desync_frames_bucket_total{bucket="1_2"} 6461
telemt_desync_frames_bucket_total{bucket="3_10"} 12698
telemt_desync_frames_bucket_total{bucket="gt_10"} 13047
telemt_pool_swap_total 146
telemt_pool_force_close_total 4151
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 389
telemt_me_draining_writers_reap_progress_total 51826
telemt_me_writer_removed_unexpected_total 1660
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4125
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49415
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3707
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47675
telemt_me_writer_teardown_success_total{mode="normal"} 53540
telemt_me_writer_teardown_noop_total 51833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105373
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.768841
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105373
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 389
telemt_me_refill_failed_total 2748
telemt_me_writer_restored_same_endpoint_total 1714
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5719260
telemt_user_connections_current{user="hello"} 904
telemt_user_octets_from_client{user="hello"} 121032321984 (112.72 GB)
telemt_user_octets_to_client{user="hello"} 2229726274230 (2.03 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 370
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 118371.4 (32h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1623834
telemt_connections_bad_total 37182
telemt_connections_current 580
telemt_connections_me_current 580
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 33229
telemt_upstream_connect_attempt_total 55944
telemt_upstream_connect_success_total 55770
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 55916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28661
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 819
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2421
telemt_me_reconnect_success_total 983
telemt_me_reader_eof_total 977
telemt_me_idle_close_by_peer_total 977
telemt_me_route_drop_no_conn_total 541592
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1443294
telemt_me_endpoint_quarantine_total 1001
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 980
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
telemt_desync_total 10107
telemt_desync_full_logged_total 2846
telemt_desync_suppressed_total 7261
telemt_desync_frames_bucket_total{bucket="1_2"} 3205
telemt_desync_frames_bucket_total{bucket="3_10"} 3807
telemt_desync_frames_bucket_total{bucket="gt_10"} 3095
telemt_pool_swap_total 128
telemt_pool_force_close_total 3222
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 176
telemt_me_draining_writers_reap_progress_total 47660
telemt_me_writer_removed_unexpected_total 941
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3595
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45049
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3134
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44438
telemt_me_writer_teardown_success_total{mode="normal"} 48644
telemt_me_writer_teardown_noop_total 47664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96308
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.553774
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96308
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 176
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 841
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 1438956
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 26932199409 (25.08 GB)
telemt_user_octets_to_client{user="hello"} 600330823399 (559.10 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 200569.1 (55h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13469470
telemt_connections_bad_total 1628051
telemt_connections_current 1199
telemt_connections_me_current 1199
telemt_handshake_timeouts_total 393841
telemt_upstream_connect_attempt_total 80663
telemt_upstream_connect_success_total 80303
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 80526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40497
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3160
telemt_me_reconnect_success_total 1594
telemt_me_reader_eof_total 1582
telemt_me_idle_close_by_peer_total 1582
telemt_me_route_drop_no_conn_total 4506268
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10151016
telemt_me_endpoint_quarantine_total 1475
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1522
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
telemt_me_writers_active_current 41
telemt_desync_total 42593
telemt_desync_full_logged_total 13905
telemt_desync_suppressed_total 28688
telemt_desync_frames_bucket_total{bucket="1_2"} 10369
telemt_desync_frames_bucket_total{bucket="3_10"} 15645
telemt_desync_frames_bucket_total{bucket="gt_10"} 16579
telemt_pool_swap_total 222
telemt_pool_force_close_total 5810
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 690
telemt_me_draining_writers_reap_progress_total 73021
telemt_me_writer_removed_unexpected_total 1515
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5627
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68966
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5636
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67211
telemt_me_writer_teardown_success_total{mode="normal"} 74593
telemt_me_writer_teardown_noop_total 73023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 144995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 146724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 147107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 147483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 147603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 147616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 147616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 147616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 147616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 147616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 147616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 147616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 147616
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.898917
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 147616
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 690
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1403
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 10117589
telemt_user_connections_current{user="hello"} 1199
telemt_user_octets_from_client{user="hello"} 195979126776 (182.52 GB)
telemt_user_octets_to_client{user="hello"} 4503429654396 (4.10 TB)
telemt_user_unique_ips_current{user="hello"} 443
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 200565.7 (55h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11787128
telemt_connections_bad_total 1381719
telemt_connections_current 939
telemt_connections_me_current 939
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 316246
telemt_upstream_connect_attempt_total 108446
telemt_upstream_connect_success_total 107515
telemt_upstream_connect_fail_total 723
telemt_upstream_connect_attempts_per_request{bucket="1"} 108238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46134
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2070
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 723
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10971
telemt_me_reconnect_success_total 2720
telemt_me_reader_eof_total 2522
telemt_me_idle_close_by_peer_total 2521
telemt_me_seq_mismatch_total 104
telemt_me_route_drop_no_conn_total 5673932
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9069325
telemt_me_endpoint_quarantine_total 1649
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1527
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_desync_total 42246
telemt_desync_full_logged_total 13606
telemt_desync_suppressed_total 28640
telemt_desync_frames_bucket_total{bucket="1_2"} 10980
telemt_desync_frames_bucket_total{bucket="3_10"} 15520
telemt_desync_frames_bucket_total{bucket="gt_10"} 15746
telemt_pool_swap_total 212
telemt_pool_force_close_total 5573
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 678
telemt_me_draining_writers_reap_progress_total 73312
telemt_me_writer_removed_unexpected_total 2558
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7021
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68946
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5102
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67739
telemt_me_writer_teardown_success_total{mode="normal"} 75967
telemt_me_writer_teardown_noop_total 73317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 146578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 148376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 148915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 149234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 149284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 149284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 149284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 149284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 149284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 149284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 149284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 149284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 149284
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.609977
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 149284
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 678
telemt_me_refill_failed_total 428
telemt_me_writer_restored_same_endpoint_total 2171
telemt_me_writer_restored_fallback_total 140
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 9073851
telemt_user_connections_current{user="hello"} 939
telemt_user_octets_from_client{user="hello"} 158510717848 (147.62 GB)
telemt_user_octets_to_client{user="hello"} 3546411763934 (3.23 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 398
telemt_user_unique_ips_recent_window{user="hello"} 121
```
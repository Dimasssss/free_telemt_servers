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

# Server Metrics 2026-03-22 18:11:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 75929.2 (21h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2755715
telemt_connections_bad_total 161998
telemt_connections_current 1493
telemt_connections_me_current 1493
telemt_handshake_timeouts_total 94088
telemt_upstream_connect_attempt_total 27917
telemt_upstream_connect_success_total 27916
telemt_upstream_connect_attempts_per_request{bucket="1"} 27916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18137
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 67
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1130
telemt_me_reconnect_success_total 480
telemt_me_reader_eof_total 482
telemt_me_idle_close_by_peer_total 482
telemt_me_route_drop_no_conn_total 2250852
telemt_me_route_drop_channel_closed_total 948
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2342871
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 515
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 594
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 10715
telemt_desync_full_logged_total 3394
telemt_desync_suppressed_total 7321
telemt_desync_frames_bucket_total{bucket="1_2"} 2870
telemt_desync_frames_bucket_total{bucket="3_10"} 3978
telemt_desync_frames_bucket_total{bucket="gt_10"} 3867
telemt_pool_swap_total 84
telemt_pool_force_close_total 2610
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 540
telemt_me_draining_writers_reap_progress_total 25494
telemt_me_writer_removed_unexpected_total 468
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1871
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23850
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2557
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22884
telemt_me_writer_teardown_success_total{mode="normal"} 25721
telemt_me_writer_teardown_noop_total 25504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51225
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 255.701618
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51225
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 540
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 425
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 2339001
telemt_user_connections_current{user="hello"} 1493
telemt_user_octets_from_client{user="hello"} 34420552000 (32.06 GB)
telemt_user_octets_to_client{user="hello"} 621020643964 (578.37 GB)
telemt_user_unique_ips_current{user="hello"} 552
telemt_user_unique_ips_recent_window{user="hello"} 259
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 89295.2 (24h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3723862
telemt_connections_bad_total 335788
telemt_connections_current 1265
telemt_connections_me_current 1265
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 94755
telemt_upstream_connect_attempt_total 54741
telemt_upstream_connect_success_total 54063
telemt_upstream_connect_fail_total 597
telemt_upstream_connect_attempts_per_request{bucket="1"} 54660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22936
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 597
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6300
telemt_me_reconnect_success_total 2308
telemt_me_reader_eof_total 2238
telemt_me_idle_close_by_peer_total 2238
telemt_me_route_drop_no_conn_total 3571621
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2956562
telemt_me_endpoint_quarantine_total 700
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 687
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
telemt_me_writers_active_current 77
telemt_me_writers_warm_current 16
telemt_desync_total 11674
telemt_desync_full_logged_total 6523
telemt_desync_suppressed_total 5151
telemt_desync_frames_bucket_total{bucket="1_2"} 2700
telemt_desync_frames_bucket_total{bucket="3_10"} 4573
telemt_desync_frames_bucket_total{bucket="gt_10"} 4401
telemt_pool_swap_total 84
telemt_pool_force_close_total 2522
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 212
telemt_me_draining_writers_reap_progress_total 35268
telemt_me_writer_removed_unexpected_total 2189
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4219
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33249
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2160
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 362
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32746
telemt_me_writer_teardown_success_total{mode="normal"} 37468
telemt_me_writer_teardown_noop_total 35268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72736
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.302910
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72736
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 212
telemt_me_refill_failed_total 158
telemt_me_writer_restored_same_endpoint_total 1996
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 2967442
telemt_user_connections_current{user="hello"} 1265
telemt_user_octets_from_client{user="hello"} 38305824567 (35.68 GB)
telemt_user_octets_to_client{user="hello"} 682550436346 (635.67 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 723
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 164155.0 (45h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15664316
telemt_connections_bad_total 1498753
telemt_connections_current 2075
telemt_connections_me_current 2075
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 386170
telemt_upstream_connect_attempt_total 73530
telemt_upstream_connect_success_total 73433
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 73450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35002
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1681
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2748
telemt_me_reconnect_success_total 1403
telemt_me_reader_eof_total 1342
telemt_me_idle_close_by_peer_total 1340
telemt_me_route_drop_no_conn_total 13894702
telemt_me_route_drop_channel_closed_total 141
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12487546
telemt_me_endpoint_quarantine_total 1034
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1224
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
telemt_me_writers_active_current 45
telemt_desync_total 51282
telemt_desync_full_logged_total 16098
telemt_desync_suppressed_total 35184
telemt_desync_frames_bucket_total{bucket="1_2"} 11460
telemt_desync_frames_bucket_total{bucket="3_10"} 19991
telemt_desync_frames_bucket_total{bucket="gt_10"} 19831
telemt_pool_swap_total 177
telemt_pool_force_close_total 5997
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 970
telemt_me_draining_writers_reap_progress_total 53925
telemt_me_writer_removed_unexpected_total 1296
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4719
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49793
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5533
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 464
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47928
telemt_me_writer_teardown_success_total{mode="normal"} 54512
telemt_me_writer_teardown_noop_total 53975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108487
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 305.682950
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108487
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 970
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1207
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 12488388
telemt_user_connections_current{user="hello"} 2075
telemt_user_octets_from_client{user="hello"} 180551713637 (168.15 GB)
telemt_user_octets_to_client{user="hello"} 3265542515107 (2.97 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 775
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 164156.5 (45h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11304489
telemt_connections_bad_total 1113984
telemt_connections_current 1677
telemt_connections_me_current 1677
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 338598
telemt_upstream_connect_attempt_total 86020
telemt_upstream_connect_success_total 84820
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 85658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34918
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3702
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4070
telemt_me_reconnect_success_total 1684
telemt_me_reader_eof_total 1553
telemt_me_idle_close_by_peer_total 1553
telemt_me_route_drop_no_conn_total 4429966
telemt_me_route_drop_channel_closed_total 490
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8419643
telemt_me_endpoint_quarantine_total 1042
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1243
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
telemt_desync_total 37479
telemt_desync_full_logged_total 12603
telemt_desync_suppressed_total 24876
telemt_desync_frames_bucket_total{bucket="1_2"} 9221
telemt_desync_frames_bucket_total{bucket="3_10"} 14440
telemt_desync_frames_bucket_total{bucket="gt_10"} 13818
telemt_pool_swap_total 174
telemt_pool_force_close_total 5416
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 52394
telemt_me_writer_removed_unexpected_total 1592
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4855
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48975
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4918
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 498
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46978
telemt_me_writer_teardown_success_total{mode="normal"} 53830
telemt_me_writer_teardown_noop_total 52417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106247
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 102.658126
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106247
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 129
telemt_me_writer_restored_same_endpoint_total 1442
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 8358095
telemt_user_connections_current{user="hello"} 1677
telemt_user_octets_from_client{user="hello"} 208706610197 (194.37 GB)
telemt_user_octets_to_client{user="hello"} 3768951502982 (3.43 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 619
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 164122.1 (45h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10643494
telemt_connections_bad_total 916365
telemt_connections_current 1362
telemt_connections_me_current 1362
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 341048
telemt_upstream_connect_attempt_total 71123
telemt_upstream_connect_success_total 70113
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 70295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33417
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1443
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4823
telemt_me_reconnect_success_total 1954
telemt_me_reader_eof_total 1705
telemt_me_idle_close_by_peer_total 1704
telemt_me_route_drop_no_conn_total 5194698
telemt_me_route_drop_channel_closed_total 369
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8036922
telemt_me_endpoint_quarantine_total 1116
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1206
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 36955
telemt_desync_full_logged_total 12231
telemt_desync_suppressed_total 24724
telemt_desync_frames_bucket_total{bucket="1_2"} 9344
telemt_desync_frames_bucket_total{bucket="3_10"} 14144
telemt_desync_frames_bucket_total{bucket="gt_10"} 13467
telemt_pool_swap_total 172
telemt_pool_force_close_total 5345
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 695
telemt_me_draining_writers_reap_progress_total 52654
telemt_me_writer_removed_unexpected_total 1848
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5283
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49134
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4802
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 543
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47309
telemt_me_writer_teardown_success_total{mode="normal"} 54417
telemt_me_writer_teardown_noop_total 52725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107142
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.049776
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107142
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 695
telemt_me_refill_failed_total 152
telemt_me_writer_restored_same_endpoint_total 1690
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 8029631
telemt_user_connections_current{user="hello"} 1362
telemt_user_octets_from_client{user="hello"} 185504687537 (172.76 GB)
telemt_user_octets_to_client{user="hello"} 3343931012621 (3.04 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 504
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 34400.5 (9h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10505062
telemt_connections_bad_total 644042
telemt_connections_current 2195
telemt_connections_me_current 2195
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 211405
telemt_upstream_connect_attempt_total 42083
telemt_upstream_connect_success_total 39969
telemt_upstream_connect_fail_total 1486
telemt_upstream_connect_attempts_per_request{bucket="1"} 41455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12130
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5920
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1486
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6280
telemt_me_reconnect_success_total 806
telemt_me_reader_eof_total 510
telemt_me_idle_close_by_peer_total 510
telemt_me_route_drop_no_conn_total 25084478
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8729380
telemt_me_endpoint_quarantine_total 219
telemt_me_single_endpoint_outage_enter_total 60
telemt_me_single_endpoint_outage_exit_total 60
telemt_me_single_endpoint_outage_reconnect_attempt_total 111
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 111
telemt_me_single_endpoint_shadow_rotate_total 272
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
telemt_me_writers_active_current 44
telemt_desync_total 13916
telemt_desync_full_logged_total 3626
telemt_desync_suppressed_total 10290
telemt_desync_frames_bucket_total{bucket="1_2"} 2563
telemt_desync_frames_bucket_total{bucket="3_10"} 5641
telemt_desync_frames_bucket_total{bucket="gt_10"} 5712
telemt_pool_swap_total 34
telemt_pool_force_close_total 1284
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 394
telemt_me_draining_writers_reap_progress_total 9696
telemt_me_writer_removed_unexpected_total 712
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1494
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8872
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1000
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 284
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8412
telemt_me_writer_teardown_success_total{mode="normal"} 10366
telemt_me_writer_teardown_noop_total 9702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 17014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 18935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 20019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 20068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 20068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 20068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 20068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 20068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 20068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 20068
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 43.911975
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 20068
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 394
telemt_me_refill_failed_total 303
telemt_me_writer_restored_same_endpoint_total 538
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 8750998
telemt_user_connections_current{user="hello"} 2195
telemt_user_octets_from_client{user="hello"} 74924901299 (69.78 GB)
telemt_user_octets_to_client{user="hello"} 397205090097 (369.93 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 778
telemt_user_unique_ips_recent_window{user="hello"} 742
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 164127.1 (45h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10480637
telemt_connections_bad_total 883093
telemt_connections_current 1614
telemt_connections_me_current 1614
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 232091
telemt_upstream_connect_attempt_total 99911
telemt_upstream_connect_success_total 98860
telemt_upstream_connect_fail_total 895
telemt_upstream_connect_attempts_per_request{bucket="1"} 99755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36630
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1321
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 895
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72179
telemt_me_reconnect_success_total 2706
telemt_me_reader_eof_total 2397
telemt_me_idle_close_by_peer_total 2395
telemt_me_route_drop_no_conn_total 5130841
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8270709
telemt_me_endpoint_quarantine_total 1094
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1226
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_me_writers_active_current 51
telemt_desync_total 43763
telemt_desync_full_logged_total 14924
telemt_desync_suppressed_total 28839
telemt_desync_frames_bucket_total{bucket="1_2"} 8892
telemt_desync_frames_bucket_total{bucket="3_10"} 16818
telemt_desync_frames_bucket_total{bucket="gt_10"} 18053
telemt_pool_swap_total 168
telemt_pool_force_close_total 5002
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 622
telemt_me_draining_writers_reap_progress_total 55821
telemt_me_writer_removed_unexpected_total 2438
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5961
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52321
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4307
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 695
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50819
telemt_me_writer_teardown_success_total{mode="normal"} 58282
telemt_me_writer_teardown_noop_total 55822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114104
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.677891
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114104
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 622
telemt_me_refill_failed_total 4281
telemt_me_writer_restored_same_endpoint_total 2264
telemt_me_writer_restored_fallback_total 47
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 8274316
telemt_user_connections_current{user="hello"} 1614
telemt_user_octets_from_client{user="hello"} 187488584277 (174.61 GB)
telemt_user_octets_to_client{user="hello"} 3127829375240 (2.84 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 621
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 100963.3 (28h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10970114
telemt_connections_bad_total 423271
telemt_connections_current 1868
telemt_connections_me_current 1868
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4551808
telemt_upstream_connect_attempt_total 48079
telemt_upstream_connect_success_total 47720
telemt_upstream_connect_fail_total 350
telemt_upstream_connect_attempts_per_request{bucket="1"} 48070
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21073
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 350
telemt_me_reconnect_attempts_total 48242
telemt_me_reconnect_success_total 1576
telemt_me_reader_eof_total 1233
telemt_me_idle_close_by_peer_total 1232
telemt_me_route_drop_no_conn_total 3981279
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5278147
telemt_me_endpoint_quarantine_total 657
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 760
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 29451
telemt_desync_full_logged_total 9970
telemt_desync_suppressed_total 19481
telemt_desync_frames_bucket_total{bucket="1_2"} 5916
telemt_desync_frames_bucket_total{bucket="3_10"} 11626
telemt_desync_frames_bucket_total{bucket="gt_10"} 11909
telemt_pool_swap_total 107
telemt_pool_force_close_total 3249
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 337
telemt_me_draining_writers_reap_progress_total 34768
telemt_me_writer_removed_unexpected_total 1294
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3103
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32992
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2826
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 423
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31519
telemt_me_writer_teardown_success_total{mode="normal"} 36095
telemt_me_writer_teardown_noop_total 34775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70870
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.144808
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70870
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 337
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1400
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5271320
telemt_user_connections_current{user="hello"} 1868
telemt_user_octets_from_client{user="hello"} 113649827028 (105.84 GB)
telemt_user_octets_to_client{user="hello"} 2005358153462 (1.82 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 695
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 81934.1 (22h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1176948
telemt_connections_bad_total 23037
telemt_connections_current 1297
telemt_connections_me_current 1297
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 22816
telemt_upstream_connect_attempt_total 39409
telemt_upstream_connect_success_total 39293
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 39383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20879
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 627
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1757
telemt_me_reconnect_success_total 749
telemt_me_reader_eof_total 726
telemt_me_idle_close_by_peer_total 726
telemt_me_route_drop_no_conn_total 411177
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1044081
telemt_me_endpoint_quarantine_total 684
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 672
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
telemt_me_writers_warm_current 7
telemt_desync_total 6020
telemt_desync_full_logged_total 1846
telemt_desync_suppressed_total 4174
telemt_desync_frames_bucket_total{bucket="1_2"} 1395
telemt_desync_frames_bucket_total{bucket="3_10"} 2362
telemt_desync_frames_bucket_total{bucket="gt_10"} 2263
telemt_pool_swap_total 87
telemt_pool_force_close_total 2237
telemt_me_writer_close_signal_drop_total 127
telemt_me_draining_writers_reap_progress_total 32729
telemt_me_writer_removed_unexpected_total 699
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2533
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30924
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2154
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30492
telemt_me_writer_teardown_success_total{mode="normal"} 33457
telemt_me_writer_teardown_noop_total 32732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66189
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.880162
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66189
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 127
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 639
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1040421
telemt_user_connections_current{user="hello"} 1297
telemt_user_octets_from_client{user="hello"} 19163082333 (17.85 GB)
telemt_user_octets_to_client{user="hello"} 446070797639 (415.44 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 443
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 164131.7 (45h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12780048
telemt_connections_bad_total 1484547
telemt_connections_current 2063
telemt_connections_me_current 2063
telemt_handshake_timeouts_total 359243
telemt_upstream_connect_attempt_total 61844
telemt_upstream_connect_success_total 61530
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 61722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31081
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2434
telemt_me_reconnect_success_total 1295
telemt_me_reader_eof_total 1256
telemt_me_idle_close_by_peer_total 1256
telemt_me_route_drop_no_conn_total 4347935
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9670933
telemt_me_endpoint_quarantine_total 1096
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1228
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
telemt_me_writers_active_current 44
telemt_desync_total 39731
telemt_desync_full_logged_total 12958
telemt_desync_suppressed_total 26773
telemt_desync_frames_bucket_total{bucket="1_2"} 9465
telemt_desync_frames_bucket_total{bucket="3_10"} 14693
telemt_desync_frames_bucket_total{bucket="gt_10"} 15573
telemt_pool_swap_total 182
telemt_pool_force_close_total 5019
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 638
telemt_me_draining_writers_reap_progress_total 55615
telemt_me_writer_removed_unexpected_total 1210
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4591
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52270
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4845
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50596
telemt_me_writer_teardown_success_total{mode="normal"} 56861
telemt_me_writer_teardown_noop_total 55617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112478
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.054414
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112478
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 638
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 1133
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 9638928
telemt_user_connections_current{user="hello"} 2063
telemt_user_octets_from_client{user="hello"} 188624983236 (175.67 GB)
telemt_user_octets_to_client{user="hello"} 4250881402548 (3.87 TB)
telemt_user_unique_ips_current{user="hello"} 642
telemt_user_unique_ips_recent_window{user="hello"} 372
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 164128.3 (45h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11094355
telemt_connections_bad_total 1250933
telemt_connections_current 1740
telemt_connections_me_current 1740
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 289709
telemt_upstream_connect_attempt_total 87910
telemt_upstream_connect_success_total 87141
telemt_upstream_connect_fail_total 588
telemt_upstream_connect_attempts_per_request{bucket="1"} 87729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36364
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2052
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 588
telemt_me_reconnect_attempts_total 9273
telemt_me_reconnect_success_total 2205
telemt_me_reader_eof_total 2056
telemt_me_idle_close_by_peer_total 2056
telemt_me_seq_mismatch_total 77
telemt_me_route_drop_no_conn_total 5520477
telemt_me_route_drop_channel_closed_total 351
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8575421
telemt_me_endpoint_quarantine_total 1262
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 44
telemt_me_single_endpoint_outage_reconnect_success_total 42
telemt_me_single_endpoint_quarantine_bypass_total 44
telemt_me_single_endpoint_shadow_rotate_total 1229
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
telemt_me_writers_active_current 42
telemt_desync_total 38991
telemt_desync_full_logged_total 12591
telemt_desync_suppressed_total 26400
telemt_desync_frames_bucket_total{bucket="1_2"} 9703
telemt_desync_frames_bucket_total{bucket="3_10"} 14515
telemt_desync_frames_bucket_total{bucket="gt_10"} 14773
telemt_pool_swap_total 173
telemt_pool_force_close_total 4840
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 623
telemt_me_draining_writers_reap_progress_total 55255
telemt_me_writer_removed_unexpected_total 2083
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5788
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51621
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4384
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 456
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50415
telemt_me_writer_teardown_success_total{mode="normal"} 57409
telemt_me_writer_teardown_noop_total 55260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112669
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.928140
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112669
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 623
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 1789
telemt_me_writer_restored_fallback_total 105
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 8581203
telemt_user_connections_current{user="hello"} 1740
telemt_user_octets_from_client{user="hello"} 150638815613 (140.29 GB)
telemt_user_octets_to_client{user="hello"} 3295869807675 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 626
telemt_user_unique_ips_recent_window{user="hello"} 225
```
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

# Server Metrics 2026-03-22 19:34:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 80872.3 (22h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3009013
telemt_connections_bad_total 200521
telemt_connections_current 1159
telemt_connections_me_current 1159
telemt_handshake_timeouts_total 97865
telemt_upstream_connect_attempt_total 29594
telemt_upstream_connect_success_total 29593
telemt_upstream_connect_attempts_per_request{bucket="1"} 29593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19234
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 74
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1185
telemt_me_reconnect_success_total 499
telemt_me_reader_eof_total 504
telemt_me_idle_close_by_peer_total 504
telemt_me_route_drop_no_conn_total 2681528
telemt_me_route_drop_channel_closed_total 1065
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2549091
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 542
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 626
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
telemt_me_writers_active_current 45
telemt_desync_total 10983
telemt_desync_full_logged_total 3492
telemt_desync_suppressed_total 7491
telemt_desync_frames_bucket_total{bucket="1_2"} 2947
telemt_desync_frames_bucket_total{bucket="3_10"} 4079
telemt_desync_frames_bucket_total{bucket="gt_10"} 3957
telemt_pool_swap_total 89
telemt_pool_force_close_total 2762
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 576
telemt_me_draining_writers_reap_progress_total 27054
telemt_me_writer_removed_unexpected_total 488
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1966
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25313
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2709
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24292
telemt_me_writer_teardown_success_total{mode="normal"} 27279
telemt_me_writer_teardown_noop_total 27064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54343
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 300.292294
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54343
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 576
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 441
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 2541555
telemt_user_connections_current{user="hello"} 1159
telemt_user_octets_from_client{user="hello"} 37172811164 (34.62 GB)
telemt_user_octets_to_client{user="hello"} 666082166092 (620.34 GB)
telemt_user_unique_ips_current{user="hello"} 480
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 94238.4 (26h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3813442
telemt_connections_bad_total 339957
telemt_connections_current 1327
telemt_connections_me_current 1327
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 97330
telemt_upstream_connect_attempt_total 57152
telemt_upstream_connect_success_total 56449
telemt_upstream_connect_fail_total 620
telemt_upstream_connect_attempts_per_request{bucket="1"} 57069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 620
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6491
telemt_me_reconnect_success_total 2398
telemt_me_reader_eof_total 2336
telemt_me_idle_close_by_peer_total 2336
telemt_me_route_drop_no_conn_total 3599248
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3034155
telemt_me_endpoint_quarantine_total 729
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 726
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 12126
telemt_desync_full_logged_total 6779
telemt_desync_suppressed_total 5347
telemt_desync_frames_bucket_total{bucket="1_2"} 2783
telemt_desync_frames_bucket_total{bucket="3_10"} 4749
telemt_desync_frames_bucket_total{bucket="gt_10"} 4594
telemt_pool_swap_total 88
telemt_pool_force_close_total 2657
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 225
telemt_me_draining_writers_reap_progress_total 37403
telemt_me_writer_removed_unexpected_total 2286
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4426
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35275
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2268
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34746
telemt_me_writer_teardown_success_total{mode="normal"} 39701
telemt_me_writer_teardown_noop_total 37403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77104
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.964738
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77104
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 225
telemt_me_refill_failed_total 164
telemt_me_writer_restored_same_endpoint_total 2085
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 3044954
telemt_user_connections_current{user="hello"} 1327
telemt_user_octets_from_client{user="hello"} 39415831827 (36.71 GB)
telemt_user_octets_to_client{user="hello"} 717770883946 (668.48 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 731
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 169098.3 (46h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15882016
telemt_connections_bad_total 1532060
telemt_connections_current 2400
telemt_connections_me_current 2400
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 391640
telemt_upstream_connect_attempt_total 75297
telemt_upstream_connect_success_total 75199
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 75216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36008
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1685
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2780
telemt_me_reconnect_success_total 1435
telemt_me_reader_eof_total 1376
telemt_me_idle_close_by_peer_total 1374
telemt_me_route_drop_no_conn_total 13956307
telemt_me_route_drop_channel_closed_total 143
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12656957
telemt_me_endpoint_quarantine_total 1064
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1258
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 52183
telemt_desync_full_logged_total 16416
telemt_desync_suppressed_total 35767
telemt_desync_frames_bucket_total{bucket="1_2"} 11631
telemt_desync_frames_bucket_total{bucket="3_10"} 20325
telemt_desync_frames_bucket_total{bucket="gt_10"} 20227
telemt_pool_swap_total 182
telemt_pool_force_close_total 6145
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 999
telemt_me_draining_writers_reap_progress_total 55510
telemt_me_writer_removed_unexpected_total 1328
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4869
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51262
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5677
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 468
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49365
telemt_me_writer_teardown_success_total{mode="normal"} 56131
telemt_me_writer_teardown_noop_total 55561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111692
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 310.806339
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111692
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 999
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1237
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 12657511
telemt_user_connections_current{user="hello"} 2400
telemt_user_octets_from_client{user="hello"} 184799265089 (172.11 GB)
telemt_user_octets_to_client{user="hello"} 3351615652451 (3.05 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 925
telemt_user_unique_ips_recent_window{user="hello"} 328
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 169099.9 (46h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11476304
telemt_connections_bad_total 1139489
telemt_connections_current 1639
telemt_connections_me_current 1639
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 341636
telemt_upstream_connect_attempt_total 87753
telemt_upstream_connect_success_total 86525
telemt_upstream_connect_fail_total 843
telemt_upstream_connect_attempts_per_request{bucket="1"} 87368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35873
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3708
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 843
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4133
telemt_me_reconnect_success_total 1713
telemt_me_reader_eof_total 1582
telemt_me_idle_close_by_peer_total 1582
telemt_me_route_drop_no_conn_total 4478930
telemt_me_route_drop_channel_closed_total 491
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8553394
telemt_me_endpoint_quarantine_total 1064
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1278
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
telemt_me_writers_active_current 44
telemt_desync_total 37894
telemt_desync_full_logged_total 12767
telemt_desync_suppressed_total 25127
telemt_desync_frames_bucket_total{bucket="1_2"} 9341
telemt_desync_frames_bucket_total{bucket="3_10"} 14596
telemt_desync_frames_bucket_total{bucket="gt_10"} 13957
telemt_pool_swap_total 179
telemt_pool_force_close_total 5554
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 701
telemt_me_draining_writers_reap_progress_total 53924
telemt_me_writer_removed_unexpected_total 1620
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4985
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50405
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5051
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 503
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48370
telemt_me_writer_teardown_success_total{mode="normal"} 55390
telemt_me_writer_teardown_noop_total 53949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109339
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.643139
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109339
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 701
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1466
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 8491628
telemt_user_connections_current{user="hello"} 1639
telemt_user_octets_from_client{user="hello"} 213110651005 (198.47 GB)
telemt_user_octets_to_client{user="hello"} 3831586874686 (3.48 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 617
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 169063.7 (46h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10780387
telemt_connections_bad_total 929917
telemt_connections_current 921
telemt_connections_me_current 921
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 343377
telemt_upstream_connect_attempt_total 72859
telemt_upstream_connect_success_total 71757
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 71942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34303
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1574
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 4943
telemt_me_reconnect_success_total 2001
telemt_me_reader_eof_total 1748
telemt_me_idle_close_by_peer_total 1747
telemt_me_route_drop_no_conn_total 5250420
telemt_me_route_drop_channel_closed_total 374
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8150884
telemt_me_endpoint_quarantine_total 1152
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1241
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 60
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
telemt_desync_total 37372
telemt_desync_full_logged_total 12368
telemt_desync_suppressed_total 25004
telemt_desync_frames_bucket_total{bucket="1_2"} 9452
telemt_desync_frames_bucket_total{bucket="3_10"} 14298
telemt_desync_frames_bucket_total{bucket="gt_10"} 13622
telemt_pool_swap_total 177
telemt_pool_force_close_total 5501
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 708
telemt_me_draining_writers_reap_progress_total 54059
telemt_me_writer_removed_unexpected_total 1888
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5417
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50449
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4950
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 551
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48558
telemt_me_writer_teardown_success_total{mode="normal"} 55866
telemt_me_writer_teardown_noop_total 54130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109996
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.766286
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109996
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 708
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 1722
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 8143218
telemt_user_connections_current{user="hello"} 921
telemt_user_octets_from_client{user="hello"} 189171037617 (176.18 GB)
telemt_user_octets_to_client{user="hello"} 3388510065481 (3.08 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 403
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 39343.7 (10h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10747715
telemt_connections_bad_total 656310
telemt_connections_current 2073
telemt_connections_me_current 2073
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 229489
telemt_upstream_connect_attempt_total 44571
telemt_upstream_connect_success_total 42332
telemt_upstream_connect_fail_total 1541
telemt_upstream_connect_attempts_per_request{bucket="1"} 43873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13299
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5956
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1541
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6470
telemt_me_reconnect_success_total 873
telemt_me_reader_eof_total 545
telemt_me_idle_close_by_peer_total 545
telemt_me_route_drop_no_conn_total 25171822
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8924320
telemt_me_endpoint_quarantine_total 241
telemt_me_single_endpoint_outage_enter_total 63
telemt_me_single_endpoint_outage_exit_total 63
telemt_me_single_endpoint_outage_reconnect_attempt_total 114
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 114
telemt_me_single_endpoint_shadow_rotate_total 306
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
telemt_desync_total 14407
telemt_desync_full_logged_total 3775
telemt_desync_suppressed_total 10632
telemt_desync_frames_bucket_total{bucket="1_2"} 2668
telemt_desync_frames_bucket_total{bucket="3_10"} 5847
telemt_desync_frames_bucket_total{bucket="gt_10"} 5892
telemt_pool_swap_total 39
telemt_pool_force_close_total 1442
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 425
telemt_me_draining_writers_reap_progress_total 11103
telemt_me_writer_removed_unexpected_total 789
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1681
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10164
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1150
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 292
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9661
telemt_me_writer_teardown_success_total{mode="normal"} 11845
telemt_me_writer_teardown_noop_total 11122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 21103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 21689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 22450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22967
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.043069
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22967
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 425
telemt_me_refill_failed_total 310
telemt_me_writer_restored_same_endpoint_total 583
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 8946507
telemt_user_connections_current{user="hello"} 2073
telemt_user_octets_from_client{user="hello"} 81710677231 (76.10 GB)
telemt_user_octets_to_client{user="hello"} 466558776475 (434.52 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 772
telemt_user_unique_ips_recent_window{user="hello"} 274
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 169070.3 (46h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10650652
telemt_connections_bad_total 897092
telemt_connections_current 1684
telemt_connections_me_current 1684
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 233881
telemt_upstream_connect_attempt_total 102202
telemt_upstream_connect_success_total 101123
telemt_upstream_connect_fail_total 920
telemt_upstream_connect_attempts_per_request{bucket="1"} 102043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37886
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 920
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72292
telemt_me_reconnect_success_total 2803
telemt_me_reader_eof_total 2492
telemt_me_idle_close_by_peer_total 2490
telemt_me_route_drop_no_conn_total 5181954
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8413518
telemt_me_endpoint_quarantine_total 1118
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1260
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 44751
telemt_desync_full_logged_total 15241
telemt_desync_suppressed_total 29510
telemt_desync_frames_bucket_total{bucket="1_2"} 9069
telemt_desync_frames_bucket_total{bucket="3_10"} 17156
telemt_desync_frames_bucket_total{bucket="gt_10"} 18526
telemt_pool_swap_total 172
telemt_pool_force_close_total 5137
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 631
telemt_me_draining_writers_reap_progress_total 57836
telemt_me_writer_removed_unexpected_total 2530
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6169
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54223
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4412
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 725
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52699
telemt_me_writer_teardown_success_total{mode="normal"} 60392
telemt_me_writer_teardown_noop_total 57837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118229
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.967338
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118229
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 631
telemt_me_refill_failed_total 4281
telemt_me_writer_restored_same_endpoint_total 2355
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 8416909
telemt_user_connections_current{user="hello"} 1684
telemt_user_octets_from_client{user="hello"} 191097850797 (177.97 GB)
telemt_user_octets_to_client{user="hello"} 3196625560732 (2.91 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 703
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 105906.6 (29h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11220420
telemt_connections_bad_total 443452
telemt_connections_current 1413
telemt_connections_me_current 1413
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4631642
telemt_upstream_connect_attempt_total 50315
telemt_upstream_connect_success_total 49938
telemt_upstream_connect_fail_total 368
telemt_upstream_connect_attempts_per_request{bucket="1"} 50306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22276
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 368
telemt_me_reconnect_attempts_total 48461
telemt_me_reconnect_success_total 1660
telemt_me_reader_eof_total 1316
telemt_me_idle_close_by_peer_total 1315
telemt_me_route_drop_no_conn_total 4023993
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5398561
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
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30294
telemt_desync_full_logged_total 10242
telemt_desync_suppressed_total 20052
telemt_desync_frames_bucket_total{bucket="1_2"} 6059
telemt_desync_frames_bucket_total{bucket="3_10"} 11970
telemt_desync_frames_bucket_total{bucket="gt_10"} 12265
telemt_pool_swap_total 111
telemt_pool_force_close_total 3403
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 345
telemt_me_draining_writers_reap_progress_total 36802
telemt_me_writer_removed_unexpected_total 1376
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3276
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34936
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2963
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 440
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33399
telemt_me_writer_teardown_success_total{mode="normal"} 38212
telemt_me_writer_teardown_noop_total 36809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75021
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.449988
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75021
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 345
telemt_me_refill_failed_total 2720
telemt_me_writer_restored_same_endpoint_total 1476
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5391486
telemt_user_connections_current{user="hello"} 1413
telemt_user_octets_from_client{user="hello"} 116534043492 (108.53 GB)
telemt_user_octets_to_client{user="hello"} 2063007274514 (1.88 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 514
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 86877.3 (24h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1298605
telemt_connections_bad_total 29153
telemt_connections_current 1180
telemt_connections_me_current 1180
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 24626
telemt_upstream_connect_attempt_total 41323
telemt_upstream_connect_success_total 41199
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 41296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21914
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 696
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1896
telemt_me_reconnect_success_total 802
telemt_me_reader_eof_total 778
telemt_me_idle_close_by_peer_total 778
telemt_me_route_drop_no_conn_total 452637
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1151390
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
telemt_desync_total 6790
telemt_desync_full_logged_total 2093
telemt_desync_suppressed_total 4697
telemt_desync_frames_bucket_total{bucket="1_2"} 1515
telemt_desync_frames_bucket_total{bucket="3_10"} 2683
telemt_desync_frames_bucket_total{bucket="gt_10"} 2592
telemt_pool_swap_total 93
telemt_pool_force_close_total 2408
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 141
telemt_me_draining_writers_reap_progress_total 34362
telemt_me_writer_removed_unexpected_total 751
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2712
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32431
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2323
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31954
telemt_me_writer_teardown_success_total{mode="normal"} 35143
telemt_me_writer_teardown_noop_total 34366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69509
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.284607
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69509
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 141
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 680
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 1147548
telemt_user_connections_current{user="hello"} 1180
telemt_user_octets_from_client{user="hello"} 21906647585 (20.40 GB)
telemt_user_octets_to_client{user="hello"} 485628384943 (452.28 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 421
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 169074.9 (46h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12966630
telemt_connections_bad_total 1514378
telemt_connections_current 1593
telemt_connections_me_current 1593
telemt_handshake_timeouts_total 371028
telemt_upstream_connect_attempt_total 63709
telemt_upstream_connect_success_total 63378
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 63574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31951
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2518
telemt_me_reconnect_success_total 1311
telemt_me_reader_eof_total 1276
telemt_me_idle_close_by_peer_total 1276
telemt_me_route_drop_no_conn_total 4404689
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9810428
telemt_me_endpoint_quarantine_total 1129
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1263
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
telemt_me_writers_active_current 42
telemt_desync_total 40514
telemt_desync_full_logged_total 13210
telemt_desync_suppressed_total 27304
telemt_desync_frames_bucket_total{bucket="1_2"} 9679
telemt_desync_frames_bucket_total{bucket="3_10"} 14946
telemt_desync_frames_bucket_total{bucket="gt_10"} 15889
telemt_pool_swap_total 187
telemt_pool_force_close_total 5148
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 645
telemt_me_draining_writers_reap_progress_total 57395
telemt_me_writer_removed_unexpected_total 1228
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4699
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53962
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4974
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52247
telemt_me_writer_teardown_success_total{mode="normal"} 58661
telemt_me_writer_teardown_noop_total 57397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116058
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.202804
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116058
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 645
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 1146
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 9778245
telemt_user_connections_current{user="hello"} 1593
telemt_user_octets_from_client{user="hello"} 191503160584 (178.35 GB)
telemt_user_octets_to_client{user="hello"} 4319987836644 (3.93 TB)
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 169071.6 (46h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11273181
telemt_connections_bad_total 1276709
telemt_connections_current 1305
telemt_connections_me_current 1305
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 296237
telemt_upstream_connect_attempt_total 90171
telemt_upstream_connect_success_total 89355
telemt_upstream_connect_fail_total 610
telemt_upstream_connect_attempts_per_request{bucket="1"} 89965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37483
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 610
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9732
telemt_me_reconnect_success_total 2332
telemt_me_reader_eof_total 2177
telemt_me_idle_close_by_peer_total 2176
telemt_me_seq_mismatch_total 78
telemt_me_route_drop_no_conn_total 5581550
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8713254
telemt_me_endpoint_quarantine_total 1293
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1263
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
telemt_me_writers_active_current 45
telemt_desync_total 39757
telemt_desync_full_logged_total 12844
telemt_desync_suppressed_total 26913
telemt_desync_frames_bucket_total{bucket="1_2"} 9913
telemt_desync_frames_bucket_total{bucket="3_10"} 14793
telemt_desync_frames_bucket_total{bucket="gt_10"} 15051
telemt_pool_swap_total 177
telemt_pool_force_close_total 4948
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 634
telemt_me_draining_writers_reap_progress_total 57184
telemt_me_writer_removed_unexpected_total 2211
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6038
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53430
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4477
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52236
telemt_me_writer_teardown_success_total{mode="normal"} 59468
telemt_me_writer_teardown_noop_total 57189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116657
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.115833
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116657
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 634
telemt_me_refill_failed_total 382
telemt_me_writer_restored_same_endpoint_total 1904
telemt_me_writer_restored_fallback_total 106
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 8718878
telemt_user_connections_current{user="hello"} 1305
telemt_user_octets_from_client{user="hello"} 154267121729 (143.67 GB)
telemt_user_octets_to_client{user="hello"} 3361914642327 (3.06 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 522
telemt_user_unique_ips_recent_window{user="hello"} 182
```
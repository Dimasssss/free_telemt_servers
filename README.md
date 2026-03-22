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

# Server Metrics 2026-03-22 17:10:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 72233.8 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2605826
telemt_connections_bad_total 140195
telemt_connections_current 1490
telemt_connections_me_current 1490
telemt_handshake_timeouts_total 90377
telemt_upstream_connect_attempt_total 26657
telemt_upstream_connect_success_total 26656
telemt_upstream_connect_attempts_per_request{bucket="1"} 26656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17293
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 59
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1084
telemt_me_reconnect_success_total 458
telemt_me_reader_eof_total 462
telemt_me_idle_close_by_peer_total 462
telemt_me_route_drop_no_conn_total 2186708
telemt_me_route_drop_channel_closed_total 885
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2223528
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 495
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 567
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
telemt_me_writers_active_current 44
telemt_desync_total 10339
telemt_desync_full_logged_total 3269
telemt_desync_suppressed_total 7070
telemt_desync_frames_bucket_total{bucket="1_2"} 2770
telemt_desync_frames_bucket_total{bucket="3_10"} 3860
telemt_desync_frames_bucket_total{bucket="gt_10"} 3709
telemt_pool_swap_total 80
telemt_pool_force_close_total 2488
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 492
telemt_me_draining_writers_reap_progress_total 24356
telemt_me_writer_removed_unexpected_total 447
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1782
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22792
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2436
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 52
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21868
telemt_me_writer_teardown_success_total{mode="normal"} 24574
telemt_me_writer_teardown_noop_total 24362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48936
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 238.308677
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48936
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 492
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 406
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 2219843
telemt_user_connections_current{user="hello"} 1490
telemt_user_octets_from_client{user="hello"} 32835156640 (30.58 GB)
telemt_user_octets_to_client{user="hello"} 582989444544 (542.95 GB)
telemt_user_unique_ips_current{user="hello"} 578
telemt_user_unique_ips_recent_window{user="hello"} 265
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 85599.8 (23h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3649764
telemt_connections_bad_total 330112
telemt_connections_current 1254
telemt_connections_me_current 1254
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 91254
telemt_upstream_connect_attempt_total 53285
telemt_upstream_connect_success_total 52625
telemt_upstream_connect_fail_total 580
telemt_upstream_connect_attempts_per_request{bucket="1"} 53205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 580
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6130
telemt_me_reconnect_success_total 2232
telemt_me_reader_eof_total 2166
telemt_me_idle_close_by_peer_total 2166
telemt_me_route_drop_no_conn_total 3546693
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2895475
telemt_me_endpoint_quarantine_total 680
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 659
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 26
telemt_desync_total 11381
telemt_desync_full_logged_total 6355
telemt_desync_suppressed_total 5026
telemt_desync_frames_bucket_total{bucket="1_2"} 2653
telemt_desync_frames_bucket_total{bucket="3_10"} 4460
telemt_desync_frames_bucket_total{bucket="gt_10"} 4268
telemt_pool_swap_total 80
telemt_pool_force_close_total 2404
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 203
telemt_me_draining_writers_reap_progress_total 34057
telemt_me_writer_removed_unexpected_total 2119
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4071
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32113
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2044
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 360
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31653
telemt_me_writer_teardown_success_total{mode="normal"} 36184
telemt_me_writer_teardown_noop_total 34057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70241
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.132030
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70241
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 203
telemt_me_refill_failed_total 153
telemt_me_writer_restored_same_endpoint_total 1932
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 2906713
telemt_user_connections_current{user="hello"} 1254
telemt_user_octets_from_client{user="hello"} 36597390047 (34.08 GB)
telemt_user_octets_to_client{user="hello"} 657829518486 (612.65 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 715
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 160459.6 (44h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15471482
telemt_connections_bad_total 1467056
telemt_connections_current 2139
telemt_connections_me_current 2139
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 378293
telemt_upstream_connect_attempt_total 72263
telemt_upstream_connect_success_total 72167
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 72184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34238
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1676
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2692
telemt_me_reconnect_success_total 1382
telemt_me_reader_eof_total 1321
telemt_me_idle_close_by_peer_total 1319
telemt_me_route_drop_no_conn_total 13841333
telemt_me_route_drop_channel_closed_total 140
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12342861
telemt_me_endpoint_quarantine_total 1011
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1197
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
telemt_desync_total 50450
telemt_desync_full_logged_total 15843
telemt_desync_suppressed_total 34607
telemt_desync_frames_bucket_total{bucket="1_2"} 11268
telemt_desync_frames_bucket_total{bucket="3_10"} 19698
telemt_desync_frames_bucket_total{bucket="gt_10"} 19484
telemt_pool_swap_total 173
telemt_pool_force_close_total 5877
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 950
telemt_me_draining_writers_reap_progress_total 52783
telemt_me_writer_removed_unexpected_total 1275
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4627
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48722
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5417
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46906
telemt_me_writer_teardown_success_total{mode="normal"} 53349
telemt_me_writer_teardown_noop_total 52833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106182
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 303.602406
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106182
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 950
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 1188
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 12343898
telemt_user_connections_current{user="hello"} 2139
telemt_user_octets_from_client{user="hello"} 176367601989 (164.26 GB)
telemt_user_octets_to_client{user="hello"} 3203709728435 (2.91 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 802
telemt_user_unique_ips_recent_window{user="hello"} 313
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 160461.1 (44h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11156817
telemt_connections_bad_total 1084719
telemt_connections_current 1577
telemt_connections_me_current 1577
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 333257
telemt_upstream_connect_attempt_total 84475
telemt_upstream_connect_success_total 83317
telemt_upstream_connect_fail_total 834
telemt_upstream_connect_attempts_per_request{bucket="1"} 84151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34101
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3696
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 834
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3958
telemt_me_reconnect_success_total 1621
telemt_me_reader_eof_total 1493
telemt_me_idle_close_by_peer_total 1493
telemt_me_route_drop_no_conn_total 4384344
telemt_me_route_drop_channel_closed_total 482
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8318265
telemt_me_endpoint_quarantine_total 1016
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1215
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
telemt_desync_total 36998
telemt_desync_full_logged_total 12432
telemt_desync_suppressed_total 24566
telemt_desync_frames_bucket_total{bucket="1_2"} 9085
telemt_desync_frames_bucket_total{bucket="3_10"} 14261
telemt_desync_frames_bucket_total{bucket="gt_10"} 13652
telemt_pool_swap_total 171
telemt_pool_force_close_total 5320
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 672
telemt_me_draining_writers_reap_progress_total 51105
telemt_me_writer_removed_unexpected_total 1521
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4706
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47762
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4842
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 478
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45785
telemt_me_writer_teardown_success_total{mode="normal"} 52468
telemt_me_writer_teardown_noop_total 51128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103596
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 100.754051
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103596
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 672
telemt_me_refill_failed_total 126
telemt_me_writer_restored_same_endpoint_total 1382
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8256842
telemt_user_connections_current{user="hello"} 1577
telemt_user_octets_from_client{user="hello"} 206487163213 (192.31 GB)
telemt_user_octets_to_client{user="hello"} 3720346698902 (3.38 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 566
telemt_user_unique_ips_recent_window{user="hello"} 303
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 160425.0 (44h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10536967
telemt_connections_bad_total 909389
telemt_connections_current 1279
telemt_connections_me_current 1279
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 336568
telemt_upstream_connect_attempt_total 69715
telemt_upstream_connect_success_total 68728
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 68910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32625
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1371
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2088
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4754
telemt_me_reconnect_success_total 1920
telemt_me_reader_eof_total 1671
telemt_me_idle_close_by_peer_total 1670
telemt_me_route_drop_no_conn_total 5158320
telemt_me_route_drop_channel_closed_total 365
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7949632
telemt_me_endpoint_quarantine_total 1096
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1181
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 36484
telemt_desync_full_logged_total 12067
telemt_desync_suppressed_total 24417
telemt_desync_frames_bucket_total{bucket="1_2"} 9238
telemt_desync_frames_bucket_total{bucket="3_10"} 13952
telemt_desync_frames_bucket_total{bucket="gt_10"} 13294
telemt_pool_swap_total 168
telemt_pool_force_close_total 5242
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 687
telemt_me_draining_writers_reap_progress_total 51446
telemt_me_writer_removed_unexpected_total 1813
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5162
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48010
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4700
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46204
telemt_me_writer_teardown_success_total{mode="normal"} 53172
telemt_me_writer_teardown_noop_total 51517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104689
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3171.852787
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104689
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 687
telemt_me_refill_failed_total 150
telemt_me_writer_restored_same_endpoint_total 1659
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 7942484
telemt_user_connections_current{user="hello"} 1279
telemt_user_octets_from_client{user="hello"} 183456622333 (170.86 GB)
telemt_user_octets_to_client{user="hello"} 3304067376837 (3.01 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 477
telemt_user_unique_ips_recent_window{user="hello"} 351
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 30705.1 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10301606
telemt_connections_bad_total 628051
telemt_connections_current 2256
telemt_connections_me_current 2256
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 197224
telemt_upstream_connect_attempt_total 40751
telemt_upstream_connect_success_total 38678
telemt_upstream_connect_fail_total 1478
telemt_upstream_connect_attempts_per_request{bucket="1"} 40156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11380
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5914
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1478
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6077
telemt_me_reconnect_success_total 774
telemt_me_reader_eof_total 475
telemt_me_idle_close_by_peer_total 475
telemt_me_route_drop_no_conn_total 24995055
telemt_me_route_drop_channel_closed_total 50
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8568305
telemt_me_endpoint_quarantine_total 186
telemt_me_single_endpoint_outage_enter_total 58
telemt_me_single_endpoint_outage_exit_total 58
telemt_me_single_endpoint_outage_reconnect_attempt_total 109
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 109
telemt_me_single_endpoint_shadow_rotate_total 241
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 40
telemt_desync_total 13500
telemt_desync_full_logged_total 3499
telemt_desync_suppressed_total 10001
telemt_desync_frames_bucket_total{bucket="1_2"} 2454
telemt_desync_frames_bucket_total{bucket="3_10"} 5490
telemt_desync_frames_bucket_total{bucket="gt_10"} 5556
telemt_pool_swap_total 29
telemt_pool_force_close_total 1126
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 376
telemt_me_draining_writers_reap_progress_total 8488
telemt_me_writer_removed_unexpected_total 679
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1382
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7750
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 844
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 282
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7362
telemt_me_writer_teardown_success_total{mode="normal"} 9132
telemt_me_writer_teardown_noop_total 8493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 14805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 17227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 17500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 17598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 17625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 17625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 17625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 17625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 17625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 17625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 17625
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 37.529835
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 17625
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 376
telemt_me_refill_failed_total 293
telemt_me_writer_restored_same_endpoint_total 518
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 8590064
telemt_user_connections_current{user="hello"} 2256
telemt_user_octets_from_client{user="hello"} 67957549191 (63.29 GB)
telemt_user_octets_to_client{user="hello"} 341146497449 (317.72 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 795
telemt_user_unique_ips_recent_window{user="hello"} 288
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 160431.7 (44h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10340155
telemt_connections_bad_total 869660
telemt_connections_current 1347
telemt_connections_me_current 1347
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 229064
telemt_upstream_connect_attempt_total 98494
telemt_upstream_connect_success_total 97472
telemt_upstream_connect_fail_total 869
telemt_upstream_connect_attempts_per_request{bucket="1"} 98341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35841
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1312
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 869
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72074
telemt_me_reconnect_success_total 2650
telemt_me_reader_eof_total 2351
telemt_me_idle_close_by_peer_total 2349
telemt_me_route_drop_no_conn_total 5090759
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8156085
telemt_me_endpoint_quarantine_total 1084
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1197
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
telemt_me_writers_active_current 46
telemt_desync_total 42603
telemt_desync_full_logged_total 14542
telemt_desync_suppressed_total 28061
telemt_desync_frames_bucket_total{bucket="1_2"} 8664
telemt_desync_frames_bucket_total{bucket="3_10"} 16450
telemt_desync_frames_bucket_total{bucket="gt_10"} 17489
telemt_pool_swap_total 164
telemt_pool_force_close_total 4881
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 614
telemt_me_draining_writers_reap_progress_total 54598
telemt_me_writer_removed_unexpected_total 2393
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5839
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51174
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4195
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 686
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49717
telemt_me_writer_teardown_success_total{mode="normal"} 57013
telemt_me_writer_teardown_noop_total 54599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111612
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.578866
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111612
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 614
telemt_me_refill_failed_total 4279
telemt_me_writer_restored_same_endpoint_total 2218
telemt_me_writer_restored_fallback_total 46
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7365
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 8159874
telemt_user_connections_current{user="hello"} 1347
telemt_user_octets_from_client{user="hello"} 184693288945 (172.01 GB)
telemt_user_octets_to_client{user="hello"} 3079066414956 (2.80 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 473
telemt_user_unique_ips_recent_window{user="hello"} 366
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 97267.8 (27h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10783701
telemt_connections_bad_total 409190
telemt_connections_current 2084
telemt_connections_me_current 2084
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4509698
telemt_upstream_connect_attempt_total 46642
telemt_upstream_connect_success_total 46298
telemt_upstream_connect_fail_total 334
telemt_upstream_connect_attempts_per_request{bucket="1"} 46632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20273
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 334
telemt_me_reconnect_attempts_total 48174
telemt_me_reconnect_success_total 1531
telemt_me_reader_eof_total 1198
telemt_me_idle_close_by_peer_total 1197
telemt_me_route_drop_no_conn_total 3942466
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5174572
telemt_me_endpoint_quarantine_total 626
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 729
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_me_writers_warm_current 18
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 28553
telemt_desync_full_logged_total 9652
telemt_desync_suppressed_total 18901
telemt_desync_frames_bucket_total{bucket="1_2"} 5760
telemt_desync_frames_bucket_total{bucket="3_10"} 11256
telemt_desync_frames_bucket_total{bucket="gt_10"} 11537
telemt_pool_swap_total 102
telemt_pool_force_close_total 3135
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 324
telemt_me_draining_writers_reap_progress_total 33509
telemt_me_writer_removed_unexpected_total 1260
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2996
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31804
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2716
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30374
telemt_me_writer_teardown_success_total{mode="normal"} 34800
telemt_me_writer_teardown_noop_total 33516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68316
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.946630
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68316
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 324
telemt_me_refill_failed_total 2711
telemt_me_writer_restored_same_endpoint_total 1361
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5167968
telemt_user_connections_current{user="hello"} 2084
telemt_user_octets_from_client{user="hello"} 111500535256 (103.84 GB)
telemt_user_octets_to_client{user="hello"} 1954646988074 (1.78 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 838
telemt_user_unique_ips_recent_window{user="hello"} 303
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 78239.6 (21h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1082833
telemt_connections_bad_total 16489
telemt_connections_current 1298
telemt_connections_me_current 1298
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 20575
telemt_upstream_connect_attempt_total 38056
telemt_upstream_connect_success_total 37947
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 38032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 569
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_reconnect_attempts_total 1738
telemt_me_reconnect_success_total 730
telemt_me_reader_eof_total 705
telemt_me_idle_close_by_peer_total 705
telemt_me_route_drop_no_conn_total 378269
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 964229
telemt_me_endpoint_quarantine_total 660
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 644
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
telemt_me_writers_active_current 44
telemt_desync_total 5470
telemt_desync_full_logged_total 1682
telemt_desync_suppressed_total 3788
telemt_desync_frames_bucket_total{bucket="1_2"} 1277
telemt_desync_frames_bucket_total{bucket="3_10"} 2170
telemt_desync_frames_bucket_total{bucket="gt_10"} 2023
telemt_pool_swap_total 83
telemt_pool_force_close_total 2117
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 31547
telemt_me_writer_removed_unexpected_total 681
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2443
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29811
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2035
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 82
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29430
telemt_me_writer_teardown_success_total{mode="normal"} 32254
telemt_me_writer_teardown_noop_total 31550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63804
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.787890
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63804
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 621
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 960710
telemt_user_connections_current{user="hello"} 1298
telemt_user_octets_from_client{user="hello"} 17868432833 (16.64 GB)
telemt_user_octets_to_client{user="hello"} 417050512495 (388.41 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 438
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 160436.2 (44h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12619992
telemt_connections_bad_total 1466103
telemt_connections_current 1905
telemt_connections_me_current 1905
telemt_handshake_timeouts_total 350061
telemt_upstream_connect_attempt_total 60349
telemt_upstream_connect_success_total 60077
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 60263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30349
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_reconnect_attempts_total 2375
telemt_me_reconnect_success_total 1253
telemt_me_reader_eof_total 1218
telemt_me_idle_close_by_peer_total 1218
telemt_me_route_drop_no_conn_total 4215854
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9544222
telemt_me_endpoint_quarantine_total 1077
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1198
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
telemt_desync_total 39179
telemt_desync_full_logged_total 12790
telemt_desync_suppressed_total 26389
telemt_desync_frames_bucket_total{bucket="1_2"} 9327
telemt_desync_frames_bucket_total{bucket="3_10"} 14509
telemt_desync_frames_bucket_total{bucket="gt_10"} 15343
telemt_pool_swap_total 178
telemt_pool_force_close_total 4913
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 627
telemt_me_draining_writers_reap_progress_total 54318
telemt_me_writer_removed_unexpected_total 1170
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4468
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51054
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4739
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49405
telemt_me_writer_teardown_success_total{mode="normal"} 55522
telemt_me_writer_teardown_noop_total 54320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109842
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.482981
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109842
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 627
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 1096
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 9513353
telemt_user_connections_current{user="hello"} 1905
telemt_user_octets_from_client{user="hello"} 186612030868 (173.80 GB)
telemt_user_octets_to_client{user="hello"} 4201864684644 (3.82 TB)
telemt_user_unique_ips_current{user="hello"} 633
telemt_user_unique_ips_recent_window{user="hello"} 326
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 160432.9 (44h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10940906
telemt_connections_bad_total 1220538
telemt_connections_current 1503
telemt_connections_me_current 1503
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 282645
telemt_upstream_connect_attempt_total 86159
telemt_upstream_connect_success_total 85456
telemt_upstream_connect_fail_total 571
telemt_upstream_connect_attempts_per_request{bucket="1"} 86027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35531
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2038
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 571
telemt_me_reconnect_attempts_total 9074
telemt_me_reconnect_success_total 2098
telemt_me_reader_eof_total 1954
telemt_me_idle_close_by_peer_total 1954
telemt_me_seq_mismatch_total 75
telemt_me_route_drop_no_conn_total 5463412
telemt_me_route_drop_channel_closed_total 351
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8465179
telemt_me_endpoint_quarantine_total 1222
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1202
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
telemt_me_writers_active_current 46
telemt_desync_total 38614
telemt_desync_full_logged_total 12469
telemt_desync_suppressed_total 26145
telemt_desync_frames_bucket_total{bucket="1_2"} 9613
telemt_desync_frames_bucket_total{bucket="3_10"} 14375
telemt_desync_frames_bucket_total{bucket="gt_10"} 14626
telemt_pool_swap_total 170
telemt_pool_force_close_total 4752
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 613
telemt_me_draining_writers_reap_progress_total 53782
telemt_me_writer_removed_unexpected_total 1979
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5570
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50261
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4313
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49030
telemt_me_writer_teardown_success_total{mode="normal"} 55831
telemt_me_writer_teardown_noop_total 53787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109618
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.704580
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109618
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 613
telemt_me_refill_failed_total 358
telemt_me_writer_restored_same_endpoint_total 1697
telemt_me_writer_restored_fallback_total 101
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 8471096
telemt_user_connections_current{user="hello"} 1503
telemt_user_octets_from_client{user="hello"} 148958748401 (138.73 GB)
telemt_user_octets_to_client{user="hello"} 3242185992655 (2.95 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 550
telemt_user_unique_ips_recent_window{user="hello"} 441
```
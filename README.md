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

# Server Metrics 2026-03-23 03:02:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 107787.0 (29h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3686730
telemt_connections_bad_total 352706
telemt_connections_current 1145
telemt_connections_me_current 1145
telemt_handshake_timeouts_total 118512
telemt_upstream_connect_attempt_total 40198
telemt_upstream_connect_success_total 40197
telemt_upstream_connect_attempts_per_request{bucket="1"} 40197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26057
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1425
telemt_me_reconnect_success_total 627
telemt_me_reader_eof_total 644
telemt_me_idle_close_by_peer_total 644
telemt_me_route_drop_no_conn_total 3007299
telemt_me_route_drop_channel_closed_total 1237
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3014696
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 761
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 841
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
telemt_desync_total 12952
telemt_desync_full_logged_total 4115
telemt_desync_suppressed_total 8837
telemt_desync_frames_bucket_total{bucket="1_2"} 3439
telemt_desync_frames_bucket_total{bucket="3_10"} 4729
telemt_desync_frames_bucket_total{bucket="gt_10"} 4784
telemt_pool_swap_total 119
telemt_pool_force_close_total 3636
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 673
telemt_me_draining_writers_reap_progress_total 36814
telemt_me_writer_removed_unexpected_total 621
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2621
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34463
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3580
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33178
telemt_me_writer_teardown_success_total{mode="normal"} 37084
telemt_me_writer_teardown_noop_total 36825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73909
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 379.526932
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73909
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 673
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 562
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 3003587
telemt_user_connections_current{user="hello"} 1145
telemt_user_octets_from_client{user="hello"} 42751235528 (39.82 GB)
telemt_user_octets_to_client{user="hello"} 819547500496 (763.26 GB)
telemt_user_unique_ips_current{user="hello"} 474
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 121153.2 (33h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4037602
telemt_connections_bad_total 372646
telemt_connections_current 358
telemt_connections_me_current 358
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 101531
telemt_upstream_connect_attempt_total 75233
telemt_upstream_connect_success_total 74318
telemt_upstream_connect_fail_total 808
telemt_upstream_connect_attempts_per_request{bucket="1"} 75126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32983
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 808
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10425
telemt_me_reconnect_success_total 3731
telemt_me_reader_eof_total 3716
telemt_me_idle_close_by_peer_total 3716
telemt_me_route_drop_no_conn_total 3646413
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3207890
telemt_me_endpoint_quarantine_total 975
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 952
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
telemt_me_writers_active_current 48
telemt_desync_total 13088
telemt_desync_full_logged_total 7351
telemt_desync_suppressed_total 5737
telemt_desync_frames_bucket_total{bucket="1_2"} 2975
telemt_desync_frames_bucket_total{bucket="3_10"} 5135
telemt_desync_frames_bucket_total{bucket="gt_10"} 4978
telemt_pool_swap_total 114
telemt_pool_force_close_total 3200
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 255
telemt_me_draining_writers_reap_progress_total 50311
telemt_me_writer_removed_unexpected_total 3642
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6485
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47505
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2742
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47111
telemt_me_writer_teardown_success_total{mode="normal"} 53990
telemt_me_writer_teardown_noop_total 50312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104302
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.677158
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104302
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 255
telemt_me_refill_failed_total 262
telemt_me_writer_restored_same_endpoint_total 3312
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 3221243
telemt_user_connections_current{user="hello"} 358
telemt_user_octets_from_client{user="hello"} 43341613158 (40.37 GB)
telemt_user_octets_to_client{user="hello"} 800113956834 (745.16 GB)
telemt_user_msgs_from_client{user="hello"} 49767
telemt_user_msgs_to_client{user="hello"} 185105
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 196013.1 (54h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16434116
telemt_connections_bad_total 1668024
telemt_connections_current 1078
telemt_connections_me_current 1078
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 399457
telemt_upstream_connect_attempt_total 88279
telemt_upstream_connect_success_total 88172
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 88189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43367
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1725
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3054
telemt_me_reconnect_success_total 1628
telemt_me_reader_eof_total 1578
telemt_me_idle_close_by_peer_total 1576
telemt_me_route_drop_no_conn_total 14060568
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13045766
telemt_me_endpoint_quarantine_total 1315
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1479
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
telemt_me_writers_active_current 46
telemt_desync_total 54153
telemt_desync_full_logged_total 17255
telemt_desync_suppressed_total 36898
telemt_desync_frames_bucket_total{bucket="1_2"} 12078
telemt_desync_frames_bucket_total{bucket="3_10"} 21155
telemt_desync_frames_bucket_total{bucket="gt_10"} 20920
telemt_pool_swap_total 212
telemt_pool_force_close_total 6877
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1070
telemt_me_draining_writers_reap_progress_total 67421
telemt_me_writer_removed_unexpected_total 1516
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5688
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62530
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60544
telemt_me_writer_teardown_success_total{mode="normal"} 68218
telemt_me_writer_teardown_noop_total 67474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 128192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 129969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 132364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 135690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 135692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135692
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.979678
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135692
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1070
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1410
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 13045729
telemt_user_connections_current{user="hello"} 1078
telemt_user_octets_from_client{user="hello"} 197898944597 (184.31 GB)
telemt_user_octets_to_client{user="hello"} 3519435118699 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 489
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 196014.4 (54h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11974244
telemt_connections_bad_total 1254760
telemt_connections_current 687
telemt_connections_me_current 687
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 345491
telemt_upstream_connect_attempt_total 102533
telemt_upstream_connect_success_total 101197
telemt_upstream_connect_fail_total 883
telemt_upstream_connect_attempts_per_request{bucket="1"} 102080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43197
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3803
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 883
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4483
telemt_me_reconnect_success_total 1936
telemt_me_reader_eof_total 1802
telemt_me_idle_close_by_peer_total 1802
telemt_me_route_drop_no_conn_total 4567105
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8874222
telemt_me_endpoint_quarantine_total 1330
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1499
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
telemt_me_writers_active_current 45
telemt_desync_total 39081
telemt_desync_full_logged_total 13162
telemt_desync_suppressed_total 25919
telemt_desync_frames_bucket_total{bucket="1_2"} 9678
telemt_desync_frames_bucket_total{bucket="3_10"} 15009
telemt_desync_frames_bucket_total{bucket="gt_10"} 14394
telemt_pool_swap_total 209
telemt_pool_force_close_total 6228
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 715
telemt_me_draining_writers_reap_progress_total 65527
telemt_me_writer_removed_unexpected_total 1829
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5767
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61448
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5716
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59299
telemt_me_writer_teardown_success_total{mode="normal"} 67215
telemt_me_writer_teardown_noop_total 65552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 126001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 129243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 130392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 131583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 132342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 132682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 132757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 132759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 132765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 132767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 132767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 132767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 132767
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.543713
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 132767
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 715
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1656
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 8811932
telemt_user_connections_current{user="hello"} 687
telemt_user_octets_from_client{user="hello"} 218304935584 (203.31 GB)
telemt_user_octets_to_client{user="hello"} 3981753303899 (3.62 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 195978.5 (54h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11131150
telemt_connections_bad_total 995524
telemt_connections_current 621
telemt_connections_me_current 621
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 346281
telemt_upstream_connect_attempt_total 86989
telemt_upstream_connect_success_total 85424
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 85629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41745
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2039
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5804
telemt_me_reconnect_success_total 2423
telemt_me_reader_eof_total 2169
telemt_me_idle_close_by_peer_total 2168
telemt_me_route_drop_no_conn_total 5346463
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8400833
telemt_me_endpoint_quarantine_total 1379
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1460
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_desync_total 38312
telemt_desync_full_logged_total 12700
telemt_desync_suppressed_total 25612
telemt_desync_frames_bucket_total{bucket="1_2"} 9679
telemt_desync_frames_bucket_total{bucket="3_10"} 14669
telemt_desync_frames_bucket_total{bucket="gt_10"} 13964
telemt_pool_swap_total 205
telemt_pool_force_close_total 6122
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 747
telemt_me_draining_writers_reap_progress_total 66054
telemt_me_writer_removed_unexpected_total 2317
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6521
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61784
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5551
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59932
telemt_me_writer_teardown_success_total{mode="normal"} 68305
telemt_me_writer_teardown_noop_total 66125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 133949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 134163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 134291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 134322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 134330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 134343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 134376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 134379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 134430
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.871617
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 134430
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 747
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2110
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 8392743
telemt_user_connections_current{user="hello"} 621
telemt_user_octets_from_client{user="hello"} 193094906563 (179.83 GB)
telemt_user_octets_to_client{user="hello"} 3484463935177 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 66258.5 (18h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11360926
telemt_connections_bad_total 670518
telemt_connections_current 1130
telemt_connections_me_current 1130
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 287823
telemt_upstream_connect_attempt_total 61462
telemt_upstream_connect_success_total 58286
telemt_upstream_connect_fail_total 2056
telemt_upstream_connect_attempts_per_request{bucket="1"} 60342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20889
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6019
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2056
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7890
telemt_me_reconnect_success_total 1337
telemt_me_reader_eof_total 872
telemt_me_idle_close_by_peer_total 871
telemt_me_route_drop_no_conn_total 25308282
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9419873
telemt_me_endpoint_quarantine_total 495
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 531
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
telemt_me_writers_active_current 45
telemt_desync_total 16626
telemt_desync_full_logged_total 4564
telemt_desync_suppressed_total 12062
telemt_desync_frames_bucket_total{bucket="1_2"} 3164
telemt_desync_frames_bucket_total{bucket="3_10"} 6782
telemt_desync_frames_bucket_total{bucket="gt_10"} 6680
telemt_pool_swap_total 68
telemt_pool_force_close_total 2170
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 494
telemt_me_draining_writers_reap_progress_total 21712
telemt_me_writer_removed_unexpected_total 1226
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2810
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20074
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1849
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 321
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19542
telemt_me_writer_teardown_success_total{mode="normal"} 22884
telemt_me_writer_teardown_noop_total 21731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44615
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.025210
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44615
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 494
telemt_me_refill_failed_total 341
telemt_me_writer_restored_same_endpoint_total 881
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 332
telemt_user_connections_total{user="hello"} 9445712
telemt_user_connections_current{user="hello"} 1130
telemt_user_octets_from_client{user="hello"} 87873838506 (81.84 GB)
telemt_user_octets_to_client{user="hello"} 635297063606 (591.67 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 486
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 195985.2 (54h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11084655
telemt_connections_bad_total 967153
telemt_connections_current 940
telemt_connections_me_current 940
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 244431
telemt_upstream_connect_attempt_total 115791
telemt_upstream_connect_success_total 114606
telemt_upstream_connect_fail_total 1010
telemt_upstream_connect_attempts_per_request{bucket="1"} 115616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45222
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1010
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73195
telemt_me_reconnect_success_total 3157
telemt_me_reader_eof_total 2854
telemt_me_idle_close_by_peer_total 2852
telemt_me_route_drop_no_conn_total 5275436
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8735100
telemt_me_endpoint_quarantine_total 1330
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1486
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_me_writers_active_current 46
telemt_desync_total 46566
telemt_desync_full_logged_total 15979
telemt_desync_suppressed_total 30587
telemt_desync_frames_bucket_total{bucket="1_2"} 9465
telemt_desync_frames_bucket_total{bucket="3_10"} 17825
telemt_desync_frames_bucket_total{bucket="gt_10"} 19276
telemt_pool_swap_total 201
telemt_pool_force_close_total 5838
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 672
telemt_me_draining_writers_reap_progress_total 70065
telemt_me_writer_removed_unexpected_total 2874
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7054
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65929
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5089
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64227
telemt_me_writer_teardown_success_total{mode="normal"} 72983
telemt_me_writer_teardown_noop_total 70066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 140895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 142313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 142732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 143005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 143039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 143042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 143042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 143045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 143049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 143049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 143049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 143049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 143049
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.315402
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 143049
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 672
telemt_me_refill_failed_total 4310
telemt_me_writer_restored_same_endpoint_total 2660
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 8737967
telemt_user_connections_current{user="hello"} 940
telemt_user_octets_from_client{user="hello"} 196511311185 (183.02 GB)
telemt_user_octets_to_client{user="hello"} 3338639122080 (3.04 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 132821.5 (36h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11802998
telemt_connections_bad_total 483906
telemt_connections_current 678
telemt_connections_me_current 678
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4784463
telemt_upstream_connect_attempt_total 64466
telemt_upstream_connect_success_total 63999
telemt_upstream_connect_fail_total 454
telemt_upstream_connect_attempts_per_request{bucket="1"} 64453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29841
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 454
telemt_me_reconnect_attempts_total 49144
telemt_me_reconnect_success_total 1894
telemt_me_reader_eof_total 1569
telemt_me_idle_close_by_peer_total 1568
telemt_me_route_drop_no_conn_total 4104089
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5669981
telemt_me_endpoint_quarantine_total 909
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1024
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31874
telemt_desync_full_logged_total 10894
telemt_desync_suppressed_total 20980
telemt_desync_frames_bucket_total{bucket="1_2"} 6361
telemt_desync_frames_bucket_total{bucket="3_10"} 12578
telemt_desync_frames_bucket_total{bucket="gt_10"} 12935
telemt_pool_swap_total 141
telemt_pool_force_close_total 4050
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 383
telemt_me_draining_writers_reap_progress_total 49678
telemt_me_writer_removed_unexpected_total 1614
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3992
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47349
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3606
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45628
telemt_me_writer_teardown_success_total{mode="normal"} 51341
telemt_me_writer_teardown_noop_total 49685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101026
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.735438
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101026
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 383
telemt_me_refill_failed_total 2745
telemt_me_writer_restored_same_endpoint_total 1673
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5662061
telemt_user_connections_current{user="hello"} 678
telemt_user_octets_from_client{user="hello"} 120375820916 (112.11 GB)
telemt_user_octets_to_client{user="hello"} 2204242007582 (2.00 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 113792.1 (31h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1571781
telemt_connections_bad_total 36949
telemt_connections_current 517
telemt_connections_me_current 517
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32370
telemt_upstream_connect_attempt_total 53956
telemt_upstream_connect_success_total 53787
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 53928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27782
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 805
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2367
telemt_me_reconnect_success_total 965
telemt_me_reader_eof_total 956
telemt_me_idle_close_by_peer_total 956
telemt_me_route_drop_no_conn_total 528828
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1397398
telemt_me_endpoint_quarantine_total 966
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 944
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
telemt_desync_total 9781
telemt_desync_full_logged_total 2771
telemt_desync_suppressed_total 7010
telemt_desync_frames_bucket_total{bucket="1_2"} 3020
telemt_desync_frames_bucket_total{bucket="3_10"} 3696
telemt_desync_frames_bucket_total{bucket="gt_10"} 3065
telemt_pool_swap_total 123
telemt_pool_force_close_total 3099
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 173
telemt_me_draining_writers_reap_progress_total 45848
telemt_me_writer_removed_unexpected_total 921
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3483
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43328
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3011
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42749
telemt_me_writer_teardown_success_total{mode="normal"} 46811
telemt_me_writer_teardown_noop_total 45852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92663
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.448008
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92663
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 173
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 823
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 1393133
telemt_user_connections_current{user="hello"} 517
telemt_user_octets_from_client{user="hello"} 26435909621 (24.62 GB)
telemt_user_octets_to_client{user="hello"} 588761113803 (548.33 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 195989.7 (54h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13407045
telemt_connections_bad_total 1625519
telemt_connections_current 762
telemt_connections_me_current 762
telemt_handshake_timeouts_total 391513
telemt_upstream_connect_attempt_total 78375
telemt_upstream_connect_success_total 78020
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 78239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39385
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3074
telemt_me_reconnect_success_total 1551
telemt_me_reader_eof_total 1537
telemt_me_idle_close_by_peer_total 1537
telemt_me_route_drop_no_conn_total 4491866
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10095382
telemt_me_endpoint_quarantine_total 1429
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1485
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
telemt_me_writers_active_current 44
telemt_desync_total 42334
telemt_desync_full_logged_total 13827
telemt_desync_suppressed_total 28507
telemt_desync_frames_bucket_total{bucket="1_2"} 10296
telemt_desync_frames_bucket_total{bucket="3_10"} 15548
telemt_desync_frames_bucket_total{bucket="gt_10"} 16490
telemt_pool_swap_total 217
telemt_pool_force_close_total 5708
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 685
telemt_me_draining_writers_reap_progress_total 70932
telemt_me_writer_removed_unexpected_total 1472
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5508
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66951
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5534
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65224
telemt_me_writer_teardown_success_total{mode="normal"} 72459
telemt_me_writer_teardown_noop_total 70934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 140773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 142501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 142884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 143260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 143380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 143393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 143393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 143393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 143393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 143393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 143393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 143393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 143393
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.840985
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 143393
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 685
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1364
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 10062020
telemt_user_connections_current{user="hello"} 762
telemt_user_octets_from_client{user="hello"} 195172289868 (181.77 GB)
telemt_user_octets_to_client{user="hello"} 4474915678320 (4.07 TB)
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 195986.3 (54h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11712531
telemt_connections_bad_total 1368779
telemt_connections_current 684
telemt_connections_me_current 684
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 313411
telemt_upstream_connect_attempt_total 105994
telemt_upstream_connect_success_total 105081
telemt_upstream_connect_fail_total 705
telemt_upstream_connect_attempts_per_request{bucket="1"} 105786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44962
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 705
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10753
telemt_me_reconnect_success_total 2661
telemt_me_reader_eof_total 2467
telemt_me_idle_close_by_peer_total 2466
telemt_me_seq_mismatch_total 102
telemt_me_route_drop_no_conn_total 5659655
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9012656
telemt_me_endpoint_quarantine_total 1606
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 52
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 1490
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
telemt_me_writers_active_current 45
telemt_desync_total 42093
telemt_desync_full_logged_total 13554
telemt_desync_suppressed_total 28539
telemt_desync_frames_bucket_total{bucket="1_2"} 10922
telemt_desync_frames_bucket_total{bucket="3_10"} 15475
telemt_desync_frames_bucket_total{bucket="gt_10"} 15696
telemt_pool_swap_total 207
telemt_pool_force_close_total 5476
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 673
telemt_me_draining_writers_reap_progress_total 71090
telemt_me_writer_removed_unexpected_total 2507
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6890
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66798
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5005
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65614
telemt_me_writer_teardown_success_total{mode="normal"} 73688
telemt_me_writer_teardown_noop_total 71095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 142091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 143875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 144414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 144733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 144783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 144783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 144783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 144783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 144783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 144783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 144783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 144783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 144783
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.527613
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 144783
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 673
telemt_me_refill_failed_total 419
telemt_me_writer_restored_same_endpoint_total 2131
telemt_me_writer_restored_fallback_total 138
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 9017221
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 157744677716 (146.91 GB)
telemt_user_octets_to_client{user="hello"} 3517237105242 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 92
```
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

# Server Metrics 2026-03-22 16:29:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 69790.2 (19h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2468931
telemt_connections_bad_total 132005
telemt_connections_current 1705
telemt_connections_me_current 1705
telemt_handshake_timeouts_total 87882
telemt_upstream_connect_attempt_total 25797
telemt_upstream_connect_success_total 25796
telemt_upstream_connect_attempts_per_request{bucket="1"} 25796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16762
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 55
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1037
telemt_me_reconnect_success_total 443
telemt_me_reader_eof_total 446
telemt_me_idle_close_by_peer_total 446
telemt_me_route_drop_no_conn_total 1986317
telemt_me_route_drop_channel_closed_total 819
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2102534
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 475
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 547
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
telemt_me_writers_active_current 45
telemt_desync_total 10127
telemt_desync_full_logged_total 3174
telemt_desync_suppressed_total 6953
telemt_desync_frames_bucket_total{bucket="1_2"} 2701
telemt_desync_frames_bucket_total{bucket="3_10"} 3794
telemt_desync_frames_bucket_total{bucket="gt_10"} 3632
telemt_pool_swap_total 77
telemt_pool_force_close_total 2383
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 464
telemt_me_draining_writers_reap_progress_total 23564
telemt_me_writer_removed_unexpected_total 432
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1721
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22062
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2334
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 49
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21181
telemt_me_writer_teardown_success_total{mode="normal"} 23783
telemt_me_writer_teardown_noop_total 23570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47353
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 218.179859
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47353
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 464
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 393
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2099087
telemt_user_connections_current{user="hello"} 1705
telemt_user_octets_from_client{user="hello"} 31793791784 (29.61 GB)
telemt_user_octets_to_client{user="hello"} 560136105356 (521.67 GB)
telemt_user_unique_ips_current{user="hello"} 643
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 83156.3 (23h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3602380
telemt_connections_bad_total 327691
telemt_connections_current 635
telemt_connections_me_current 635
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 89564
telemt_upstream_connect_attempt_total 52255
telemt_upstream_connect_success_total 51617
telemt_upstream_connect_fail_total 566
telemt_upstream_connect_attempts_per_request{bucket="1"} 52183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21459
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 566
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6065
telemt_me_reconnect_success_total 2203
telemt_me_reader_eof_total 2139
telemt_me_idle_close_by_peer_total 2139
telemt_me_route_drop_no_conn_total 3532671
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2854681
telemt_me_endpoint_quarantine_total 665
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 642
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
telemt_me_writers_active_current 52
telemt_desync_total 11145
telemt_desync_full_logged_total 6216
telemt_desync_suppressed_total 4929
telemt_desync_frames_bucket_total{bucket="1_2"} 2594
telemt_desync_frames_bucket_total{bucket="3_10"} 4370
telemt_desync_frames_bucket_total{bucket="gt_10"} 4181
telemt_pool_swap_total 78
telemt_pool_force_close_total 2346
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 198
telemt_me_draining_writers_reap_progress_total 33175
telemt_me_writer_removed_unexpected_total 2094
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3990
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31285
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1990
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 356
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30829
telemt_me_writer_teardown_success_total{mode="normal"} 35275
telemt_me_writer_teardown_noop_total 33175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68450
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.956231
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68450
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 198
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 1911
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 2865948
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 35639354607 (33.19 GB)
telemt_user_octets_to_client{user="hello"} 639518367178 (595.60 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 414
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 158016.4 (43h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15328309
telemt_connections_bad_total 1430316
telemt_connections_current 2285
telemt_connections_me_current 2285
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 372850
telemt_upstream_connect_attempt_total 71379
telemt_upstream_connect_success_total 71284
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 71301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33740
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1673
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2664
telemt_me_reconnect_success_total 1357
telemt_me_reader_eof_total 1296
telemt_me_idle_close_by_peer_total 1294
telemt_me_route_drop_no_conn_total 13807247
telemt_me_route_drop_channel_closed_total 138
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12248587
telemt_me_endpoint_quarantine_total 993
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1178
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 49886
telemt_desync_full_logged_total 15657
telemt_desync_suppressed_total 34229
telemt_desync_frames_bucket_total{bucket="1_2"} 11168
telemt_desync_frames_bucket_total{bucket="3_10"} 19492
telemt_desync_frames_bucket_total{bucket="gt_10"} 19226
telemt_pool_swap_total 170
telemt_pool_force_close_total 5794
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 939
telemt_me_draining_writers_reap_progress_total 51988
telemt_me_writer_removed_unexpected_total 1250
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4529
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48001
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5334
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46194
telemt_me_writer_teardown_success_total{mode="normal"} 52530
telemt_me_writer_teardown_noop_total 52038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104568
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 298.936679
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104568
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 939
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 1164
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 12249754
telemt_user_connections_current{user="hello"} 2285
telemt_user_octets_from_client{user="hello"} 173955831845 (162.01 GB)
telemt_user_octets_to_client{user="hello"} 3167771083543 (2.88 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 924
telemt_user_unique_ips_recent_window{user="hello"} 281
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 158018.1 (43h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11059292
telemt_connections_bad_total 1073139
telemt_connections_current 1442
telemt_connections_me_current 1442
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 328176
telemt_upstream_connect_attempt_total 83560
telemt_upstream_connect_success_total 82404
telemt_upstream_connect_fail_total 832
telemt_upstream_connect_attempts_per_request{bucket="1"} 83236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33595
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3695
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 832
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3934
telemt_me_reconnect_success_total 1598
telemt_me_reader_eof_total 1469
telemt_me_idle_close_by_peer_total 1469
telemt_me_route_drop_no_conn_total 4361175
telemt_me_route_drop_channel_closed_total 478
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8248639
telemt_me_endpoint_quarantine_total 994
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1196
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
telemt_desync_total 36635
telemt_desync_full_logged_total 12309
telemt_desync_suppressed_total 24326
telemt_desync_frames_bucket_total{bucket="1_2"} 8985
telemt_desync_frames_bucket_total{bucket="3_10"} 14120
telemt_desync_frames_bucket_total{bucket="gt_10"} 13530
telemt_pool_swap_total 168
telemt_pool_force_close_total 5212
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 666
telemt_me_draining_writers_reap_progress_total 50267
telemt_me_writer_removed_unexpected_total 1498
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4630
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46995
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4736
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 476
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45055
telemt_me_writer_teardown_success_total{mode="normal"} 51625
telemt_me_writer_teardown_noop_total 50285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101910
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.270417
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101910
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 666
telemt_me_refill_failed_total 126
telemt_me_writer_restored_same_endpoint_total 1360
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8187319
telemt_user_connections_current{user="hello"} 1442
telemt_user_octets_from_client{user="hello"} 204748202517 (190.69 GB)
telemt_user_octets_to_client{user="hello"} 3692276359306 (3.36 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 575
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 157981.8 (43h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10454681
telemt_connections_bad_total 899874
telemt_connections_current 1157
telemt_connections_me_current 1157
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 333820
telemt_upstream_connect_attempt_total 68762
telemt_upstream_connect_success_total 67802
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 67984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32128
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2075
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4673
telemt_me_reconnect_success_total 1891
telemt_me_reader_eof_total 1645
telemt_me_idle_close_by_peer_total 1644
telemt_me_route_drop_no_conn_total 5133142
telemt_me_route_drop_channel_closed_total 359
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7895137
telemt_me_endpoint_quarantine_total 1080
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1162
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
telemt_desync_total 36154
telemt_desync_full_logged_total 11979
telemt_desync_suppressed_total 24175
telemt_desync_frames_bucket_total{bucket="1_2"} 9147
telemt_desync_frames_bucket_total{bucket="3_10"} 13818
telemt_desync_frames_bucket_total{bucket="gt_10"} 13189
telemt_pool_swap_total 165
telemt_pool_force_close_total 5161
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 685
telemt_me_draining_writers_reap_progress_total 50621
telemt_me_writer_removed_unexpected_total 1785
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5068
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47250
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4619
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45460
telemt_me_writer_teardown_success_total{mode="normal"} 52318
telemt_me_writer_teardown_noop_total 50692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103010
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3170.565158
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103010
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 685
telemt_me_refill_failed_total 147
telemt_me_writer_restored_same_endpoint_total 1635
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 7888086
telemt_user_connections_current{user="hello"} 1157
telemt_user_octets_from_client{user="hello"} 181721232665 (169.24 GB)
telemt_user_octets_to_client{user="hello"} 3279218139665 (2.98 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 483
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 28262.3 (7h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10160756
telemt_connections_bad_total 620873
telemt_connections_current 2158
telemt_connections_me_current 2158
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 188647
telemt_upstream_connect_attempt_total 35853
telemt_upstream_connect_success_total 34059
telemt_upstream_connect_fail_total 1254
telemt_upstream_connect_attempts_per_request{bucket="1"} 35313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9322
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5301
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1254
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5891
telemt_me_reconnect_success_total 713
telemt_me_reader_eof_total 456
telemt_me_idle_close_by_peer_total 456
telemt_me_route_drop_no_conn_total 24934245
telemt_me_route_drop_channel_closed_total 46
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8458341
telemt_me_endpoint_quarantine_total 175
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 223
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 13216
telemt_desync_full_logged_total 3410
telemt_desync_suppressed_total 9806
telemt_desync_frames_bucket_total{bucket="1_2"} 2357
telemt_desync_frames_bucket_total{bucket="3_10"} 5375
telemt_desync_frames_bucket_total{bucket="gt_10"} 5484
telemt_pool_swap_total 27
telemt_pool_force_close_total 1067
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 366
telemt_me_draining_writers_reap_progress_total 7751
telemt_me_writer_removed_unexpected_total 616
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1283
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7049
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 787
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 280
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6684
telemt_me_writer_teardown_success_total{mode="normal"} 8332
telemt_me_writer_teardown_noop_total 7756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 15121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 15693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 15963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16088
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 36.830559
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16088
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 366
telemt_me_refill_failed_total 293
telemt_me_writer_restored_same_endpoint_total 488
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8476403
telemt_user_connections_current{user="hello"} 2158
telemt_user_octets_from_client{user="hello"} 63862942326 (59.48 GB)
telemt_user_octets_to_client{user="hello"} 304054792112 (283.17 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 797
telemt_user_unique_ips_recent_window{user="hello"} 302
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 157988.6 (43h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10248512
telemt_connections_bad_total 859355
telemt_connections_current 1909
telemt_connections_me_current 1909
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 227768
telemt_upstream_connect_attempt_total 97530
telemt_upstream_connect_success_total 96540
telemt_upstream_connect_fail_total 843
telemt_upstream_connect_attempts_per_request{bucket="1"} 97383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35356
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1305
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 843
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71836
telemt_me_reconnect_success_total 2616
telemt_me_reader_eof_total 2320
telemt_me_idle_close_by_peer_total 2319
telemt_me_route_drop_no_conn_total 5061891
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8081107
telemt_me_endpoint_quarantine_total 1065
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1178
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
telemt_me_writers_active_current 44
telemt_desync_total 42132
telemt_desync_full_logged_total 14376
telemt_desync_suppressed_total 27756
telemt_desync_frames_bucket_total{bucket="1_2"} 8572
telemt_desync_frames_bucket_total{bucket="3_10"} 16295
telemt_desync_frames_bucket_total{bucket="gt_10"} 17265
telemt_pool_swap_total 161
telemt_pool_force_close_total 4795
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 603
telemt_me_draining_writers_reap_progress_total 53761
telemt_me_writer_removed_unexpected_total 2363
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5748
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50397
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4110
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 685
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48966
telemt_me_writer_teardown_success_total{mode="normal"} 56145
telemt_me_writer_teardown_noop_total 53762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109907
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.453440
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109907
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 603
telemt_me_refill_failed_total 4268
telemt_me_writer_restored_same_endpoint_total 2197
telemt_me_writer_restored_fallback_total 44
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7360
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 8085044
telemt_user_connections_current{user="hello"} 1909
telemt_user_octets_from_client{user="hello"} 183121210213 (170.54 GB)
telemt_user_octets_to_client{user="hello"} 3044488187504 (2.77 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 710
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 94824.6 (26h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10665444
telemt_connections_bad_total 399616
telemt_connections_current 1363
telemt_connections_me_current 1363
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4479238
telemt_upstream_connect_attempt_total 45667
telemt_upstream_connect_success_total 45335
telemt_upstream_connect_fail_total 323
telemt_upstream_connect_attempts_per_request{bucket="1"} 45658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 323
telemt_me_reconnect_attempts_total 48084
telemt_me_reconnect_success_total 1515
telemt_me_reader_eof_total 1180
telemt_me_idle_close_by_peer_total 1179
telemt_me_route_drop_no_conn_total 3917884
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5112589
telemt_me_endpoint_quarantine_total 619
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 715
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
telemt_me_writers_active_current 50
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 28029
telemt_desync_full_logged_total 9474
telemt_desync_suppressed_total 18555
telemt_desync_frames_bucket_total{bucket="1_2"} 5641
telemt_desync_frames_bucket_total{bucket="3_10"} 11060
telemt_desync_frames_bucket_total{bucket="gt_10"} 11328
telemt_pool_swap_total 100
telemt_pool_force_close_total 3081
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 313
telemt_me_draining_writers_reap_progress_total 32657
telemt_me_writer_removed_unexpected_total 1243
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2936
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30994
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2662
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29576
telemt_me_writer_teardown_success_total{mode="normal"} 33930
telemt_me_writer_teardown_noop_total 32664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66594
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.886057
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66594
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 313
telemt_me_refill_failed_total 2707
telemt_me_writer_restored_same_endpoint_total 1348
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5106092
telemt_user_connections_current{user="hello"} 1363
telemt_user_octets_from_client{user="hello"} 109836791808 (102.29 GB)
telemt_user_octets_to_client{user="hello"} 1929554542642 (1.75 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 545
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 75795.6 (21h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1021716
telemt_connections_bad_total 15098
telemt_connections_current 921
telemt_connections_me_current 921
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 19614
telemt_upstream_connect_attempt_total 37264
telemt_upstream_connect_success_total 37167
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 37247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19780
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 531
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_reconnect_attempts_total 1720
telemt_me_reconnect_success_total 713
telemt_me_reader_eof_total 688
telemt_me_idle_close_by_peer_total 688
telemt_me_route_drop_no_conn_total 357200
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 909792
telemt_me_endpoint_quarantine_total 652
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 626
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 5097
telemt_desync_full_logged_total 1564
telemt_desync_suppressed_total 3533
telemt_desync_frames_bucket_total{bucket="1_2"} 1199
telemt_desync_frames_bucket_total{bucket="3_10"} 2025
telemt_desync_frames_bucket_total{bucket="gt_10"} 1873
telemt_pool_swap_total 81
telemt_pool_force_close_total 2053
telemt_me_writer_close_signal_drop_total 119
telemt_me_draining_writers_reap_progress_total 30876
telemt_me_writer_removed_unexpected_total 664
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2392
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29174
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1972
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28823
telemt_me_writer_teardown_success_total{mode="normal"} 31566
telemt_me_writer_teardown_noop_total 30879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62445
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.753521
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62445
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 119
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 606
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 906326
telemt_user_connections_current{user="hello"} 921
telemt_user_octets_from_client{user="hello"} 16370637417 (15.25 GB)
telemt_user_octets_to_client{user="hello"} 400823026759 (373.30 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 287
telemt_user_unique_ips_recent_window{user="hello"} 278
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 157993.6 (43h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12519828
telemt_connections_bad_total 1450011
telemt_connections_current 1980
telemt_connections_me_current 1980
telemt_handshake_timeouts_total 345661
telemt_upstream_connect_attempt_total 59355
telemt_upstream_connect_success_total 59117
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 59298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29856
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_reconnect_attempts_total 2337
telemt_me_reconnect_success_total 1233
telemt_me_reader_eof_total 1197
telemt_me_idle_close_by_peer_total 1197
telemt_me_route_drop_no_conn_total 4178346
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9468537
telemt_me_endpoint_quarantine_total 1069
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1181
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
telemt_me_writers_active_current 46
telemt_desync_total 38837
telemt_desync_full_logged_total 12681
telemt_desync_suppressed_total 26156
telemt_desync_frames_bucket_total{bucket="1_2"} 9233
telemt_desync_frames_bucket_total{bucket="3_10"} 14391
telemt_desync_frames_bucket_total{bucket="gt_10"} 15213
telemt_pool_swap_total 175
telemt_pool_force_close_total 4831
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 619
telemt_me_draining_writers_reap_progress_total 53459
telemt_me_writer_removed_unexpected_total 1150
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4379
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50263
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4658
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48628
telemt_me_writer_teardown_success_total{mode="normal"} 54642
telemt_me_writer_teardown_noop_total 53461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108103
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.083325
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108103
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 619
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 1077
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 9437767
telemt_user_connections_current{user="hello"} 1980
telemt_user_octets_from_client{user="hello"} 185355733400 (172.63 GB)
telemt_user_octets_to_client{user="hello"} 4165902321560 (3.79 TB)
telemt_user_unique_ips_current{user="hello"} 727
telemt_user_unique_ips_recent_window{user="hello"} 258
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 157989.6 (43h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10853683
telemt_connections_bad_total 1213563
telemt_connections_current 1458
telemt_connections_me_current 1458
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 280142
telemt_upstream_connect_attempt_total 85134
telemt_upstream_connect_success_total 84489
telemt_upstream_connect_fail_total 554
telemt_upstream_connect_attempts_per_request{bucket="1"} 85043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35090
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2029
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 554
telemt_me_reconnect_attempts_total 8941
telemt_me_reconnect_success_total 2061
telemt_me_reader_eof_total 1921
telemt_me_idle_close_by_peer_total 1921
telemt_me_seq_mismatch_total 74
telemt_me_route_drop_no_conn_total 5419838
telemt_me_route_drop_channel_closed_total 348
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8391218
telemt_me_endpoint_quarantine_total 1202
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1183
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
telemt_me_writers_active_current 44
telemt_desync_total 38293
telemt_desync_full_logged_total 12370
telemt_desync_suppressed_total 25923
telemt_desync_frames_bucket_total{bucket="1_2"} 9519
telemt_desync_frames_bucket_total{bucket="3_10"} 14270
telemt_desync_frames_bucket_total{bucket="gt_10"} 14504
telemt_pool_swap_total 167
telemt_pool_force_close_total 4672
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 607
telemt_me_draining_writers_reap_progress_total 52921
telemt_me_writer_removed_unexpected_total 1946
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5480
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49456
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4233
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48249
telemt_me_writer_teardown_success_total{mode="normal"} 54936
telemt_me_writer_teardown_noop_total 52926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107862
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.587961
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107862
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 607
telemt_me_refill_failed_total 353
telemt_me_writer_restored_same_endpoint_total 1672
telemt_me_writer_restored_fallback_total 99
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 8397188
telemt_user_connections_current{user="hello"} 1458
telemt_user_octets_from_client{user="hello"} 147758864921 (137.61 GB)
telemt_user_octets_to_client{user="hello"} 3208818664143 (2.92 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 558
telemt_user_unique_ips_recent_window{user="hello"} 255
```
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

# Server Metrics 2026-03-22 17:05:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 71928.2 (19h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2589610
telemt_connections_bad_total 139260
telemt_connections_current 1734
telemt_connections_me_current 1734
telemt_handshake_timeouts_total 90089
telemt_upstream_connect_attempt_total 26494
telemt_upstream_connect_success_total 26493
telemt_upstream_connect_attempts_per_request{bucket="1"} 26493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17202
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 59
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1066
telemt_me_reconnect_success_total 456
telemt_me_reader_eof_total 458
telemt_me_idle_close_by_peer_total 458
telemt_me_route_drop_no_conn_total 2163193
telemt_me_route_drop_channel_closed_total 881
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2209125
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 485
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 562
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
telemt_me_writers_active_current 49
telemt_desync_total 10318
telemt_desync_full_logged_total 3258
telemt_desync_suppressed_total 7060
telemt_desync_frames_bucket_total{bucket="1_2"} 2764
telemt_desync_frames_bucket_total{bucket="3_10"} 3851
telemt_desync_frames_bucket_total{bucket="gt_10"} 3703
telemt_pool_swap_total 79
telemt_pool_force_close_total 2457
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 484
telemt_me_draining_writers_reap_progress_total 24192
telemt_me_writer_removed_unexpected_total 444
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1762
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22647
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2406
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21735
telemt_me_writer_teardown_success_total{mode="normal"} 24409
telemt_me_writer_teardown_noop_total 24198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48607
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 235.413721
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48607
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 484
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 404
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 2205496
telemt_user_connections_current{user="hello"} 1734
telemt_user_octets_from_client{user="hello"} 32678127768 (30.43 GB)
telemt_user_octets_to_client{user="hello"} 580266976820 (540.42 GB)
telemt_user_unique_ips_current{user="hello"} 626
telemt_user_unique_ips_recent_window{user="hello"} 269
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 85294.8 (23h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3644171
telemt_connections_bad_total 330020
telemt_connections_current 1181
telemt_connections_me_current 1181
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 91000
telemt_upstream_connect_attempt_total 53171
telemt_upstream_connect_success_total 52511
telemt_upstream_connect_fail_total 580
telemt_upstream_connect_attempts_per_request{bucket="1"} 53091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 580
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6130
telemt_me_reconnect_success_total 2232
telemt_me_reader_eof_total 2166
telemt_me_idle_close_by_peer_total 2166
telemt_me_route_drop_no_conn_total 3544801
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2890545
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
telemt_desync_total 11357
telemt_desync_full_logged_total 6337
telemt_desync_suppressed_total 5020
telemt_desync_frames_bucket_total{bucket="1_2"} 2646
telemt_desync_frames_bucket_total{bucket="3_10"} 4454
telemt_desync_frames_bucket_total{bucket="gt_10"} 4257
telemt_pool_swap_total 80
telemt_pool_force_close_total 2404
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 203
telemt_me_draining_writers_reap_progress_total 33972
telemt_me_writer_removed_unexpected_total 2119
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4069
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32030
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2044
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 360
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31568
telemt_me_writer_teardown_success_total{mode="normal"} 36099
telemt_me_writer_teardown_noop_total 33972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70071
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.130684
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70071
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 203
telemt_me_refill_failed_total 153
telemt_me_writer_restored_same_endpoint_total 1932
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 2901782
telemt_user_connections_current{user="hello"} 1181
telemt_user_octets_from_client{user="hello"} 36515771563 (34.01 GB)
telemt_user_octets_to_client{user="hello"} 655635928682 (610.61 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 675
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 160154.6 (44h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15452489
telemt_connections_bad_total 1462424
telemt_connections_current 2403
telemt_connections_me_current 2403
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 377192
telemt_upstream_connect_attempt_total 72114
telemt_upstream_connect_success_total 72018
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 72035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34165
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1676
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2687
telemt_me_reconnect_success_total 1377
telemt_me_reader_eof_total 1316
telemt_me_idle_close_by_peer_total 1314
telemt_me_route_drop_no_conn_total 13836040
telemt_me_route_drop_channel_closed_total 140
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12330250
telemt_me_endpoint_quarantine_total 1007
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1192
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
telemt_desync_total 50365
telemt_desync_full_logged_total 15823
telemt_desync_suppressed_total 34542
telemt_desync_frames_bucket_total{bucket="1_2"} 11244
telemt_desync_frames_bucket_total{bucket="3_10"} 19670
telemt_desync_frames_bucket_total{bucket="gt_10"} 19451
telemt_pool_swap_total 172
telemt_pool_force_close_total 5849
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 943
telemt_me_draining_writers_reap_progress_total 52638
telemt_me_writer_removed_unexpected_total 1270
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4595
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48604
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5389
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46789
telemt_me_writer_teardown_success_total{mode="normal"} 53199
telemt_me_writer_teardown_noop_total 52688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105887
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 301.813384
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105887
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 943
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 1183
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 12331338
telemt_user_connections_current{user="hello"} 2403
telemt_user_octets_from_client{user="hello"} 176197417425 (164.10 GB)
telemt_user_octets_to_client{user="hello"} 3198841354887 (2.91 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 1013
telemt_user_unique_ips_recent_window{user="hello"} 283
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 160156.1 (44h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11144022
telemt_connections_bad_total 1083356
telemt_connections_current 1579
telemt_connections_me_current 1579
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 332723
telemt_upstream_connect_attempt_total 84317
telemt_upstream_connect_success_total 83159
telemt_upstream_connect_fail_total 834
telemt_upstream_connect_attempts_per_request{bucket="1"} 83993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34027
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3696
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 834
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3954
telemt_me_reconnect_success_total 1617
telemt_me_reader_eof_total 1489
telemt_me_idle_close_by_peer_total 1489
telemt_me_route_drop_no_conn_total 4381083
telemt_me_route_drop_channel_closed_total 481
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8309101
telemt_me_endpoint_quarantine_total 1007
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1209
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
telemt_desync_total 36928
telemt_desync_full_logged_total 12421
telemt_desync_suppressed_total 24507
telemt_desync_frames_bucket_total{bucket="1_2"} 9063
telemt_desync_frames_bucket_total{bucket="3_10"} 14238
telemt_desync_frames_bucket_total{bucket="gt_10"} 13627
telemt_pool_swap_total 170
telemt_pool_force_close_total 5273
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 667
telemt_me_draining_writers_reap_progress_total 50934
telemt_me_writer_removed_unexpected_total 1517
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4691
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47621
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4795
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 478
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45661
telemt_me_writer_teardown_success_total{mode="normal"} 52312
telemt_me_writer_teardown_noop_total 50952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103264
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.292526
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103264
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 667
telemt_me_refill_failed_total 126
telemt_me_writer_restored_same_endpoint_total 1379
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8247698
telemt_user_connections_current{user="hello"} 1579
telemt_user_octets_from_client{user="hello"} 206043700637 (191.89 GB)
telemt_user_octets_to_client{user="hello"} 3715633939498 (3.38 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 634
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 160120.1 (44h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10525209
telemt_connections_bad_total 908577
telemt_connections_current 1387
telemt_connections_me_current 1387
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 336356
telemt_upstream_connect_attempt_total 69552
telemt_upstream_connect_success_total 68567
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 68749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32546
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1368
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2088
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4753
telemt_me_reconnect_success_total 1919
telemt_me_reader_eof_total 1670
telemt_me_idle_close_by_peer_total 1669
telemt_me_route_drop_no_conn_total 5155647
telemt_me_route_drop_channel_closed_total 365
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7942093
telemt_me_endpoint_quarantine_total 1094
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1178
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
telemt_me_writers_active_current 44
telemt_desync_total 36402
telemt_desync_full_logged_total 12048
telemt_desync_suppressed_total 24354
telemt_desync_frames_bucket_total{bucket="1_2"} 9218
telemt_desync_frames_bucket_total{bucket="3_10"} 13914
telemt_desync_frames_bucket_total{bucket="gt_10"} 13270
telemt_pool_swap_total 167
telemt_pool_force_close_total 5215
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 685
telemt_me_draining_writers_reap_progress_total 51296
telemt_me_writer_removed_unexpected_total 1812
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5145
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47876
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4673
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46081
telemt_me_writer_teardown_success_total{mode="normal"} 53021
telemt_me_writer_teardown_noop_total 51367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104388
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3171.811942
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104388
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 685
telemt_me_refill_failed_total 150
telemt_me_writer_restored_same_endpoint_total 1658
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 7934952
telemt_user_connections_current{user="hello"} 1383
telemt_user_octets_from_client{user="hello"} 183370083605 (170.78 GB)
telemt_user_octets_to_client{user="hello"} 3300341972173 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 515
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 30400.0 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10284561
telemt_connections_bad_total 627004
telemt_connections_current 2229
telemt_connections_me_current 2229
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 196446
telemt_upstream_connect_attempt_total 40626
telemt_upstream_connect_success_total 38560
telemt_upstream_connect_fail_total 1475
telemt_upstream_connect_attempts_per_request{bucket="1"} 40035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11316
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5914
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1475
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6077
telemt_me_reconnect_success_total 774
telemt_me_reader_eof_total 475
telemt_me_idle_close_by_peer_total 475
telemt_me_route_drop_no_conn_total 24983870
telemt_me_route_drop_channel_closed_total 50
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8554102
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
telemt_desync_total 13445
telemt_desync_full_logged_total 3486
telemt_desync_suppressed_total 9959
telemt_desync_frames_bucket_total{bucket="1_2"} 2440
telemt_desync_frames_bucket_total{bucket="3_10"} 5461
telemt_desync_frames_bucket_total{bucket="gt_10"} 5544
telemt_pool_swap_total 29
telemt_pool_force_close_total 1126
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 376
telemt_me_draining_writers_reap_progress_total 8410
telemt_me_writer_removed_unexpected_total 679
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1382
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7672
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 844
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 282
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7284
telemt_me_writer_teardown_success_total{mode="normal"} 9054
telemt_me_writer_teardown_noop_total 8415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 14649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 15998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 17071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 17344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 17442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 17469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 17469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 17469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 17469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 17469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 17469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 17469
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 37.525839
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 17469
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 376
telemt_me_refill_failed_total 293
telemt_me_writer_restored_same_endpoint_total 518
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 8575859
telemt_user_connections_current{user="hello"} 2229
telemt_user_octets_from_client{user="hello"} 66616060139 (62.04 GB)
telemt_user_octets_to_client{user="hello"} 337359191329 (314.19 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 810
telemt_user_unique_ips_recent_window{user="hello"} 309
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 160126.7 (44h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10328049
telemt_connections_bad_total 868431
telemt_connections_current 1826
telemt_connections_me_current 1826
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 228860
telemt_upstream_connect_attempt_total 98314
telemt_upstream_connect_success_total 97299
telemt_upstream_connect_fail_total 864
telemt_upstream_connect_attempts_per_request{bucket="1"} 98163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35751
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1310
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 864
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72056
telemt_me_reconnect_success_total 2637
telemt_me_reader_eof_total 2340
telemt_me_idle_close_by_peer_total 2338
telemt_me_route_drop_no_conn_total 5086782
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8146085
telemt_me_endpoint_quarantine_total 1076
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 1191
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
telemt_desync_total 42533
telemt_desync_full_logged_total 14518
telemt_desync_suppressed_total 28015
telemt_desync_frames_bucket_total{bucket="1_2"} 8646
telemt_desync_frames_bucket_total{bucket="3_10"} 16425
telemt_desync_frames_bucket_total{bucket="gt_10"} 17462
telemt_pool_swap_total 163
telemt_pool_force_close_total 4850
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 613
telemt_me_draining_writers_reap_progress_total 54446
telemt_me_writer_removed_unexpected_total 2383
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5810
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51040
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4165
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 685
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49596
telemt_me_writer_teardown_success_total{mode="normal"} 56850
telemt_me_writer_teardown_noop_total 54447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111297
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.526722
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111297
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 613
telemt_me_refill_failed_total 4279
telemt_me_writer_restored_same_endpoint_total 2209
telemt_me_writer_restored_fallback_total 45
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7365
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 8149925
telemt_user_connections_current{user="hello"} 1826
telemt_user_octets_from_client{user="hello"} 184389043845 (171.73 GB)
telemt_user_octets_to_client{user="hello"} 3073821203640 (2.80 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 729
telemt_user_unique_ips_recent_window{user="hello"} 252
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 96962.8 (26h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10767491
telemt_connections_bad_total 407394
telemt_connections_current 1539
telemt_connections_me_current 1539
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4505669
telemt_upstream_connect_attempt_total 46526
telemt_upstream_connect_success_total 46185
telemt_upstream_connect_fail_total 331
telemt_upstream_connect_attempts_per_request{bucket="1"} 46516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 331
telemt_me_reconnect_attempts_total 48171
telemt_me_reconnect_success_total 1528
telemt_me_reader_eof_total 1195
telemt_me_idle_close_by_peer_total 1194
telemt_me_route_drop_no_conn_total 3939007
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5166276
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 28486
telemt_desync_full_logged_total 9627
telemt_desync_suppressed_total 18859
telemt_desync_frames_bucket_total{bucket="1_2"} 5740
telemt_desync_frames_bucket_total{bucket="3_10"} 11231
telemt_desync_frames_bucket_total{bucket="gt_10"} 11515
telemt_pool_swap_total 102
telemt_pool_force_close_total 3135
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 324
telemt_me_draining_writers_reap_progress_total 33424
telemt_me_writer_removed_unexpected_total 1257
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2993
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31719
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2716
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30289
telemt_me_writer_teardown_success_total{mode="normal"} 34712
telemt_me_writer_teardown_noop_total 33431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68143
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.946052
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68143
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 324
telemt_me_refill_failed_total 2711
telemt_me_writer_restored_same_endpoint_total 1358
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5159672
telemt_user_connections_current{user="hello"} 1539
telemt_user_octets_from_client{user="hello"} 111334695724 (103.69 GB)
telemt_user_octets_to_client{user="hello"} 1951060244734 (1.77 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 612
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 77933.6 (21h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1075098
telemt_connections_bad_total 16282
telemt_connections_current 1187
telemt_connections_me_current 1187
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 20354
telemt_upstream_connect_attempt_total 37985
telemt_upstream_connect_success_total 37876
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 37961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 564
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_reconnect_attempts_total 1738
telemt_me_reconnect_success_total 730
telemt_me_reader_eof_total 705
telemt_me_idle_close_by_peer_total 705
telemt_me_route_drop_no_conn_total 375643
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 957477
telemt_me_endpoint_quarantine_total 660
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 643
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
telemt_me_writers_active_current 44
telemt_desync_total 5437
telemt_desync_full_logged_total 1674
telemt_desync_suppressed_total 3763
telemt_desync_frames_bucket_total{bucket="1_2"} 1266
telemt_desync_frames_bucket_total{bucket="3_10"} 2159
telemt_desync_frames_bucket_total{bucket="gt_10"} 2012
telemt_pool_swap_total 83
telemt_pool_force_close_total 2117
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 31481
telemt_me_writer_removed_unexpected_total 681
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2442
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29746
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2035
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 82
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29364
telemt_me_writer_teardown_success_total{mode="normal"} 32188
telemt_me_writer_teardown_noop_total 31484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63672
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.785381
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63672
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 621
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 953959
telemt_user_connections_current{user="hello"} 1187
telemt_user_octets_from_client{user="hello"} 17740457029 (16.52 GB)
telemt_user_octets_to_client{user="hello"} 414666126367 (386.19 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 428
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 160131.2 (44h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12606715
telemt_connections_bad_total 1463489
telemt_connections_current 1999
telemt_connections_me_current 1999
telemt_handshake_timeouts_total 349512
telemt_upstream_connect_attempt_total 60169
telemt_upstream_connect_success_total 59901
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 60086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30263
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_reconnect_attempts_total 2370
telemt_me_reconnect_success_total 1249
telemt_me_reader_eof_total 1214
telemt_me_idle_close_by_peer_total 1214
telemt_me_route_drop_no_conn_total 4212660
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9534535
telemt_me_endpoint_quarantine_total 1072
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1194
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
telemt_desync_total 39141
telemt_desync_full_logged_total 12772
telemt_desync_suppressed_total 26369
telemt_desync_frames_bucket_total{bucket="1_2"} 9315
telemt_desync_frames_bucket_total{bucket="3_10"} 14493
telemt_desync_frames_bucket_total{bucket="gt_10"} 15333
telemt_pool_swap_total 177
telemt_pool_force_close_total 4891
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 624
telemt_me_draining_writers_reap_progress_total 54171
telemt_me_writer_removed_unexpected_total 1166
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4446
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50925
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4717
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49280
telemt_me_writer_teardown_success_total{mode="normal"} 55371
telemt_me_writer_teardown_noop_total 54173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109544
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.358012
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109544
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 624
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 1092
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 9503717
telemt_user_connections_current{user="hello"} 1999
telemt_user_octets_from_client{user="hello"} 186426133432 (173.62 GB)
telemt_user_octets_to_client{user="hello"} 4196308084620 (3.82 TB)
telemt_user_unique_ips_current{user="hello"} 693
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 160127.8 (44h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10929818
telemt_connections_bad_total 1220063
telemt_connections_current 1782
telemt_connections_me_current 1782
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 282111
telemt_upstream_connect_attempt_total 85992
telemt_upstream_connect_success_total 85298
telemt_upstream_connect_fail_total 568
telemt_upstream_connect_attempts_per_request{bucket="1"} 85866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35459
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 568
telemt_me_reconnect_attempts_total 9032
telemt_me_reconnect_success_total 2094
telemt_me_reader_eof_total 1950
telemt_me_idle_close_by_peer_total 1950
telemt_me_seq_mismatch_total 75
telemt_me_route_drop_no_conn_total 5457108
telemt_me_route_drop_channel_closed_total 350
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8455600
telemt_me_endpoint_quarantine_total 1219
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1197
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
telemt_me_writers_active_current 44
telemt_desync_total 38554
telemt_desync_full_logged_total 12457
telemt_desync_suppressed_total 26097
telemt_desync_frames_bucket_total{bucket="1_2"} 9596
telemt_desync_frames_bucket_total{bucket="3_10"} 14355
telemt_desync_frames_bucket_total{bucket="gt_10"} 14603
telemt_pool_swap_total 169
telemt_pool_force_close_total 4725
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 610
telemt_me_draining_writers_reap_progress_total 53632
telemt_me_writer_removed_unexpected_total 1975
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5549
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50128
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4286
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48907
telemt_me_writer_teardown_success_total{mode="normal"} 55677
telemt_me_writer_teardown_noop_total 53637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109314
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.628688
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109314
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 610
telemt_me_refill_failed_total 356
telemt_me_writer_restored_same_endpoint_total 1695
telemt_me_writer_restored_fallback_total 101
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 8461528
telemt_user_connections_current{user="hello"} 1782
telemt_user_octets_from_client{user="hello"} 148839766833 (138.62 GB)
telemt_user_octets_to_client{user="hello"} 3236620575411 (2.94 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 667
telemt_user_unique_ips_recent_window{user="hello"} 200
```
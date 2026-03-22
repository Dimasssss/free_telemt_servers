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

# Server Metrics 2026-03-22 18:47:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 78084.3 (21h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2874477
telemt_connections_bad_total 181150
telemt_connections_current 1681
telemt_connections_me_current 1681
telemt_handshake_timeouts_total 97010
telemt_upstream_connect_attempt_total 28554
telemt_upstream_connect_success_total 28553
telemt_upstream_connect_attempts_per_request{bucket="1"} 28553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18556
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 68
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1152
telemt_me_reconnect_success_total 485
telemt_me_reader_eof_total 488
telemt_me_idle_close_by_peer_total 488
telemt_me_route_drop_no_conn_total 2383848
telemt_me_route_drop_channel_closed_total 994
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2435914
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 522
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 606
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
telemt_desync_total 10846
telemt_desync_full_logged_total 3440
telemt_desync_suppressed_total 7406
telemt_desync_frames_bucket_total{bucket="1_2"} 2913
telemt_desync_frames_bucket_total{bucket="3_10"} 4022
telemt_desync_frames_bucket_total{bucket="gt_10"} 3911
telemt_pool_swap_total 86
telemt_pool_force_close_total 2680
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 553
telemt_me_draining_writers_reap_progress_total 26092
telemt_me_writer_removed_unexpected_total 474
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1905
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24404
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2627
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23412
telemt_me_writer_teardown_success_total{mode="normal"} 26309
telemt_me_writer_teardown_noop_total 26102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52411
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 276.406528
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52411
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 553
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 430
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2431800
telemt_user_connections_current{user="hello"} 1681
telemt_user_octets_from_client{user="hello"} 35372130092 (32.94 GB)
telemt_user_octets_to_client{user="hello"} 641090466680 (597.06 GB)
telemt_user_unique_ips_current{user="hello"} 616
telemt_user_unique_ips_recent_window{user="hello"} 411
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 91450.4 (25h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3765808
telemt_connections_bad_total 338376
telemt_connections_current 860
telemt_connections_me_current 860
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 96087
telemt_upstream_connect_attempt_total 55870
telemt_upstream_connect_success_total 55184
telemt_upstream_connect_fail_total 604
telemt_upstream_connect_attempts_per_request{bucket="1"} 55788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 604
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6377
telemt_me_reconnect_success_total 2336
telemt_me_reader_eof_total 2269
telemt_me_idle_close_by_peer_total 2269
telemt_me_route_drop_no_conn_total 3583976
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2991695
telemt_me_endpoint_quarantine_total 716
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 707
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
telemt_me_writers_active_current 45
telemt_desync_total 11898
telemt_desync_full_logged_total 6652
telemt_desync_suppressed_total 5246
telemt_desync_frames_bucket_total{bucket="1_2"} 2734
telemt_desync_frames_bucket_total{bucket="3_10"} 4658
telemt_desync_frames_bucket_total{bucket="gt_10"} 4506
telemt_pool_swap_total 86
telemt_pool_force_close_total 2600
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 221
telemt_me_draining_writers_reap_progress_total 36356
telemt_me_writer_removed_unexpected_total 2220
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4302
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34285
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33756
telemt_me_writer_teardown_success_total{mode="normal"} 38587
telemt_me_writer_teardown_noop_total 36356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74943
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.421469
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74943
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 221
telemt_me_refill_failed_total 161
telemt_me_writer_restored_same_endpoint_total 2023
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 3002524
telemt_user_connections_current{user="hello"} 860
telemt_user_octets_from_client{user="hello"} 38815498699 (36.15 GB)
telemt_user_octets_to_client{user="hello"} 699212733902 (651.19 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 555
telemt_user_unique_ips_recent_window{user="hello"} 325
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 166310.3 (46h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15758944
telemt_connections_bad_total 1511031
telemt_connections_current 2191
telemt_connections_me_current 2191
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 389652
telemt_upstream_connect_attempt_total 74245
telemt_upstream_connect_success_total 74148
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 74165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35410
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1683
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2760
telemt_me_reconnect_success_total 1415
telemt_me_reader_eof_total 1354
telemt_me_idle_close_by_peer_total 1352
telemt_me_route_drop_no_conn_total 13922058
telemt_me_route_drop_channel_closed_total 142
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12561992
telemt_me_endpoint_quarantine_total 1047
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1238
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
telemt_desync_total 51799
telemt_desync_full_logged_total 16276
telemt_desync_suppressed_total 35523
telemt_desync_frames_bucket_total{bucket="1_2"} 11571
telemt_desync_frames_bucket_total{bucket="3_10"} 20184
telemt_desync_frames_bucket_total{bucket="gt_10"} 20044
telemt_pool_swap_total 179
telemt_pool_force_close_total 6059
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 978
telemt_me_draining_writers_reap_progress_total 54570
telemt_me_writer_removed_unexpected_total 1308
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4781
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50388
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5592
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 467
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48511
telemt_me_writer_teardown_success_total{mode="normal"} 55169
telemt_me_writer_teardown_noop_total 54620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109789
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 306.841259
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109789
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 978
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1219
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 12562653
telemt_user_connections_current{user="hello"} 2191
telemt_user_octets_from_client{user="hello"} 182886974621 (170.33 GB)
telemt_user_octets_to_client{user="hello"} 3297625984735 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 831
telemt_user_unique_ips_recent_window{user="hello"} 303
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 166311.6 (46h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11380050
telemt_connections_bad_total 1123402
telemt_connections_current 1544
telemt_connections_me_current 1544
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 339868
telemt_upstream_connect_attempt_total 86787
telemt_upstream_connect_success_total 85579
telemt_upstream_connect_fail_total 840
telemt_upstream_connect_attempts_per_request{bucket="1"} 86419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35362
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3705
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 840
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4099
telemt_me_reconnect_success_total 1694
telemt_me_reader_eof_total 1562
telemt_me_idle_close_by_peer_total 1562
telemt_me_route_drop_no_conn_total 4453165
telemt_me_route_drop_channel_closed_total 490
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8479001
telemt_me_endpoint_quarantine_total 1053
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1258
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
telemt_desync_total 37645
telemt_desync_full_logged_total 12680
telemt_desync_suppressed_total 24965
telemt_desync_frames_bucket_total{bucket="1_2"} 9276
telemt_desync_frames_bucket_total{bucket="3_10"} 14502
telemt_desync_frames_bucket_total{bucket="gt_10"} 13867
telemt_pool_swap_total 176
telemt_pool_force_close_total 5473
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 691
telemt_me_draining_writers_reap_progress_total 53066
telemt_me_writer_removed_unexpected_total 1601
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4902
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49609
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4972
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 501
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47593
telemt_me_writer_teardown_success_total{mode="normal"} 54511
telemt_me_writer_teardown_noop_total 53089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107600
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.064481
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107600
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 691
telemt_me_refill_failed_total 130
telemt_me_writer_restored_same_endpoint_total 1450
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 8417380
telemt_user_connections_current{user="hello"} 1544
telemt_user_octets_from_client{user="hello"} 210417130337 (195.97 GB)
telemt_user_octets_to_client{user="hello"} 3795818812802 (3.45 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 606
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 166276.4 (46h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10707142
telemt_connections_bad_total 922598
telemt_connections_current 1311
telemt_connections_me_current 1311
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 342485
telemt_upstream_connect_attempt_total 71891
telemt_upstream_connect_success_total 70837
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 71021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33808
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 4904
telemt_me_reconnect_success_total 1982
telemt_me_reader_eof_total 1731
telemt_me_idle_close_by_peer_total 1730
telemt_me_route_drop_no_conn_total 5222712
telemt_me_route_drop_channel_closed_total 371
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8089201
telemt_me_endpoint_quarantine_total 1133
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1223
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
telemt_me_writers_active_current 43
telemt_desync_total 37166
telemt_desync_full_logged_total 12296
telemt_desync_suppressed_total 24870
telemt_desync_frames_bucket_total{bucket="1_2"} 9411
telemt_desync_frames_bucket_total{bucket="3_10"} 14230
telemt_desync_frames_bucket_total{bucket="gt_10"} 13525
telemt_pool_swap_total 174
telemt_pool_force_close_total 5405
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 702
telemt_me_draining_writers_reap_progress_total 53249
telemt_me_writer_removed_unexpected_total 1872
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5356
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49682
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4860
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 545
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47844
telemt_me_writer_teardown_success_total{mode="normal"} 55038
telemt_me_writer_teardown_noop_total 53320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108358
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.638262
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108358
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 702
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 1708
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 8081686
telemt_user_connections_current{user="hello"} 1311
telemt_user_octets_from_client{user="hello"} 186436449177 (173.63 GB)
telemt_user_octets_to_client{user="hello"} 3364736436141 (3.06 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 504
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 36555.6 (10h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10613677
telemt_connections_bad_total 649923
telemt_connections_current 2258
telemt_connections_me_current 2258
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 220422
telemt_upstream_connect_attempt_total 42834
telemt_upstream_connect_success_total 40687
telemt_upstream_connect_fail_total 1491
telemt_upstream_connect_attempts_per_request{bucket="1"} 42178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12536
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5924
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1491
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6352
telemt_me_reconnect_success_total 824
telemt_me_reader_eof_total 528
telemt_me_idle_close_by_peer_total 528
telemt_me_route_drop_no_conn_total 25126598
telemt_me_route_drop_channel_closed_total 53
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8814730
telemt_me_endpoint_quarantine_total 227
telemt_me_single_endpoint_outage_enter_total 61
telemt_me_single_endpoint_outage_exit_total 61
telemt_me_single_endpoint_outage_reconnect_attempt_total 112
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 112
telemt_me_single_endpoint_shadow_rotate_total 287
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
telemt_desync_total 14130
telemt_desync_full_logged_total 3689
telemt_desync_suppressed_total 10441
telemt_desync_frames_bucket_total{bucket="1_2"} 2606
telemt_desync_frames_bucket_total{bucket="3_10"} 5722
telemt_desync_frames_bucket_total{bucket="gt_10"} 5802
telemt_pool_swap_total 36
telemt_pool_force_close_total 1345
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 400
telemt_me_draining_writers_reap_progress_total 10339
telemt_me_writer_removed_unexpected_total 729
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1554
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9473
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1056
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 289
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8994
telemt_me_writer_teardown_success_total{mode="normal"} 11027
telemt_me_writer_teardown_noop_total 10345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 19651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 20177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 20882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 21215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 21323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 21372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 21372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 21372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 21372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 21372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 21372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 21372
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.470903
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 21372
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 400
telemt_me_refill_failed_total 306
telemt_me_writer_restored_same_endpoint_total 552
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 8836263
telemt_user_connections_current{user="hello"} 2258
telemt_user_octets_from_client{user="hello"} 79945102527 (74.45 GB)
telemt_user_octets_to_client{user="hello"} 427726487981 (398.35 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 800
telemt_user_unique_ips_recent_window{user="hello"} 305
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 166282.0 (46h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10557843
telemt_connections_bad_total 889553
telemt_connections_current 1700
telemt_connections_me_current 1700
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 232804
telemt_upstream_connect_attempt_total 100813
telemt_upstream_connect_success_total 99754
telemt_upstream_connect_fail_total 902
telemt_upstream_connect_attempts_per_request{bucket="1"} 100656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37117
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1327
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 902
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72204
telemt_me_reconnect_success_total 2729
telemt_me_reader_eof_total 2421
telemt_me_idle_close_by_peer_total 2419
telemt_me_route_drop_no_conn_total 5153403
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8334867
telemt_me_endpoint_quarantine_total 1101
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1241
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 50
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
telemt_desync_total 44242
telemt_desync_full_logged_total 15086
telemt_desync_suppressed_total 29156
telemt_desync_frames_bucket_total{bucket="1_2"} 8986
telemt_desync_frames_bucket_total{bucket="3_10"} 16985
telemt_desync_frames_bucket_total{bucket="gt_10"} 18271
telemt_pool_swap_total 170
telemt_pool_force_close_total 5062
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 626
telemt_me_draining_writers_reap_progress_total 56599
telemt_me_writer_removed_unexpected_total 2461
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6026
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53058
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4365
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 697
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51537
telemt_me_writer_teardown_success_total{mode="normal"} 59084
telemt_me_writer_teardown_noop_total 56600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115684
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.859253
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115684
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 626
telemt_me_refill_failed_total 4281
telemt_me_writer_restored_same_endpoint_total 2287
telemt_me_writer_restored_fallback_total 47
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 8338366
telemt_user_connections_current{user="hello"} 1700
telemt_user_octets_from_client{user="hello"} 189335304341 (176.33 GB)
telemt_user_octets_to_client{user="hello"} 3162330267308 (2.88 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 624
telemt_user_unique_ips_recent_window{user="hello"} 258
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 103118.2 (28h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11092504
telemt_connections_bad_total 429876
telemt_connections_current 1763
telemt_connections_me_current 1763
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4598759
telemt_upstream_connect_attempt_total 48968
telemt_upstream_connect_success_total 48603
telemt_upstream_connect_fail_total 356
telemt_upstream_connect_attempts_per_request{bucket="1"} 48959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 356
telemt_me_reconnect_attempts_total 48293
telemt_me_reconnect_success_total 1626
telemt_me_reader_eof_total 1285
telemt_me_idle_close_by_peer_total 1284
telemt_me_route_drop_no_conn_total 4001118
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5333824
telemt_me_endpoint_quarantine_total 663
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 777
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
telemt_me_writers_active_current 84
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 29838
telemt_desync_full_logged_total 10093
telemt_desync_suppressed_total 19745
telemt_desync_frames_bucket_total{bucket="1_2"} 5984
telemt_desync_frames_bucket_total{bucket="3_10"} 11792
telemt_desync_frames_bucket_total{bucket="gt_10"} 12062
telemt_pool_swap_total 108
telemt_pool_force_close_total 3305
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 35545
telemt_me_writer_removed_unexpected_total 1346
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3195
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33729
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 423
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32240
telemt_me_writer_teardown_success_total{mode="normal"} 36924
telemt_me_writer_teardown_noop_total 35552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72476
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.317611
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72476
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1450
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5326889
telemt_user_connections_current{user="hello"} 1763
telemt_user_octets_from_client{user="hello"} 114566923716 (106.70 GB)
telemt_user_octets_to_client{user="hello"} 2031709525906 (1.85 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 690
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 84089.2 (23h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1233667
telemt_connections_bad_total 27015
telemt_connections_current 1212
telemt_connections_me_current 1212
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 23893
telemt_upstream_connect_attempt_total 40291
telemt_upstream_connect_success_total 40170
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 40264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 658
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1787
telemt_me_reconnect_success_total 772
telemt_me_reader_eof_total 744
telemt_me_idle_close_by_peer_total 744
telemt_me_route_drop_no_conn_total 430323
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1092638
telemt_me_endpoint_quarantine_total 707
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 694
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 6340
telemt_desync_full_logged_total 1954
telemt_desync_suppressed_total 4386
telemt_desync_frames_bucket_total{bucket="1_2"} 1447
telemt_desync_frames_bucket_total{bucket="3_10"} 2498
telemt_desync_frames_bucket_total{bucket="gt_10"} 2395
telemt_pool_swap_total 90
telemt_pool_force_close_total 2321
telemt_me_writer_close_signal_drop_total 133
telemt_me_draining_writers_reap_progress_total 33491
telemt_me_writer_removed_unexpected_total 718
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2619
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31619
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2236
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31170
telemt_me_writer_teardown_success_total{mode="normal"} 34238
telemt_me_writer_teardown_noop_total 33495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67733
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.076149
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67733
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 133
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 654
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 1088892
telemt_user_connections_current{user="hello"} 1212
telemt_user_octets_from_client{user="hello"} 20125328245 (18.74 GB)
telemt_user_octets_to_client{user="hello"} 463140812087 (431.33 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 166286.8 (46h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12865611
telemt_connections_bad_total 1498254
telemt_connections_current 1971
telemt_connections_me_current 1971
telemt_handshake_timeouts_total 364233
telemt_upstream_connect_attempt_total 62596
telemt_upstream_connect_success_total 62268
telemt_upstream_connect_fail_total 193
telemt_upstream_connect_attempts_per_request{bucket="1"} 62461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31428
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 193
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2435
telemt_me_reconnect_success_total 1296
telemt_me_reader_eof_total 1257
telemt_me_idle_close_by_peer_total 1257
telemt_me_route_drop_no_conn_total 4381219
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9734928
telemt_me_endpoint_quarantine_total 1109
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1242
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
telemt_desync_total 40007
telemt_desync_full_logged_total 13052
telemt_desync_suppressed_total 26955
telemt_desync_frames_bucket_total{bucket="1_2"} 9543
telemt_desync_frames_bucket_total{bucket="3_10"} 14773
telemt_desync_frames_bucket_total{bucket="gt_10"} 15691
telemt_pool_swap_total 184
telemt_pool_force_close_total 5073
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 642
telemt_me_draining_writers_reap_progress_total 56342
telemt_me_writer_removed_unexpected_total 1211
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4634
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52955
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4899
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51269
telemt_me_writer_teardown_success_total{mode="normal"} 57589
telemt_me_writer_teardown_noop_total 56344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113933
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.099407
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113933
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 642
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 1134
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 9702862
telemt_user_connections_current{user="hello"} 1971
telemt_user_octets_from_client{user="hello"} 189947736764 (176.90 GB)
telemt_user_octets_to_client{user="hello"} 4278446226444 (3.89 TB)
telemt_user_unique_ips_current{user="hello"} 665
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 166283.2 (46h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11171277
telemt_connections_bad_total 1260101
telemt_connections_current 1661
telemt_connections_me_current 1661
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 292539
telemt_upstream_connect_attempt_total 88858
telemt_upstream_connect_success_total 88050
telemt_upstream_connect_fail_total 602
telemt_upstream_connect_attempts_per_request{bucket="1"} 88652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36809
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 602
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9582
telemt_me_reconnect_success_total 2291
telemt_me_reader_eof_total 2135
telemt_me_idle_close_by_peer_total 2134
telemt_me_seq_mismatch_total 77
telemt_me_route_drop_no_conn_total 5558492
telemt_me_route_drop_channel_closed_total 352
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8637292
telemt_me_endpoint_quarantine_total 1272
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1240
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
telemt_me_writers_active_current 84
telemt_desync_total 39336
telemt_desync_full_logged_total 12716
telemt_desync_suppressed_total 26620
telemt_desync_frames_bucket_total{bucket="1_2"} 9786
telemt_desync_frames_bucket_total{bucket="3_10"} 14635
telemt_desync_frames_bucket_total{bucket="gt_10"} 14915
telemt_pool_swap_total 174
telemt_pool_force_close_total 4863
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 629
telemt_me_draining_writers_reap_progress_total 55981
telemt_me_writer_removed_unexpected_total 2168
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5931
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52291
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 456
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51118
telemt_me_writer_teardown_success_total{mode="normal"} 58222
telemt_me_writer_teardown_noop_total 55986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114208
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.041185
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114208
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 629
telemt_me_refill_failed_total 376
telemt_me_writer_restored_same_endpoint_total 1869
telemt_me_writer_restored_fallback_total 105
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8643034
telemt_user_connections_current{user="hello"} 1661
telemt_user_octets_from_client{user="hello"} 152120039689 (141.67 GB)
telemt_user_octets_to_client{user="hello"} 3323083712083 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 635
telemt_user_unique_ips_recent_window{user="hello"} 213
```
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

# Server Metrics 2026-03-22 19:13:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 79650.0 (22h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2965300
telemt_connections_bad_total 191115
telemt_connections_current 1303
telemt_connections_me_current 1303
telemt_handshake_timeouts_total 97664
telemt_upstream_connect_attempt_total 29111
telemt_upstream_connect_success_total 29110
telemt_upstream_connect_attempts_per_request{bucket="1"} 29110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18888
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 69
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1176
telemt_me_reconnect_success_total 492
telemt_me_reader_eof_total 496
telemt_me_idle_close_by_peer_total 496
telemt_me_route_drop_no_conn_total 2640207
telemt_me_route_drop_channel_closed_total 1046
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2516011
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 537
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 619
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
telemt_desync_total 10946
telemt_desync_full_logged_total 3476
telemt_desync_suppressed_total 7470
telemt_desync_frames_bucket_total{bucket="1_2"} 2942
telemt_desync_frames_bucket_total{bucket="3_10"} 4060
telemt_desync_frames_bucket_total{bucket="gt_10"} 3944
telemt_pool_swap_total 88
telemt_pool_force_close_total 2736
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 567
telemt_me_draining_writers_reap_progress_total 26620
telemt_me_writer_removed_unexpected_total 481
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1933
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24910
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2683
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23884
telemt_me_writer_teardown_success_total{mode="normal"} 26843
telemt_me_writer_teardown_noop_total 26630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53473
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 290.390356
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53473
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 567
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 434
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 2508799
telemt_user_connections_current{user="hello"} 1303
telemt_user_octets_from_client{user="hello"} 36519341688 (34.01 GB)
telemt_user_octets_to_client{user="hello"} 655879559552 (610.84 GB)
telemt_user_unique_ips_current{user="hello"} 516
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 93016.7 (25h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3793100
telemt_connections_bad_total 339080
telemt_connections_current 654
telemt_connections_me_current 654
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 96909
telemt_upstream_connect_attempt_total 56540
telemt_upstream_connect_success_total 55849
telemt_upstream_connect_fail_total 609
telemt_upstream_connect_attempts_per_request{bucket="1"} 56458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 609
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6392
telemt_me_reconnect_success_total 2348
telemt_me_reader_eof_total 2282
telemt_me_idle_close_by_peer_total 2282
telemt_me_route_drop_no_conn_total 3592555
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3016196
telemt_me_endpoint_quarantine_total 728
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 717
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
telemt_me_writers_active_current 43
telemt_desync_total 12041
telemt_desync_full_logged_total 6735
telemt_desync_suppressed_total 5306
telemt_desync_frames_bucket_total{bucket="1_2"} 2772
telemt_desync_frames_bucket_total{bucket="3_10"} 4708
telemt_desync_frames_bucket_total{bucket="gt_10"} 4561
telemt_pool_swap_total 88
telemt_pool_force_close_total 2657
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 225
telemt_me_draining_writers_reap_progress_total 36940
telemt_me_writer_removed_unexpected_total 2232
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4352
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34832
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2268
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34283
telemt_me_writer_teardown_success_total{mode="normal"} 39184
telemt_me_writer_teardown_noop_total 36940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76124
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.955326
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76124
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 225
telemt_me_refill_failed_total 161
telemt_me_writer_restored_same_endpoint_total 2035
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 3026996
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 39244492467 (36.55 GB)
telemt_user_octets_to_client{user="hello"} 710896883362 (662.07 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 403
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 167877.1 (46h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15831936
telemt_connections_bad_total 1524620
telemt_connections_current 2136
telemt_connections_me_current 2136
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 390671
telemt_upstream_connect_attempt_total 74856
telemt_upstream_connect_success_total 74759
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 74776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35755
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1684
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2771
telemt_me_reconnect_success_total 1426
telemt_me_reader_eof_total 1367
telemt_me_idle_close_by_peer_total 1365
telemt_me_route_drop_no_conn_total 13941968
telemt_me_route_drop_channel_closed_total 142
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12617368
telemt_me_endpoint_quarantine_total 1061
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1252
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
telemt_me_writers_active_current 43
telemt_desync_total 52041
telemt_desync_full_logged_total 16366
telemt_desync_suppressed_total 35675
telemt_desync_frames_bucket_total{bucket="1_2"} 11609
telemt_desync_frames_bucket_total{bucket="3_10"} 20269
telemt_desync_frames_bucket_total{bucket="gt_10"} 20163
telemt_pool_swap_total 181
telemt_pool_force_close_total 6118
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 993
telemt_me_draining_writers_reap_progress_total 55119
telemt_me_writer_removed_unexpected_total 1319
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4834
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50897
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5650
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 468
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49001
telemt_me_writer_teardown_success_total{mode="normal"} 55731
telemt_me_writer_teardown_noop_total 55170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110901
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 309.716381
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110901
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 993
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1230
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 12617951
telemt_user_connections_current{user="hello"} 2136
telemt_user_octets_from_client{user="hello"} 183912572349 (171.28 GB)
telemt_user_octets_to_client{user="hello"} 3328260570799 (3.03 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 868
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 167877.8 (46h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11429924
telemt_connections_bad_total 1131595
telemt_connections_current 1459
telemt_connections_me_current 1459
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 340186
telemt_upstream_connect_attempt_total 87367
telemt_upstream_connect_success_total 86139
telemt_upstream_connect_fail_total 843
telemt_upstream_connect_attempts_per_request{bucket="1"} 86982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35663
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3708
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 843
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4126
telemt_me_reconnect_success_total 1704
telemt_me_reader_eof_total 1574
telemt_me_idle_close_by_peer_total 1574
telemt_me_route_drop_no_conn_total 4468636
telemt_me_route_drop_channel_closed_total 491
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8518656
telemt_me_endpoint_quarantine_total 1059
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1272
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 37762
telemt_desync_full_logged_total 12726
telemt_desync_suppressed_total 25036
telemt_desync_frames_bucket_total{bucket="1_2"} 9317
telemt_desync_frames_bucket_total{bucket="3_10"} 14550
telemt_desync_frames_bucket_total{bucket="gt_10"} 13895
telemt_pool_swap_total 178
telemt_pool_force_close_total 5526
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 700
telemt_me_draining_writers_reap_progress_total 53579
telemt_me_writer_removed_unexpected_total 1612
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4950
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50087
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5025
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 501
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48053
telemt_me_writer_teardown_success_total{mode="normal"} 55037
telemt_me_writer_teardown_noop_total 53604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108641
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.405656
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108641
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 700
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1460
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 8456954
telemt_user_connections_current{user="hello"} 1459
telemt_user_octets_from_client{user="hello"} 211269275169 (196.76 GB)
telemt_user_octets_to_client{user="hello"} 3813312215474 (3.47 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 579
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 167842.1 (46h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10750000
telemt_connections_bad_total 926193
telemt_connections_current 1292
telemt_connections_me_current 1292
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 342938
telemt_upstream_connect_attempt_total 72410
telemt_upstream_connect_success_total 71342
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 71526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34090
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1530
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 4924
telemt_me_reconnect_success_total 1984
telemt_me_reader_eof_total 1733
telemt_me_idle_close_by_peer_total 1732
telemt_me_route_drop_no_conn_total 5237869
telemt_me_route_drop_channel_closed_total 371
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8125900
telemt_me_endpoint_quarantine_total 1144
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1231
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 59
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
telemt_desync_total 37300
telemt_desync_full_logged_total 12342
telemt_desync_suppressed_total 24958
telemt_desync_frames_bucket_total{bucket="1_2"} 9440
telemt_desync_frames_bucket_total{bucket="3_10"} 14279
telemt_desync_frames_bucket_total{bucket="gt_10"} 13581
telemt_pool_swap_total 176
telemt_pool_force_close_total 5468
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 707
telemt_me_draining_writers_reap_progress_total 53720
telemt_me_writer_removed_unexpected_total 1874
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5388
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50123
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4920
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 548
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48252
telemt_me_writer_teardown_success_total{mode="normal"} 55511
telemt_me_writer_teardown_noop_total 53791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109302
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.700281
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109302
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 707
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 1709
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 8118314
telemt_user_connections_current{user="hello"} 1292
telemt_user_octets_from_client{user="hello"} 188137316065 (175.22 GB)
telemt_user_octets_to_client{user="hello"} 3379950466345 (3.07 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 465
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 38121.1 (10h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10690743
telemt_connections_bad_total 652093
telemt_connections_current 1937
telemt_connections_me_current 1937
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 225010
telemt_upstream_connect_attempt_total 44230
telemt_upstream_connect_success_total 42002
telemt_upstream_connect_fail_total 1541
telemt_upstream_connect_attempts_per_request{bucket="1"} 43543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13085
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5953
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1541
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6460
telemt_me_reconnect_success_total 864
telemt_me_reader_eof_total 536
telemt_me_idle_close_by_peer_total 536
telemt_me_route_drop_no_conn_total 25153042
telemt_me_route_drop_channel_closed_total 53
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8879305
telemt_me_endpoint_quarantine_total 239
telemt_me_single_endpoint_outage_enter_total 63
telemt_me_single_endpoint_outage_exit_total 63
telemt_me_single_endpoint_outage_reconnect_attempt_total 114
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 114
telemt_me_single_endpoint_shadow_rotate_total 299
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
telemt_me_writers_active_current 41
telemt_desync_total 14335
telemt_desync_full_logged_total 3745
telemt_desync_suppressed_total 10590
telemt_desync_frames_bucket_total{bucket="1_2"} 2659
telemt_desync_frames_bucket_total{bucket="3_10"} 5817
telemt_desync_frames_bucket_total{bucket="gt_10"} 5859
telemt_pool_swap_total 38
telemt_pool_force_close_total 1411
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 421
telemt_me_draining_writers_reap_progress_total 10824
telemt_me_writer_removed_unexpected_total 780
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1650
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9907
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1119
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 292
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9413
telemt_me_writer_teardown_success_total{mode="normal"} 11557
telemt_me_writer_teardown_noop_total 10843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 21131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 21883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22400
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.631886
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22400
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 421
telemt_me_refill_failed_total 310
telemt_me_writer_restored_same_endpoint_total 574
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 8901536
telemt_user_connections_current{user="hello"} 1937
telemt_user_octets_from_client{user="hello"} 81199493851 (75.62 GB)
telemt_user_octets_to_client{user="hello"} 448803075467 (417.98 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 733
telemt_user_unique_ips_recent_window{user="hello"} 250
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 167847.7 (46h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10611003
telemt_connections_bad_total 893780
telemt_connections_current 1929
telemt_connections_me_current 1929
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 233516
telemt_upstream_connect_attempt_total 101588
telemt_upstream_connect_success_total 100512
telemt_upstream_connect_fail_total 917
telemt_upstream_connect_attempts_per_request{bucket="1"} 101429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1330
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 917
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72278
telemt_me_reconnect_success_total 2790
telemt_me_reader_eof_total 2479
telemt_me_idle_close_by_peer_total 2477
telemt_me_route_drop_no_conn_total 5170640
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8379794
telemt_me_endpoint_quarantine_total 1110
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1254
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
telemt_me_writers_active_current 90
telemt_desync_total 44572
telemt_desync_full_logged_total 15168
telemt_desync_suppressed_total 29404
telemt_desync_frames_bucket_total{bucket="1_2"} 9032
telemt_desync_frames_bucket_total{bucket="3_10"} 17101
telemt_desync_frames_bucket_total{bucket="gt_10"} 18439
telemt_pool_swap_total 171
telemt_pool_force_close_total 5090
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 627
telemt_me_draining_writers_reap_progress_total 57233
telemt_me_writer_removed_unexpected_total 2517
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6116
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53660
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4393
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 697
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52143
telemt_me_writer_teardown_success_total{mode="normal"} 59776
telemt_me_writer_teardown_noop_total 57234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117010
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.921893
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117010
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 627
telemt_me_refill_failed_total 4281
telemt_me_writer_restored_same_endpoint_total 2343
telemt_me_writer_restored_fallback_total 47
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 8383260
telemt_user_connections_current{user="hello"} 1929
telemt_user_octets_from_client{user="hello"} 190282314517 (177.21 GB)
telemt_user_octets_to_client{user="hello"} 3182461796572 (2.89 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 758
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 104684.0 (29h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11159905
telemt_connections_bad_total 436345
telemt_connections_current 1240
telemt_connections_me_current 1240
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4612476
telemt_upstream_connect_attempt_total 49811
telemt_upstream_connect_success_total 49438
telemt_upstream_connect_fail_total 364
telemt_upstream_connect_attempts_per_request{bucket="1"} 49802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21992
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 364
telemt_me_reconnect_attempts_total 48453
telemt_me_reconnect_success_total 1652
telemt_me_reader_eof_total 1307
telemt_me_idle_close_by_peer_total 1306
telemt_me_route_drop_no_conn_total 4014788
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5371366
telemt_me_endpoint_quarantine_total 683
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 791
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30091
telemt_desync_full_logged_total 10171
telemt_desync_suppressed_total 19920
telemt_desync_frames_bucket_total{bucket="1_2"} 6035
telemt_desync_frames_bucket_total{bucket="3_10"} 11900
telemt_desync_frames_bucket_total{bucket="gt_10"} 12156
telemt_pool_swap_total 110
telemt_pool_force_close_total 3376
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 345
telemt_me_draining_writers_reap_progress_total 36331
telemt_me_writer_removed_unexpected_total 1368
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3252
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34480
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2936
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 440
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32955
telemt_me_writer_teardown_success_total{mode="normal"} 37732
telemt_me_writer_teardown_noop_total 36338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74070
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.372014
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74070
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 345
telemt_me_refill_failed_total 2720
telemt_me_writer_restored_same_endpoint_total 1468
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5364309
telemt_user_connections_current{user="hello"} 1240
telemt_user_octets_from_client{user="hello"} 115852483152 (107.90 GB)
telemt_user_octets_to_client{user="hello"} 2052451008042 (1.87 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 457
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 85654.7 (23h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1269898
telemt_connections_bad_total 27848
telemt_connections_current 1154
telemt_connections_me_current 1154
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 24329
telemt_upstream_connect_attempt_total 40882
telemt_upstream_connect_success_total 40759
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 40855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21682
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 685
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1884
telemt_me_reconnect_success_total 791
telemt_me_reader_eof_total 767
telemt_me_idle_close_by_peer_total 767
telemt_me_route_drop_no_conn_total 443792
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1125514
telemt_me_endpoint_quarantine_total 721
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 703
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
telemt_desync_total 6596
telemt_desync_full_logged_total 2032
telemt_desync_suppressed_total 4564
telemt_desync_frames_bucket_total{bucket="1_2"} 1490
telemt_desync_frames_bucket_total{bucket="3_10"} 2597
telemt_desync_frames_bucket_total{bucket="gt_10"} 2509
telemt_pool_swap_total 92
telemt_pool_force_close_total 2351
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 138
telemt_me_draining_writers_reap_progress_total 33965
telemt_me_writer_removed_unexpected_total 740
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2669
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32066
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2266
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31614
telemt_me_writer_teardown_success_total{mode="normal"} 34735
telemt_me_writer_teardown_noop_total 33969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68704
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.198710
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68704
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 138
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 669
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 1121720
telemt_user_connections_current{user="hello"} 1154
telemt_user_octets_from_client{user="hello"} 21470464325 (20.00 GB)
telemt_user_octets_to_client{user="hello"} 476319970971 (443.61 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 430
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 167852.9 (46h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12927053
telemt_connections_bad_total 1510063
telemt_connections_current 1817
telemt_connections_me_current 1817
telemt_handshake_timeouts_total 367615
telemt_upstream_connect_attempt_total 63240
telemt_upstream_connect_success_total 62911
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 63105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31735
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2459
telemt_me_reconnect_success_total 1303
telemt_me_reader_eof_total 1266
telemt_me_idle_close_by_peer_total 1266
telemt_me_route_drop_no_conn_total 4394120
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9779763
telemt_me_endpoint_quarantine_total 1122
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1255
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
telemt_desync_total 40281
telemt_desync_full_logged_total 13131
telemt_desync_suppressed_total 27150
telemt_desync_frames_bucket_total{bucket="1_2"} 9624
telemt_desync_frames_bucket_total{bucket="3_10"} 14867
telemt_desync_frames_bucket_total{bucket="gt_10"} 15790
telemt_pool_swap_total 186
telemt_pool_force_close_total 5123
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 644
telemt_me_draining_writers_reap_progress_total 56978
telemt_me_writer_removed_unexpected_total 1218
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4675
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53559
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4949
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51855
telemt_me_writer_teardown_success_total{mode="normal"} 58234
telemt_me_writer_teardown_noop_total 56980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115214
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.135509
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115214
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 644
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 1139
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 9747610
telemt_user_connections_current{user="hello"} 1817
telemt_user_octets_from_client{user="hello"} 190920825228 (177.81 GB)
telemt_user_octets_to_client{user="hello"} 4305161544532 (3.92 TB)
telemt_user_unique_ips_current{user="hello"} 627
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 167849.2 (46h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11237298
telemt_connections_bad_total 1274662
telemt_connections_current 1591
telemt_connections_me_current 1591
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 295084
telemt_upstream_connect_attempt_total 89639
telemt_upstream_connect_success_total 88827
telemt_upstream_connect_fail_total 606
telemt_upstream_connect_attempts_per_request{bucket="1"} 89433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37194
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 606
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9658
telemt_me_reconnect_success_total 2314
telemt_me_reader_eof_total 2159
telemt_me_idle_close_by_peer_total 2158
telemt_me_seq_mismatch_total 78
telemt_me_route_drop_no_conn_total 5572809
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8682352
telemt_me_endpoint_quarantine_total 1287
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1255
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
telemt_me_writers_active_current 45
telemt_desync_total 39650
telemt_desync_full_logged_total 12811
telemt_desync_suppressed_total 26839
telemt_desync_frames_bucket_total{bucket="1_2"} 9898
telemt_desync_frames_bucket_total{bucket="3_10"} 14742
telemt_desync_frames_bucket_total{bucket="gt_10"} 15010
telemt_pool_swap_total 176
telemt_pool_force_close_total 4922
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 634
telemt_me_draining_writers_reap_progress_total 56718
telemt_me_writer_removed_unexpected_total 2193
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5998
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52986
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4451
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51796
telemt_me_writer_teardown_success_total{mode="normal"} 58984
telemt_me_writer_teardown_noop_total 56723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115707
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.103734
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115707
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 634
telemt_me_refill_failed_total 379
telemt_me_writer_restored_same_endpoint_total 1889
telemt_me_writer_restored_fallback_total 106
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 198
telemt_user_connections_total{user="hello"} 8688001
telemt_user_connections_current{user="hello"} 1591
telemt_user_octets_from_client{user="hello"} 153177963425 (142.66 GB)
telemt_user_octets_to_client{user="hello"} 3344939069995 (3.04 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 592
telemt_user_unique_ips_recent_window{user="hello"} 193
```
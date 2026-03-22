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

# Server Metrics 2026-03-22 16:34:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 70094.9 (19h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2483976
telemt_connections_bad_total 132850
telemt_connections_current 1987
telemt_connections_me_current 1987
telemt_handshake_timeouts_total 88057
telemt_upstream_connect_attempt_total 25863
telemt_upstream_connect_success_total 25862
telemt_upstream_connect_attempts_per_request{bucket="1"} 25862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16800
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 55
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1037
telemt_me_reconnect_success_total 443
telemt_me_reader_eof_total 446
telemt_me_idle_close_by_peer_total 446
telemt_me_route_drop_no_conn_total 1995248
telemt_me_route_drop_channel_closed_total 834
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2116087
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
telemt_desync_total 10159
telemt_desync_full_logged_total 3192
telemt_desync_suppressed_total 6967
telemt_desync_frames_bucket_total{bucket="1_2"} 2712
telemt_desync_frames_bucket_total{bucket="3_10"} 3805
telemt_desync_frames_bucket_total{bucket="gt_10"} 3642
telemt_pool_swap_total 77
telemt_pool_force_close_total 2383
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 464
telemt_me_draining_writers_reap_progress_total 23624
telemt_me_writer_removed_unexpected_total 432
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1722
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22121
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2334
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 49
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21241
telemt_me_writer_teardown_success_total{mode="normal"} 23843
telemt_me_writer_teardown_noop_total 23630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47473
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 219.384216
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47473
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 464
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 393
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2112638
telemt_user_connections_current{user="hello"} 1987
telemt_user_octets_from_client{user="hello"} 31897146632 (29.71 GB)
telemt_user_octets_to_client{user="hello"} 563599892612 (524.89 GB)
telemt_user_unique_ips_current{user="hello"} 683
telemt_user_unique_ips_recent_window{user="hello"} 402
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 83461.2 (23h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3608280
telemt_connections_bad_total 327838
telemt_connections_current 1104
telemt_connections_me_current 1104
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 89823
telemt_upstream_connect_attempt_total 52400
telemt_upstream_connect_success_total 51762
telemt_upstream_connect_fail_total 566
telemt_upstream_connect_attempts_per_request{bucket="1"} 52328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21558
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 566
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6072
telemt_me_reconnect_success_total 2210
telemt_me_reader_eof_total 2146
telemt_me_idle_close_by_peer_total 2146
telemt_me_route_drop_no_conn_total 3534327
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2859908
telemt_me_endpoint_quarantine_total 665
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 645
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
telemt_me_writers_active_current 54
telemt_desync_total 11190
telemt_desync_full_logged_total 6237
telemt_desync_suppressed_total 4953
telemt_desync_frames_bucket_total{bucket="1_2"} 2604
telemt_desync_frames_bucket_total{bucket="3_10"} 4385
telemt_desync_frames_bucket_total{bucket="gt_10"} 4201
telemt_pool_swap_total 78
telemt_pool_force_close_total 2346
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 198
telemt_me_draining_writers_reap_progress_total 33286
telemt_me_writer_removed_unexpected_total 2100
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3998
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31395
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1990
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 356
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30940
telemt_me_writer_teardown_success_total{mode="normal"} 35393
telemt_me_writer_teardown_noop_total 33286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68679
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.957834
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68679
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 198
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 1917
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 2871177
telemt_user_connections_current{user="hello"} 1104
telemt_user_octets_from_client{user="hello"} 35687197175 (33.24 GB)
telemt_user_octets_to_client{user="hello"} 642317740286 (598.21 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 636
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 158321.2 (43h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15343602
telemt_connections_bad_total 1432564
telemt_connections_current 2625
telemt_connections_me_current 2625
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 373290
telemt_upstream_connect_attempt_total 71466
telemt_upstream_connect_success_total 71371
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 71388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33799
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1673
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2667
telemt_me_reconnect_success_total 1360
telemt_me_reader_eof_total 1299
telemt_me_idle_close_by_peer_total 1297
telemt_me_route_drop_no_conn_total 13811634
telemt_me_route_drop_channel_closed_total 139
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12260196
telemt_me_endpoint_quarantine_total 993
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1180
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
telemt_me_writers_active_current 46
telemt_desync_total 49961
telemt_desync_full_logged_total 15679
telemt_desync_suppressed_total 34282
telemt_desync_frames_bucket_total{bucket="1_2"} 11176
telemt_desync_frames_bucket_total{bucket="3_10"} 19515
telemt_desync_frames_bucket_total{bucket="gt_10"} 19270
telemt_pool_swap_total 170
telemt_pool_force_close_total 5794
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 939
telemt_me_draining_writers_reap_progress_total 52056
telemt_me_writer_removed_unexpected_total 1253
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4533
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48068
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5334
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46262
telemt_me_writer_teardown_success_total{mode="normal"} 52601
telemt_me_writer_teardown_noop_total 52106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104707
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 298.939842
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104707
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 939
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 1167
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 12261363
telemt_user_connections_current{user="hello"} 2625
telemt_user_octets_from_client{user="hello"} 174572604837 (162.58 GB)
telemt_user_octets_to_client{user="hello"} 3173503965415 (2.89 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 1045
telemt_user_unique_ips_recent_window{user="hello"} 333
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 158322.5 (43h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11070359
telemt_connections_bad_total 1074965
telemt_connections_current 1620
telemt_connections_me_current 1620
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 328521
telemt_upstream_connect_attempt_total 83641
telemt_upstream_connect_success_total 82485
telemt_upstream_connect_fail_total 832
telemt_upstream_connect_attempts_per_request{bucket="1"} 83317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33640
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3695
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 832
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3938
telemt_me_reconnect_success_total 1602
telemt_me_reader_eof_total 1473
telemt_me_idle_close_by_peer_total 1473
telemt_me_route_drop_no_conn_total 4363898
telemt_me_route_drop_channel_closed_total 478
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8256926
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
telemt_desync_total 36691
telemt_desync_full_logged_total 12334
telemt_desync_suppressed_total 24357
telemt_desync_frames_bucket_total{bucket="1_2"} 8996
telemt_desync_frames_bucket_total{bucket="3_10"} 14137
telemt_desync_frames_bucket_total{bucket="gt_10"} 13558
telemt_pool_swap_total 168
telemt_pool_force_close_total 5212
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 666
telemt_me_draining_writers_reap_progress_total 50326
telemt_me_writer_removed_unexpected_total 1502
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4635
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47053
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4736
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 476
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45114
telemt_me_writer_teardown_success_total{mode="normal"} 51688
telemt_me_writer_teardown_noop_total 50344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102032
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.271433
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102032
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 666
telemt_me_refill_failed_total 126
telemt_me_writer_restored_same_endpoint_total 1364
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8195606
telemt_user_connections_current{user="hello"} 1620
telemt_user_octets_from_client{user="hello"} 205139769385 (191.05 GB)
telemt_user_octets_to_client{user="hello"} 3695386791002 (3.36 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 615
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 158286.7 (43h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10464341
telemt_connections_bad_total 901168
telemt_connections_current 1318
telemt_connections_me_current 1318
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 334309
telemt_upstream_connect_attempt_total 68838
telemt_upstream_connect_success_total 67876
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 68058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32176
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1307
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2075
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4673
telemt_me_reconnect_success_total 1891
telemt_me_reader_eof_total 1645
telemt_me_idle_close_by_peer_total 1644
telemt_me_route_drop_no_conn_total 5135747
telemt_me_route_drop_channel_closed_total 359
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7901318
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
telemt_desync_total 36163
telemt_desync_full_logged_total 11984
telemt_desync_suppressed_total 24179
telemt_desync_frames_bucket_total{bucket="1_2"} 9151
telemt_desync_frames_bucket_total{bucket="3_10"} 13821
telemt_desync_frames_bucket_total{bucket="gt_10"} 13191
telemt_pool_swap_total 165
telemt_pool_force_close_total 5161
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 685
telemt_me_draining_writers_reap_progress_total 50694
telemt_me_writer_removed_unexpected_total 1785
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5070
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47321
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4619
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45533
telemt_me_writer_teardown_success_total{mode="normal"} 52391
telemt_me_writer_teardown_noop_total 50765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103156
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3170.566029
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103156
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 685
telemt_me_refill_failed_total 147
telemt_me_writer_restored_same_endpoint_total 1635
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 7894267
telemt_user_connections_current{user="hello"} 1318
telemt_user_octets_from_client{user="hello"} 181792088413 (169.31 GB)
telemt_user_octets_to_client{user="hello"} 3282402208161 (2.99 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 516
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 28566.7 (7h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10177898
telemt_connections_bad_total 621810
telemt_connections_current 2318
telemt_connections_me_current 2318
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 190075
telemt_upstream_connect_attempt_total 35931
telemt_upstream_connect_success_total 34135
telemt_upstream_connect_fail_total 1254
telemt_upstream_connect_attempts_per_request{bucket="1"} 35389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9369
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5302
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1254
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5891
telemt_me_reconnect_success_total 713
telemt_me_reader_eof_total 456
telemt_me_idle_close_by_peer_total 456
telemt_me_route_drop_no_conn_total 24941567
telemt_me_route_drop_channel_closed_total 47
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8472149
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
telemt_desync_total 13253
telemt_desync_full_logged_total 3419
telemt_desync_suppressed_total 9834
telemt_desync_frames_bucket_total{bucket="1_2"} 2363
telemt_desync_frames_bucket_total{bucket="3_10"} 5394
telemt_desync_frames_bucket_total{bucket="gt_10"} 5496
telemt_pool_swap_total 27
telemt_pool_force_close_total 1067
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 366
telemt_me_draining_writers_reap_progress_total 7827
telemt_me_writer_removed_unexpected_total 616
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1283
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7125
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 787
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 280
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6760
telemt_me_writer_teardown_success_total{mode="normal"} 8408
telemt_me_writer_teardown_noop_total 7832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 15273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 15845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16240
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 36.831495
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16240
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 366
telemt_me_refill_failed_total 293
telemt_me_writer_restored_same_endpoint_total 488
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8490214
telemt_user_connections_current{user="hello"} 2318
telemt_user_octets_from_client{user="hello"} 64201352666 (59.79 GB)
telemt_user_octets_to_client{user="hello"} 308937318868 (287.72 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 821
telemt_user_unique_ips_recent_window{user="hello"} 356
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 158293.3 (43h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10260548
telemt_connections_bad_total 860870
telemt_connections_current 1828
telemt_connections_me_current 1828
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 228122
telemt_upstream_connect_attempt_total 97607
telemt_upstream_connect_success_total 96616
telemt_upstream_connect_fail_total 843
telemt_upstream_connect_attempts_per_request{bucket="1"} 97459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35404
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1305
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 843
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71836
telemt_me_reconnect_success_total 2616
telemt_me_reader_eof_total 2320
telemt_me_idle_close_by_peer_total 2319
telemt_me_route_drop_no_conn_total 5065672
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8090542
telemt_me_endpoint_quarantine_total 1065
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1179
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
telemt_desync_total 42197
telemt_desync_full_logged_total 14395
telemt_desync_suppressed_total 27802
telemt_desync_frames_bucket_total{bucket="1_2"} 8582
telemt_desync_frames_bucket_total{bucket="3_10"} 16320
telemt_desync_frames_bucket_total{bucket="gt_10"} 17295
telemt_pool_swap_total 161
telemt_pool_force_close_total 4795
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 603
telemt_me_draining_writers_reap_progress_total 53837
telemt_me_writer_removed_unexpected_total 2363
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5749
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50472
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4110
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 685
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49042
telemt_me_writer_teardown_success_total{mode="normal"} 56221
telemt_me_writer_teardown_noop_total 53838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110059
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.453961
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110059
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 603
telemt_me_refill_failed_total 4268
telemt_me_writer_restored_same_endpoint_total 2197
telemt_me_writer_restored_fallback_total 44
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7360
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 8094479
telemt_user_connections_current{user="hello"} 1828
telemt_user_octets_from_client{user="hello"} 183286057313 (170.70 GB)
telemt_user_octets_to_client{user="hello"} 3048503622084 (2.77 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 715
telemt_user_unique_ips_recent_window{user="hello"} 282
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 95129.4 (26h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10680269
telemt_connections_bad_total 400510
telemt_connections_current 1537
telemt_connections_me_current 1537
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4483701
telemt_upstream_connect_attempt_total 45790
telemt_upstream_connect_success_total 45458
telemt_upstream_connect_fail_total 323
telemt_upstream_connect_attempts_per_request{bucket="1"} 45781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19804
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 323
telemt_me_reconnect_attempts_total 48089
telemt_me_reconnect_success_total 1519
telemt_me_reader_eof_total 1184
telemt_me_idle_close_by_peer_total 1183
telemt_me_route_drop_no_conn_total 3920930
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5120155
telemt_me_endpoint_quarantine_total 619
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 716
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
telemt_desync_total 28062
telemt_desync_full_logged_total 9491
telemt_desync_suppressed_total 18571
telemt_desync_frames_bucket_total{bucket="1_2"} 5645
telemt_desync_frames_bucket_total{bucket="3_10"} 11077
telemt_desync_frames_bucket_total{bucket="gt_10"} 11340
telemt_pool_swap_total 100
telemt_pool_force_close_total 3081
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 313
telemt_me_draining_writers_reap_progress_total 32756
telemt_me_writer_removed_unexpected_total 1247
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2943
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31090
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2662
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29675
telemt_me_writer_teardown_success_total{mode="normal"} 34033
telemt_me_writer_teardown_noop_total 32763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66796
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.886511
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66796
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 313
telemt_me_refill_failed_total 2707
telemt_me_writer_restored_same_endpoint_total 1352
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5113663
telemt_user_connections_current{user="hello"} 1537
telemt_user_octets_from_client{user="hello"} 109919395124 (102.37 GB)
telemt_user_octets_to_client{user="hello"} 1932430161254 (1.76 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 619
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 76100.0 (21h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1029659
telemt_connections_bad_total 15305
telemt_connections_current 1202
telemt_connections_me_current 1202
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 19851
telemt_upstream_connect_attempt_total 37339
telemt_upstream_connect_success_total 37242
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 37322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 535
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_reconnect_attempts_total 1720
telemt_me_reconnect_success_total 713
telemt_me_reader_eof_total 688
telemt_me_idle_close_by_peer_total 688
telemt_me_route_drop_no_conn_total 360002
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 916478
telemt_me_endpoint_quarantine_total 652
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 629
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
telemt_desync_total 5182
telemt_desync_full_logged_total 1579
telemt_desync_suppressed_total 3603
telemt_desync_frames_bucket_total{bucket="1_2"} 1218
telemt_desync_frames_bucket_total{bucket="3_10"} 2052
telemt_desync_frames_bucket_total{bucket="gt_10"} 1912
telemt_pool_swap_total 81
telemt_pool_force_close_total 2053
telemt_me_writer_close_signal_drop_total 119
telemt_me_draining_writers_reap_progress_total 30945
telemt_me_writer_removed_unexpected_total 664
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2393
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29242
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1972
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28892
telemt_me_writer_teardown_success_total{mode="normal"} 31635
telemt_me_writer_teardown_noop_total 30948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62583
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.755395
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62583
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 119
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 606
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 913012
telemt_user_connections_current{user="hello"} 1202
telemt_user_octets_from_client{user="hello"} 16457383465 (15.33 GB)
telemt_user_octets_to_client{user="hello"} 402776338983 (375.11 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 420
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 158297.8 (43h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12532725
telemt_connections_bad_total 1451598
telemt_connections_current 2075
telemt_connections_me_current 2075
telemt_handshake_timeouts_total 346262
telemt_upstream_connect_attempt_total 59445
telemt_upstream_connect_success_total 59203
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 59384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29900
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_reconnect_attempts_total 2340
telemt_me_reconnect_success_total 1236
telemt_me_reader_eof_total 1200
telemt_me_idle_close_by_peer_total 1200
telemt_me_route_drop_no_conn_total 4184386
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9478485
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
telemt_desync_total 38882
telemt_desync_full_logged_total 12694
telemt_desync_suppressed_total 26188
telemt_desync_frames_bucket_total{bucket="1_2"} 9238
telemt_desync_frames_bucket_total{bucket="3_10"} 14410
telemt_desync_frames_bucket_total{bucket="gt_10"} 15234
telemt_pool_swap_total 175
telemt_pool_force_close_total 4831
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 620
telemt_me_draining_writers_reap_progress_total 53526
telemt_me_writer_removed_unexpected_total 1153
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4385
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50327
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4658
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48695
telemt_me_writer_teardown_success_total{mode="normal"} 54712
telemt_me_writer_teardown_noop_total 53528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108240
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.084965
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108240
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 620
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 1080
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 9447718
telemt_user_connections_current{user="hello"} 2075
telemt_user_octets_from_client{user="hello"} 185504264880 (172.76 GB)
telemt_user_octets_to_client{user="hello"} 4171824400996 (3.79 TB)
telemt_user_unique_ips_current{user="hello"} 744
telemt_user_unique_ips_recent_window{user="hello"} 273
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 158294.5 (43h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10863153
telemt_connections_bad_total 1214694
telemt_connections_current 1464
telemt_connections_me_current 1464
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 280278
telemt_upstream_connect_attempt_total 85230
telemt_upstream_connect_success_total 84585
telemt_upstream_connect_fail_total 554
telemt_upstream_connect_attempts_per_request{bucket="1"} 85139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35139
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2029
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 554
telemt_me_reconnect_attempts_total 8943
telemt_me_reconnect_success_total 2062
telemt_me_reader_eof_total 1921
telemt_me_idle_close_by_peer_total 1921
telemt_me_seq_mismatch_total 75
telemt_me_route_drop_no_conn_total 5422987
telemt_me_route_drop_channel_closed_total 348
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8399003
telemt_me_endpoint_quarantine_total 1203
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
telemt_desync_total 38315
telemt_desync_full_logged_total 12379
telemt_desync_suppressed_total 25936
telemt_desync_frames_bucket_total{bucket="1_2"} 9529
telemt_desync_frames_bucket_total{bucket="3_10"} 14278
telemt_desync_frames_bucket_total{bucket="gt_10"} 14508
telemt_pool_swap_total 167
telemt_pool_force_close_total 4672
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 607
telemt_me_draining_writers_reap_progress_total 53012
telemt_me_writer_removed_unexpected_total 1947
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5484
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49544
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4233
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48340
telemt_me_writer_teardown_success_total{mode="normal"} 55028
telemt_me_writer_teardown_noop_total 53017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108045
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.590030
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108045
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 607
telemt_me_refill_failed_total 353
telemt_me_writer_restored_same_endpoint_total 1672
telemt_me_writer_restored_fallback_total 100
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 8404971
telemt_user_connections_current{user="hello"} 1464
telemt_user_octets_from_client{user="hello"} 147973443925 (137.81 GB)
telemt_user_octets_to_client{user="hello"} 3211847372307 (2.92 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 582
telemt_user_unique_ips_recent_window{user="hello"} 231
```
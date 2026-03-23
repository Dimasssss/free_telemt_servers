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

# Server Metrics 2026-03-23 02:37:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 106262.4 (29h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3642088
telemt_connections_bad_total 342878
telemt_connections_current 1034
telemt_connections_me_current 1034
telemt_handshake_timeouts_total 116103
telemt_upstream_connect_attempt_total 39607
telemt_upstream_connect_success_total 39606
telemt_upstream_connect_attempts_per_request{bucket="1"} 39606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25661
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1417
telemt_me_reconnect_success_total 620
telemt_me_reader_eof_total 637
telemt_me_idle_close_by_peer_total 637
telemt_me_route_drop_no_conn_total 3001310
telemt_me_route_drop_channel_closed_total 1234
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2984325
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 750
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 828
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 28
telemt_desync_total 12867
telemt_desync_full_logged_total 4069
telemt_desync_suppressed_total 8798
telemt_desync_frames_bucket_total{bucket="1_2"} 3422
telemt_desync_frames_bucket_total{bucket="3_10"} 4699
telemt_desync_frames_bucket_total{bucket="gt_10"} 4746
telemt_pool_swap_total 117
telemt_pool_force_close_total 3584
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 669
telemt_me_draining_writers_reap_progress_total 36247
telemt_me_writer_removed_unexpected_total 614
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2578
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33932
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3528
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32663
telemt_me_writer_teardown_success_total{mode="normal"} 36510
telemt_me_writer_teardown_noop_total 36258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72768
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 379.269077
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72768
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 669
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 555
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 2973282
telemt_user_connections_current{user="hello"} 1034
telemt_user_octets_from_client{user="hello"} 42475314788 (39.56 GB)
telemt_user_octets_to_client{user="hello"} 813227739312 (757.38 GB)
telemt_user_unique_ips_current{user="hello"} 477
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 119628.5 (33h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4028222
telemt_connections_bad_total 372319
telemt_connections_current 418
telemt_connections_me_current 418
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 101303
telemt_upstream_connect_attempt_total 74381
telemt_upstream_connect_success_total 73472
telemt_upstream_connect_fail_total 802
telemt_upstream_connect_attempts_per_request{bucket="1"} 74274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 802
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10399
telemt_me_reconnect_success_total 3707
telemt_me_reader_eof_total 3690
telemt_me_idle_close_by_peer_total 3690
telemt_me_route_drop_no_conn_total 3644636
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3199758
telemt_me_endpoint_quarantine_total 965
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 937
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
telemt_desync_total 13042
telemt_desync_full_logged_total 7326
telemt_desync_suppressed_total 5716
telemt_desync_frames_bucket_total{bucket="1_2"} 2960
telemt_desync_frames_bucket_total{bucket="3_10"} 5121
telemt_desync_frames_bucket_total{bucket="gt_10"} 4961
telemt_pool_swap_total 112
telemt_pool_force_close_total 3158
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 255
telemt_me_draining_writers_reap_progress_total 49575
telemt_me_writer_removed_unexpected_total 3619
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6421
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46807
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2700
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46417
telemt_me_writer_teardown_success_total{mode="normal"} 53228
telemt_me_writer_teardown_noop_total 49576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102804
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.659178
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102804
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 255
telemt_me_refill_failed_total 262
telemt_me_writer_restored_same_endpoint_total 3289
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 3213120
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 43290418966 (40.32 GB)
telemt_user_octets_to_client{user="hello"} 797694709198 (742.91 GB)
telemt_user_msgs_from_client{user="hello"} 49767
telemt_user_msgs_to_client{user="hello"} 185105
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 194488.4 (54h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16408129
telemt_connections_bad_total 1664132
telemt_connections_current 1090
telemt_connections_me_current 1090
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 398858
telemt_upstream_connect_attempt_total 87518
telemt_upstream_connect_success_total 87411
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 87428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42927
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1724
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3044
telemt_me_reconnect_success_total 1620
telemt_me_reader_eof_total 1567
telemt_me_idle_close_by_peer_total 1565
telemt_me_route_drop_no_conn_total 14055958
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13027113
telemt_me_endpoint_quarantine_total 1301
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1464
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 41
telemt_desync_total 54068
telemt_desync_full_logged_total 17212
telemt_desync_suppressed_total 36856
telemt_desync_frames_bucket_total{bucket="1_2"} 12060
telemt_desync_frames_bucket_total{bucket="3_10"} 21116
telemt_desync_frames_bucket_total{bucket="gt_10"} 20892
telemt_pool_swap_total 210
telemt_pool_force_close_total 6834
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1067
telemt_me_draining_writers_reap_progress_total 66677
telemt_me_writer_removed_unexpected_total 1507
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5631
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61832
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6364
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59843
telemt_me_writer_teardown_success_total{mode="normal"} 67463
telemt_me_writer_teardown_noop_total 66730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 128472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 130865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 132532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 133583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 134154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 134184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 134185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 134189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 134191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 134193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 134193
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.916390
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 134193
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1067
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1402
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 13027102
telemt_user_connections_current{user="hello"} 1090
telemt_user_octets_from_client{user="hello"} 197606841837 (184.04 GB)
telemt_user_octets_to_client{user="hello"} 3509200524219 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 504
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 194489.7 (54h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11954077
telemt_connections_bad_total 1251509
telemt_connections_current 706
telemt_connections_me_current 706
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 345237
telemt_upstream_connect_attempt_total 101821
telemt_upstream_connect_success_total 100486
telemt_upstream_connect_fail_total 882
telemt_upstream_connect_attempts_per_request{bucket="1"} 101368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42801
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3803
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 882
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4473
telemt_me_reconnect_success_total 1923
telemt_me_reader_eof_total 1789
telemt_me_idle_close_by_peer_total 1789
telemt_me_route_drop_no_conn_total 4563960
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8860041
telemt_me_endpoint_quarantine_total 1316
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1484
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_warm_current 35
telemt_desync_total 39053
telemt_desync_full_logged_total 13153
telemt_desync_suppressed_total 25900
telemt_desync_frames_bucket_total{bucket="1_2"} 9674
telemt_desync_frames_bucket_total{bucket="3_10"} 14999
telemt_desync_frames_bucket_total{bucket="gt_10"} 14380
telemt_pool_swap_total 207
telemt_pool_force_close_total 6186
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 713
telemt_me_draining_writers_reap_progress_total 64829
telemt_me_writer_removed_unexpected_total 1816
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5726
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60778
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5674
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58643
telemt_me_writer_teardown_success_total{mode="normal"} 66504
telemt_me_writer_teardown_noop_total 64854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 128983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 130174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 130933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 131273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 131348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 131350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 131356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 131358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 131358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 131358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 131358
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.529548
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 131358
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 713
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1646
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 8797765
telemt_user_connections_current{user="hello"} 706
telemt_user_octets_from_client{user="hello"} 218150926740 (203.17 GB)
telemt_user_octets_to_client{user="hello"} 3976453449847 (3.62 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 314
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 194453.8 (54h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11106376
telemt_connections_bad_total 987089
telemt_connections_current 493
telemt_connections_me_current 493
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 346016
telemt_upstream_connect_attempt_total 86184
telemt_upstream_connect_success_total 84620
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 84825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41313
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5793
telemt_me_reconnect_success_total 2414
telemt_me_reader_eof_total 2159
telemt_me_idle_close_by_peer_total 2158
telemt_me_route_drop_no_conn_total 5343932
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8389578
telemt_me_endpoint_quarantine_total 1365
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1444
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_me_writers_active_current 49
telemt_me_writers_warm_current 9
telemt_desync_total 38267
telemt_desync_full_logged_total 12683
telemt_desync_suppressed_total 25584
telemt_desync_frames_bucket_total{bucket="1_2"} 9670
telemt_desync_frames_bucket_total{bucket="3_10"} 14651
telemt_desync_frames_bucket_total{bucket="gt_10"} 13946
telemt_pool_swap_total 203
telemt_pool_force_close_total 6082
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 746
telemt_me_draining_writers_reap_progress_total 65299
telemt_me_writer_removed_unexpected_total 2307
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6474
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61066
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5511
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59217
telemt_me_writer_teardown_success_total{mode="normal"} 67540
telemt_me_writer_teardown_noop_total 65370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 127069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 129792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 130755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 131828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 132429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 132643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 132771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 132802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 132810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 132823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 132856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 132859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 132910
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.853209
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 132910
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 746
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2101
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 8381499
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 193019884211 (179.76 GB)
telemt_user_octets_to_client{user="hello"} 3481396646949 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 64734.0 (17h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11331425
telemt_connections_bad_total 670129
telemt_connections_current 1082
telemt_connections_me_current 1082
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 284556
telemt_upstream_connect_attempt_total 60689
telemt_upstream_connect_success_total 57542
telemt_upstream_connect_fail_total 2052
telemt_upstream_connect_attempts_per_request{bucket="1"} 59594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20463
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6019
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2052
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7861
telemt_me_reconnect_success_total 1329
telemt_me_reader_eof_total 864
telemt_me_idle_close_by_peer_total 863
telemt_me_route_drop_no_conn_total 25303263
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9396405
telemt_me_endpoint_quarantine_total 477
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 518
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
telemt_me_writers_active_current 87
telemt_desync_total 16506
telemt_desync_full_logged_total 4528
telemt_desync_suppressed_total 11978
telemt_desync_frames_bucket_total{bucket="1_2"} 3142
telemt_desync_frames_bucket_total{bucket="3_10"} 6730
telemt_desync_frames_bucket_total{bucket="gt_10"} 6634
telemt_pool_swap_total 66
telemt_pool_force_close_total 2110
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 491
telemt_me_draining_writers_reap_progress_total 20983
telemt_me_writer_removed_unexpected_total 1218
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2748
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19399
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1803
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18873
telemt_me_writer_teardown_success_total{mode="normal"} 22147
telemt_me_writer_teardown_noop_total 21002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43149
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.978888
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43149
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 491
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 874
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 331
telemt_user_connections_total{user="hello"} 9422264
telemt_user_connections_current{user="hello"} 1082
telemt_user_octets_from_client{user="hello"} 87739675354 (81.71 GB)
telemt_user_octets_to_client{user="hello"} 629033040582 (585.83 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 440
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 194460.5 (54h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11064110
telemt_connections_bad_total 966160
telemt_connections_current 878
telemt_connections_me_current 878
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 244018
telemt_upstream_connect_attempt_total 114998
telemt_upstream_connect_success_total 113818
telemt_upstream_connect_fail_total 1005
telemt_upstream_connect_attempts_per_request{bucket="1"} 114823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44799
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1005
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73144
telemt_me_reconnect_success_total 3143
telemt_me_reader_eof_total 2840
telemt_me_idle_close_by_peer_total 2838
telemt_me_route_drop_no_conn_total 5271264
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8718215
telemt_me_endpoint_quarantine_total 1317
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1472
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_me_writers_warm_current 14
telemt_desync_total 46452
telemt_desync_full_logged_total 15941
telemt_desync_suppressed_total 30511
telemt_desync_frames_bucket_total{bucket="1_2"} 9441
telemt_desync_frames_bucket_total{bucket="3_10"} 17782
telemt_desync_frames_bucket_total{bucket="gt_10"} 19229
telemt_pool_swap_total 199
telemt_pool_force_close_total 5792
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 668
telemt_me_draining_writers_reap_progress_total 69324
telemt_me_writer_removed_unexpected_total 2860
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7017
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65211
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5043
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63532
telemt_me_writer_teardown_success_total{mode="normal"} 72228
telemt_me_writer_teardown_noop_total 69325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 139399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 140817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 141236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141553
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.303808
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141553
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 668
telemt_me_refill_failed_total 4308
telemt_me_writer_restored_same_endpoint_total 2648
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 8721144
telemt_user_connections_current{user="hello"} 878
telemt_user_octets_from_client{user="hello"} 196306574445 (182.82 GB)
telemt_user_octets_to_client{user="hello"} 3332899489264 (3.03 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 388
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 131296.8 (36h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11771791
telemt_connections_bad_total 483481
telemt_connections_current 643
telemt_connections_me_current 643
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4773742
telemt_upstream_connect_attempt_total 63616
telemt_upstream_connect_success_total 63155
telemt_upstream_connect_fail_total 449
telemt_upstream_connect_attempts_per_request{bucket="1"} 63604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29398
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 449
telemt_me_reconnect_attempts_total 49110
telemt_me_reconnect_success_total 1875
telemt_me_reader_eof_total 1552
telemt_me_idle_close_by_peer_total 1551
telemt_me_route_drop_no_conn_total 4100831
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5656507
telemt_me_endpoint_quarantine_total 898
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1009
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31822
telemt_desync_full_logged_total 10873
telemt_desync_suppressed_total 20949
telemt_desync_frames_bucket_total{bucket="1_2"} 6346
telemt_desync_frames_bucket_total{bucket="3_10"} 12561
telemt_desync_frames_bucket_total{bucket="gt_10"} 12915
telemt_pool_swap_total 139
telemt_pool_force_close_total 4000
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 380
telemt_me_draining_writers_reap_progress_total 48907
telemt_me_writer_removed_unexpected_total 1597
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3938
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46615
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3559
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44907
telemt_me_writer_teardown_success_total{mode="normal"} 50553
telemt_me_writer_teardown_noop_total 48914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99467
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.725528
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99467
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 380
telemt_me_refill_failed_total 2744
telemt_me_writer_restored_same_endpoint_total 1659
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5648624
telemt_user_connections_current{user="hello"} 643
telemt_user_octets_from_client{user="hello"} 120230424012 (111.97 GB)
telemt_user_octets_to_client{user="hello"} 2194279655066 (2.00 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 112267.4 (31h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1558629
telemt_connections_bad_total 36880
telemt_connections_current 475
telemt_connections_me_current 475
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32038
telemt_upstream_connect_attempt_total 53161
telemt_upstream_connect_success_total 52995
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 53133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27433
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 799
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2319
telemt_me_reconnect_success_total 949
telemt_me_reader_eof_total 939
telemt_me_idle_close_by_peer_total 939
telemt_me_route_drop_no_conn_total 525295
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1385606
telemt_me_endpoint_quarantine_total 944
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 931
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_me_writers_active_current 44
telemt_desync_total 9607
telemt_desync_full_logged_total 2738
telemt_desync_suppressed_total 6869
telemt_desync_frames_bucket_total{bucket="1_2"} 2911
telemt_desync_frames_bucket_total{bucket="3_10"} 3633
telemt_desync_frames_bucket_total{bucket="gt_10"} 3063
telemt_pool_swap_total 121
telemt_pool_force_close_total 3062
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 172
telemt_me_draining_writers_reap_progress_total 45149
telemt_me_writer_removed_unexpected_total 904
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3429
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42666
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2974
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42087
telemt_me_writer_teardown_success_total{mode="normal"} 46095
telemt_me_writer_teardown_noop_total 45153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91248
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.411445
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91248
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 172
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 809
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 1381368
telemt_user_connections_current{user="hello"} 475
telemt_user_octets_from_client{user="hello"} 26335344905 (24.53 GB)
telemt_user_octets_to_client{user="hello"} 584395215475 (544.26 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 194465.1 (54h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13387659
telemt_connections_bad_total 1619988
telemt_connections_current 776
telemt_connections_me_current 776
telemt_handshake_timeouts_total 390877
telemt_upstream_connect_attempt_total 77496
telemt_upstream_connect_success_total 77142
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 77360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38956
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3060
telemt_me_reconnect_success_total 1538
telemt_me_reader_eof_total 1523
telemt_me_idle_close_by_peer_total 1523
telemt_me_route_drop_no_conn_total 4489286
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10082685
telemt_me_endpoint_quarantine_total 1414
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1473
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_warm_current 22
telemt_desync_total 42292
telemt_desync_full_logged_total 13808
telemt_desync_suppressed_total 28484
telemt_desync_frames_bucket_total{bucket="1_2"} 10283
telemt_desync_frames_bucket_total{bucket="3_10"} 15535
telemt_desync_frames_bucket_total{bucket="gt_10"} 16474
telemt_pool_swap_total 215
telemt_pool_force_close_total 5677
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 683
telemt_me_draining_writers_reap_progress_total 70080
telemt_me_writer_removed_unexpected_total 1458
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5454
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66139
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5503
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64403
telemt_me_writer_teardown_success_total{mode="normal"} 71593
telemt_me_writer_teardown_noop_total 70082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 139056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 140783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 141166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141675
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.829245
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141675
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 683
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1351
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 10049358
telemt_user_connections_current{user="hello"} 776
telemt_user_octets_from_client{user="hello"} 195055345272 (181.66 GB)
telemt_user_octets_to_client{user="hello"} 4469049054136 (4.06 TB)
telemt_user_unique_ips_current{user="hello"} 332
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 194461.7 (54h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11695003
telemt_connections_bad_total 1366965
telemt_connections_current 565
telemt_connections_me_current 565
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 312956
telemt_upstream_connect_attempt_total 105146
telemt_upstream_connect_success_total 104241
telemt_upstream_connect_fail_total 696
telemt_upstream_connect_attempts_per_request{bucket="1"} 104937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44573
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 696
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10677
telemt_me_reconnect_success_total 2640
telemt_me_reader_eof_total 2451
telemt_me_idle_close_by_peer_total 2450
telemt_me_seq_mismatch_total 102
telemt_me_route_drop_no_conn_total 5656801
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8997946
telemt_me_endpoint_quarantine_total 1589
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 53
telemt_me_single_endpoint_outage_exit_total 53
telemt_me_single_endpoint_outage_reconnect_attempt_total 53
telemt_me_single_endpoint_outage_reconnect_success_total 51
telemt_me_single_endpoint_quarantine_bypass_total 53
telemt_me_single_endpoint_shadow_rotate_total 1475
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_me_writers_warm_current 19
telemt_desync_total 41985
telemt_desync_full_logged_total 13520
telemt_desync_suppressed_total 28465
telemt_desync_frames_bucket_total{bucket="1_2"} 10866
telemt_desync_frames_bucket_total{bucket="3_10"} 15441
telemt_desync_frames_bucket_total{bucket="gt_10"} 15678
telemt_pool_swap_total 205
telemt_pool_force_close_total 5443
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 671
telemt_me_draining_writers_reap_progress_total 70282
telemt_me_writer_removed_unexpected_total 2491
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6834
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66030
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4972
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64839
telemt_me_writer_teardown_success_total{mode="normal"} 72864
telemt_me_writer_teardown_noop_total 70287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 140461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 142243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 142782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 143101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 143151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 143151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 143151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 143151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 143151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 143151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 143151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 143151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 143151
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.511555
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 143151
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 671
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 2119
telemt_me_writer_restored_fallback_total 137
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 9002504
telemt_user_connections_current{user="hello"} 565
telemt_user_octets_from_client{user="hello"} 157638102412 (146.81 GB)
telemt_user_octets_to_client{user="hello"} 3509555202030 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 69
```
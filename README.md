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

# Server Metrics 2026-03-21 22:36:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 5412.2 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97441
telemt_connections_bad_total 6874
telemt_connections_current 627
telemt_connections_me_current 627
telemt_handshake_timeouts_total 4568
telemt_upstream_connect_attempt_total 2094
telemt_upstream_connect_success_total 2093
telemt_upstream_connect_attempts_per_request{bucket="1"} 2093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1347
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 45
telemt_me_reconnect_success_total 26
telemt_me_reader_eof_total 27
telemt_me_idle_close_by_peer_total 27
telemt_me_route_drop_no_conn_total 20174
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79357
telemt_me_endpoint_quarantine_total 31
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 535
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 367
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 5
telemt_pool_force_close_total 134
telemt_me_writer_close_signal_drop_total 10
telemt_me_draining_writers_reap_progress_total 1826
telemt_me_writer_removed_unexpected_total 25
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 126
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1727
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 130
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1692
telemt_me_writer_teardown_success_total{mode="normal"} 1853
telemt_me_writer_teardown_noop_total 1826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3679
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.133145
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3679
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 10
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 79287
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 1080257972 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 29806978920 (27.76 GB)
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 18778.5 (5h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 610400
telemt_connections_bad_total 28111
telemt_connections_current 892
telemt_connections_me_current 892
telemt_handshake_timeouts_total 22257
telemt_upstream_connect_attempt_total 7638
telemt_upstream_connect_success_total 7500
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 7623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_reconnect_attempts_total 624
telemt_me_reconnect_success_total 225
telemt_me_reader_eof_total 193
telemt_me_idle_close_by_peer_total 193
telemt_me_route_drop_no_conn_total 314459
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 497212
telemt_me_endpoint_quarantine_total 152
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 150
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_desync_total 2220
telemt_desync_full_logged_total 1258
telemt_desync_suppressed_total 962
telemt_desync_frames_bucket_total{bucket="1_2"} 465
telemt_desync_frames_bucket_total{bucket="3_10"} 842
telemt_desync_frames_bucket_total{bucket="gt_10"} 913
telemt_pool_swap_total 20
telemt_pool_force_close_total 579
telemt_me_writer_close_signal_drop_total 44
telemt_me_draining_writers_reap_progress_total 6705
telemt_me_writer_removed_unexpected_total 182
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 581
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6304
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 572
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6126
telemt_me_writer_teardown_success_total{mode="normal"} 6885
telemt_me_writer_teardown_noop_total 6705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13590
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.112411
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13590
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 44
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 156
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 496558
telemt_user_connections_current{user="hello"} 892
telemt_user_octets_from_client{user="hello"} 8518985928 (7.93 GB)
telemt_user_octets_to_client{user="hello"} 170078802788 (158.40 GB)
telemt_user_unique_ips_current{user="hello"} 581
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 93638.7 (26h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7263798
telemt_connections_bad_total 554671
telemt_connections_current 2544
telemt_connections_me_current 2544
telemt_handshake_timeouts_total 229141
telemt_upstream_connect_attempt_total 33682
telemt_upstream_connect_success_total 33614
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 33621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18278
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1460
telemt_me_reconnect_success_total 714
telemt_me_reader_eof_total 723
telemt_me_idle_close_by_peer_total 723
telemt_me_route_drop_no_conn_total 4467817
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5947721
telemt_me_endpoint_quarantine_total 587
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 690
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 11
telemt_desync_total 25165
telemt_desync_full_logged_total 8283
telemt_desync_suppressed_total 16882
telemt_desync_frames_bucket_total{bucket="1_2"} 5407
telemt_desync_frames_bucket_total{bucket="3_10"} 9844
telemt_desync_frames_bucket_total{bucket="gt_10"} 9914
telemt_pool_swap_total 100
telemt_pool_force_close_total 3390
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 554
telemt_me_draining_writers_reap_progress_total 30669
telemt_me_writer_removed_unexpected_total 695
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2614
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28327
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3151
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27279
telemt_me_writer_teardown_success_total{mode="normal"} 30941
telemt_me_writer_teardown_noop_total 30713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61654
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 150.493354
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61654
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 554
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 637
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 5940470
telemt_user_connections_current{user="hello"} 2544
telemt_user_octets_from_client{user="hello"} 101951623164 (94.95 GB)
telemt_user_octets_to_client{user="hello"} 1927222133960 (1.75 TB)
telemt_user_unique_ips_current{user="hello"} 1118
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 93639.9 (26h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5965755
telemt_connections_bad_total 574180
telemt_connections_current 1865
telemt_connections_me_current 1865
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 195326
telemt_upstream_connect_attempt_total 37662
telemt_upstream_connect_success_total 37328
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 37502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17958
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1738
telemt_me_reconnect_success_total 741
telemt_me_reader_eof_total 716
telemt_me_idle_close_by_peer_total 716
telemt_me_route_drop_no_conn_total 2099701
telemt_me_route_drop_channel_closed_total 242
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4460724
telemt_me_endpoint_quarantine_total 566
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 713
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 11
telemt_desync_total 21475
telemt_desync_full_logged_total 7191
telemt_desync_suppressed_total 14284
telemt_desync_frames_bucket_total{bucket="1_2"} 5195
telemt_desync_frames_bucket_total{bucket="3_10"} 8306
telemt_desync_frames_bucket_total{bucket="gt_10"} 7974
telemt_pool_swap_total 102
telemt_pool_force_close_total 3092
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 341
telemt_me_draining_writers_reap_progress_total 29283
telemt_me_writer_removed_unexpected_total 693
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2510
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27398
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2893
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26191
telemt_me_writer_teardown_success_total{mode="normal"} 29908
telemt_me_writer_teardown_noop_total 29289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59197
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.139216
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59197
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 341
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 639
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 4422982
telemt_user_connections_current{user="hello"} 1865
telemt_user_octets_from_client{user="hello"} 136642534385 (127.26 GB)
telemt_user_octets_to_client{user="hello"} 2061415810835 (1.87 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 890
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 93603.1 (26h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5887576
telemt_connections_bad_total 532929
telemt_connections_current 1851
telemt_connections_me_current 1851
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 185705
telemt_upstream_connect_attempt_total 44013
telemt_upstream_connect_success_total 43716
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 43851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19381
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1044
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1781
telemt_me_reconnect_success_total 797
telemt_me_reader_eof_total 743
telemt_me_idle_close_by_peer_total 743
telemt_me_route_drop_no_conn_total 2075179
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4405488
telemt_me_endpoint_quarantine_total 624
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 696
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 21306
telemt_desync_full_logged_total 7004
telemt_desync_suppressed_total 14302
telemt_desync_frames_bucket_total{bucket="1_2"} 5259
telemt_desync_frames_bucket_total{bucket="3_10"} 8091
telemt_desync_frames_bucket_total{bucket="gt_10"} 7956
telemt_pool_swap_total 100
telemt_pool_force_close_total 2969
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 356
telemt_me_draining_writers_reap_progress_total 30673
telemt_me_writer_removed_unexpected_total 712
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2589
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28801
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2754
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27704
telemt_me_writer_teardown_success_total{mode="normal"} 31390
telemt_me_writer_teardown_noop_total 30684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62074
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.994639
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62074
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 356
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 690
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 4407134
telemt_user_connections_current{user="hello"} 1851
telemt_user_octets_from_client{user="hello"} 129667211511 (120.76 GB)
telemt_user_octets_to_client{user="hello"} 2014782939095 (1.83 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 855
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 93642.8 (26h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19697408
telemt_connections_bad_total 1388663
telemt_connections_current 2642
telemt_connections_me_current 2642
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 561210
telemt_upstream_connect_attempt_total 183728
telemt_upstream_connect_success_total 166402
telemt_upstream_connect_fail_total 15823
telemt_upstream_connect_attempts_per_request{bucket="1"} 182225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38203
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8858
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15823
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 60240
telemt_me_reconnect_success_total 1987
telemt_me_reader_eof_total 1289
telemt_me_idle_close_by_peer_total 1288
telemt_me_route_drop_no_conn_total 39409046
telemt_me_route_drop_channel_closed_total 120
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16102663
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 690
telemt_me_single_endpoint_outage_enter_total 112
telemt_me_single_endpoint_outage_exit_total 112
telemt_me_single_endpoint_outage_reconnect_attempt_total 240
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 240
telemt_me_single_endpoint_shadow_rotate_total 725
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
telemt_me_writers_active_current 49
telemt_me_writers_warm_current 13
telemt_desync_total 30898
telemt_desync_full_logged_total 9150
telemt_desync_suppressed_total 21748
telemt_desync_frames_bucket_total{bucket="1_2"} 6772
telemt_desync_frames_bucket_total{bucket="3_10"} 13692
telemt_desync_frames_bucket_total{bucket="gt_10"} 10434
telemt_pool_swap_total 95
telemt_pool_force_close_total 3202
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 723
telemt_me_draining_writers_reap_progress_total 28926
telemt_me_writer_removed_unexpected_total 1862
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3918
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26597
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2694
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 508
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25724
telemt_me_writer_teardown_success_total{mode="normal"} 30515
telemt_me_writer_teardown_noop_total 28952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59467
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 208.552207
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59467
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 723
telemt_me_refill_failed_total 3549
telemt_me_writer_restored_same_endpoint_total 1397
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14284
telemt_me_writer_removed_unexpected_minus_restored_total 451
telemt_user_connections_total{user="hello"} 16227577
telemt_user_connections_current{user="hello"} 2642
telemt_user_octets_from_client{user="hello"} 172820189162 (160.95 GB)
telemt_user_octets_to_client{user="hello"} 1062263817522 (989.31 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1133
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 93610.2 (26h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5707243
telemt_connections_bad_total 534606
telemt_connections_current 1854
telemt_connections_me_current 1854
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 118193
telemt_upstream_connect_attempt_total 51466
telemt_upstream_connect_success_total 50916
telemt_upstream_connect_fail_total 464
telemt_upstream_connect_attempts_per_request{bucket="1"} 51380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19901
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 464
telemt_me_reconnect_attempts_total 11764
telemt_me_reconnect_success_total 1341
telemt_me_reader_eof_total 1245
telemt_me_idle_close_by_peer_total 1245
telemt_me_route_drop_no_conn_total 2334356
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4446083
telemt_me_endpoint_quarantine_total 583
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 697
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 22406
telemt_desync_full_logged_total 7798
telemt_desync_suppressed_total 14608
telemt_desync_frames_bucket_total{bucket="1_2"} 4268
telemt_desync_frames_bucket_total{bucket="3_10"} 8695
telemt_desync_frames_bucket_total{bucket="gt_10"} 9443
telemt_pool_swap_total 95
telemt_pool_force_close_total 2785
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 361
telemt_me_draining_writers_reap_progress_total 31646
telemt_me_writer_removed_unexpected_total 1246
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3220
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29686
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2417
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28861
telemt_me_writer_teardown_success_total{mode="normal"} 32906
telemt_me_writer_teardown_noop_total 31647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64553
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.641526
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64553
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 361
telemt_me_refill_failed_total 625
telemt_me_writer_restored_same_endpoint_total 1118
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 1544
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 4439214
telemt_user_connections_current{user="hello"} 1854
telemt_user_octets_from_client{user="hello"} 117668628300 (109.59 GB)
telemt_user_octets_to_client{user="hello"} 1806800747682 (1.64 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 859
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 30445.9 (8h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3550594
telemt_connections_bad_total 125545
telemt_connections_current 1689
telemt_connections_me_current 1689
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1497805
telemt_upstream_connect_attempt_total 15535
telemt_upstream_connect_success_total 15410
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 15529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5793
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_reconnect_attempts_total 22083
telemt_me_reconnect_success_total 542
telemt_me_reader_eof_total 376
telemt_me_idle_close_by_peer_total 376
telemt_me_route_drop_no_conn_total 975355
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1698007
telemt_me_endpoint_quarantine_total 183
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 225
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_me_floor_cap_block_total 13
telemt_me_floor_swap_idle_failed_total 13
telemt_desync_total 9399
telemt_desync_full_logged_total 3173
telemt_desync_suppressed_total 6226
telemt_desync_frames_bucket_total{bucket="1_2"} 1668
telemt_desync_frames_bucket_total{bucket="3_10"} 3610
telemt_desync_frames_bucket_total{bucket="gt_10"} 4121
telemt_pool_swap_total 32
telemt_pool_force_close_total 1053
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 103
telemt_me_draining_writers_reap_progress_total 9223
telemt_me_writer_removed_unexpected_total 411
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 950
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8698
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 904
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 149
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8170
telemt_me_writer_teardown_success_total{mode="normal"} 9648
telemt_me_writer_teardown_noop_total 9224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 18766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 18872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 18872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 18872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 18872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 18872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 18872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 18872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 18872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 18872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 18872
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.730719
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 18872
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 103
telemt_me_refill_failed_total 1212
telemt_me_writer_restored_same_endpoint_total 474
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 160
telemt_me_async_recovery_trigger_total 2130
telemt_user_connections_total{user="hello"} 1698162
telemt_user_connections_current{user="hello"} 1689
telemt_user_octets_from_client{user="hello"} 49130228960 (45.76 GB)
telemt_user_octets_to_client{user="hello"} 730673656514 (680.49 GB)
telemt_user_msgs_from_client{user="hello"} 43112
telemt_user_msgs_to_client{user="hello"} 113951
telemt_user_unique_ips_current{user="hello"} 820
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 11417.1 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133484
telemt_connections_bad_total 1338
telemt_connections_current 410
telemt_connections_me_current 410
telemt_handshake_timeouts_total 3330
telemt_upstream_connect_attempt_total 4987
telemt_upstream_connect_success_total 4972
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 4986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2843
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 106
telemt_me_reconnect_success_total 57
telemt_me_reader_eof_total 61
telemt_me_idle_close_by_peer_total 61
telemt_me_route_drop_no_conn_total 37870
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115853
telemt_me_endpoint_quarantine_total 91
telemt_me_single_endpoint_shadow_rotate_total 101
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 928
telemt_desync_full_logged_total 229
telemt_desync_suppressed_total 699
telemt_desync_frames_bucket_total{bucket="1_2"} 377
telemt_desync_frames_bucket_total{bucket="3_10"} 338
telemt_desync_frames_bucket_total{bucket="gt_10"} 213
telemt_pool_swap_total 12
telemt_pool_force_close_total 299
telemt_me_writer_close_signal_drop_total 15
telemt_me_draining_writers_reap_progress_total 4411
telemt_me_writer_removed_unexpected_total 59
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 282
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4190
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 297
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4112
telemt_me_writer_teardown_success_total{mode="normal"} 4472
telemt_me_writer_teardown_noop_total 4411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 8873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 8883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8883
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.610691
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8883
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 15
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 115686
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 2256005324 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 69100952828 (64.36 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 93614.9 (26h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6821377
telemt_connections_bad_total 689435
telemt_connections_current 2214
telemt_connections_me_current 2214
telemt_handshake_timeouts_total 194824
telemt_upstream_connect_attempt_total 35436
telemt_upstream_connect_success_total 35295
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 35399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17759
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_reconnect_attempts_total 1437
telemt_me_reconnect_success_total 740
telemt_me_reader_eof_total 717
telemt_me_idle_close_by_peer_total 717
telemt_me_route_drop_no_conn_total 2070599
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5199896
telemt_me_endpoint_quarantine_total 621
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 714
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
telemt_me_writers_active_current 47
telemt_desync_total 19964
telemt_desync_full_logged_total 6671
telemt_desync_suppressed_total 13293
telemt_desync_frames_bucket_total{bucket="1_2"} 4857
telemt_desync_frames_bucket_total{bucket="3_10"} 7275
telemt_desync_frames_bucket_total{bucket="gt_10"} 7832
telemt_pool_swap_total 103
telemt_pool_force_close_total 2824
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 353
telemt_me_draining_writers_reap_progress_total 31848
telemt_me_writer_removed_unexpected_total 696
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2580
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29975
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2736
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29024
telemt_me_writer_teardown_success_total{mode="normal"} 32555
telemt_me_writer_teardown_noop_total 31850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64405
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.293360
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64405
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 353
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 662
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 5175312
telemt_user_connections_current{user="hello"} 2214
telemt_user_octets_from_client{user="hello"} 104362881172 (97.20 GB)
telemt_user_octets_to_client{user="hello"} 2433071857004 (2.21 TB)
telemt_user_unique_ips_current{user="hello"} 983
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 93611.5 (26h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5821733
telemt_connections_bad_total 553212
telemt_connections_current 2179
telemt_connections_me_current 2179
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 163770
telemt_upstream_connect_attempt_total 51556
telemt_upstream_connect_success_total 51166
telemt_upstream_connect_fail_total 331
telemt_upstream_connect_attempts_per_request{bucket="1"} 51497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19524
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 331
telemt_me_reconnect_attempts_total 5223
telemt_me_reconnect_success_total 1047
telemt_me_reader_eof_total 924
telemt_me_idle_close_by_peer_total 924
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2122639
telemt_me_route_drop_channel_closed_total 188
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4567855
telemt_me_endpoint_quarantine_total 726
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 710
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 18655
telemt_desync_full_logged_total 6299
telemt_desync_suppressed_total 12356
telemt_desync_frames_bucket_total{bucket="1_2"} 4641
telemt_desync_frames_bucket_total{bucket="3_10"} 6798
telemt_desync_frames_bucket_total{bucket="gt_10"} 7216
telemt_pool_swap_total 101
telemt_pool_force_close_total 2779
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 358
telemt_me_draining_writers_reap_progress_total 30780
telemt_me_writer_removed_unexpected_total 934
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3077
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28680
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2556
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28001
telemt_me_writer_teardown_success_total{mode="normal"} 31757
telemt_me_writer_teardown_noop_total 30784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62541
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.489409
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62541
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 358
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 810
telemt_me_writer_restored_fallback_total 49
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 4571395
telemt_user_connections_current{user="hello"} 2179
telemt_user_octets_from_client{user="hello"} 87559377337 (81.55 GB)
telemt_user_octets_to_client{user="hello"} 1962505489344 (1.78 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 909
telemt_user_unique_ips_recent_window{user="hello"} 226
```
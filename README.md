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

# Server Metrics 2026-03-22 04:53:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 28053.8 (7h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 462046
telemt_connections_bad_total 31275
telemt_connections_current 959
telemt_connections_me_current 959
telemt_handshake_timeouts_total 25790
telemt_upstream_connect_attempt_total 11664
telemt_upstream_connect_success_total 11663
telemt_upstream_connect_attempts_per_request{bucket="1"} 11663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7509
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 310
telemt_me_reconnect_success_total 181
telemt_me_reader_eof_total 177
telemt_me_idle_close_by_peer_total 177
telemt_me_route_drop_no_conn_total 96427
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 380911
telemt_me_endpoint_quarantine_total 223
telemt_me_single_endpoint_shadow_rotate_total 233
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
telemt_desync_total 3431
telemt_desync_full_logged_total 931
telemt_desync_suppressed_total 2500
telemt_desync_frames_bucket_total{bucket="1_2"} 1188
telemt_desync_frames_bucket_total{bucket="3_10"} 1313
telemt_desync_frames_bucket_total{bucket="gt_10"} 930
telemt_pool_swap_total 31
telemt_pool_force_close_total 793
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 10532
telemt_me_writer_removed_unexpected_total 175
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 718
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9981
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 788
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9739
telemt_me_writer_teardown_success_total{mode="normal"} 10699
telemt_me_writer_teardown_noop_total 10533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 20537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 21043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 21154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 21214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 21232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 21232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 21232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 21232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 21232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 21232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 21232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 21232
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.483964
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 21232
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 164
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 379973
telemt_user_connections_current{user="hello"} 959
telemt_user_octets_from_client{user="hello"} 5165911924 (4.81 GB)
telemt_user_octets_to_client{user="hello"} 134766084608 (125.51 GB)
telemt_user_unique_ips_current{user="hello"} 455
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 41420.2 (11h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 912467
telemt_connections_bad_total 64293
telemt_connections_current 1046
telemt_connections_me_current 1046
telemt_handshake_timeouts_total 31848
telemt_upstream_connect_attempt_total 19377
telemt_upstream_connect_success_total 19074
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 19346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10635
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_reconnect_attempts_total 1613
telemt_me_reconnect_success_total 600
telemt_me_reader_eof_total 530
telemt_me_idle_close_by_peer_total 530
telemt_me_route_drop_no_conn_total 364007
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 720768
telemt_me_endpoint_quarantine_total 384
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 334
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
telemt_desync_total 3083
telemt_desync_full_logged_total 1781
telemt_desync_suppressed_total 1302
telemt_desync_frames_bucket_total{bucket="1_2"} 643
telemt_desync_frames_bucket_total{bucket="3_10"} 1192
telemt_desync_frames_bucket_total{bucket="gt_10"} 1248
telemt_pool_swap_total 44
telemt_pool_force_close_total 1178
telemt_me_writer_close_signal_drop_total 85
telemt_me_draining_writers_reap_progress_total 17171
telemt_me_writer_removed_unexpected_total 505
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1433
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16255
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1156
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15993
telemt_me_writer_teardown_success_total{mode="normal"} 17688
telemt_me_writer_teardown_noop_total 17171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34859
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.076867
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34859
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 85
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 450
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 719592
telemt_user_connections_current{user="hello"} 1046
telemt_user_octets_from_client{user="hello"} 11541145040 (10.75 GB)
telemt_user_octets_to_client{user="hello"} 261021256956 (243.09 GB)
telemt_user_unique_ips_current{user="hello"} 678
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 116280.1 (32h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8109990
telemt_connections_bad_total 694080
telemt_connections_current 3114
telemt_connections_me_current 3114
telemt_handshake_timeouts_total 265582
telemt_upstream_connect_attempt_total 43403
telemt_upstream_connect_success_total 43325
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 43333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23513
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1638
telemt_me_reconnect_success_total 855
telemt_me_reader_eof_total 863
telemt_me_idle_close_by_peer_total 863
telemt_me_route_drop_no_conn_total 4600019
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6521959
telemt_me_endpoint_quarantine_total 746
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 873
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 27396
telemt_desync_full_logged_total 9121
telemt_desync_suppressed_total 18275
telemt_desync_frames_bucket_total{bucket="1_2"} 5912
telemt_desync_frames_bucket_total{bucket="3_10"} 10709
telemt_desync_frames_bucket_total{bucket="gt_10"} 10775
telemt_pool_swap_total 126
telemt_pool_force_close_total 4111
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 621
telemt_me_draining_writers_reap_progress_total 39590
telemt_me_writer_removed_unexpected_total 831
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3279
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36671
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3870
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 241
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35479
telemt_me_writer_teardown_success_total{mode="normal"} 39950
telemt_me_writer_teardown_noop_total 39634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79584
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 165.343509
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79584
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 621
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 762
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6513665
telemt_user_connections_current{user="hello"} 3114
telemt_user_octets_from_client{user="hello"} 110661638032 (103.06 GB)
telemt_user_octets_to_client{user="hello"} 2200212567952 (2.00 TB)
telemt_user_unique_ips_current{user="hello"} 1354
telemt_user_unique_ips_recent_window{user="hello"} 358
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 116281.4 (32h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6685949
telemt_connections_bad_total 598009
telemt_connections_current 2549
telemt_connections_me_current 2549
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 222272
telemt_upstream_connect_attempt_total 47343
telemt_upstream_connect_success_total 46944
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 47146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23142
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 558
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2039
telemt_me_reconnect_success_total 917
telemt_me_reader_eof_total 894
telemt_me_idle_close_by_peer_total 894
telemt_me_route_drop_no_conn_total 2309180
telemt_me_route_drop_channel_closed_total 285
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4995028
telemt_me_endpoint_quarantine_total 736
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 898
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
telemt_desync_total 23258
telemt_desync_full_logged_total 7960
telemt_desync_suppressed_total 15298
telemt_desync_frames_bucket_total{bucket="1_2"} 5587
telemt_desync_frames_bucket_total{bucket="3_10"} 9034
telemt_desync_frames_bucket_total{bucket="gt_10"} 8637
telemt_pool_swap_total 127
telemt_pool_force_close_total 3737
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 380
telemt_me_draining_writers_reap_progress_total 38030
telemt_me_writer_removed_unexpected_total 874
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3140
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35706
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3519
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34293
telemt_me_writer_teardown_success_total{mode="normal"} 38846
telemt_me_writer_teardown_noop_total 38036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76882
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.255605
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76882
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 380
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 799
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 4916646
telemt_user_connections_current{user="hello"} 2549
telemt_user_octets_from_client{user="hello"} 145018661297 (135.06 GB)
telemt_user_octets_to_client{user="hello"} 2346523423703 (2.13 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1100
telemt_user_unique_ips_recent_window{user="hello"} 474
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 116246.0 (32h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6536010
telemt_connections_bad_total 556114
telemt_connections_current 2068
telemt_connections_me_current 2068
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 216417
telemt_upstream_connect_attempt_total 53772
telemt_upstream_connect_success_total 53251
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 53394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24699
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 693
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 2386
telemt_me_reconnect_success_total 1046
telemt_me_reader_eof_total 984
telemt_me_idle_close_by_peer_total 984
telemt_me_route_drop_no_conn_total 2271565
telemt_me_route_drop_channel_closed_total 133
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4859603
telemt_me_endpoint_quarantine_total 829
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 864
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
telemt_me_writers_active_current 41
telemt_desync_total 23129
telemt_desync_full_logged_total 7847
telemt_desync_suppressed_total 15282
telemt_desync_frames_bucket_total{bucket="1_2"} 5643
telemt_desync_frames_bucket_total{bucket="3_10"} 8863
telemt_desync_frames_bucket_total{bucket="gt_10"} 8623
telemt_pool_swap_total 125
telemt_pool_force_close_total 3607
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 410
telemt_me_draining_writers_reap_progress_total 39123
telemt_me_writer_removed_unexpected_total 975
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3341
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36776
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3372
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 235
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35516
telemt_me_writer_teardown_success_total{mode="normal"} 40117
telemt_me_writer_teardown_noop_total 39135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79252
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 32.926435
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79252
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 410
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 916
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 4854305
telemt_user_connections_current{user="hello"} 2068
telemt_user_octets_from_client{user="hello"} 136282516607 (126.92 GB)
telemt_user_octets_to_client{user="hello"} 2222992306147 (2.02 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 910
telemt_user_unique_ips_recent_window{user="hello"} 441
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 116284.8 (32h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20934894
telemt_connections_bad_total 1760822
telemt_connections_current 3305
telemt_connections_me_current 3305
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 635395
telemt_upstream_connect_attempt_total 204423
telemt_upstream_connect_success_total 186104
telemt_upstream_connect_fail_total 16475
telemt_upstream_connect_attempts_per_request{bucket="1"} 202579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45158
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8952
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16475
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65224
telemt_me_reconnect_success_total 2473
telemt_me_reader_eof_total 1561
telemt_me_idle_close_by_peer_total 1560
telemt_me_route_drop_no_conn_total 39698624
telemt_me_route_drop_channel_closed_total 129
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16830680
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 904
telemt_me_single_endpoint_outage_enter_total 144
telemt_me_single_endpoint_outage_exit_total 144
telemt_me_single_endpoint_outage_reconnect_attempt_total 297
telemt_me_single_endpoint_outage_reconnect_success_total 76
telemt_me_single_endpoint_quarantine_bypass_total 297
telemt_me_single_endpoint_shadow_rotate_total 913
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_desync_total 32642
telemt_desync_full_logged_total 9843
telemt_desync_suppressed_total 22799
telemt_desync_frames_bucket_total{bucket="1_2"} 7092
telemt_desync_frames_bucket_total{bucket="3_10"} 14479
telemt_desync_frames_bucket_total{bucket="gt_10"} 11071
telemt_pool_swap_total 120
telemt_pool_force_close_total 3859
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 839
telemt_me_draining_writers_reap_progress_total 36674
telemt_me_writer_removed_unexpected_total 2299
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4933
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33786
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3302
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 557
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32815
telemt_me_writer_teardown_success_total{mode="normal"} 38719
telemt_me_writer_teardown_noop_total 36701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75420
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 217.293260
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75420
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 839
telemt_me_refill_failed_total 3809
telemt_me_writer_restored_same_endpoint_total 1696
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 582
telemt_user_connections_total{user="hello"} 16965321
telemt_user_connections_current{user="hello"} 3305
telemt_user_octets_from_client{user="hello"} 245919075368 (229.03 GB)
telemt_user_octets_to_client{user="hello"} 1302075290595 (1.18 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1391
telemt_user_unique_ips_recent_window{user="hello"} 470
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 116252.3 (32h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6312436
telemt_connections_bad_total 606513
telemt_connections_current 2305
telemt_connections_me_current 2305
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 133450
telemt_upstream_connect_attempt_total 62249
telemt_upstream_connect_success_total 61529
telemt_upstream_connect_fail_total 614
telemt_upstream_connect_attempts_per_request{bucket="1"} 62143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25624
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 359
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 614
telemt_me_reconnect_attempts_total 69868
telemt_me_reconnect_success_total 1865
telemt_me_reader_eof_total 1644
telemt_me_idle_close_by_peer_total 1643
telemt_me_route_drop_no_conn_total 2443120
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4900446
telemt_me_endpoint_quarantine_total 789
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 884
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 24419
telemt_desync_full_logged_total 8568
telemt_desync_suppressed_total 15851
telemt_desync_frames_bucket_total{bucket="1_2"} 4798
telemt_desync_frames_bucket_total{bucket="3_10"} 9439
telemt_desync_frames_bucket_total{bucket="gt_10"} 10182
telemt_pool_swap_total 121
telemt_pool_force_close_total 3431
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 408
telemt_me_draining_writers_reap_progress_total 41071
telemt_me_writer_removed_unexpected_total 1680
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4165
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38618
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3027
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 404
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37640
telemt_me_writer_teardown_success_total{mode="normal"} 42783
telemt_me_writer_teardown_noop_total 41072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83855
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.855535
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83855
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 408
telemt_me_refill_failed_total 4213
telemt_me_writer_restored_same_endpoint_total 1561
telemt_me_writer_restored_fallback_total 37
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 4892708
telemt_user_connections_current{user="hello"} 2305
telemt_user_octets_from_client{user="hello"} 128124622052 (119.33 GB)
telemt_user_octets_to_client{user="hello"} 2027194093234 (1.84 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1126
telemt_user_unique_ips_recent_window{user="hello"} 320
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 53088.2 (14h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4270366
telemt_connections_bad_total 180743
telemt_connections_current 2145
telemt_connections_me_current 2145
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1692288
telemt_upstream_connect_attempt_total 31075
telemt_upstream_connect_success_total 30871
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 31068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_reconnect_attempts_total 45983
telemt_me_reconnect_success_total 1019
telemt_me_reader_eof_total 707
telemt_me_idle_close_by_peer_total 707
telemt_me_route_drop_no_conn_total 1072873
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2106875
telemt_me_endpoint_quarantine_total 383
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 410
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 11372
telemt_desync_full_logged_total 3916
telemt_desync_suppressed_total 7456
telemt_desync_frames_bucket_total{bucket="1_2"} 2154
telemt_desync_frames_bucket_total{bucket="3_10"} 4365
telemt_desync_frames_bucket_total{bucket="gt_10"} 4853
telemt_pool_swap_total 57
telemt_pool_force_close_total 1672
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 150
telemt_me_draining_writers_reap_progress_total 19789
telemt_me_writer_removed_unexpected_total 778
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1708
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18888
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1465
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 207
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18117
telemt_me_writer_teardown_success_total{mode="normal"} 20596
telemt_me_writer_teardown_noop_total 19791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40387
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.523744
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40387
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 150
telemt_me_refill_failed_total 2612
telemt_me_writer_restored_same_endpoint_total 912
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2110041
telemt_user_connections_current{user="hello"} 2145
telemt_user_octets_from_client{user="hello"} 57152907296 (53.23 GB)
telemt_user_octets_to_client{user="hello"} 917557510234 (854.54 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 961
telemt_user_unique_ips_recent_window{user="hello"} 264
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 34059.0 (9h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239653
telemt_connections_bad_total 1869
telemt_connections_current 480
telemt_connections_me_current 480
telemt_handshake_timeouts_total 6324
telemt_upstream_connect_attempt_total 16472
telemt_upstream_connect_success_total 16431
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 16468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 402
telemt_me_reconnect_success_total 224
telemt_me_reader_eof_total 225
telemt_me_idle_close_by_peer_total 225
telemt_me_route_drop_no_conn_total 66519
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 212856
telemt_me_endpoint_quarantine_total 330
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 295
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1194
telemt_desync_full_logged_total 323
telemt_desync_suppressed_total 871
telemt_desync_frames_bucket_total{bucket="1_2"} 419
telemt_desync_frames_bucket_total{bucket="3_10"} 460
telemt_desync_frames_bucket_total{bucket="gt_10"} 315
telemt_pool_swap_total 37
telemt_pool_force_close_total 822
telemt_me_writer_close_signal_drop_total 30
telemt_me_draining_writers_reap_progress_total 14912
telemt_me_writer_removed_unexpected_total 215
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 943
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14194
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 820
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14090
telemt_me_writer_teardown_success_total{mode="normal"} 15137
telemt_me_writer_teardown_noop_total 14912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30049
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.216530
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30049
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 30
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 194
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 212504
telemt_user_connections_current{user="hello"} 480
telemt_user_octets_from_client{user="hello"} 3604735068 (3.36 GB)
telemt_user_octets_to_client{user="hello"} 132609023904 (123.50 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 116256.7 (32h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7654513
telemt_connections_bad_total 765142
telemt_connections_current 2604
telemt_connections_me_current 2604
telemt_handshake_timeouts_total 217746
telemt_upstream_connect_attempt_total 45864
telemt_upstream_connect_success_total 45696
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 45827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23055
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_reconnect_attempts_total 1679
telemt_me_reconnect_success_total 897
telemt_me_reader_eof_total 889
telemt_me_idle_close_by_peer_total 889
telemt_me_route_drop_no_conn_total 2178208
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5698874
telemt_me_endpoint_quarantine_total 835
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 893
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 22286
telemt_desync_full_logged_total 7342
telemt_desync_suppressed_total 14944
telemt_desync_frames_bucket_total{bucket="1_2"} 5575
telemt_desync_frames_bucket_total{bucket="3_10"} 8102
telemt_desync_frames_bucket_total{bucket="gt_10"} 8609
telemt_pool_swap_total 129
telemt_pool_force_close_total 3413
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 404
telemt_me_draining_writers_reap_progress_total 41377
telemt_me_writer_removed_unexpected_total 854
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3229
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39027
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3325
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37964
telemt_me_writer_teardown_success_total{mode="normal"} 42256
telemt_me_writer_teardown_noop_total 41379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83635
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.799236
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83635
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 404
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 802
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 5673578
telemt_user_connections_current{user="hello"} 2604
telemt_user_octets_from_client{user="hello"} 112693930044 (104.95 GB)
telemt_user_octets_to_client{user="hello"} 2645119580508 (2.41 TB)
telemt_user_unique_ips_current{user="hello"} 1091
telemt_user_unique_ips_recent_window{user="hello"} 307
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 116253.3 (32h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6635244
telemt_connections_bad_total 650239
telemt_connections_current 2663
telemt_connections_me_current 2663
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 180455
telemt_upstream_connect_attempt_total 61718
telemt_upstream_connect_success_total 61252
telemt_upstream_connect_fail_total 406
telemt_upstream_connect_attempts_per_request{bucket="1"} 61658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24665
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 406
telemt_me_reconnect_attempts_total 5757
telemt_me_reconnect_success_total 1261
telemt_me_reader_eof_total 1132
telemt_me_idle_close_by_peer_total 1132
telemt_me_seq_mismatch_total 53
telemt_me_route_drop_no_conn_total 2232419
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5067566
telemt_me_endpoint_quarantine_total 916
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 890
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
telemt_desync_total 21007
telemt_desync_full_logged_total 7014
telemt_desync_suppressed_total 13993
telemt_desync_frames_bucket_total{bucket="1_2"} 5332
telemt_desync_frames_bucket_total{bucket="3_10"} 7684
telemt_desync_frames_bucket_total{bucket="gt_10"} 7991
telemt_pool_swap_total 127
telemt_pool_force_close_total 3365
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 398
telemt_me_draining_writers_reap_progress_total 39972
telemt_me_writer_removed_unexpected_total 1144
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3781
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37391
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3142
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36607
telemt_me_writer_teardown_success_total{mode="normal"} 41172
telemt_me_writer_teardown_noop_total 39976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81148
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.416490
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81148
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 398
telemt_me_refill_failed_total 259
telemt_me_writer_restored_same_endpoint_total 986
telemt_me_writer_restored_fallback_total 71
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 5070341
telemt_user_connections_current{user="hello"} 2663
telemt_user_octets_from_client{user="hello"} 95593869317 (89.03 GB)
telemt_user_octets_to_client{user="hello"} 2179528383900 (1.98 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1120
telemt_user_unique_ips_recent_window{user="hello"} 288
```
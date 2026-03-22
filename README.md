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

# Server Metrics 2026-03-22 04:33:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 26816.0 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432498
telemt_connections_bad_total 28569
telemt_connections_current 1138
telemt_connections_me_current 1138
telemt_handshake_timeouts_total 24088
telemt_upstream_connect_attempt_total 11186
telemt_upstream_connect_success_total 11185
telemt_upstream_connect_attempts_per_request{bucket="1"} 11185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7207
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 302
telemt_me_reconnect_success_total 173
telemt_me_reader_eof_total 169
telemt_me_idle_close_by_peer_total 169
telemt_me_route_drop_no_conn_total 88834
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 357041
telemt_me_endpoint_quarantine_total 209
telemt_me_single_endpoint_shadow_rotate_total 224
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_desync_total 3242
telemt_desync_full_logged_total 881
telemt_desync_suppressed_total 2361
telemt_desync_frames_bucket_total{bucket="1_2"} 1122
telemt_desync_frames_bucket_total{bucket="3_10"} 1232
telemt_desync_frames_bucket_total{bucket="gt_10"} 888
telemt_pool_swap_total 29
telemt_pool_force_close_total 765
telemt_me_writer_close_signal_drop_total 58
telemt_me_draining_writers_reap_progress_total 10107
telemt_me_writer_removed_unexpected_total 167
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 679
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9587
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 760
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9342
telemt_me_writer_teardown_success_total{mode="normal"} 10266
telemt_me_writer_teardown_noop_total 10108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 20229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 20323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 20366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 20374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 20374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 20374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 20374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 20374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 20374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 20374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 20374
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.852148
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 20374
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 58
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 356122
telemt_user_connections_current{user="hello"} 1137
telemt_user_octets_from_client{user="hello"} 4780678760 (4.45 GB)
telemt_user_octets_to_client{user="hello"} 124127776984 (115.60 GB)
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 40182.1 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 885921
telemt_connections_bad_total 59678
telemt_connections_current 750
telemt_connections_me_current 750
telemt_handshake_timeouts_total 31463
telemt_upstream_connect_attempt_total 18835
telemt_upstream_connect_success_total 18542
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 18804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_reconnect_attempts_total 1527
telemt_me_reconnect_success_total 573
telemt_me_reader_eof_total 510
telemt_me_idle_close_by_peer_total 510
telemt_me_route_drop_no_conn_total 358354
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 701409
telemt_me_endpoint_quarantine_total 372
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 326
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 2978
telemt_desync_full_logged_total 1710
telemt_desync_suppressed_total 1268
telemt_desync_frames_bucket_total{bucket="1_2"} 630
telemt_desync_frames_bucket_total{bucket="3_10"} 1146
telemt_desync_frames_bucket_total{bucket="gt_10"} 1202
telemt_pool_swap_total 43
telemt_pool_force_close_total 1149
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 16713
telemt_me_writer_removed_unexpected_total 486
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1389
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15821
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1127
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15564
telemt_me_writer_teardown_success_total{mode="normal"} 17210
telemt_me_writer_teardown_noop_total 16713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33923
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.065661
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33923
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 430
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 700308
telemt_user_connections_current{user="hello"} 750
telemt_user_octets_from_client{user="hello"} 11225054756 (10.45 GB)
telemt_user_octets_to_client{user="hello"} 253554642492 (236.14 GB)
telemt_user_unique_ips_current{user="hello"} 501
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 115042.1 (31h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8031898
telemt_connections_bad_total 683601
telemt_connections_current 2481
telemt_connections_me_current 2481
telemt_handshake_timeouts_total 263664
telemt_upstream_connect_attempt_total 42931
telemt_upstream_connect_success_total 42853
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 42861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23279
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1634
telemt_me_reconnect_success_total 850
telemt_me_reader_eof_total 859
telemt_me_idle_close_by_peer_total 859
telemt_me_route_drop_no_conn_total 4585219
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6470494
telemt_me_endpoint_quarantine_total 742
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 863
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
telemt_me_writers_active_current 44
telemt_desync_total 27144
telemt_desync_full_logged_total 9023
telemt_desync_suppressed_total 18121
telemt_desync_frames_bucket_total{bucket="1_2"} 5872
telemt_desync_frames_bucket_total{bucket="3_10"} 10613
telemt_desync_frames_bucket_total{bucket="gt_10"} 10659
telemt_pool_swap_total 124
telemt_pool_force_close_total 4074
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 618
telemt_me_draining_writers_reap_progress_total 39186
telemt_me_writer_removed_unexpected_total 827
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3247
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36301
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3834
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 240
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35112
telemt_me_writer_teardown_success_total{mode="normal"} 39548
telemt_me_writer_teardown_noop_total 39230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78778
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 164.466764
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78778
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 618
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 758
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6462217
telemt_user_connections_current{user="hello"} 2481
telemt_user_octets_from_client{user="hello"} 109809380024 (102.27 GB)
telemt_user_octets_to_client{user="hello"} 2175182573040 (1.98 TB)
telemt_user_unique_ips_current{user="hello"} 1111
telemt_user_unique_ips_recent_window{user="hello"} 305
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 115043.3 (31h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6631511
telemt_connections_bad_total 596022
telemt_connections_current 2480
telemt_connections_me_current 2480
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 220056
telemt_upstream_connect_attempt_total 46859
telemt_upstream_connect_success_total 46462
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 46662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22876
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1976
telemt_me_reconnect_success_total 907
telemt_me_reader_eof_total 881
telemt_me_idle_close_by_peer_total 881
telemt_me_route_drop_no_conn_total 2297270
telemt_me_route_drop_channel_closed_total 284
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4950729
telemt_me_endpoint_quarantine_total 726
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 888
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
telemt_me_writers_active_current 45
telemt_desync_total 23086
telemt_desync_full_logged_total 7893
telemt_desync_suppressed_total 15193
telemt_desync_frames_bucket_total{bucket="1_2"} 5544
telemt_desync_frames_bucket_total{bucket="3_10"} 8969
telemt_desync_frames_bucket_total{bucket="gt_10"} 8573
telemt_pool_swap_total 125
telemt_pool_force_close_total 3706
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 374
telemt_me_draining_writers_reap_progress_total 37625
telemt_me_writer_removed_unexpected_total 863
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3101
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35327
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3489
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 217
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33919
telemt_me_writer_teardown_success_total{mode="normal"} 38428
telemt_me_writer_teardown_noop_total 37631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76059
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.817612
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76059
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 374
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 792
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 4872386
telemt_user_connections_current{user="hello"} 2480
telemt_user_octets_from_client{user="hello"} 143639697117 (133.77 GB)
telemt_user_octets_to_client{user="hello"} 2323688030079 (2.11 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1075
telemt_user_unique_ips_recent_window{user="hello"} 303
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 115008.1 (31h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6489676
telemt_connections_bad_total 554024
telemt_connections_current 2019
telemt_connections_me_current 2019
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 214507
telemt_upstream_connect_attempt_total 53317
telemt_upstream_connect_success_total 52817
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 52959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24463
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 2337
telemt_me_reconnect_success_total 1026
telemt_me_reader_eof_total 968
telemt_me_idle_close_by_peer_total 968
telemt_me_route_drop_no_conn_total 2253950
telemt_me_route_drop_channel_closed_total 131
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4823250
telemt_me_endpoint_quarantine_total 815
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 855
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
telemt_me_writers_active_current 42
telemt_desync_total 22979
telemt_desync_full_logged_total 7774
telemt_desync_suppressed_total 15205
telemt_desync_frames_bucket_total{bucket="1_2"} 5620
telemt_desync_frames_bucket_total{bucket="3_10"} 8812
telemt_desync_frames_bucket_total{bucket="gt_10"} 8547
telemt_pool_swap_total 123
telemt_pool_force_close_total 3579
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 406
telemt_me_draining_writers_reap_progress_total 38777
telemt_me_writer_removed_unexpected_total 955
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3294
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36456
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3345
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 234
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35198
telemt_me_writer_teardown_success_total{mode="normal"} 39750
telemt_me_writer_teardown_noop_total 38789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78539
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 32.315361
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78539
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 406
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 899
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 4818108
telemt_user_connections_current{user="hello"} 2019
telemt_user_octets_from_client{user="hello"} 135849969471 (126.52 GB)
telemt_user_octets_to_client{user="hello"} 2204973911763 (2.01 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 909
telemt_user_unique_ips_recent_window{user="hello"} 273
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 115046.7 (31h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20827766
telemt_connections_bad_total 1736365
telemt_connections_current 3253
telemt_connections_me_current 3253
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 630792
telemt_upstream_connect_attempt_total 203687
telemt_upstream_connect_success_total 185387
telemt_upstream_connect_fail_total 16472
telemt_upstream_connect_attempts_per_request{bucket="1"} 201859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44709
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8951
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16472
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65173
telemt_me_reconnect_success_total 2424
telemt_me_reader_eof_total 1510
telemt_me_idle_close_by_peer_total 1509
telemt_me_route_drop_no_conn_total 39630231
telemt_me_route_drop_channel_closed_total 128
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16757748
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 891
telemt_me_single_endpoint_outage_enter_total 144
telemt_me_single_endpoint_outage_exit_total 144
telemt_me_single_endpoint_outage_reconnect_attempt_total 297
telemt_me_single_endpoint_outage_reconnect_success_total 76
telemt_me_single_endpoint_quarantine_bypass_total 297
telemt_me_single_endpoint_shadow_rotate_total 902
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
telemt_me_writers_active_current 43
telemt_desync_total 32531
telemt_desync_full_logged_total 9786
telemt_desync_suppressed_total 22745
telemt_desync_frames_bucket_total{bucket="1_2"} 7065
telemt_desync_frames_bucket_total{bucket="3_10"} 14427
telemt_desync_frames_bucket_total{bucket="gt_10"} 11039
telemt_pool_swap_total 119
telemt_pool_force_close_total 3836
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 835
telemt_me_draining_writers_reap_progress_total 36079
telemt_me_writer_removed_unexpected_total 2249
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4848
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33225
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3302
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 534
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32243
telemt_me_writer_teardown_success_total{mode="normal"} 38073
telemt_me_writer_teardown_noop_total 36106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74179
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 217.269226
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74179
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 835
telemt_me_refill_failed_total 3809
telemt_me_writer_restored_same_endpoint_total 1647
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 581
telemt_user_connections_total{user="hello"} 16892444
telemt_user_connections_current{user="hello"} 3253
telemt_user_octets_from_client{user="hello"} 241330906628 (224.76 GB)
telemt_user_octets_to_client{user="hello"} 1284596817591 (1.17 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1389
telemt_user_unique_ips_recent_window{user="hello"} 407
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 115013.8 (31h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6264938
telemt_connections_bad_total 604473
telemt_connections_current 2342
telemt_connections_me_current 2342
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 132022
telemt_upstream_connect_attempt_total 61749
telemt_upstream_connect_success_total 61051
telemt_upstream_connect_fail_total 595
telemt_upstream_connect_attempts_per_request{bucket="1"} 61646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25369
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 595
telemt_me_reconnect_attempts_total 69836
telemt_me_reconnect_success_total 1841
telemt_me_reader_eof_total 1624
telemt_me_idle_close_by_peer_total 1623
telemt_me_route_drop_no_conn_total 2429237
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4860754
telemt_me_endpoint_quarantine_total 779
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 874
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
telemt_me_writers_active_current 44
telemt_desync_total 24275
telemt_desync_full_logged_total 8508
telemt_desync_suppressed_total 15767
telemt_desync_frames_bucket_total{bucket="1_2"} 4762
telemt_desync_frames_bucket_total{bucket="3_10"} 9390
telemt_desync_frames_bucket_total{bucket="gt_10"} 10123
telemt_pool_swap_total 119
telemt_pool_force_close_total 3401
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 407
telemt_me_draining_writers_reap_progress_total 40668
telemt_me_writer_removed_unexpected_total 1660
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4121
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38239
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3000
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37267
telemt_me_writer_teardown_success_total{mode="normal"} 42360
telemt_me_writer_teardown_noop_total 40669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83029
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.560620
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83029
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 407
telemt_me_refill_failed_total 4213
telemt_me_writer_restored_same_endpoint_total 1545
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 4853135
telemt_user_connections_current{user="hello"} 2342
telemt_user_octets_from_client{user="hello"} 127230769136 (118.49 GB)
telemt_user_octets_to_client{user="hello"} 2002340908610 (1.82 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1057
telemt_user_unique_ips_recent_window{user="hello"} 280
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 51849.7 (14h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4216374
telemt_connections_bad_total 178742
telemt_connections_current 1972
telemt_connections_me_current 1972
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1683411
telemt_upstream_connect_attempt_total 30628
telemt_upstream_connect_success_total 30427
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 30621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_reconnect_attempts_total 45976
telemt_me_reconnect_success_total 1013
telemt_me_reader_eof_total 700
telemt_me_idle_close_by_peer_total 700
telemt_me_route_drop_no_conn_total 1055306
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2069544
telemt_me_endpoint_quarantine_total 379
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 403
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 11084
telemt_desync_full_logged_total 3836
telemt_desync_suppressed_total 7248
telemt_desync_frames_bucket_total{bucket="1_2"} 2075
telemt_desync_frames_bucket_total{bucket="3_10"} 4247
telemt_desync_frames_bucket_total{bucket="gt_10"} 4762
telemt_pool_swap_total 56
telemt_pool_force_close_total 1647
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 149
telemt_me_draining_writers_reap_progress_total 19388
telemt_me_writer_removed_unexpected_total 772
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1681
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18507
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1440
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 207
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17741
telemt_me_writer_teardown_success_total{mode="normal"} 20188
telemt_me_writer_teardown_noop_total 19390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39578
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.518964
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39578
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 149
telemt_me_refill_failed_total 2612
telemt_me_writer_restored_same_endpoint_total 906
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2072941
telemt_user_connections_current{user="hello"} 1972
telemt_user_octets_from_client{user="hello"} 56541474824 (52.66 GB)
telemt_user_octets_to_client{user="hello"} 896523971618 (834.95 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 980
telemt_user_unique_ips_recent_window{user="hello"} 271
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 32820.8 (9h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231485
telemt_connections_bad_total 1857
telemt_connections_current 417
telemt_connections_me_current 417
telemt_handshake_timeouts_total 6018
telemt_upstream_connect_attempt_total 15921
telemt_upstream_connect_success_total 15883
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 15919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_reconnect_attempts_total 384
telemt_me_reconnect_success_total 206
telemt_me_reader_eof_total 213
telemt_me_idle_close_by_peer_total 213
telemt_me_route_drop_no_conn_total 64590
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205471
telemt_me_endpoint_quarantine_total 320
telemt_me_single_endpoint_shadow_rotate_total 287
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1174
telemt_desync_full_logged_total 314
telemt_desync_suppressed_total 860
telemt_desync_frames_bucket_total{bucket="1_2"} 418
telemt_desync_frames_bucket_total{bucket="3_10"} 450
telemt_desync_frames_bucket_total{bucket="gt_10"} 306
telemt_pool_swap_total 36
telemt_pool_force_close_total 803
telemt_me_writer_close_signal_drop_total 29
telemt_me_draining_writers_reap_progress_total 14402
telemt_me_writer_removed_unexpected_total 204
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 913
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13702
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 801
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13599
telemt_me_writer_teardown_success_total{mode="normal"} 14615
telemt_me_writer_teardown_noop_total 14402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29017
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.173261
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29017
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 29
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 186
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 205116
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 3510376556 (3.27 GB)
telemt_user_octets_to_client{user="hello"} 125713725612 (117.08 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 115018.4 (31h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7594072
telemt_connections_bad_total 762918
telemt_connections_current 2408
telemt_connections_me_current 2408
telemt_handshake_timeouts_total 216251
telemt_upstream_connect_attempt_total 45362
telemt_upstream_connect_success_total 45198
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 45325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22771
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_reconnect_attempts_total 1654
telemt_me_reconnect_success_total 889
telemt_me_reader_eof_total 878
telemt_me_idle_close_by_peer_total 878
telemt_me_route_drop_no_conn_total 2166407
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5655209
telemt_me_endpoint_quarantine_total 823
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 884
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 22123
telemt_desync_full_logged_total 7277
telemt_desync_suppressed_total 14846
telemt_desync_frames_bucket_total{bucket="1_2"} 5544
telemt_desync_frames_bucket_total{bucket="3_10"} 8039
telemt_desync_frames_bucket_total{bucket="gt_10"} 8540
telemt_pool_swap_total 127
telemt_pool_force_close_total 3390
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 399
telemt_me_draining_writers_reap_progress_total 40960
telemt_me_writer_removed_unexpected_total 844
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3186
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38642
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3302
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37570
telemt_me_writer_teardown_success_total{mode="normal"} 41828
telemt_me_writer_teardown_noop_total 40962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82790
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.743849
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82790
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 399
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 794
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 5629980
telemt_user_connections_current{user="hello"} 2408
telemt_user_octets_from_client{user="hello"} 112078784180 (104.38 GB)
telemt_user_octets_to_client{user="hello"} 2624396702596 (2.39 TB)
telemt_user_unique_ips_current{user="hello"} 1057
telemt_user_unique_ips_recent_window{user="hello"} 289
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 115014.7 (31h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6582670
telemt_connections_bad_total 645900
telemt_connections_current 2351
telemt_connections_me_current 2351
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 177972
telemt_upstream_connect_attempt_total 61191
telemt_upstream_connect_success_total 60728
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 61131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24405
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_reconnect_attempts_total 5744
telemt_me_reconnect_success_total 1249
telemt_me_reader_eof_total 1121
telemt_me_idle_close_by_peer_total 1121
telemt_me_seq_mismatch_total 52
telemt_me_route_drop_no_conn_total 2220514
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5024398
telemt_me_endpoint_quarantine_total 906
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 882
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
telemt_me_writers_active_current 49
telemt_desync_total 20821
telemt_desync_full_logged_total 6952
telemt_desync_suppressed_total 13869
telemt_desync_frames_bucket_total{bucket="1_2"} 5296
telemt_desync_frames_bucket_total{bucket="3_10"} 7623
telemt_desync_frames_bucket_total{bucket="gt_10"} 7902
telemt_pool_swap_total 125
telemt_pool_force_close_total 3338
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 395
telemt_me_draining_writers_reap_progress_total 39518
telemt_me_writer_removed_unexpected_total 1132
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3738
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36968
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3115
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36180
telemt_me_writer_teardown_success_total{mode="normal"} 40706
telemt_me_writer_teardown_noop_total 39522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80228
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.403382
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80228
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 395
telemt_me_refill_failed_total 259
telemt_me_writer_restored_same_endpoint_total 975
telemt_me_writer_restored_fallback_total 70
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 5027199
telemt_user_connections_current{user="hello"} 2351
telemt_user_octets_from_client{user="hello"} 94837370981 (88.32 GB)
telemt_user_octets_to_client{user="hello"} 2156975989616 (1.96 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1022
telemt_user_unique_ips_recent_window{user="hello"} 297
```
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

# Server Metrics 2026-03-22 16:19:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 69179.3 (19h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2442861
telemt_connections_bad_total 130075
telemt_connections_current 1881
telemt_connections_me_current 1881
telemt_handshake_timeouts_total 87570
telemt_upstream_connect_attempt_total 25565
telemt_upstream_connect_success_total 25564
telemt_upstream_connect_attempts_per_request{bucket="1"} 25564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16620
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 55
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1032
telemt_me_reconnect_success_total 438
telemt_me_reader_eof_total 440
telemt_me_idle_close_by_peer_total 440
telemt_me_route_drop_no_conn_total 1973940
telemt_me_route_drop_channel_closed_total 804
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2079844
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 469
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 539
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
telemt_desync_total 10080
telemt_desync_full_logged_total 3144
telemt_desync_suppressed_total 6936
telemt_desync_frames_bucket_total{bucket="1_2"} 2687
telemt_desync_frames_bucket_total{bucket="3_10"} 3782
telemt_desync_frames_bucket_total{bucket="gt_10"} 3611
telemt_pool_swap_total 76
telemt_pool_force_close_total 2349
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 452
telemt_me_draining_writers_reap_progress_total 23354
telemt_me_writer_removed_unexpected_total 427
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1699
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21868
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2302
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21005
telemt_me_writer_teardown_success_total{mode="normal"} 23567
telemt_me_writer_teardown_noop_total 23360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46927
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 215.558728
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46927
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 452
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 388
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2076437
telemt_user_connections_current{user="hello"} 1881
telemt_user_octets_from_client{user="hello"} 31541734960 (29.38 GB)
telemt_user_octets_to_client{user="hello"} 554491329592 (516.41 GB)
telemt_user_unique_ips_current{user="hello"} 694
telemt_user_unique_ips_recent_window{user="hello"} 388
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 82546.4 (22h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3590696
telemt_connections_bad_total 326904
telemt_connections_current 1184
telemt_connections_me_current 1184
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 88751
telemt_upstream_connect_attempt_total 51946
telemt_upstream_connect_success_total 51315
telemt_upstream_connect_fail_total 559
telemt_upstream_connect_attempts_per_request{bucket="1"} 51874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 559
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6049
telemt_me_reconnect_success_total 2187
telemt_me_reader_eof_total 2130
telemt_me_idle_close_by_peer_total 2130
telemt_me_route_drop_no_conn_total 3529179
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2845106
telemt_me_endpoint_quarantine_total 663
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 636
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_desync_total 11083
telemt_desync_full_logged_total 6178
telemt_desync_suppressed_total 4905
telemt_desync_frames_bucket_total{bucket="1_2"} 2585
telemt_desync_frames_bucket_total{bucket="3_10"} 4353
telemt_desync_frames_bucket_total{bucket="gt_10"} 4145
telemt_pool_swap_total 77
telemt_pool_force_close_total 2318
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 196
telemt_me_draining_writers_reap_progress_total 32908
telemt_me_writer_removed_unexpected_total 2085
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3961
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31038
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1962
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 356
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30590
telemt_me_writer_teardown_success_total{mode="normal"} 34999
telemt_me_writer_teardown_noop_total 32908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67907
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.878721
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67907
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 196
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 1897
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 2856388
telemt_user_connections_current{user="hello"} 1184
telemt_user_octets_from_client{user="hello"} 35501633727 (33.06 GB)
telemt_user_octets_to_client{user="hello"} 633718775722 (590.20 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 648
telemt_user_unique_ips_recent_window{user="hello"} 360
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 157405.4 (43h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15299688
telemt_connections_bad_total 1427778
telemt_connections_current 2516
telemt_connections_me_current 2516
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 371985
telemt_upstream_connect_attempt_total 71129
telemt_upstream_connect_success_total 71034
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 71051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33606
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1673
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2618
telemt_me_reconnect_success_total 1348
telemt_me_reader_eof_total 1288
telemt_me_idle_close_by_peer_total 1286
telemt_me_route_drop_no_conn_total 13798629
telemt_me_route_drop_channel_closed_total 138
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12224499
telemt_me_endpoint_quarantine_total 990
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1172
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
telemt_desync_total 49762
telemt_desync_full_logged_total 15616
telemt_desync_suppressed_total 34146
telemt_desync_frames_bucket_total{bucket="1_2"} 11158
telemt_desync_frames_bucket_total{bucket="3_10"} 19450
telemt_desync_frames_bucket_total{bucket="gt_10"} 19154
telemt_pool_swap_total 169
telemt_pool_force_close_total 5765
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 937
telemt_me_draining_writers_reap_progress_total 51761
telemt_me_writer_removed_unexpected_total 1242
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4500
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47795
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5305
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45996
telemt_me_writer_teardown_success_total{mode="normal"} 52295
telemt_me_writer_teardown_noop_total 51811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104106
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 295.985204
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104106
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 937
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 1158
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 12225695
telemt_user_connections_current{user="hello"} 2516
telemt_user_octets_from_client{user="hello"} 172952563801 (161.07 GB)
telemt_user_octets_to_client{user="hello"} 3157863023819 (2.87 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 1026
telemt_user_unique_ips_recent_window{user="hello"} 354
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 157406.7 (43h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11037020
telemt_connections_bad_total 1070990
telemt_connections_current 1412
telemt_connections_me_current 1412
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 327231
telemt_upstream_connect_attempt_total 83313
telemt_upstream_connect_success_total 82158
telemt_upstream_connect_fail_total 831
telemt_upstream_connect_attempts_per_request{bucket="1"} 82989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33479
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3693
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 831
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3931
telemt_me_reconnect_success_total 1595
telemt_me_reader_eof_total 1466
telemt_me_idle_close_by_peer_total 1466
telemt_me_route_drop_no_conn_total 4355647
telemt_me_route_drop_channel_closed_total 478
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8231067
telemt_me_endpoint_quarantine_total 988
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1189
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
telemt_me_writers_active_current 43
telemt_desync_total 36548
telemt_desync_full_logged_total 12285
telemt_desync_suppressed_total 24263
telemt_desync_frames_bucket_total{bucket="1_2"} 8958
telemt_desync_frames_bucket_total{bucket="3_10"} 14092
telemt_desync_frames_bucket_total{bucket="gt_10"} 13498
telemt_pool_swap_total 167
telemt_pool_force_close_total 5185
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 666
telemt_me_draining_writers_reap_progress_total 50030
telemt_me_writer_removed_unexpected_total 1495
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4611
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46774
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4709
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 476
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44845
telemt_me_writer_teardown_success_total{mode="normal"} 51385
telemt_me_writer_teardown_noop_total 50048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101433
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.262733
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101433
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 666
telemt_me_refill_failed_total 126
telemt_me_writer_restored_same_endpoint_total 1357
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8169779
telemt_user_connections_current{user="hello"} 1412
telemt_user_octets_from_client{user="hello"} 204303313753 (190.27 GB)
telemt_user_octets_to_client{user="hello"} 3684971469310 (3.35 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 557
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 157371.8 (43h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10436285
telemt_connections_bad_total 897304
telemt_connections_current 1246
telemt_connections_me_current 1246
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 333068
telemt_upstream_connect_attempt_total 68488
telemt_upstream_connect_success_total 67549
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 67731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31986
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4653
telemt_me_reconnect_success_total 1877
telemt_me_reader_eof_total 1634
telemt_me_idle_close_by_peer_total 1633
telemt_me_route_drop_no_conn_total 5127474
telemt_me_route_drop_channel_closed_total 357
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7881932
telemt_me_endpoint_quarantine_total 1074
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 1156
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 36101
telemt_desync_full_logged_total 11962
telemt_desync_suppressed_total 24139
telemt_desync_frames_bucket_total{bucket="1_2"} 9138
telemt_desync_frames_bucket_total{bucket="3_10"} 13796
telemt_desync_frames_bucket_total{bucket="gt_10"} 13167
telemt_pool_swap_total 164
telemt_pool_force_close_total 5133
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 685
telemt_me_draining_writers_reap_progress_total 50414
telemt_me_writer_removed_unexpected_total 1774
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5043
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47057
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4593
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 540
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45281
telemt_me_writer_teardown_success_total{mode="normal"} 52100
telemt_me_writer_teardown_noop_total 50485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102585
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3170.534462
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102585
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 685
telemt_me_refill_failed_total 147
telemt_me_writer_restored_same_endpoint_total 1627
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 7874907
telemt_user_connections_current{user="hello"} 1246
telemt_user_octets_from_client{user="hello"} 181540774109 (169.07 GB)
telemt_user_octets_to_client{user="hello"} 3273533654921 (2.98 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 481
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 27650.4 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10124255
telemt_connections_bad_total 619067
telemt_connections_current 2174
telemt_connections_me_current 2174
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 185488
telemt_upstream_connect_attempt_total 35591
telemt_upstream_connect_success_total 33803
telemt_upstream_connect_fail_total 1253
telemt_upstream_connect_attempts_per_request{bucket="1"} 35056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9191
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5297
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1253
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5881
telemt_me_reconnect_success_total 703
telemt_me_reader_eof_total 446
telemt_me_idle_close_by_peer_total 446
telemt_me_route_drop_no_conn_total 24912624
telemt_me_route_drop_channel_closed_total 46
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8428800
telemt_me_endpoint_quarantine_total 171
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 216
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
telemt_me_writers_active_current 44
telemt_desync_total 13162
telemt_desync_full_logged_total 3392
telemt_desync_suppressed_total 9770
telemt_desync_frames_bucket_total{bucket="1_2"} 2332
telemt_desync_frames_bucket_total{bucket="3_10"} 5356
telemt_desync_frames_bucket_total{bucket="gt_10"} 5474
telemt_pool_swap_total 26
telemt_pool_force_close_total 1039
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 362
telemt_me_draining_writers_reap_progress_total 7532
telemt_me_writer_removed_unexpected_total 607
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1256
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6847
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 759
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 280
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6493
telemt_me_writer_teardown_success_total{mode="normal"} 8103
telemt_me_writer_teardown_noop_total 7537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 15269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 15520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 15613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 15640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 15640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 15640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 15640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 15640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 15640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 15640
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 35.610233
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 15640
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 362
telemt_me_refill_failed_total 293
telemt_me_writer_restored_same_endpoint_total 479
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8446934
telemt_user_connections_current{user="hello"} 2174
telemt_user_octets_from_client{user="hello"} 61139330414 (56.94 GB)
telemt_user_octets_to_client{user="hello"} 296830281800 (276.44 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 814
telemt_user_unique_ips_recent_window{user="hello"} 292
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 157377.1 (43h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10223261
telemt_connections_bad_total 855751
telemt_connections_current 1807
telemt_connections_me_current 1807
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 226742
telemt_upstream_connect_attempt_total 97279
telemt_upstream_connect_success_total 96289
telemt_upstream_connect_fail_total 843
telemt_upstream_connect_attempts_per_request{bucket="1"} 97132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35213
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1303
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 843
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71830
telemt_me_reconnect_success_total 2609
telemt_me_reader_eof_total 2314
telemt_me_idle_close_by_peer_total 2313
telemt_me_route_drop_no_conn_total 5055629
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8061861
telemt_me_endpoint_quarantine_total 1062
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1173
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
telemt_me_writers_active_current 43
telemt_desync_total 42005
telemt_desync_full_logged_total 14337
telemt_desync_suppressed_total 27668
telemt_desync_frames_bucket_total{bucket="1_2"} 8550
telemt_desync_frames_bucket_total{bucket="3_10"} 16240
telemt_desync_frames_bucket_total{bucket="gt_10"} 17215
telemt_pool_swap_total 160
telemt_pool_force_close_total 4763
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 601
telemt_me_draining_writers_reap_progress_total 53544
telemt_me_writer_removed_unexpected_total 2357
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5730
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50192
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4078
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 685
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48781
telemt_me_writer_teardown_success_total{mode="normal"} 55922
telemt_me_writer_teardown_noop_total 53545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109467
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.448705
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109467
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 601
telemt_me_refill_failed_total 4268
telemt_me_writer_restored_same_endpoint_total 2191
telemt_me_writer_restored_fallback_total 44
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7360
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 8065837
telemt_user_connections_current{user="hello"} 1807
telemt_user_octets_from_client{user="hello"} 182766028777 (170.21 GB)
telemt_user_octets_to_client{user="hello"} 3038029411304 (2.76 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 730
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 94213.2 (26h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10636074
telemt_connections_bad_total 397409
telemt_connections_current 1399
telemt_connections_me_current 1399
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4471978
telemt_upstream_connect_attempt_total 45366
telemt_upstream_connect_success_total 45036
telemt_upstream_connect_fail_total 321
telemt_upstream_connect_attempts_per_request{bucket="1"} 45357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 321
telemt_me_reconnect_attempts_total 48063
telemt_me_reconnect_success_total 1510
telemt_me_reader_eof_total 1174
telemt_me_idle_close_by_peer_total 1173
telemt_me_route_drop_no_conn_total 3912184
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5096800
telemt_me_endpoint_quarantine_total 614
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 708
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 27935
telemt_desync_full_logged_total 9436
telemt_desync_suppressed_total 18499
telemt_desync_frames_bucket_total{bucket="1_2"} 5625
telemt_desync_frames_bucket_total{bucket="3_10"} 11013
telemt_desync_frames_bucket_total{bucket="gt_10"} 11297
telemt_pool_swap_total 99
telemt_pool_force_close_total 3055
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 311
telemt_me_draining_writers_reap_progress_total 32391
telemt_me_writer_removed_unexpected_total 1237
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2911
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30747
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2636
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29336
telemt_me_writer_teardown_success_total{mode="normal"} 33658
telemt_me_writer_teardown_noop_total 32398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66056
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.878590
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66056
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 311
telemt_me_refill_failed_total 2706
telemt_me_writer_restored_same_endpoint_total 1343
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5090346
telemt_user_connections_current{user="hello"} 1399
telemt_user_octets_from_client{user="hello"} 109557650780 (102.03 GB)
telemt_user_octets_to_client{user="hello"} 1922533457322 (1.75 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 562
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 75184.5 (20h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1006689
telemt_connections_bad_total 14795
telemt_connections_current 1106
telemt_connections_me_current 1106
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 19290
telemt_upstream_connect_attempt_total 37015
telemt_upstream_connect_success_total 36920
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 36998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19655
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 523
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_reconnect_attempts_total 1718
telemt_me_reconnect_success_total 711
telemt_me_reader_eof_total 685
telemt_me_idle_close_by_peer_total 685
telemt_me_route_drop_no_conn_total 347716
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 893803
telemt_me_endpoint_quarantine_total 647
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 624
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
telemt_me_writers_active_current 45
telemt_desync_total 4996
telemt_desync_full_logged_total 1534
telemt_desync_suppressed_total 3462
telemt_desync_frames_bucket_total{bucket="1_2"} 1180
telemt_desync_frames_bucket_total{bucket="3_10"} 1994
telemt_desync_frames_bucket_total{bucket="gt_10"} 1822
telemt_pool_swap_total 80
telemt_pool_force_close_total 2023
telemt_me_writer_close_signal_drop_total 119
telemt_me_draining_writers_reap_progress_total 30636
telemt_me_writer_removed_unexpected_total 662
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2375
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28948
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1943
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 80
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28613
telemt_me_writer_teardown_success_total{mode="normal"} 31323
telemt_me_writer_teardown_noop_total 30639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61962
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.733282
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61962
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 119
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 604
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 892982
telemt_user_connections_current{user="hello"} 1106
telemt_user_octets_from_client{user="hello"} 16058259513 (14.96 GB)
telemt_user_octets_to_client{user="hello"} 396507929003 (369.28 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 426
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 157381.9 (43h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12495222
telemt_connections_bad_total 1447731
telemt_connections_current 1882
telemt_connections_me_current 1882
telemt_handshake_timeouts_total 344623
telemt_upstream_connect_attempt_total 59091
telemt_upstream_connect_success_total 58859
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 59038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29735
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_reconnect_attempts_total 2283
telemt_me_reconnect_success_total 1225
telemt_me_reader_eof_total 1190
telemt_me_idle_close_by_peer_total 1190
telemt_me_route_drop_no_conn_total 4169148
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9448300
telemt_me_endpoint_quarantine_total 1064
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1175
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
telemt_me_writers_active_current 44
telemt_desync_total 38756
telemt_desync_full_logged_total 12654
telemt_desync_suppressed_total 26102
telemt_desync_frames_bucket_total{bucket="1_2"} 9212
telemt_desync_frames_bucket_total{bucket="3_10"} 14359
telemt_desync_frames_bucket_total{bucket="gt_10"} 15185
telemt_pool_swap_total 174
telemt_pool_force_close_total 4804
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 618
telemt_me_draining_writers_reap_progress_total 53221
telemt_me_writer_removed_unexpected_total 1143
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4353
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50044
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4631
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48417
telemt_me_writer_teardown_success_total{mode="normal"} 54397
telemt_me_writer_teardown_noop_total 53223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107620
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.071896
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107620
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 618
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 1074
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 9417556
telemt_user_connections_current{user="hello"} 1882
telemt_user_octets_from_client{user="hello"} 184605023004 (171.93 GB)
telemt_user_octets_to_client{user="hello"} 4158698638336 (3.78 TB)
telemt_user_unique_ips_current{user="hello"} 684
telemt_user_unique_ips_recent_window{user="hello"} 251
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 157378.2 (43h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10831952
telemt_connections_bad_total 1211237
telemt_connections_current 1596
telemt_connections_me_current 1596
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 279574
telemt_upstream_connect_attempt_total 84850
telemt_upstream_connect_success_total 84215
telemt_upstream_connect_fail_total 550
telemt_upstream_connect_attempts_per_request{bucket="1"} 84765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34961
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2028
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 550
telemt_me_reconnect_attempts_total 8881
telemt_me_reconnect_success_total 2045
telemt_me_reader_eof_total 1909
telemt_me_idle_close_by_peer_total 1909
telemt_me_seq_mismatch_total 74
telemt_me_route_drop_no_conn_total 5411710
telemt_me_route_drop_channel_closed_total 347
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8373367
telemt_me_endpoint_quarantine_total 1189
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1176
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_desync_total 38220
telemt_desync_full_logged_total 12346
telemt_desync_suppressed_total 25874
telemt_desync_frames_bucket_total{bucket="1_2"} 9499
telemt_desync_frames_bucket_total{bucket="3_10"} 14248
telemt_desync_frames_bucket_total{bucket="gt_10"} 14473
telemt_pool_swap_total 166
telemt_pool_force_close_total 4650
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 605
telemt_me_draining_writers_reap_progress_total 52672
telemt_me_writer_removed_unexpected_total 1935
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5448
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49227
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48022
telemt_me_writer_teardown_success_total{mode="normal"} 54675
telemt_me_writer_teardown_noop_total 52677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107352
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.494641
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107352
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 605
telemt_me_refill_failed_total 351
telemt_me_writer_restored_same_endpoint_total 1663
telemt_me_writer_restored_fallback_total 99
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 8379356
telemt_user_connections_current{user="hello"} 1596
telemt_user_octets_from_client{user="hello"} 147439853369 (137.31 GB)
telemt_user_octets_to_client{user="hello"} 3200345030167 (2.91 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 618
telemt_user_unique_ips_recent_window{user="hello"} 205
```
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

# Server Metrics 2026-03-22 16:14:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 68873.8 (19h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2430158
telemt_connections_bad_total 129400
telemt_connections_current 1749
telemt_connections_me_current 1749
telemt_handshake_timeouts_total 87340
telemt_upstream_connect_attempt_total 25481
telemt_upstream_connect_success_total 25480
telemt_upstream_connect_attempts_per_request{bucket="1"} 25480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16554
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 55
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1032
telemt_me_reconnect_success_total 438
telemt_me_reader_eof_total 440
telemt_me_idle_close_by_peer_total 440
telemt_me_route_drop_no_conn_total 1959432
telemt_me_route_drop_channel_closed_total 799
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2068604
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
telemt_desync_total 10035
telemt_desync_full_logged_total 3123
telemt_desync_suppressed_total 6912
telemt_desync_frames_bucket_total{bucket="1_2"} 2672
telemt_desync_frames_bucket_total{bucket="3_10"} 3768
telemt_desync_frames_bucket_total{bucket="gt_10"} 3595
telemt_pool_swap_total 76
telemt_pool_force_close_total 2349
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 452
telemt_me_draining_writers_reap_progress_total 23270
telemt_me_writer_removed_unexpected_total 427
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1697
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21786
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2302
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20921
telemt_me_writer_teardown_success_total{mode="normal"} 23483
telemt_me_writer_teardown_noop_total 23276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46759
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 214.364063
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46759
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 452
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 388
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2065202
telemt_user_connections_current{user="hello"} 1749
telemt_user_octets_from_client{user="hello"} 31444990180 (29.29 GB)
telemt_user_octets_to_client{user="hello"} 551501908948 (513.63 GB)
telemt_user_unique_ips_current{user="hello"} 653
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 82239.9 (22h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3584316
telemt_connections_bad_total 326679
telemt_connections_current 711
telemt_connections_me_current 711
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 88205
telemt_upstream_connect_attempt_total 51853
telemt_upstream_connect_success_total 51222
telemt_upstream_connect_fail_total 559
telemt_upstream_connect_attempts_per_request{bucket="1"} 51781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 559
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6049
telemt_me_reconnect_success_total 2187
telemt_me_reader_eof_total 2130
telemt_me_idle_close_by_peer_total 2130
telemt_me_route_drop_no_conn_total 3527496
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2839649
telemt_me_endpoint_quarantine_total 663
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 633
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
telemt_desync_total 11059
telemt_desync_full_logged_total 6160
telemt_desync_suppressed_total 4899
telemt_desync_frames_bucket_total{bucket="1_2"} 2579
telemt_desync_frames_bucket_total{bucket="3_10"} 4346
telemt_desync_frames_bucket_total{bucket="gt_10"} 4134
telemt_pool_swap_total 77
telemt_pool_force_close_total 2318
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 196
telemt_me_draining_writers_reap_progress_total 32818
telemt_me_writer_removed_unexpected_total 2085
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3958
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30951
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1962
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 356
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30500
telemt_me_writer_teardown_success_total{mode="normal"} 34909
telemt_me_writer_teardown_noop_total 32818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67727
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.877395
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67727
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 196
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 1897
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 2850930
telemt_user_connections_current{user="hello"} 711
telemt_user_octets_from_client{user="hello"} 35354043155 (32.93 GB)
telemt_user_octets_to_client{user="hello"} 631510534470 (588.14 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 465
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 157099.8 (43h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15280987
telemt_connections_bad_total 1421490
telemt_connections_current 2232
telemt_connections_me_current 2232
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 371764
telemt_upstream_connect_attempt_total 71034
telemt_upstream_connect_success_total 70938
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 70955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33547
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1673
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2618
telemt_me_reconnect_success_total 1348
telemt_me_reader_eof_total 1288
telemt_me_idle_close_by_peer_total 1286
telemt_me_route_drop_no_conn_total 13794201
telemt_me_route_drop_channel_closed_total 138
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12212899
telemt_me_endpoint_quarantine_total 990
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1171
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
telemt_desync_total 49696
telemt_desync_full_logged_total 15589
telemt_desync_suppressed_total 34107
telemt_desync_frames_bucket_total{bucket="1_2"} 11148
telemt_desync_frames_bucket_total{bucket="3_10"} 19423
telemt_desync_frames_bucket_total{bucket="gt_10"} 19125
telemt_pool_swap_total 169
telemt_pool_force_close_total 5765
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 937
telemt_me_draining_writers_reap_progress_total 51664
telemt_me_writer_removed_unexpected_total 1242
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4495
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47703
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5305
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45899
telemt_me_writer_teardown_success_total{mode="normal"} 52198
telemt_me_writer_teardown_noop_total 51714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103912
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 295.982565
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103912
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 937
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 1158
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 12214095
telemt_user_connections_current{user="hello"} 2232
telemt_user_octets_from_client{user="hello"} 172291350141 (160.46 GB)
telemt_user_octets_to_client{user="hello"} 3152640982255 (2.87 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 888
telemt_user_unique_ips_recent_window{user="hello"} 309
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 157101.2 (43h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11025057
telemt_connections_bad_total 1068855
telemt_connections_current 1434
telemt_connections_me_current 1434
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 326846
telemt_upstream_connect_attempt_total 83249
telemt_upstream_connect_success_total 82094
telemt_upstream_connect_fail_total 831
telemt_upstream_connect_attempts_per_request{bucket="1"} 82925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33438
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3693
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 831
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3931
telemt_me_reconnect_success_total 1595
telemt_me_reader_eof_total 1466
telemt_me_idle_close_by_peer_total 1466
telemt_me_route_drop_no_conn_total 4352967
telemt_me_route_drop_channel_closed_total 478
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8223345
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
telemt_desync_total 36516
telemt_desync_full_logged_total 12274
telemt_desync_suppressed_total 24242
telemt_desync_frames_bucket_total{bucket="1_2"} 8944
telemt_desync_frames_bucket_total{bucket="3_10"} 14079
telemt_desync_frames_bucket_total{bucket="gt_10"} 13493
telemt_pool_swap_total 167
telemt_pool_force_close_total 5185
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 666
telemt_me_draining_writers_reap_progress_total 49966
telemt_me_writer_removed_unexpected_total 1495
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4611
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46710
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4709
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 476
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44781
telemt_me_writer_teardown_success_total{mode="normal"} 51321
telemt_me_writer_teardown_noop_total 49984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101305
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.261774
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101305
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 666
telemt_me_refill_failed_total 126
telemt_me_writer_restored_same_endpoint_total 1357
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8162074
telemt_user_connections_current{user="hello"} 1434
telemt_user_octets_from_client{user="hello"} 204156297033 (190.14 GB)
telemt_user_octets_to_client{user="hello"} 3681615549386 (3.35 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 571
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 157065.3 (43h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10427606
telemt_connections_bad_total 896676
telemt_connections_current 1392
telemt_connections_me_current 1392
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 332765
telemt_upstream_connect_attempt_total 68401
telemt_upstream_connect_success_total 67466
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 67648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31931
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4650
telemt_me_reconnect_success_total 1875
telemt_me_reader_eof_total 1632
telemt_me_idle_close_by_peer_total 1631
telemt_me_route_drop_no_conn_total 5124265
telemt_me_route_drop_channel_closed_total 356
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7874932
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
telemt_me_writers_active_current 43
telemt_desync_total 36051
telemt_desync_full_logged_total 11944
telemt_desync_suppressed_total 24107
telemt_desync_frames_bucket_total{bucket="1_2"} 9131
telemt_desync_frames_bucket_total{bucket="3_10"} 13773
telemt_desync_frames_bucket_total{bucket="gt_10"} 13147
telemt_pool_swap_total 164
telemt_pool_force_close_total 5133
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 685
telemt_me_draining_writers_reap_progress_total 50358
telemt_me_writer_removed_unexpected_total 1772
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5039
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47003
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4593
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 540
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45225
telemt_me_writer_teardown_success_total{mode="normal"} 52042
telemt_me_writer_teardown_noop_total 50429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102471
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3170.533647
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102471
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 685
telemt_me_refill_failed_total 147
telemt_me_writer_restored_same_endpoint_total 1625
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 7867904
telemt_user_connections_current{user="hello"} 1392
telemt_user_octets_from_client{user="hello"} 181394000813 (168.94 GB)
telemt_user_octets_to_client{user="hello"} 3270356247513 (2.97 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 506
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 27345.6 (7h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10108515
telemt_connections_bad_total 618224
telemt_connections_current 2155
telemt_connections_me_current 2155
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 184011
telemt_upstream_connect_attempt_total 35495
telemt_upstream_connect_success_total 33710
telemt_upstream_connect_fail_total 1252
telemt_upstream_connect_attempts_per_request{bucket="1"} 34962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9140
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5296
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1252
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5878
telemt_me_reconnect_success_total 702
telemt_me_reader_eof_total 444
telemt_me_idle_close_by_peer_total 444
telemt_me_route_drop_no_conn_total 24905125
telemt_me_route_drop_channel_closed_total 45
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8416482
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
telemt_me_writers_active_current 45
telemt_desync_total 13056
telemt_desync_full_logged_total 3357
telemt_desync_suppressed_total 9699
telemt_desync_frames_bucket_total{bucket="1_2"} 2287
telemt_desync_frames_bucket_total{bucket="3_10"} 5312
telemt_desync_frames_bucket_total{bucket="gt_10"} 5457
telemt_pool_swap_total 26
telemt_pool_force_close_total 1039
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 362
telemt_me_draining_writers_reap_progress_total 7458
telemt_me_writer_removed_unexpected_total 605
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1254
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6773
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 759
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 280
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6419
telemt_me_writer_teardown_success_total{mode="normal"} 8027
telemt_me_writer_teardown_noop_total 7463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 15119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 15370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 15463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 15490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 15490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 15490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 15490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 15490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 15490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 15490
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 35.607801
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 15490
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 362
telemt_me_refill_failed_total 293
telemt_me_writer_restored_same_endpoint_total 478
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 8434618
telemt_user_connections_current{user="hello"} 2155
telemt_user_octets_from_client{user="hello"} 60213780810 (56.08 GB)
telemt_user_octets_to_client{user="hello"} 292829795592 (272.72 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 793
telemt_user_unique_ips_recent_window{user="hello"} 318
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 157071.9 (43h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10210788
telemt_connections_bad_total 853575
telemt_connections_current 1846
telemt_connections_me_current 1846
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 226244
telemt_upstream_connect_attempt_total 97191
telemt_upstream_connect_success_total 96201
telemt_upstream_connect_fail_total 843
telemt_upstream_connect_attempts_per_request{bucket="1"} 97044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35161
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1303
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 843
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71826
telemt_me_reconnect_success_total 2606
telemt_me_reader_eof_total 2310
telemt_me_idle_close_by_peer_total 2309
telemt_me_route_drop_no_conn_total 5052629
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8052879
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
telemt_desync_total 41958
telemt_desync_full_logged_total 14320
telemt_desync_suppressed_total 27638
telemt_desync_frames_bucket_total{bucket="1_2"} 8544
telemt_desync_frames_bucket_total{bucket="3_10"} 16224
telemt_desync_frames_bucket_total{bucket="gt_10"} 17190
telemt_pool_swap_total 160
telemt_pool_force_close_total 4763
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 601
telemt_me_draining_writers_reap_progress_total 53484
telemt_me_writer_removed_unexpected_total 2354
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5723
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50135
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4078
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 685
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48721
telemt_me_writer_teardown_success_total{mode="normal"} 55858
telemt_me_writer_teardown_noop_total 53485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109343
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.448254
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109343
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 601
telemt_me_refill_failed_total 4268
telemt_me_writer_restored_same_endpoint_total 2188
telemt_me_writer_restored_fallback_total 44
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7360
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 8056856
telemt_user_connections_current{user="hello"} 1846
telemt_user_octets_from_client{user="hello"} 182550625737 (170.01 GB)
telemt_user_octets_to_client{user="hello"} 3034484739028 (2.76 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 712
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 93908.0 (26h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10621972
telemt_connections_bad_total 395940
telemt_connections_current 1371
telemt_connections_me_current 1371
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4468816
telemt_upstream_connect_attempt_total 45261
telemt_upstream_connect_success_total 44931
telemt_upstream_connect_fail_total 321
telemt_upstream_connect_attempts_per_request{bucket="1"} 45252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19497
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 321
telemt_me_reconnect_attempts_total 48063
telemt_me_reconnect_success_total 1510
telemt_me_reader_eof_total 1174
telemt_me_idle_close_by_peer_total 1173
telemt_me_route_drop_no_conn_total 3909259
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5089563
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
telemt_desync_total 27877
telemt_desync_full_logged_total 9417
telemt_desync_suppressed_total 18460
telemt_desync_frames_bucket_total{bucket="1_2"} 5613
telemt_desync_frames_bucket_total{bucket="3_10"} 10992
telemt_desync_frames_bucket_total{bucket="gt_10"} 11272
telemt_pool_swap_total 99
telemt_pool_force_close_total 3055
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 311
telemt_me_draining_writers_reap_progress_total 32284
telemt_me_writer_removed_unexpected_total 1237
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2909
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30642
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2636
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29229
telemt_me_writer_teardown_success_total{mode="normal"} 33551
telemt_me_writer_teardown_noop_total 32291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65842
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.878153
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65842
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 311
telemt_me_refill_failed_total 2706
telemt_me_writer_restored_same_endpoint_total 1343
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5083116
telemt_user_connections_current{user="hello"} 1371
telemt_user_octets_from_client{user="hello"} 109446535596 (101.93 GB)
telemt_user_octets_to_client{user="hello"} 1919382683074 (1.75 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 523
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 74879.1 (20h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 998691
telemt_connections_bad_total 14594
telemt_connections_current 1127
telemt_connections_me_current 1127
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 19176
telemt_upstream_connect_attempt_total 36894
telemt_upstream_connect_success_total 36800
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 36878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19586
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 520
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_reconnect_attempts_total 1717
telemt_me_reconnect_success_total 710
telemt_me_reader_eof_total 684
telemt_me_idle_close_by_peer_total 684
telemt_me_route_drop_no_conn_total 342366
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 884772
telemt_me_endpoint_quarantine_total 647
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 619
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
telemt_me_writers_active_current 44
telemt_desync_total 4955
telemt_desync_full_logged_total 1518
telemt_desync_suppressed_total 3437
telemt_desync_frames_bucket_total{bucket="1_2"} 1169
telemt_desync_frames_bucket_total{bucket="3_10"} 1977
telemt_desync_frames_bucket_total{bucket="gt_10"} 1809
telemt_pool_swap_total 80
telemt_pool_force_close_total 1996
telemt_me_writer_close_signal_drop_total 117
telemt_me_draining_writers_reap_progress_total 30512
telemt_me_writer_removed_unexpected_total 661
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2366
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28832
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1916
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 80
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28516
telemt_me_writer_teardown_success_total{mode="normal"} 31198
telemt_me_writer_teardown_noop_total 30515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61713
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.546023
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61713
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 117
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 603
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 885778
telemt_user_connections_current{user="hello"} 1127
telemt_user_octets_from_client{user="hello"} 16001147945 (14.90 GB)
telemt_user_octets_to_client{user="hello"} 394293441007 (367.21 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 428
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 157076.4 (43h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12482611
telemt_connections_bad_total 1446730
telemt_connections_current 1994
telemt_connections_me_current 1994
telemt_handshake_timeouts_total 344135
telemt_upstream_connect_attempt_total 59010
telemt_upstream_connect_success_total 58781
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 58960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29693
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_reconnect_attempts_total 2283
telemt_me_reconnect_success_total 1225
telemt_me_reader_eof_total 1190
telemt_me_idle_close_by_peer_total 1190
telemt_me_route_drop_no_conn_total 4161564
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9437731
telemt_me_endpoint_quarantine_total 1064
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1174
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
telemt_desync_total 38702
telemt_desync_full_logged_total 12632
telemt_desync_suppressed_total 26070
telemt_desync_frames_bucket_total{bucket="1_2"} 9203
telemt_desync_frames_bucket_total{bucket="3_10"} 14336
telemt_desync_frames_bucket_total{bucket="gt_10"} 15163
telemt_pool_swap_total 174
telemt_pool_force_close_total 4804
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 618
telemt_me_draining_writers_reap_progress_total 53145
telemt_me_writer_removed_unexpected_total 1143
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4352
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49969
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4631
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48341
telemt_me_writer_teardown_success_total{mode="normal"} 54321
telemt_me_writer_teardown_noop_total 53147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107468
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.071187
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107468
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 618
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 1074
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 9406986
telemt_user_connections_current{user="hello"} 1994
telemt_user_octets_from_client{user="hello"} 184493709460 (171.82 GB)
telemt_user_octets_to_client{user="hello"} 4155281362004 (3.78 TB)
telemt_user_unique_ips_current{user="hello"} 704
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 157073.1 (43h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10822194
telemt_connections_bad_total 1209957
telemt_connections_current 1398
telemt_connections_me_current 1398
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 279113
telemt_upstream_connect_attempt_total 84740
telemt_upstream_connect_success_total 84105
telemt_upstream_connect_fail_total 550
telemt_upstream_connect_attempts_per_request{bucket="1"} 84655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2028
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 550
telemt_me_reconnect_attempts_total 8881
telemt_me_reconnect_success_total 2045
telemt_me_reader_eof_total 1909
telemt_me_idle_close_by_peer_total 1909
telemt_me_seq_mismatch_total 74
telemt_me_route_drop_no_conn_total 5408912
telemt_me_route_drop_channel_closed_total 347
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8365680
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
telemt_desync_total 38201
telemt_desync_full_logged_total 12338
telemt_desync_suppressed_total 25863
telemt_desync_frames_bucket_total{bucket="1_2"} 9491
telemt_desync_frames_bucket_total{bucket="3_10"} 14245
telemt_desync_frames_bucket_total{bucket="gt_10"} 14465
telemt_pool_swap_total 166
telemt_pool_force_close_total 4650
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 605
telemt_me_draining_writers_reap_progress_total 52568
telemt_me_writer_removed_unexpected_total 1935
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5445
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49126
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47918
telemt_me_writer_teardown_success_total{mode="normal"} 54571
telemt_me_writer_teardown_noop_total 52573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107144
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.492881
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107144
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 605
telemt_me_refill_failed_total 351
telemt_me_writer_restored_same_endpoint_total 1663
telemt_me_writer_restored_fallback_total 99
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 8371669
telemt_user_connections_current{user="hello"} 1398
telemt_user_octets_from_client{user="hello"} 147354054645 (137.23 GB)
telemt_user_octets_to_client{user="hello"} 3195912621583 (2.91 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 518
telemt_user_unique_ips_recent_window{user="hello"} 190
```